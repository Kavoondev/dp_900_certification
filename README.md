# 🧠 DP-900 Practice Test

Below are **30 practice questions** covering **Azure Data Fundamentals (DP-900)** topics.  
Answer choices are provided for each question.  
Provide your answer in the format: `question-number-option` (for example, `1-a` or `5-b`).

---

### 1. 
An extract, transform, and load (ETL) process requires ____.

a. A matching schema in the data source and the data target  
b. A target data store powerful enough to perform data transformations  
c. Data that is fully processed before being loaded to the target data store  
d. That the data target be a relational database  

---

### 2. 
For the load stage of the ELT process, data processing occurs in ____.

a. An in-memory data integration tool  
b. The CRM system  
c. The data warehouse  

---

### 3. 
Which type of analytics describes what has already happened (for example, reports of past sales)?

a. Descriptive  
b. Diagnostic  
c. Predictive  
d. Prescriptive  

---

### 4. 
An extract, load, and transform (ELT) process requires ____.

a. A separate transformation engine  
b. A target data store powerful enough to transform data  
c. Data that is fully processed before being loaded to the target data store  
d. A data pipeline that includes a transformation engine  

---

### 5. 
Azure SQL Database can use Azure Defender for threat protection. (Yes/No)

a. Yes  
b. No  

---

### 6. 
Which Azure storage solution provides native support for POSIX-compliant Access Control Lists (ACLs)?

a. Azure Table Storage  
b. Azure Data Lake Storage  
c. Azure Queue Storage  
d. Azure Files  

---

### 7. 
You need to embed documents and query results into a SQL notebook while troubleshooting an Azure SQL Database. Which tool should you use?

a. Microsoft SQL Server Management Studio  
b. Azure Data Studio  
c. Azure CLI  
d. Azure PowerShell  

---

### 8. 
Which command-line tool can you use to query Azure SQL Databases?

a. sqlcmd  
b. bcp  
c. az data  
d. Azure CLI  

---

### 9. 
Your company needs to ensure that an Azure virtual machine can connect to Azure SQL Databases without exposing the databases to the internet. What should you use?

a. Azure Application Gateway  
b. Azure Traffic Manager  
c. Azure DNS  
d. Azure Private Link  

---

### 10. 
Which setting can only be configured during the creation of an Azure Cosmos DB account?

a. Geo-redundancy  
b. Multi-region writes  
c. Production or non-production account type  
d. API  

---

### 11. 
When provisioning an Azure Cosmos DB account, which feature provides redundancy within an Azure region?

a. Multi-master replication  
b. Availability Zones  
c. The strong consistency level  
d. Automatic failover  

---

### 12. 
Which Azure service does NOT support Power BI paginated reports?

a. SQL Server via Gateway  
b. Teradata  
c. Oracle databases  
d. Azure Data Lake  

---

### 13. 
If you change Azure Storage tiers from Hot to Cool, what is the key consideration?

a. Hot storage has a higher storage cost but lower access costs  
b. Storage tiers are relative to the amount of data stored, not the age of the data  
c. Cool storage has a lower storage cost but higher access costs  
d. Storage tiering is complicated; you should move back to storage accounts or page blob storage  

---

### 14. 
Which Azure analytics service supports Apache Spark, SQL data warehousing, Azure Machine Learning, and Power BI integration?

a. Azure Synapse Analytics  
b. Azure Databricks  
c. Azure Data Explorer  
d. Azure HDInsight  

---

### 15. 
In the event of a regional failure, Azure Cosmos DB can restore service with both an RTO and an RPO of zero. (Yes/No)

a. Yes  
b. No  

---

### 16. 
A hosted application installed on virtual hardware managed by a third party is an example of which cloud service model?

a. Software as a service (SaaS)  
b. Internet of Things (IoT)  
c. Infrastructure as a service (IaaS)  
d. Platform as a service (PaaS)  

---

### 17. 
In a data model, which object should you create to allow users to drill up and drill down in a report?

a. A cube  
b. A dimension  
c. A hierarchy  
d. A fact table  

---

### 18. 
Which Azure data service allows you to use every feature of Microsoft SQL Server in the cloud?

