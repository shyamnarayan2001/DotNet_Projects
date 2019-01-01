## Objective
The objective of this tutorial is to write .NET core code to receive messages from Azure Service Bus.
===============RECEIVER
## Pre-requisites
1. Visual Studio 2017 Update 3 (version 15.3, 26730.01) or later.
2. NET Core SDK, version 2.0 or later.
3. An Azure subscription.

## Instructions
1. Clone or download this GitHub repo.
2. Create an Service Bus namespace and a Queue (refer the section "Create a namespace using the Azure portal" and "Create a queue using the Azure portal" in the blog)
3. In Visual Studio, select File, then Open Project/Soultion. Navigate to the AzureServiceBus\CoreAzureServiceBusReceiver folder.
4. Load the CoreAzureServiceBusReceiver.sln solution file into Visual Studio.
5. Add the Microsoft.Azure.ServiceBus NuGet package to the project.
6. In Program.cs, replace the placeholders in brackets with the proper values that were obtained when creating the event hub.
```csharp
const string ServiceBusConnectionString = "<your_connection_string>"; 
const string QueueName = "<your_queue_name>"; 
```
7. Run the program, and ensure that there are no errors.

## Output
* Your program will receive messages from Azure Service Bus.
* You can monitor the messages in your Service Bus in Azure.

## Blog Reference
You can find all the instructions in the blog link provided below.
https://shyamtechno.blogspot.com/2019/01/what-is-azure-service-bus.html

