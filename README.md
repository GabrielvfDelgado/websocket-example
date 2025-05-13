# Spring WebSocket STOMP Exemplo

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-green.svg)
![Java](https://img.shields.io/badge/Java-11-blue.svg)
![Maven](https://img.shields.io/badge/Maven-3.8.1-red.svg)

Uma aplicação de exemplo que demonstra o uso de **WebSocket** com o protocolo **STOMP** no **Spring Boot**, baseada no tutorial oficial do Spring: [Messaging with STOMP over WebSocket](https://spring.io/guides/gs/messaging-stomp-websocket). A aplicação permite que usuários enviem um nome através de uma interface web e recebam uma saudação personalizada em tempo real.

## Funcionalidades

- **Comunicação em tempo real**: Usa WebSocket para troca de mensagens instantâneas entre cliente e servidor.
- **Protocolo STOMP**: Estrutura mensagens em destinos (`/app/hello` para enviar nomes, `/topic/greetings` para receber saudações).
- **Interface web simples**: Um formulário HTML onde o usuário digita um nome e vê as saudações retornadas.
- **Suporte a SockJS**: Garante compatibilidade com navegadores que não suportam WebSocket puro.
- **Segurança básica**: Escapa caracteres HTML para prevenir ataques XSS.

## Tecnologias Utilizadas

- **Spring Boot**: Framework para criar a aplicação web e gerenciar dependências.
- **Spring WebSocket**: Suporte para WebSocket e STOMP.
- **SockJS**: Biblioteca JavaScript para conexões WebSocket com fallback.
- **STOMP.js**: Biblioteca para comunicação STOMP no cliente.
- **jQuery**: Simplifica manipulação do DOM e eventos no cliente.
- **Maven**: Gerenciamento de dependências e build.
- **Java 21**: Linguagem principal do backend.

---

# Spring WebSocket STOMP Example

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-green.svg)
![Java](https://img.shields.io/badge/Java-21-blue.svg)
![Maven](https://img.shields.io/badge/Maven-3.8.1-red.svg)

A sample application demonstrating the use of **WebSocket** with the **STOMP** protocol in **Spring Boot**, based on the official Spring tutorial: [Messaging with STOMP over WebSocket](https://spring.io/guides/gs/messaging-stomp-websocket). The application allows users to send a name through a web interface and receive a personalized greeting in real-time.

## Features

- **Real-time communication**: Uses WebSocket for instant message exchange between client and server.
- **STOMP protocol**: Structures messages into destinations (`/app/hello` for sending names, `/topic/greetings` for receiving greetings).
- **Simple web interface**: An HTML form where users enter a name and view returned greetings.
- **SockJS support**: Ensures compatibility with browsers that do not support native WebSocket.
- **Basic security**: Escapes HTML characters to prevent XSS attacks.

## Technologies Used

- **Spring Boot**: Framework for building the web application and managing dependencies.
- **Spring WebSocket**: Support for WebSocket and STOMP.
- **SockJS**: JavaScript library for WebSocket connections with fallback.
- **STOMP.js**: Library for STOMP communication on the client side.
- **jQuery**: Simplifies DOM manipulation and event handling on the client.
- **Maven**: Dependency management and build tool.
- **Java 21**: Primary backend language.