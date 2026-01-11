# Sky AI-Powered Team Collaboration Platform

**Sky** is a modern, real-time team collaboration platform designed for **high productivity and AI augmentation**.  
It combines real-time chat, channels, threads, notifications, and a signature **AI-powered voice-to-chat feature**, plus automated summarization and task extraction.

Unlike Discord or Slack, TeamCollab includes **custom AI models fine-tuned for your team’s workflow**, making it an intelligent, context-aware collaboration tool.

---

## Features

### 1. **Real-Time Chat**

- Channels, threads, and private messages
- Typing indicators and read receipts
- WebSocket-based push updates
- Redis for online presence and caching
- Fast and scalable architecture for large teams

### 2. **AI Voice-to-Chat (Signature Feature)**

- Convert voice to structured chat messages in real-time
- AI understands technical and domain-specific terms
- Can detect tasks, decisions, or code snippets from speech
- Fine-tuned custom speech-to-text model for natural team conversation

### 3. **AI Summaries & Task Extraction**

- Automatically summarizes channel conversations
- Extracts actionable tasks and decisions
- Generates daily or weekly summaries for team productivity

### 4. **Intent Detection & Smart Tagging**

- Automatically classifies messages as: Bug, Feature, Meeting, Question, Idea
- Can route messages or trigger workflows
- Domain-specific AI model for context-aware classification

### 5. **Voice Commands for Productivity**

- Users can give natural voice commands:
  > "Create weekly report for backend team"
- AI converts commands into structured tasks or messages
- Improves productivity beyond normal chat

### 6. **Integrated Knowledge Base**

- Chat history, AI summaries, and structured tasks stored in **Weaviate/pgvector**
- Context-aware AI can answer team-specific questions
- Acts as persistent “team memory”

### 7. **Event-Driven Scalable Architecture**

- Backend: Spring Boot
- Frontend: React + Tailwind CSS
- Database: PostgreSQL
- Real-time events: Kafka + Redis + WebSocket
- Microservices-ready for AI pipeline, notifications, analytics

### 8. **Custom AI Models**

- Speech-to-text fine-tuned for team chat
- Conversation summarization and task extraction
- Intent detection and smart tagging
- Trained with team-specific vocabulary and style

---

## Tech Stack

| Layer           | Technology                                     |
| --------------- | ---------------------------------------------- |
| Frontend        | React 19, Tailwind CSS, React Router           |
| Backend         | Spring Boot, REST API, WebSocket, Kafka, Redis |
| Database        | PostgreSQL                                     |
| AI & ML         | PyTorch, HuggingFace, Custom Fine-Tuned Models |
| Search / Memory | Weaviate / pgvector                            |
| Deployment      | Docker, Docker Compose, Optional Kubernetes    |
