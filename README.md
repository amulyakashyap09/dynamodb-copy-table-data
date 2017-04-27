# dynamodb-copy-table-data

## script copies data from dynamoDb table of old region to new region where s3 pipeline services are not available yet.

`const dynamodbCopyTableData = require('dynamodb-copy-table-data);`

`let myTables = ["users", "admin"];`

`let credentials = {"accessKeyId": "YOUR_accessKeyId", "secretAccessKey": "YOUR_secretAccessKey"};` 

`let oldRegion = "us-east-1";` 

`let newregion = "ap-southeast-1";`

`dynamodbCopyTableData.copyData(myTables, credentials, oldRegion, newregion);`

### Your tables would be copied. Thanks!

