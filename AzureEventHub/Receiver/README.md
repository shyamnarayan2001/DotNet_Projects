## Objective
The objective of this tutorial is write an Event Consumer code to receive messages from Azure Event Hub.

## Pre-requisites
Ensure that the following softwares are already installed:
1) Microsoft Visual Studio 2017
2) Azure Subscription
3) An event hub namespace and an event hub. (refer the section "Create an event hub using Azure portal" in the blog)

## Instructions
1. Clone or download this GitHub repo.
2. Create an Event Hubs namespace and an event hub (refer the section "Create an event hub using Azure portal" in the blog)
3. In Visual Studio, select File, then Open Project/Soultion. Navigate to the AzureEventHub\Receiver folder.
4. Load the Receiver.sln solution file into Visual Studio.
5. Add the "Microsoft Azure Service Bus Event Hub - EventProcessorHost" NuGet package to the project.
6. In Program.cs, replace the placeholders in brackets with the proper values that were obtained when creating the event hub.
```csharp
  string eventHubConnectionString = "{Event Hubs namespace connection string}";
  string eventHubName = "{Event Hub name}";
  string storageAccountName = "{storage account name}";
  string storageAccountKey = "{storage account key}";
```
7. Run the program, and ensure that there are no errors.


## Output
* Your program will receive messages from Event Hub.
* You can monitor the messages in your EventHub in Azure.

## Blog Reference
You can find all the instructions in the blog link provided below.
https://shyamtechno.blogspot.com/2018/12/azure-what-is-azure-event-hub.html

