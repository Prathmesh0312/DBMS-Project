**Overview:**
This project involves the design and implementation of a scalable database for a Smart Home Automation System using Azure SQL Server. The system efficiently manages real-time sensor data, automation rules, device states, and user interactions, ensuring enhanced energy efficiency and responsiveness.

**Database Design & Implementation**
Designed tables for key entities such as users, houses, devices, rooms, automation rules, events, and notifications to create a structured database.
Established relationships between tables (e.g., user-houses, user-automation rules) to reflect real-world smart home interactions.
**Data Handling & Querying**
Used T-SQL queries to insert and retrieve data, including user-house mappings, device types, and automation rules.
Leveraged JOINS, GROUP BY, HAVING, and DISTINCT to derive insights, such as identifying users with multiple houses and the most-used device types.
**Business Logic & Functions**
Developed a function to count automation rules per user, enabling personalized automation experiences.
Implemented a WINDOW FUNCTION to rank users based on their automation rule usage, providing insights into user engagement.
**Stored Procedures & Triggers**
Created a stored procedure to retrieve the latest device state, ensuring real-time responsiveness.
Implemented an AFTER INSERT trigger for the users table to automatically assign default notification preferences, improving usability.
**Transactions & Error Handling**
Implemented transactions to maintain data integrity, rolling back in case of errors (e.g., duplicate user entries).
Ensured reliable database operations with effective error-handling mechanisms to prevent data corruption.
**Conclusion**
This T-SQL-powered Azure SQL Server backend supports the real-time Smart Home Automation System by efficiently managing device states, automation rules, and user preferences while ensuring data accuracy, scalability, and system responsiveness.
