# Lambda-DynamoDB-Ice-cream-shop-example

npm init -f
npm install aws-sdk claudia-api-builder -S 
claudia create --region us-east-1 --api-module index --policies policy
claudia update

1. index.js - Node JS for post and get for icecreams
2. ./policy/dynamodb-policy.json - AWS policy for DynamoDB
3. Create table in AWS DynamoDB, table name:icecreams, primary key:icecreamid

