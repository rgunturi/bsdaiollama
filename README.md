Download and install ollama locally
run ollma run <any model>

Add dependency 
<dependency>
  <groupId>org.springframework.ai</groupId>
  <artifactId>spring-ai-starter-model-ollama</artifactId>
</dependency>

if ollama is running locally no additional setting is rqured
if ollama runing on another host use its url

application.properties 
spring.ai.model.chat=ollama
spring.ai.ollama.chat.model=gemma3:1b
// if ollama runing in another host 
spiring.ai.ollama.base-url="http://host:port

<no openai apikey required>

