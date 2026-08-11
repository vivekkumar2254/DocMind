# DocMind

AI-powered document assistant using RAG (Retrieval-Augmented Generation).

## Project Structure

```
DocMind/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── docmind/
│   │   │           └── DocMind/
│   │   │               ├── DocMindApplication.java
│   │   │               ├── config/
│   │   │               │   ├── AiConfig.java
│   │   │               │   └── VectorStoreConfig.java
│   │   │               ├── controller/
│   │   │               │   ├── DocumentController.java
│   │   │               │   └── ChatController.java
│   │   │               ├── service/
│   │   │               │   ├── DocumentService.java
│   │   │               │   ├── ChatService.java
│   │   │               │   └── RagService.java
│   │   │               ├── serviceimpl/
│   │   │               │   ├── DocumentServiceImpl.java
│   │   │               │   ├── ChatServiceImpl.java
│   │   │               │   └── RagServiceImpl.java
│   │   │               ├── dto/
│   │   │               │   ├── ChatRequest.java
│   │   │               │   ├── ChatResponse.java
│   │   │               │   └── DocumentResponse.java
│   │   │               ├── entity/
│   │   │               │   └── Document.java
│   │   │               ├── repository/
│   │   │               │   └── DocumentRepository.java
│   │   │               ├── exception/
│   │   │               │   ├── DocumentNotFoundException.java
│   │   │               │   └── GlobalExceptionHandler.java
│   │   │               └── util/
│   │   │                   └── FileUtil.java
│   │   │
│   │   └── resources/
│   │       ├── application.properties
│   │       └── prompts/
│   │           └── rag-prompt.txt
│   │
│   └── test/
│
├── uploads/
├── pom.xml
└── README.md
```