a. Azure SQL Database  
b. Azure SQL Managed Instance  
c. SQL Server on an Azure Virtual Machine (Linux)  
d. SQL Server on an Azure Virtual Machine (Windows)  

---

### 19. 
Which open-source database has built-in support for temporal data?

a. MariaDB  
b. MySQL  
c. Oracle Database  
d. PostgreSQL  

---

### 20. 
Which type of Azure Storage is used to store key/value pairs grouped in partitions?

a. Azure Data Lake Storage Gen2  
b. Azure Files  
c. Azure Storage page blobs  
d. Azure Table storage  

---

### 21. 
Which type of database is optimized for storing sequential data in the fastest way possible?

a. Azure SQL Database  
b. Azure Table storage  
c. Graph Database  
d. Time series database  

---

### 22. 
Which type of data workload is optimized for updates and relies on relationships between entities to correlate data?

a. Analytical  
b. Graph  
c. Time series  
d. Transactional  

---

### 23. 
Which feature of transactional data processing guarantees that concurrent processes cannot see the data in an inconsistent state?

a. Atomicity  
b. Consistency  
c. Durability  
d. Isolation  

---

### 24. 
What should you create first in Azure Data Factory when copying data from Microsoft Excel files to Parquet files?

a. A dataset  
b. A linked service  
c. A pipeline  
d. An activity  

---

### 25. 
Which Azure service can you use to perpetually retrieve data from a Kafka queue, process the data, and write the data to Azure Data Lake?

a. Azure Cosmos DB  
b. Azure Data Factory  
c. Azure Stream Analytics  
d. Azure Synapse Analytics  

---

### 26. 
When processing data by using both batches and streams, which technology ensures that transactional consistency is enforced during processing?

a. Azure Blob storage  
b. Azure Delta Lake  
c. Azure SQL Database  
d. Azure Table storage  

---

### 27. 
Which open-source database is a hybrid relational-object database?

a. MariaDB  
b. MySQL  
c. Oracle Database  
d. PostgreSQL  

---

### 28. 
Which job role is responsible for designing database solutions, creating databases, and developing stored procedures?

a. Database administrator  
b. Database analyst  
c. Database engineer  
d. Database user  

---

### 29. 
Which job role is responsible for managing the security of the data in a database, implementing backup and recovery plans, and monitoring the performance of database solutions?

a. Database administrator  
b. Data analyst  
c. Data engineer  
d. Database user  

---

### 30. 
Which type of Azure Storage is the least expensive option for storing new or modified image files?

a. Append blobs in the Archive tier  
b. Append blobs in the Cool tier  
c. Block blobs in the Archive tier  
d. Block blobs in the Cool tier  

---

## Question 31 
**For each application description, identify if it is better suited to batch or stream processing.**

- Employee payroll processing and generating payroll checks  
  - a) Batch ✅  
  - b) Stream

- Reporting the number of users and bandwidth used for an online game  
  - a) Batch  
  - b) Stream ✅

- Identifying defective manufacturing errors to automatically reject failing parts  
  - a) Batch  
  - b) Stream ✅

- Setting inventory stocking levels based on seasonal sales volume  
  - a) Batch ✅  
  - b) Stream

---

## Question 32
**What are two characteristics of data in batch processing? (Choose two)**

- 1) A short latency is required. — ❌  
- 2) A long latency is acceptable. — ✅  
- 3) Data is processed as it is generated. — ❌  
- 4) Data is collected for periodic processing. — ✅

---

## Question 33
**For each statement, select Yes or No.**

- Rows in the same table can have different numbers of columns. — **No** ❌  
- A table can have any number of rows. — **Yes** ✅  
- The primary key is used to enforce uniqueness on rows. — **Yes** ✅  
- Normalization helps to minimize data duplication. — **Yes** ✅

---

## Question 34
**You need to store structured data in a relational database. How is data organized?**

1. Tables containing keys and values — ❌  
2. Graphs containing edges and nodes — ❌  
3. Documents containing fields and values — ❌  
4. Tables containing rows and columns — **✅**

---

## Question 35
**Which two datasets are best suited for stream processing? (Choose two)**

- 1) List of potential customers — ❌  
- 2) Real-time data from users navigating a website — **✅**  
- 3) Data from sensors and IoT devices — **✅**  
- 4) Sales data for the last semester — ❌

---

