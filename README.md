# AWS DynamoDB Assignment

This repository contains my AWS DynamoDB assignment. In this assignment, I created a DynamoDB table, added items to it, and performed queries to retrieve and view the data. Below are the steps I followed to complete the assignment and the concepts I learned along the way.

## Project Overview

This project demonstrates how to:

1. Create a DynamoDB table on AWS.
2. Add items to the table using the AWS Console.
3. Query data from the table.
4. Scan the table to view all items.
5. Optionally, create a Global Secondary Index (GSI) for alternate queries.

## Table Setup

The table created is called `ace-product-table`. The **Partition Key** is `ProductID`, and the data is added with the following attributes:

- ProductID
- Name
- Price
- Stock

The table was created with **On-demand capacity** to automatically handle read and write throughput.

## Files in this Repository

- `README.md`: Overview of the project.
- `HOW-TO-USE-DYNAMODB.md`: Step-by-step guide on using DynamoDB, including how I created the table, added items, and queried the data.

## Screenshots

- **Items Tab Screenshot**: This screenshot shows the items I added to the table.
- **Query Results Screenshot**: This screenshot shows the results of a successful query to retrieve an item by its `ProductID`.

## Concepts Learned

- **Partition Key**: The partition key uniquely identifies each item in the table. I used `ProductID` as the partition key.
- **On-demand Capacity**: This mode allows DynamoDB to automatically scale the table's capacity to handle variable workloads.
- **Global Secondary Index (GSI)**: Though not created for this assignment, a GSI would allow you to query the table by other attributes, such as `Price`.

## How to Use

See `HOW-TO-USE-DYNAMODB.md` for detailed instructions on how to interact with the DynamoDB table and how to query the data.

