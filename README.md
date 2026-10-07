# 💬 Real-Time Chat Application

A real-time chat application built using **Spring Boot, WebSocket, STOMP, SockJS, HTML, CSS, JavaScript, and Bootstrap**.

The application allows users to send and receive messages instantly without refreshing the webpage.

---

## 🚀 Features

- 💬 Real-time messaging
- ⚡ WebSocket communication
- 🔄 STOMP messaging protocol
- 🌐 SockJS support
- 🎨 Modern dark-themed UI
- 📱 Responsive design
- 👤 Displays sender name
- ↔️ Messages appear alternately on left and right
- 📜 Automatic chat scrolling
- 🔴 Interactive Send button

---

## 🛠️ Technologies Used

### Backend
- Java
- Spring Boot
- Spring WebSocket
- STOMP

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Tools
- IntelliJ IDEA
- Maven
- Git
- GitHub

---

## 📂 Project Structure

```text
realtime-chat-springboot/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/chat/app/
│   │   │   │   └── AppApplication.java
│   │   │   │
│   │   │   ├── config/
│   │   │   │   └── WebSocketConfig.java
│   │   │   │
│   │   │   ├── controller/
│   │   │   │   └── ChatController.java
│   │   │   │
│   │   │   └── model/
│   │   │       └── ChatMessage.java
│   │   │
│   │   └── resources/
│   │       ├── templates/
│   │       │   └── chat.html
│   │       └── application.yaml
│   │
│   └── test/
│
├── pom.xml
├── mvnw
├── mvnw.cmd
├── .gitignore
└── README.md
