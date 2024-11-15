# tokyo-olympic-azure-data-engineering-project




# Tokyo Olympic Azure Data Engineering Project

## Project Overview
<p>This project leverages various Azure services to collect, process, and analyze data related to the Tokyo 2020 Olympics. The key components of this project include:</p>
<ul>
  <li><strong>Azure Data Factory:</strong> Used for ETL (Extract, Transform, Load) processes, automating data extraction from GitHub and loading it into Azure Data Lake.</li>
  <li><strong>Azure Databricks:</strong> For transforming and processing data, ensuring it is ready for analysis.</li>
  <li><strong>Azure Synapse Analytics:</strong> Provides advanced analytics on the transformed data.</li>
  <li><strong>Azure Data Lake Storage Gen2:</strong> Used for storing raw and transformed datasets.</li>
</ul>

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
  <li><strong>Visualization:</strong> The processed data is visualized using Power BI or directly in Azure Synapse Analytics.</li>
</ul>

## Technical Setup
<p>The project is designed to be flexible and scalable, enabling you to create a full-fledged pipeline for Olympic data processing. Here's a brief guide to set up:</p>

<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Ensure you have an Azure subscription and set up resources like Data Factory, Databricks, and Synapse Analytics.</li>
  <li>Upload the Tokyo Olympics dataset from Kaggle to GitHub.</li>
  <li>Use Azure Data Factory to ingest data into Azure Data Lake Storage Gen2.</li>
  <li>Use Azure Databricks for data transformation and Azure Synapse for advanced analytics.</li>
  <li>Visualize the results in Power BI or Azure Synapse Analytics.</li>
</ol>

## Folder Structure
<p>The repository contains the following key files:</p>
<ul>
  <li><strong>Data Folder:</strong> Contains the CSV files for athletes, teams, and medals.</li>
  <li><strong>Python Folder:</strong> Contains Python scripts for data processing and transformation using Azure Databricks.</li>
  <li><strong>SQL Scripts:</strong> Contains SQL queries for analysis in Azure Synapse Analytics.</li>
  <li><strong>JSON Files:</strong> Contains configuration files like <code>data_ingestion_pipelines_datafactory.JSON</code> for Azure Data Factory pipelines.</li>
</ul>

## Azure Services Used
<p>This project utilizes the following Azure services:</p>
<ul>
  <li><strong>Azure Data Factory:</strong> To automate and orchestrate the ETL process.</li>
  <li><strong>Azure Databricks:</strong> For scalable data processing and transformation.</li>
  <li><strong>Azure Synapse Analytics:</strong> For running advanced analytics on the data.</li>
  <li><strong>Azure Data Lake Storage Gen2:</strong> As the data storage solution.</li>
</ul>

## Workflow

### 1. Initial Setup
<ol>
  <li>Create an Azure free subscription account.</li>
  <li>Set up a resource group called <code>tokyo-olympic-data</code>.</li>
  <li>Create a storage account within the resource group.</li>
  <li>Create two directories: <code>raw-data</code> and <code>transformed-data</code> to store raw and transformed datasets.</li>
</ol>

### 2. Data Ingestion
<p>Use Azure Data Factory to ingest data into Azure Data Lake. Create a pipeline to automate data transfer from GitHub to Azure Data Lake.</p>

### 3. Data Transformation
<p>After ingestion, use Azure Databricks for processing and transforming the data. You can clean and aggregate the data for analysis.</p>

### 4. Data Analytics
<p>Analyze the transformed data using Azure Synapse Analytics to derive insights from the Olympics dataset.</p>

### 5. Data Visualization
<p>Use Power BI or Azure Synapse Analytics to visualize the insights and share the results.</p>

## Getting Started
<p>To get started with this project:</p>
<ol>
  <li>Fork this repository.</li>
  <li>Clone the forked repository to your local environment.</li>
  <li>Follow the instructions in the <code>README.md</code> for setting up Azure services and running the pipelines.</li>
</ol>

## Conclusion
<p>This project provides an example of how to build a data engineering pipeline using Azure to process and analyze large datasets like the Tokyo 2020 Olympics. It integrates several Azure services and demonstrates their power in handling complex data engineering tasks.</p>

<p>Feel free to contribute to this project or adapt it to your own use cases!</p>

## License
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
