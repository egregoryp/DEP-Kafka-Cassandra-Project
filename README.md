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
    
1. **Explain the case**
2. **Demo**
3. **Questions**