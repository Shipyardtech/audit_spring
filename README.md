
# Goal

Write a new Audit Microservice using Spring Boot.  

## Requirements

* Setup spring boot application
* Create Audit Log DB Table
* DAO Layer - user JDBC templates
* REST Layer
  * Save audit record call
  * Get audit records by user id
  * Secure with spring security
  * Acceptance

## Example Post

{
    "request_time":"2019-12-06T11:58:08.398Z",
    "user_id":2,
    "request_body":"{\"data\":\"json\"}",
    "url":"http://www.noel.com",
    "http_status":200
}
