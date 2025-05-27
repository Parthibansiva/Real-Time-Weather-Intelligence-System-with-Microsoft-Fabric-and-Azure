**Real-Time-Weather-Intelligence-System-with-Microsoft-Fabric-and-Azure**

📘 Overview

This project demonstrates how to build a real-time weather monitoring and alerting system using a modern data engineering stack. By integrating Weather APIs, Azure Databricks, Azure Functions, Event Hubs, Microsoft Fabric, Kusto DB, and Power BI, we enable real-time data streaming, processing, visualization, and alerts.

![weatherdata_ultrahighres](https://github.com/user-attachments/assets/8ede0de6-bb41-4987-a736-a66df0aae22d)


**📅 Agenda**

*Data Ingestion  
*Cost Analysis & Architectural Decisions  
*Real-Time Streaming & Processing  
*Power BI Dashboard & Real-Time Alerts  




## 📓 Notebook  (Weather API Ingestion)


![data_ingestion](https://github.com/user-attachments/assets/47cd8611-8361-4f4f-899c-acd841d18dd8)
<img src="path/to/image.png](https://github.com/user-attachments/assets/47cd8611-8361-4f4f-899c-acd841d18dd8" alt="Data Ingestion" width="100"/>



### 📋 Steps:

1. **Create and Setup Event HUB**  
   Set up an Event Hub namespace and event stream to receive real-time weather data.

2. **Create Cluster in Notebooks**  
   Use Azure Databricks or Jupyter to create a compute environment for running ingestion logic.

3. **Install Event HUB Libraries**  
   Install necessary libraries like `azure-eventhub` and `azure-eventhub-checkpointstore`.

4. **Send Test Event from Notebook to Event HUB**  
   Validate the connection by sending a test message to Event Hub from your notebook.

5. **Configure Key Vault Secrets**  
   Use Azure Key Vault and integrate it with your notebook to securely access API keys.

6. **Weather API Testing in Notebook**  
   Use Python and `requests` to fetch and validate live weather data from the REST API.

7. **Develop Code to Get Weather Data**  
   Write code to parse, transform, and prepare weather data for streaming.

8. **Ingest Data from Notebook to Event HUB**  
   Stream the transformed weather data into Event Hub for downstream processing.

---

  
## ⚙️ Azure Function  (Weather API Ingestion)

1. **Create Function App** in Azure with Python runtime.  
2. **Add Timer Trigger** to call Weather API at regular intervals 30sec.  
3. **Store API Key in Azure Key Vault** and access it securely via Managed Identity.  
4. **Write Code** to fetch weather data using `requests` and transform as needed.  
5. **Send Data to Event Hub** using the Azure Event Hub SDK. 


