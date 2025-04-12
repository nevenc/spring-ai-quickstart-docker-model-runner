# spring-ai-quickstart-docker-model-runner

This is an example of a simple Spring AI application that connects to
Docker Model Runner running in your Docker Desktop.

## Requirements
* Docker Desktop 4.40+ with Docker Model Runner enabled.

## Run the application

`./mvnw spring-boot:run`

## Test the application

```
http :8080

HTTP/1.1 200 
Connection: keep-alive
Content-Length: 101
Content-Type: text/plain;charset=UTF-8
Date: Tue, 11 Apr 2025 08:05:00 GMT
Keep-Alive: timeout=60

I'm an artificial intelligence model known as Llama. Llama stands for "Large Language Model Meta AI."
```

## References
* [Spring AI Docker Model Runner Chat](https://docs.spring.io/spring-ai/reference/api/chat/dmr-chat.html)
* [Spring AI with Docker Model Runner](https://spring.io/blog/2025/04/10/spring-ai-docker-model-runner)
* [How to get started with Spring AI](https://nevenc.com/how-to-get-started-with-spring-ai)
