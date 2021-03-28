## [Mulesoft Meetups: Delayed Message Reprocessing](https://meetups.mulesoft.com/events/details/mulesoft-san-francisco-presents-delayed-message-reprocessing/)

### About the event: 

When synchronizing data between two systems, occasionally, data for a child object arrives at the target system slightly before the parent object creating a referential integrity error. Ideally, the child object should be resent to the target after the parent object arrives. The community at MuleLearning has developed a delayed reprocessing algorithm using queues and a scheduler. Developers must take special care with the queues' configuration to successfully reprocess errant messages on a time delay. In this session, Tim will build the error reprocessing solution from scratch so that all meetup participants can walk away with a working delayed reprocessing solution.

##### curl request for localhost (exported on Postman):  

```
curl --location --request POST 'localhost:8081/reprocessing' \
--header 'Content-Type: application/json' \
--data-raw '{
    "message": 0,
    "firstName": "Admasu",
    "lastName": "Jemaneh",
    "occupation": "MuleSoft superstar"
}'
```