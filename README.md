# FussionCordAPI — ふゅっしょんこーどAPI ✦ uwu

> Backend heart of FussionCord — built with Golang + Firebase + Postgres, designed to power dev-first chat, git magic, and AI workflows.  
> Fast, scalable, developer-friendly, and cute on the inside.

## 🌸 Smol Description
“FussionCordAPI — the cozy Golang-powered backend for FussionCord ✦ handles chat, git, AI, and dev workflows with speed and care. uwu”

## ✧ What is FussionCordAPI?
FussionCordAPI is the backend engine for FussionCord.  
It’s where all the real magic lives — authentication, chat services, repo integration, AI inference routing, and security layers.  

If FussionCord is the cozy café for devs to hang out in, then FussionCordAPI is the espresso machine making everything run smoothly behind the scenes. uwu ✦

## ✧ Tech Stack
- Language: Golang (concurrency + speed + simplicity)
- Frameworks: Gin / Fiber for REST API, gRPC for typed microservice comms
- Database:
  - Firebase Firestore (realtime + auth bootstrap)
  - PostgreSQL (relational data + git metadata)
- Cache & Queues: Redis (caching, pub/sub)
- Storage: MinIO (S3-compatible object store)
- Git Magic: go-git / libgit2 for repo operations
- AI Service Routing: Protobuf/gRPC contracts for OpenDevin integration
- Security: JWT + OAuth2, rate-limiting, audit logs, encryption for sensitive data
- Infra: GitHub Actions CI/CD, later Kubernetes

## ✧ Features (planned & in-progress)
- 🔑 Auth & User Management — Firebase auth + JWT
- 💬 Chat Service — Channels, DMs, threads, reactions
- 📂 Git Integration — Create, clone, browse repos, handle commits
- 🤖 AI Gateway — Routes requests to OpenDevin (future)
- 📡 Realtime Events — Websockets or Firebase sync
- 🛡 Security Core — Continuous verification + logging
- 📊 Monitoring — Prometheus + Grafana + Sentry

## ✧ Workflow (API-specific roadmap)
1. Bootstrap auth & user system with Firebase + JWT refresh tokens.  
2. Core chat service: messages, channels, threads (REST + WebSocket).  
3. Git service integration: using go-git for repo operations.  
4. AI service gateway: define gRPC interfaces for OpenDevin integration.  
5. Storage + file uploads via MinIO.  
6. Realtime sync layer: Redis pub/sub and WebSockets.  
7. Security hardening: audit logging, encryption, rate limiting.  
8. Observability: metrics, traces, logs with OpenTelemetry.  

## ✧ Getting Started (dev setup)

### Prerequisites
- Go 1.22+  
- Firebase project & service credentials  
- PostgreSQL running locally  
- Redis running locally  
- MinIO (optional, for object storage)  

### Setup
git clone https://github.com/yourusername/FussionCordAPI.git  
cd FussionCordAPI  

cp .env.example .env  

go run cmd/server/main.go  

## ✧ Contributing
We are open to contributions!  
- Issues = bugs, features, questions  
- PRs = fixes, docs, or even experimental features (yay!)  
- Please follow commit messages that are clear & happy ✧  

## ✧ License
MIT License — open-source and free uwu ✦

## ✧ Final Note
This API is still in its early rebirth stage! We’ve abandoned old progress and restarted everything to align with our clean, scalable new vision.  
Stay tuned — this backend will soon become the strong but soft-spoken pillar of FussionCord.  

Ganbatte! (がんばって) ✧ UwU