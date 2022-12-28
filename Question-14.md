## MetaData
Question Type : Single Choice

## Question
You have written a stored procedure that creates 5 items with 3 distinct logical partition key values. When you run this stored procedure, you receive an error. What is causing this?

## Options
Option 1 : Stored procedures are scoped to a single item
Option 2 : Stored procedures are scoped to a single logical partition
Option 3 : Stored procedures support the creation of at most 3 item
Option 4 : None of the items above

## Answers
Option 2 : 12

## Reference Links
https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/stored-procedures-triggers-udfs#scope-of-a-transaction

## Explanation
Stored procedures are associated with an Azure Cosmos DB container and stored procedure execution is scoped to a logical partition key. Stored procedures must include a logical partition key value during execution that defines the logical partition for the scope of the transaction. 