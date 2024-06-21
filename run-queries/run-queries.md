# Run Queries in HeatWave

## Introduction

You can run queries on the data in Amazon S3 from the HeatWave console, without having to copy the data in the MySQL database. The performance of querying data in Amazon S3 is identical to the performance of querying data inside the database. The HeatWave console provides a Query Editor to ease your interaction with the DB system eliminating the need to go back and forth between the Console and an external MySQL client for resource and data management.

_Estimated Time:_ 10 minutes

### Objectives

In this lab, you will be guided through the following task:

- Run queries with  HeatWave.

### Prerequisites

- Must complete Lab 2

## Task 1: Run queries with HeatWave

1. In the **Workspaces** tab, click **Query Editor**. Under Database Objects, you can see the schemas and tables in the MySQL DB System, the associated table definitions, and the HeatWave load status of each table.
 
    ![Schema details](./images/1-heatwave-loaded-details.png "Schema details")

2. Enter the following query in the query editor:

    ```bash
    <copy>USE airportdb; 
    SELECT booking.col_5, count(*) FROM booking WHERE booking.col_5 > 500 GROUP BY booking.col_5 ORDER BY booking.col_5 LIMIT 100;</copy> 
    ```

3. Click the **Run Query** button to run the query.

    When you run the query with HeatWave, it took only 0.0279 seconds.

    ![Run queries with HeatWave](./images/2-run-query.png "Run queries with HeatWave")

You may now **proceed to the next lab**.

## Learn More

- [MySQL HeatWave on AWS Service Guiden](https://dev.mysql.com/doc/heatwave-aws/en/)

- [MySQL Database Documentation](https://dev.mysql.com/)

## Acknowledgements

- **Author** - Aijaz Fatima, Product Manager
- **Contributors** - Mandy Pang, Senior Principal Product Manager
- **Last Updated By/Date** - Aijaz Fatima, Product Manager, June 2024
