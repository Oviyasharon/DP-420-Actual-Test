## MetaData
Question Type : Single Choice

## Question
You run the query below against a container in the Azure Cosmos DB Core (SQL) API account.
SELECT   
    IS_NUMBER(true) AS A,   
    IS_NUMBER({prop: "value"}) AS B,   
    IS_NUMBER([1, 2, 3]) AS C,  
    IS_NUMBER({stringProp: "value"}.stringProp) AS D, 
    IS_NUMBER({numberProp: 1}.numberProp) AS E

## Options
Option 1 : [{"A": false, "B": false, "C": false, "D": false, "E": true}]
Option 2 :  [{"A": true, "B": true, "C": false, "D": false, "E": true}]
Option 3 : [{"A": false, "B": false, "C": true, "D": false, "E": true}]
Option 4 : [{"A": true, "B": false, "C": false, "D": true, "E": false}]

## Answers
Option 1 : 12

## Reference Links
https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/query/is-number

## Explanation
The following example checks objects of JSON Boolean, number, string, null, object, array, and undefined types using the IS_NUMBER function. 