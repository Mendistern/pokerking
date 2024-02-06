# PokerKing

### A Java & React Multiplayer Poker Game

### Description

PokerKing is a multiplayer poker game that allows users to play poker with their friends and optionally an AI agent. The game is built using Java (Spring Boot), React & Tailwind, KeyCloack, Stripe, PostgresDB, RabbitMQ, and ELK-Stack for analytics. The game is played in real-time and allows users to chat with each other.

### Features

- Real-time multiplayer poker game
- User authentication and authorization
- Play with friends or AI agent
- Chat with other players
- Achievements and leaderboards
- Top-up balance using Stripe
- Analytics using ELK-Stack

### How to run the project

- Clone the repository
- Run `docker-compose up` in the root directory
- Run `docker compose up` in the `analytics/dockerSetup` directory

### How to run the game

- Spin up the Database, Analytics, and KeyCloack docker containers
- Run the Dockerfile in the game `poker` directory
- Run the Dockerfile in the game `frontend` directory