## Question 36
**For each statement, select Yes or No.**

- You can process stream data at the moment it is generated. — **Yes** ✅  
- You can stream a large set of data at once in stream processing. — **No** ❌  
- You can use stream data to perform complex analytics. — **Yes** ✅

---

## Question 37
**For each statement, select Yes or No.**

- You can load a large set of data at once using batch processing. — **Yes** ✅  
- Batch processing requires near real-time data latency. — **No** ❌  
- You can perform complex analytics using batch processing. — **Yes** ✅

---

## Question 38
**Complete the sentence:**  
In the relational database you can use **_normalization_** ✅ to eliminate data repetition and inconsistent dependencies by separating data into multiple tables and relating these tables by a foreign key.

---

## Question 39
**The HR department needs to send employee data monthly. Which type of processing should you use?**

1. Stream processing — ❌  
2. Online Analytical Processing (OLAP) — ❌  
3. Online Transaction Processing (OLTP) — ❌  
4. Batch processing — **✅**

---

## Question 40
**For each statement, select Yes or No.**

- Each row in a table contains the same set of columns. — **Yes** ✅  
- Data is stored in a tabular format. — **Yes** ✅  
- Different rows in the same table can share the same primary key value. — **No** ❌

---

## Question 41
**Line chart that tracks past sales and also shows projected sales — which analysis?**

1. Prescriptive — ❌  
2. Diagnostic — ❌  
3. Predictive — **✅**  
4. Descriptive — ❌

---

## Question 42
Match each business question to the analysis type:

- You need to cut cost of sales by at least 5% over the next two quarters. — **Prescriptive** ✅  
- You need to see the correlation between ad campaigns and recent orders. — **Diagnostic** ✅  
- You need to determine when to rotate floor stock from summer to fall items. — **Predictive** ✅

---

## Question 43
For each statement, select Yes or No.

- Extract, transform, and load (ETL) can reduce the transfer of sensitive data to destination systems. — **Yes** ✅  
  *(ETL can transform/mask/redact before loading.)*

- Extract, load, and transform (ELT) transforms data by using a compute resource independent of the source system and destination system. — **Yes** ✅  
  *(ELT typically uses target compute e.g., in data warehouse / Synapse.)*

- Extract, load, and transform (ELT) minimizes the time it takes to copy large volumes of data to destination systems. — **Yes** ✅

---

## Question 44
**Complete the sentence:**  
The Extract, Load and Transform (ELT) process **loads raw data into the destination first and then performs transformations in the destination compute (for example a data warehouse or analytics engine).** ✅

---

## Question 45
**Scenario:** Extract from on-prem SQL Server, XML, Blob, Table Storage; minimal transform (filter, sort, dedupe) and map to Azure SQL Managed Instance. Which product?

1. Azure Synapse Analytics — ❌  
2. SQL Server Integration Services (SSIS) — ❌  
3. **Azure Data Factory (ADF)** — **✅**  
4. Azure Data Share — ❌

*(ADF is the cloud ETL/ELT orchestration service.)*

---

## Question 46
**Which service for each step?** (suggested mapping)

- **Extract data** → **Azure Data Factory** ✅  
- **Data storage (raw)** → **Azure Data Lake Storage (ADLS Gen2)** ✅  
- **Final processed store / analytics target** → **Azure SQL Database** (or Synapse as appropriate) ✅

---

## Question 47
Which type of analytics to know which factors influence purchase of a product?  
1. Predictive analytics — ❌  
2. Prescriptive analytics — ❌  
3. Descriptive analytics — ❌  
4. **Diagnostic analytics** — **✅**

---

## Question 48
Which analytics technique created the forecast chart?  
1. **Predictive analytics** — **✅**  
2. Diagnostic — ❌  
3. Descriptive — ❌  
4. Prescriptive — ❌

---

## Question 49
Which chart type should you use?  
1. Bubble chart — ❌  
2. **Bar chart** — **✅**  
3. Pie chart — ❌  
4. Doughnut chart — ❌

---

## Question 50
**Complete the sentence:**  
**Business Intelligence (BI)** allows businesses to achieve better decision making by combining technologies, applications, and processes to collect, analyze, and present business information. ✅

---

