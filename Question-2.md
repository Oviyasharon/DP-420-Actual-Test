## MetaData
Question Type : Single Choice

## Question
Assess the veracity of the statements below:
Statement 1: After you create an Azure Cosmos DB container or a database, you can update the provisioned throughput.
Statement 2: Containers in a shared throughput database share the throughput (RU/s) allocated to that database.

## Options
Option 1 : Only Statement 1 is true
Option 2 : Only Statement 2 is true
Option 3 : Both statements are true
Option 4 : Both statements are false

## Answers
Option 3 : 12

## Reference Links
https://learn.microsoft.com/en-us/azure/cosmos-db/set-throughput

## Explanation
After you create an Azure Cosmos DB container or a database, you can update the provisioned throughput. There is no limit on the maximum provisioned throughput that you can configure on the database or the container.<br>Containers in a shared throughput database share the throughput (RU/s) allocated to that database. With standard (manual) provisioned throughput, you can have up to 25 containers with a minimum of 400 RU/s on the database. With autoscale provisioned throughput, you can have up to 25 containers in a database with autoscale minimum 1000 RU/s (scales between 100 - 1000 RU/s). 
