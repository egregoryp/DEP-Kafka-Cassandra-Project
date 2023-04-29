![alt text](https://github.com/egregoryp/DEP-Kafka-Cassandra-Project/blob/main/zStreamingProjectArquitecture.png?raw=true)

# Project description
- **Reading**
    - Product searches in Ecommerce App (Kafka Producer in python - **Topico "product-search"**)
- **Data structures**
    - Json Streams of product searches with Customer ID and Location ID
    - Join with Location Catalog in csv file
    - Join with Customers Table in Cassandra Database
- **Aggregation**
    - Number of product searches by location and Customer
- **Output in file or other topic**
    - **Topic "product-customer-qty"**
- **Joins**
    - Product Search
    - Join with Location Catalog in csv file
    - Join with Customers Table in Cassandra Database

**Steps to implement:**
 1. Use files starting with z1.Proy
 2. Configure Cassandra Database using DataStax
 3. Create DB spark_db in Cassandra
 4. Create Tables Customer and Customer_search (file zCustomers.cql)
 5. Insert Customer Data
 6. Download CDATA Driver for ODBC to connect with PowerBI

 Note: extra file to generate files as an example is ProyCustomerFileWriter.ipynb
