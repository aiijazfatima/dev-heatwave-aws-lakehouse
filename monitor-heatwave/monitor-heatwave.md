# Monitor HeatWave Performance

## Introduction

The HeatWave console enables you to monitor the overall and per-node utilization of MySQL HeatWave hardware resources such as CPU, memory, and storage. It also provides a detailed breakdown of your resource consumption, such as data dictionary size, buffer pool size, and database connections.

_Estimated Time:_ 10 minutes

### Objectives

In this lab, you will be guided through the following task:

- Monitor HeatWave Performance - Cluster.
- Monitor HeatWave Performance - Workload.
- Monitor HeatWave Performance - Autopilot Shape Advisor.

### Prerequisites

- Must complete Lab 3.

## Task 1: Monitor HeatWave Performance - Cluster

You can monitor the HeatWave Cluster performance by performing the following steps:

1. Click the **Performance** tab.
2. Click the **Cluster** tab.
3. Select the DB System whose performance you want to monitor.

    You can see performance data such as cluster memory utilization, node memory utilization, and buffer pool.

    ![Performance  monitor cluster](./images/1-performace-monitor-cluster.png "Performance  monitor cluster")

## Task 2: Monitor HeatWave Performance - Workload

You can monitor the most recent queries that ran in HeatWave, allowing you to analyze when a query was executed, how long it took, and what the query actually does. Perform the following steps:

1. Click the **Performance** tab.
2. Click the **Workload** tab.
3. Select the DB System whose workload you want to monitor.

    You can see the details of execution and recent queries that were run on HeatWave.

    ![Performance  monitor workload](./images/2-performace-monitor-workload.png "Performance  monitor workload")

## Task 3: Monitor HeatWave Performance - Autopilot Shape Advisor

Autopilot Shape Advisor analyses the buffer pool usage, workload activity, and access patterns, and then assesses the suitability of the current MySQL shape. The advisor collects statistics at varying intervals and creates a prediction every five minutes while it is active. If there is insufficient or no activity in a five-minute interval Autopilot Shape Advisor cannot make a prediction for that interval. Perform the following steps:

1. Click the **Performance** tab.
2. Click the **Autopilot Shape Advisor** tab.
3. Select the  DB System  whose workload you want to monitor.

    You can see the shape prediction details and the recommended actions.

    ![performance  monitor workload](./images/3-performace-monitor-autopilot.png "performance  monitor -workload")
.

By making HeatWave natively available on AWS, you can very easily benefit from the only cloud database service that combines transactions, analytics, and machine learning services into one MySQL database, delivering real-time, secure analytics without the complexity, latency, and cost of ETL duplication—on AWS.
HeatWave on AWS is optimized for AWS with a superior architecture that delivers higher performance and lower cost, as demonstrated by industry-standard benchmarks.

## Learn More

- [HeatWave on AWS Service Guide](https://dev.mysql.com/doc/heatwave-aws/en/)

- [MySQL Database Documentation](https://dev.mysql.com/)

## Acknowledgements

- **Author** - Aijaz Fatima, Product Manager
- **Contributors** - Mandy Pang, Senior Principal Product Manager
- **Last Updated By/Date** - Aijaz Fatima, Product Manager, June 2024
