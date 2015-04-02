1)`curl -i -X POST -H "Content-Type:application/json" -d '{"name":"Test Event 1", "description":"Test description 1"}' http://localhost:8080/events`   
HTTP/1.1 201 Created   
Server: Apache-Coyote/1.1   
Location: http://localhost:8080/events/1   

2) `curl -v localhost:8080/events/1`   
HTTP/1.1 200 OK   
Server Apache-Coyote/1.1 is not blacklisted   
Server: Apache-Coyote/1.1   
Content-Type: application/hal+json;charset=UTF-8   

No ETag in response, should there be?


