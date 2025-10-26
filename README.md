# WebSocket Chat Application

A real-time chat application built with Spring Boot WebSocket and Java.

## Features

- Real-time messaging using WebSocket protocol
- Simple and intuitive chat interface
- Support for sending and receiving messages in a chat room

## Technologies Used

- Java 17
- Spring Boot
- Spring WebSocket
- HTML/JavaScript
- Maven

## Prerequisites

Before running this application, make sure you have:

- Java JDK 17 or higher installed
- Maven installed
- Your favorite IDE (IntelliJ IDEA, Eclipse, VS Code, etc.)

## Getting Started

1. Clone the repository:
```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:
```bash
cd app
```

3. Build the project:
```bash
./mvnw clean install
```

4. Run the application:
```bash
./mvnw spring-boot:run
```

5. Access the chat application:
Open your web browser and navigate to `http://localhost:8080`

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── chat/
│   │           └── app/
│   │               ├── config/
│   │               │   └── WebSocketConfig.java
│   │               ├── controller/
│   │               │   └── ChatController.java
│   │               ├── model/
│   │               │   └── ChatMessage.java
│   │               └── AppApplication.java
│   └── resources/
│       ├── static/
│       ├── templates/
│       │   └── chat.html
│       └── application.properties
```

## Docker Support

The application includes Docker support. To run using Docker:

1. Build the Docker image:
```bash
docker build -t websocket-chat-app .
```

2. Run the container:
```bash
docker run -p 8080:8080 websocket-chat-app
```

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
