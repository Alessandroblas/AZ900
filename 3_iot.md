# Internet of Things

IoT enables devices to gather and then relay information for data analysis. Smart devices are equipped with sensors that collect data.

**Azure IoT Hub** is a managed service that acts as a central message hub for bi-directional communication between your IoT application and the devices it manages. You can connect virtually any device to your IoT hub. The IoT Hub service supports communications both from the device to the cloud and from the cloud to the device. It also supports multiple messaging patterns, such as *device-to-cloud* telemetry, file upload from devices, and request-reply methods to control your devices from the cloud. After an IoT hub receives messages from a device, it can route that message to other Azure services. From a *cloud-to-device* perspective, IoT Hub allows for command and control. That is, you can have either manual or automated remote control of connected devices, so you can instruct the device to open valves, set target temperatures, restart stuck devices, and so on. 

**IoT Hub monitoring** helps you maintain the health of your solution by tracking events such as device creation, device failures, and device connections.

**Azure IoT Central** builds on top of IoT Hub by adding a dashboard that allows you to connect, monitor, and manage your IoT devices. The visual user interface (UI) makes it easy to quickly connect new devices and watch as they begin sending telemetry or error messages. 

**Azure Sphere** creates an end-to-end, highly secure IoT solution for customers that encompasses everything from the hardware and operating system on the device to the secure method of sending messages from the device to the message hub. 

<details>
  <summary> Check your knowledge </summary>
1. A company wants to build a new voting kiosk for sales to governments around the world. Which IoT technologies should the company choose to ensure the highest degree of security?

- IoT Hub
- IoT Central
- **Azure Sphere**

*Azure Sphere provides the highest degree of security to ensure the device has not been tampered with.*
2. A company wants to quickly manage its individual IoT devices by using a web-based user interface. Which IoT technology should it choose?

- IoT Hub
- **IoT Central**
- Azure Sphere

*IoT Central quickly creates a web-based management portal to enable reporting and communication with IoT devices.*

3. You want to send messages from the IoT device to the cloud and vice versa. Which IoT technology can send and receive messages?

- **IoT Hub**
- IoT Central
- Azure Sphere

*An IoT hub communicates to IoT devices by sending and receiving messages.*
</details>