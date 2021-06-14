# Azure Networking services

We'll take a look at several of the core networking resources that are available in Azure. 

**Azure virtual networking** is a set of resources that links other resources. It provides the following capabilities: 

- Internet communications
    - A VM can connect to the internet by default. You can enable incoming traffic from the internet by defining a public IP address or a public load balancer.
- Communicate between cloud and on-prem resources
    - You can connect different resources using virtual networks or service endpoints
    - You can connect Azure resources to on-prem data center leveraging: 
        - Point-to-site VPN
        - Site-to-site VPN
        - Azure ExpressRoute: best approach for environments requiring greater bandwidth and higher level of security.
- Route (Route tables and BGP) and filter (Network security groups and virtual appliances) traffic
- Connect different networks - peering

## Azure VPN Gateway

VPNs use an encrypted tunnel within another network. They're typically deployed to connect two or more trusted private networks to one another over an untrusted network (typically the public internet). Traffic is encrypted while traveling over the untrusted network to prevent eavesdropping or other attacks.

**Azure VPN Gateway** instances are deployed in Azure Virtual Network instances and enable the following connectivity:

- Connect on-premises datacenters to virtual networks through a *site-to-site* connection.
- Connect individual devices to virtual networks through a *point-to-site* connection.
- Connect virtual networks to other virtual networks through a *network-to-network* connection.

You can deploy only one VPN gateway in each virtual network, but you can use one gateway to connect to multiple locations.

The *capabilities* of your VPN gateway are determined by the SKU or size that you deploy. This table shows the main capabilities of each available SKU.
> A Basic VPN gateway should only be used for Dev/Test workloads. In addition, it's unsupported to migrate from Basic to the VpnGW1/2/3/Az SKUs at a later time without having to remove the gateway and redeploy.

### Deploy VPN gateway

You'll need these Azure resources before you can deploy an operational VPN gateway:

- Virtual Network (vNet)
- GatewaySubnet
- Public IP address
- Local network gateway
- Virtual network gateway
- Connection

To connect your DC to a VPN gateway, you'll need these on-prem resources: 
- A VPN device that support policy/route-based VPN gateways
- A public-facing IPv4 address

### High Availability

- **Active/standby** by default: connections are interrupted during failover, but they're typically restored within a few seconds for planned maintenance and within 90 seconds for unplanned disruptions.
- **Active/Active** you can deploy 1+ VPN gateways assigning a unique public IP address to eachs instance and the create separate tunnels from the on-prem DC to each VPN gateway.
- **ExpressRoute failover** ExpressRoute circuits have resiliency built in but you can also provision a VPN gateway that uses the internet as an alternative method of connectivity.
- **Zone-redundant gateways**  Deploying gateways in Azure availability zones physically and logically separates gateways within a region while protecting your on-premises network connectivity to Azure from zone-level failures. These gateways require different gateway SKUs and use Standard public IP addresses instead of Basic public IP addresses.

## Azure ExpressRoute

[ExpressRoute](https://docs.microsoft.com/en-us/azure/expressroute/) lets you extend your on-premises networks into the Microsoft cloud over a private connection with the help of a connectivity provider. ExpressRoute uses the Border Gateway Protocol (BGP) routing protocol. BGP is used to exchange routes between on-premises networks and resources running in Azure. With ExpressRoute, your data doesn't travel over the public internet, so it's not exposed to the potential risks associated with internet communications.

You can enable **ExpressRoute Global Reach** to exchange data across your on-premises sites by connecting your ExpressRoute circuits. With ExpressRoute Global Reach, you can connect your private datacenters through two ExpressRoute circuits. Your cross-datacenter traffic will travel through the Microsoft network. 

ExpressRoute supports three models that you can use to connect your on-premises network to the Microsoft cloud:

- CloudExchange colocation
- Point-to-point Ethernet connection
- Any-to-any connection

Official docs [here](https://docs.microsoft.com/en-us/azure/networking/fundamentals/networking-overview).