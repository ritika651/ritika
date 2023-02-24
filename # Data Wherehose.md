A Database Management System (DBMS) stores data in the form of tables, uses ER model and the goal is ACID properties.
A Data Warehouse is separate from DBMS, it stores a huge amount of data, which is typically collected from multiple heterogeneous sources like files, DBMS, etc
An ordinary Database can store MBs to GBs of data and that too for a specific purpose.
Data warehouse plays an important role in every business to store and analysis of all the past data and records of the company.
Data warehouse is designed to handle large queries that’s why it runs queries faster than the database.
The warehouse stores all your historical data which contains details about the business so that one can analyze it at any time and extract insights from it.
Data Warehousing can be applied anywhere where we have a huge amount of data and we want to see statistical results that help in decision making. 
The social networking websites like Facebook, Twitter, Linkedin, etc. are based on analyzing large data sets. 
Being a large amount of data, Data Warehouse is needed for implementing the same. Government uses a data warehouse to store and analyze tax payments which are used to detect tax thefts.
A data warehouse system enables an organization to run powerful analytics on huge volumes (petabytes and petabytes) of historical data in ways that a standard database cannot.
Data warehousing systems have been a part of business intelligence (BI) solutions for over three decades, but they have evolved recently with the emergence of new data types and data hosting methods.
The bottom tier consists of a data warehouse server, usually a relational database system, which collects, cleanses, and transforms data from multiple data sources through a process known as Extract, Transform, and Load (ETL) or a process known as Extract, Load, and Transform (ELT).
The middle tier consists of an OLAP (i.e. online analytical processing) server which enables fast query speeds. Three types of OLAP models can be used in this tier, which are known as ROLAP, MOLAP and HOLAP. The type of OLAP model used is dependent on the type of database system that exists.
The top tier is represented by some kind of front-end user interface or reporting tool, which enables end users to conduct ad-hoc data analysis on their business data.  
This schema consists of one fact table which can be joined to a number of denormalized dimension tables.
It is considered the simplest and most common type of schema, and its users benefit from its faster speeds while querying.
While not as widely adopted, the snowflake schema is another organization structure in data warehouses.
A data warehouse gathers raw data from multiple sources into a central repository, structured using predefined schemas designed for data analytics.
A data lake is a data warehouse without the predefined schemas.
A data mart is a subset of a data warehouse that contains data specific to a particular business line or department.
A database typically serves as the focused data store for a specific application, whereas a data warehouse stores data from any number (or even all) of the applications in your organization.
A cloud data warehouse is a data warehouse specifically built to run in the cloud, and it is offered to customers as a managed service.
A business can purchase a data warehouse license and then deploy a data warehouse on their own on-premises infrastructure.
A data warehouse appliance is a pre-integrated bundle of hardware and software—CPUs, storage, operating system, and data warehouse software—that a business can connect to its network and start using as-is. A data warehouse appliance sits somewhere between cloud and on-premises implementations in terms of upfront cost, speed of deployment, ease of scalability, and management control.
Data from disparate sources limit the ability of decision makers to set business strategies with confidence. 
All of the above combine to help an organization finding more opportunities in data, more quickly than is possible from disparate data stores.
Data Warehouse is a relational database management system (RDBMS) construct to meet the requirement of transaction processing systems.
It can be loosely described as any centralized data repository which can be queried for business benefits. It is a database that stores information oriented to satisfy decision-making requests.
A Data Warehouse (DW) is a relational database that is designed for query and analysis rather than transaction processing. It includes historical data derived from transaction data from single and multiple sources.
A Data Warehouse provides integrated, enterprise-wide, historical data and focuses on providing support for decision-makers for data modeling and analysis.
It is not used for daily operations and transaction processing but used for making decisions.
It is a database designed for investigative tasks, using data from various applications.
It supports a relatively small number of clients with relatively long interactions.
It includes current and historical data to provide a historical perspective of information.
Its usage is read-intensive.
It contains a few large tables.
"Data Warehouse is a subject-oriented, integrated, and time-variant store of information in support of management's decisions."
This is done by excluding data that are not useful concerning the subject and including all data needed by the users to understand the subject.
It requires performing data cleaning and integration during data warehousing to ensure consistency in naming conventions, attributes types, etc., among different data sources.
The data warehouse is a physically separate data storage, which is transformed from the source operational RDBMS.
Non-Volatile defines that once entered into the warehouse, and data should not change.
The idea of data warehousing came to the late 1980's when IBM researchers Barry Devlin and Paul Murphy established the "Business Data Warehouse."
In the absence of data warehousing architecture, a vast amount of space was required to support multiple decision support environments.
To help reporting as well as analysis
Maintain the organization's historical information
Be the foundation for decision making.
Data Warehouse is required to store the time variable data from the past. This input is made to be used for various purposes.
Some strategies may be depending upon the data in the data warehouse. So, data warehouse contributes to making strategic decisions.
Understand business trends and make better forecasting decisions.
Data Warehouses are designed to perform well enormous amounts of data.
The structure of data warehouses is more accessible for end-users to navigate, understand, and query.
Queries that would be complex in many normalized databases could be easier to build and maintain in data warehouses.
Data warehousing is an efficient method to manage demand for lots of information from lots of users.
Data warehousing provide the capabilities to analyze a large amount of historical data.
Data warehouse has to be ready for somewhat unexpected loads and types of queries, which demands a significant degree of flexibility and quick response time.
