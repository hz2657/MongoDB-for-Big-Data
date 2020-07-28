# MongoDB-for-Big-Data

1. imports dataset in MongoDB
2. write queries

resources:
1. MongoDB documentation: https://docs.mongodb.com/manual/reference/method/db.collection.aggregate/
2. w3resource: https://www.w3resource.com/mongodb/aggregation/mongodb-aggregatrion-unwind-operator.php
3. studio3T documentation: https://studio3t.com/knowledge-base/articles/mongodb-aggregation-framework/#aggregation-stages


Install MongoDB Guides: 
1. To install MongoDB copy/paste and run the following command in your terminal:
docker run -d -p 27017-27019:27017-27019 --name mongodb --restart always mongo

2. Every time you need to interact with MongoDB via the mongo shell, first execute this command to connect to the container:
docker exec -it mongodb bash

3. And then:
mongo
