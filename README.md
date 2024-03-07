# Tracing in Spring boot 3 with Micrometer plugin

1. Clone the repo & run the application in local
2. Send a GET request to `/test` endpoint
3. You will see the traceId and spanId in logs

### Sample Logs

```java
2024-03-08T00:21:49.729+05:30 " INFO [demo-application,traceId=9cc69f815d1d76bfa69b0986b9d3506f,spanId=06f175a0e23e7b8b]" 21972 --- [nio-8080-exec-1] com.spring3.demo.DemoApplication         : success response
```
