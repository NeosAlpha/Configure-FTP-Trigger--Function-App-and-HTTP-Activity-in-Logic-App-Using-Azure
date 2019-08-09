# Configure Auto Event when csv file is created or modified on FTP Server, Parse data into JSON and Configure with RestAPI using Logic App.
**Produced by NeosAlpha Technologies**

# Introduction
In this demo we will logic App which automatically trigger when any CSV file create or modified on FTP server. Trasform file data into JSON format using Function App
and configure Rest API for all data.

# Soltion Architecture Design
![SolutionArchitecture.png](Image/SolutionArchitecture.png)


# Set up

In the Azure portal, create a HTTP Trigger Function App auto configure with Azure Blob storage.File name of CSV file stored into blob storage read from Function App Url Query string or Header values.
Read data from CSV file and Transform data into JSON format.

In the Logic App interface, go to the Logic App designer and add a recurrence trigger.


Functionality we are including in this Process:

•	Auto event occur when new file is created or modified on FTP server.
•	Copy file from FTP server to Azure Blob Storage
•	Transform CSV file into JSON format using Azure Function App HTTP Trigger.
•	Initialize Parameter and set value of that parameter from response of Rest API.
•	Perform Various Http Request Type like PUT/POST/DELETE using Logic App and perform each activity.
•	Manage Proper Handling.
•	Configure Azure Log Analytics.


# Function App

HTTP Trigger Function App auto configure with Azure Blob storage.File name of CSV file stored into blob storage read from Function App Url Query string or Header values.
Read data from CSV file and Transform data into JSON format.

# Logic App
![addRole.png](images/addRole.png)

