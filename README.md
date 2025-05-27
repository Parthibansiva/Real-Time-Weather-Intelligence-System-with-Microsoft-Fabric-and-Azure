**Real-Time-Weather-Intelligence-System-with-Microsoft-Fabric-and-Azure**

📘 Overview

This project demonstrates how to build a real-time weather monitoring and alerting system using a modern data engineering stack. By integrating Weather APIs, Azure Databricks, Azure Functions, Event Hubs, Microsoft Fabric, Kusto DB, and Power BI, we enable real-time data streaming, processing, visualization, and alerts.

![weatherdata_ultrahighres](https://github.com/user-attachments/assets/8ede0de6-bb41-4987-a736-a66df0aae22d)


📅 Agenda
Environment Setup

Data Ingestion

Cost Analysis & Architectural Decisions

Real-Time Streaming & Processing

Power BI Dashboard & Real-Time Alerts




**🔄 Data Ingestion using Notebook**

 **Steps:**
 
1.Create and Set Up Event Hub
  
2.Create a notebook in fabric
  
3.Install Event Hub Libraries
  
4.Send a Test Event from Notebook to Event Hub
  
5.Configure Azure Key Vault in Notebook
 
6.Weather API Testing in Notebook
  
7.Develop Complete Code for Weather Data Extraction
  
8.Ingest Final Weather Data from Notebook to Event Hub

  
Data Ingestion using Azure Function

1.Create Function App in Azure with Python runtime.

2.Add Timer Trigger to call Weather API at regular intervals 30sec.

3.Store API Key in Azure Key Vault and access it securely via Managed Identity.

4.Write Code to fetch weather data using requests and transform as needed.

5.Send Data to Event Hub using the Azure Event Hub SDK.

6.Test Locally and Deploy using VS Code or Azure CLI.


