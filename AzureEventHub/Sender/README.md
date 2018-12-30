## Objective
The objective of this tutorial is write an Event Publisher code to publish messages to Azure Event Hub.

## Pre-requisites
Ensure that the following softwares are already installed:
1) Microsoft Visual Studio 2017
2) Azure Subscription
3) An event hub namespace and an event hub.

## Instructions
1. Clone or download this GitHub repo.
2. Create an Event Hubs namespace and an event hub (refer the blog for instructions)
3. In Visual Studio, select File, then Open Project/Soultion. Navigate to the AzureEventHub\Sender folder.
4. Load the Sender.sln solution file into Visual Studio.
5. Add the Microsoft.Azure.EventHubs NuGet package to the project.
6. In Program.cs, replace the placeholders in brackets with the proper values that were obtained when creating the event hub.
```csharp
static string eventHubName = "Your Event Hub name";
static string connectionString = "namespace connection string";
```
7. Run the program, and ensure that there are no errors.


## Output
* Your program will keep on sending messages for every 200 seconds to Event Hub.
* You can monitor the incoming requests in your EventHub in Azure.

## Blog Reference
You can find all the instructions in the blog link provided below.
https://shyamtechno.blogspot.com/2018/12/azure-what-is-azure-event-hub.html
