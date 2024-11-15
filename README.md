# tokyo-olympic-azure-data-engineering-project



## Project Overview
<p>This project leverages various Azure services to collect, process, and analyze data related to the Tokyo 2020 Olympics. The key components of this project include:</p>
<ul>
  <li><strong>Azure Data Factory:</strong> Used for ETL (Extract, Transform, Load) processes, automating data extraction from GitHub and loading it into Azure Data Lake.</li>
  <li><strong>Azure Databricks:</strong> For transforming and processing data, ensuring it is ready for analysis.</li>
  <li><strong>Azure Synapse Analytics:</strong> Provides advanced analytics on the transformed data.</li>
  <li><strong>Azure Data Lake Storage Gen2:</strong> Used for storing raw and transformed datasets.</li>
</ul>



## Project Architecture
![arc_1](https://github.com/user-attachments/assets/91e0191c-4810-46a2-ac33-551a79045bc1)




## Dataset
<p>The project uses a dataset from Kaggle that includes detailed information about the Tokyo 2020 Olympics, covering:</p>
<ul>
  <li>11,000 athletes</li>
  <li>47 disciplines</li>
  <li>743 teams</li>
</ul>
<p>Data is available in CSV format, containing information about athletes, medals, and teams, which can be found in the project's GitHub repository.</p>

## Key Features
<p>The project integrates the following Azure components:</p>
<ul>
  <li><strong>Data Ingestion:</strong> Using Azure Data Factory to ingest raw data from GitHub into Azure Data Lake.</li>
  <li><strong>Data Transformation:</strong> The raw data is processed and cleaned using Azure Databricks.</li>
  <li><strong>Data Analytics:</strong> Azure Synapse Analytics is used to perform complex analytics on the data.</li>
</ul>

## Technical Setup
<p>The project is designed to be flexible and scalable, enabling you to create a full-fledged pipeline for Olympic data processing. Here's a brief guide to set up:</p>

<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Ensure you have an Azure subscription and set up resources like Data Factory, Databricks, and Synapse Analytics.</li>
  <li>Upload the Tokyo Olympics dataset from Kaggle to GitHub.</li>
  <li>Use Azure Data Factory to ingest data into Azure Data Lake Storage Gen2.</li>
  <li>Use Azure Databricks for data transformation and Azure Synapse for advanced analytics.</li>
</ol>

## Folder Structure
<p>The repository contains the following key files:</p>
<ul>
  <li><strong>Data Folder:</strong> Contains the CSV files for athletes, teams, and medals.</li>
  <li><strong>Python Folder:</strong> Contains Python scripts for data processing and transformation using Azure Databricks.</li>
  <li><strong>SQL Folder:</strong> Contains SQL queries for analysis in Azure Synapse Analytics.</li>
</ul>

## Azure Services Used
<p>This project utilizes the following Azure services:</p>
<ul>
  <li><strong>Azure Data Factory:</strong> To automate and orchestrate the ETL process.</li>
  <li><strong>Azure Databricks:</strong> For scalable data processing and transformation.</li>
  <li><strong>Azure Synapse Analytics:</strong> For running advanced analytics on the data.</li>
  <li><strong>Azure Data Lake Storage Gen2:</strong> As the data storage solution.</li>
</ul>

![img_2](https://github.com/user-attachments/assets/2d6304cb-a787-4058-8a64-6a611304aa53)


## Workflow

### 1. Initial Setup
<ol>
  <li>Create an Azure free subscription account.</li>
  <li>Set up a resource group called <code>tokyo-olympic-data</code>.</li>
  <li>Create a storage account within the resource group.</li>
  <li>Create two directories: <code>raw-data</code> and <code>transformed-data</code> to store raw and transformed datasets.</li>
</ol>

![img_1](https://github.com/user-attachments/assets/bd1c3df7-c31f-457e-a123-006c87dd0283)



### 2. Data Ingestion
<p>Use Azure Data Factory to ingest data into Azure Data Lake. Create a pipeline to automate data transfer from GitHub to Azure Data Lake.</p>

![adf_2](https://github.com/user-attachments/assets/64af9f92-d500-4073-b43f-5a1ba336204f)


### 3. Data Transformation
<p>After ingestion, use Azure Databricks for processing and transforming the data. You can clean and aggregate the data for analysis.</p>

![databricks_3](https://github.com/user-attachments/assets/c3f532f7-f99b-4ecf-9217-5855bbe849c5)


### 4. Data Analytics
<p>Analyze the transformed data using Azure Synapse Analytics to derive insights from the Olympics dataset.</p>

![synapse_4](https://github.com/user-attachments/assets/3d6235fa-edad-43a1-aa5e-50b615031727)



## Conclusion
<p>This project provides an example of how to build a data engineering pipeline using Azure to process and analyze large datasets like the Tokyo 2020 Olympics. It integrates several Azure services and demonstrates their power in handling complex data engineering tasks.</p>

<p>Feel free to contribute to this project or adapt it to your own use cases!</p>