## Question 51
**Complete the sentence:**  
**Data integration (ETL/ELT)** is the process of getting data from source datasets, preparing this data using business rules, and saving it in a data store for use in reports and dashboards. ✅

---

## Question 52
Which visual type should you use?  
1. Line chart — ❌  
2. Bar/column chart — ❌  
3. Scatter chart — ❌  
4. **Key influencers chart** — **✅**

---

## Question 53
Which technique?  
1. Descriptive — ❌  
2. Predictive — ❌  
3. **Diagnostic analytics** — **✅**  
4. Cognitive analytics — ❌

---

## Question 54
Match descriptions → structure:

- The structure used to sort values to help optimize query performance — **Index** ✅  
- A virtual table whose contents is defined through a query — **View** ✅  
- The value used to identify each table entity as unique — **Primary key** ✅

---

## Question 55
Which application is best supported through a relational database?

1. Streaming media files: No — ❌  
2. CRM with entities with different numbers of values: No — semi-structured often better — ❌  
3. Rapidly load IoT sensor values: No — ❌  
4. **An order processing engine for an online sales application (OLTP)** — **✅**

---

## Question 56
You design a query joining customer, inventory and order data with calculated columns and want the query readily available while keeping normalization.  
What should you create?  
1. Key — ❌  
2. Table — ❌  
3. **View** — **✅**  
4. Index — ❌

---

## Question 57

- The clustered index defines the order in which data rows are stored and sorted in the table. — **Yes** ✅  
- You can define one or more clustered indexes per table. — **No** ❌ (only one clustered index per table)  
- You can define nonclustered indexes after you implement a clustered index. — **Yes** ✅  
- A table with an implemented clustered index is called a heap. — **No** ❌ (a heap is a table *without* clustered index)

---

## Question 58
**Complete the sentence:**  
A **Primary key** ✅ is a constraint used to enforce data integrity in relational databases by indicating which column (or combination of columns) uniquely identifies each row in a table.

---

## Question 59
**Complete the sentence:**  
A **View** ✅ is a database object where content is based on a query. You can use this to query data from one or more tables and display the data in a different structure, like filtering or joining data from different tables.

---

## Question 60
Which is correct?  
1. **To improve read performance by searching for specific data in a table.** — **✅**  
2. To create relationships between tables. — ❌  
3. To query data from one or more tables and display the data in a different format. — ❌  
4. To enforce data integrity by indicating which column uniquely identifies each row in a table. — ❌

---

## Question 61
Best scenario:  
1. **Guarantee strong consistency while processing transactions** — **✅**  
2. Large images and videos — ❌  
3. Columnar analytics — ❌  
4. Dynamic / semi-structured schema — ❌

---

## Question 62

- A structure where content is based on a query — **View** ✅  
- A structure used to store data in rows and columns — **Table** ✅  
- A structure that improves read performance in data searching — **Index** ✅

---

## Question 63

- To uniquely identify each row in the table. — **Primary Key** ✅  
- To easily access aggregated results from the table. — **View** ✅  
- To quickly access rows using specific product tags in the table. — **Index** ✅

---

## Question 65

- Inventory management system — **Azure SQL Database** ✅  
- Enterprise data analytics system — **Azure Synapse Analytics** ✅  
- Finance and accounting system — **Azure SQL Database** ✅

*(Finance could also use Managed Instance for near-100% compatibility; general cloud PaaS Azure SQL DB is commonly used.)*

---

## Question 66
Which service should you implement?  
1. **Azure SQL Database** — **✅**  
2. SQL Server on Azure VMs — ❌  
3. Azure SQL Managed Instance — ❌  
4. Azure SQL Edge — ❌

---

## Question 67

- **Infrastructure as a Service (IaaS)** → **PostgreSQL on Azure VMs** ✅  
- **Platform as a Service (PaaS)** → **Azure Database for PostgreSQL** ✅  
- **Software as a Service (SaaS)** → *(no typical Microsoft SaaS for PostgreSQL; leave blank)*

---

✅ **Tip before exam:**  
Focus on understanding **ETL vs ELT**, **Azure data services (Synapse, Data Factory, Databricks, Cosmos DB)**, **storage tiers**, and **types of analytics (descriptive, diagnostic, predictive, prescriptive)**.

Good luck on your **DP-900 exam!**
