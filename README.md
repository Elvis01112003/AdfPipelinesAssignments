# Azure Data Factory Pipelines Assignments

![Azure](https://img.shields.io/badge/Azure-Data%20Factory-blue)
![ADF](https://img.shields.io/badge/ETL-Azure_Data_Factory-success)
![SQL](https://img.shields.io/badge/Database-Azure_SQL-orange)
![ADLS](https://img.shields.io/badge/Storage-ADLS_Gen2-green)
![GitHub](https://img.shields.io/badge/Version_Control-GitHub-black)

## 📌 Project Overview

This repository contains Azure Data Factory (ADF) assignments completed during my Data Engineering training.

The project demonstrates how to build ETL pipelines using Azure Data Factory by integrating Azure SQL Database and Azure Data Lake Storage Gen2 (ADLS Gen2). It also covers Azure Blob Storage, dataset creation, linked services, triggers, and Git integration.

---

## 🛠 Technologies Used

- Azure Data Factory
- Azure SQL Database
- Azure Data Lake Storage Gen2
- Azure Blob Storage
- Azure Key Vault
- Git & GitHub
- CSV
- JSON

---

## 📁 Repository Structure

```
AdfPipelinesAssignments
│
├── dataset/
├── factory/
├── linkedService/
├── pipeline/
├── Azure Data Factory Assignment.pdf
├── publish_config.json
└── README.md
```

---

# 📚 Assignments

## Assignment 1 – Azure Data Lake Storage Gen2

### Completed Tasks

- Created ADLS Gen2 Storage Account
- Configured Soft Delete
- Created Containers
- Created Directories
- Uploaded Files
- Deleted Files
- Restored Deleted Files

---

## Assignment 2 – Azure SQL Database

### Completed Tasks

- Created Azure SQL Server
- Created Azure SQL Database
- Configured Firewall Rules
- Executed SQL Queries
- Verified Data

---

## Assignment 3 – Azure Blob Storage

### Completed Tasks

- Created Blob Storage Account
- Enabled Blob Versioning
- Created Public Container
- Uploaded Files
- Tested Blob Versioning

---

## Assignment 4 – Azure Data Factory Pipelines

### Pipeline 1

**Copy_ProductTable_To_CSV**

**Source**

Azure SQL Database

**Destination**

ADLS Gen2 (CSV)

---

### Pipeline 2

**Copy_Customer_To_JSON**

**Source**

Azure SQL Database

**Destination**

ADLS Gen2 (JSON)

---

### Pipeline 3

**Copy_Customer_JSON_To_Folder**

**Source**

ADLS Gen2

**Destination**

Another ADLS Folder

---

### Pipeline 4

**Copy_Customer_To_CSV_Pipe**

**Source**

Azure SQL Database

**Destination**

Pipe Delimited CSV

---

# 🚀 Azure Data Factory Concepts Covered

- Linked Services
- Datasets
- Copy Activity
- Source & Sink Configuration
- Schema Mapping
- Pipeline Validation
- Debug
- Publish
- Schedule Trigger
- Git Integration
- Data Movement
- CSV Export
- JSON Export

---

# 📂 Repository Contents

| Folder | Description |
|---------|-------------|
| dataset | Dataset definitions |
| linkedService | Azure SQL & ADLS linked services |
| pipeline | ADF pipeline JSON files |
| factory | Factory configuration |
| publish_config.json | Publish configuration |
| Azure Data Factory Assignment.pdf | Assignment document |

---

# 🎯 Learning Outcomes

Through these assignments I gained practical experience in:

- Building ETL pipelines
- Azure Data Factory
- Azure SQL Database
- Azure Data Lake Storage Gen2
- Azure Blob Storage
- Data Ingestion
- Git Version Control
- Pipeline Debugging
- Publishing Pipelines

---

# 📖 How to Use

1. Clone this repository.

```
git clone https://github.com/Elvis01112003/AdfPipelinesAssignments.git
```

2. Open Azure Data Factory.

3. Connect the repository to Git.

4. Import the factory resources.

5. Publish the pipelines.

---

## 👨‍💻 Author

**Elvis Titus Cherukara**

Associate Data Engineer Trainee

GitHub: https://github.com/Elvis01112003
