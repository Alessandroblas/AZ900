# Azure Serverless

Serverless computing is an execution environment that runs your code but abstracts the underlying hosting environment. You create an instance of the service, and you then add your code. No infrastructure configuration or maintenance is required, or even allowed. 

Serverless computing is ordinarily used to handle back-end scenarios. In other words, serverless computing is responsible for sending messages from one system to another, or processing messages that were sent from other systems. It's not used for user-facing systems but, rather, it works in the background.

## Azure Functions

With the Azure Functions service, you can host a service by using a popular programming language in the cloud that runs in response to an event. Azure Functions scales automatically, and charges accrue only when a function is triggered. These qualities make Azure Functions a solid choice when demand is variable. If state is required, function can be connected to a storage account.

Its pricing is based on the number of executions and the running time of each execution
## Azure Logic Apps

Logic Apps is a low-code/no-code development platform to **automate and orchestrate** tasks, business prcesses, and workflow when you need to integrate different components (app/systems/data/...). You build an app by linking triggers to actions with connectors. 

It is priced based on the number of executions and on the type of connectors that it utilizes.

<details>
    <summary>Check your knowledge</summary>
1. You need to process messages from a queue, parse them by using some existing imperative logic written in Java, and then send them to a third-party API. Which serverless option should you choose?

- **Azure Functions**
- Azure Logic Apps

*Azure Functions is the correct choice because you can use existing Java code with minimal modification.*

2. You want to orchestrate a workflow by using APIs from several well-known services. Which is the best option for this scenario?

- Azure Functions
- **Azure Logic Apps**

*Azure Logic Apps makes it easy to create a workflow across well-known services with less effort than writing code and manually orchestrating all the steps yourself.*
3. Your team has limited experience with writing custom code, but it sees tremendous value in automating several important business processes. Which of the following options is your team's best option?

- Azure Functions
- **Azure Logic Apps**

*Azure Logic Apps is best suited for users who are more comfortable in a visual environment that allows them to automate their business processes. Logic Apps is the best option in this scenario.*
</details>