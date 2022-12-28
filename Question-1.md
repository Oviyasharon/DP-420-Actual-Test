## MetaData
Question Type : Single Choice

## Question
You are developing a system of engagement for a multinational bank. The bank operates in 5 different geographies. They have significant market share in 2 of the geographies and very small market share in the other 3. You consider using the geographyId as the partition key for this container. 
Which of the following statements would be true?

## Options
Option 1 : This partition key will cause fan out when filtering by geographyId
Option 2 : This partition key will not cause throughput hot partitions
Option 3 : This partition key will cause storage hot partitions
Option 4 : All of the above

## Answers
Option 3 : 12

## Reference Links
https://learn.microsoft.com/en-us/azure/cosmos-db/partitioning-overview

## Explanation
Throughput provisioned for a container is divided evenly among physical partitions. A partition key design that doesn't distribute requests evenly might result in too many requests directed to a small subset of partitions that become "hot." Hot partitions lead to inefficient use of provisioned throughput, which might result in rate-limiting and higher costs.