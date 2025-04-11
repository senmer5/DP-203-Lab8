# DP-203-Lab8

# Explore a Relational Data Warehouse 📊

Azure Synapse Analytics is a powerful platform designed to support enterprise-level data warehousing. It integrates various capabilities, including file-based data analytics in a data lake and large-scale relational data warehouses. The system supports essential processes like data transfer and transformation pipelines used to load data warehouses.

In this lab, you will explore how to leverage a dedicated SQL pool in Azure Synapse Analytics to store and query data in a relational data warehouse.

---

## Provisioning Your Azure Synapse Analytics Workspace 🛠️

A Synapse workspace is a central point for managing your data and processing resources. You can easily provision the workspace through the Azure portal interface, or automate the process using a script or ARM template (recommended for production environments).

Here’s how you can set up the workspace:
1. Log into the Azure portal at [Azure Portal](https://portal.azure.com).
2. Use Cloud Shell for easy scripting. Choose the PowerShell environment for command execution.
3. Clone the repository to retrieve the necessary files for the lab.

---

## Exploring the Data Warehouse Schema 🏗️

In this lab, you’ll be working with a relational data warehouse hosted in the dedicated SQL pool. A relational data warehouse typically has a schema with fact and dimension tables. These tables are designed for analytical queries, where numeric metrics in the fact tables are aggregated by attributes in the dimension tables.

### Key concepts you will explore:
- **Fact tables**: Large tables that store measurable data, such as sales figures or transactions.
- **Dimension tables**: Provide context and attributes for the data in the fact tables, such as product information, time, or geographical data.

---

## Querying Data in Your Data Warehouse 🔍

After understanding the schema, you’ll begin querying the data to extract valuable insights. Using SQL, you can:
- Join fact and dimension tables to aggregate data.
- Use **GROUP BY** clauses to analyze data based on various attributes (e.g., time, region, or product category).
- Apply ranking functions to assess metrics like sales performance across different partitions.

### Additional Skills You Will Learn:
- Writing and executing SQL queries for data analysis.
- Using ranking functions to sort and assess data.
- Optimizing SQL queries for better performance (using functions like **APPROX_COUNT_DISTINCT**).
- Analyzing **Reseller Sales** to identify patterns and performance.

---

## Additional Tips 💡
- Always ensure that your data is well-organized in tables before querying.
- Use SQL functions to calculate aggregates like sums, averages, and ranks.

---
##screenshot

<img width="1133" alt="1" src="https://github.com/user-attachments/assets/133bf0a8-b49b-40fd-813e-510415493f4d" />

<img width="1422" alt="4" src="https://github.com/user-attachments/assets/98c2f5d1-cfe4-44b7-a1e8-447729ba05bd" />

<img width="1504" alt="5" src="https://github.com/user-attachments/assets/1e83d0d1-7d4b-43f3-bd26-8aef9e36d7ec" />

<img width="1152" alt="8" src="https://github.com/user-attachments/assets/d947d884-1f98-42dd-950c-17eeb99644e9" />

<img width="1319" alt="9" src="https://github.com/user-attachments/assets/be901ee1-0222-489e-9858-2c7d8e66e90a" />


