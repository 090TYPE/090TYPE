<div align="center">

# 090_TYPE

**Software Developer** · Russia · Open to remote & freelance

[![GitHub](https://img.shields.io/badge/GitHub-090TYPE-181717?style=flat-square&logo=github)](https://github.com/090TYPE)
[![Profile Views](https://komarev.com/ghpvc/?username=090TYPE&color=58a6ff&style=flat-square&label=Profile+Views)](https://github.com/090TYPE)

</div>

---

## About

Full-stack developer with a strong focus on C# / .NET and systems programming in C++. I build things I actually use — desktop tools, production-shaped SaaS, real-time visualizers, crypto instruments, and AI-powered utilities. Most of my projects ship with Docker, tests, and CI from day one.

```
Languages   C# · C++ · Python · TypeScript · JavaScript
Backend     ASP.NET Core · .NET 9/10 · EF Core · REST · JWT
Frontend    React · TypeScript · Vite · Tailwind CSS
Desktop     WPF · WinForms · Avalonia · Qt6 · Dear ImGui
Infra       Docker · Docker Compose · RabbitMQ · MassTransit · YARP
Databases   PostgreSQL · SQLite
AI / CV     OpenCV · MediaPipe · ONNX · Whisper.net · ML.NET · OpenAI API
Crypto      Binance API · OKX · Bybit · WebSocket orderbook feeds
```

---

## Featured Projects

### ⭐ memscope — Real-time C++ heap visualizer
> C++20 · Dear ImGui · SDL2 · CMake · Windows / Linux / macOS

See every `new` and `delete` as it happens. While Valgrind and AddressSanitizer give you a report *after* the program exits, **memscope shows the heap *live***: a heat-mapped heap map, flame graph of memory by call path, leak suspects grouped by stack, double-free detection, per-thread breakdown, timeline, and one-click export.

[![memscope live overview](https://raw.githubusercontent.com/090TYPE/memscope/main/docs/overview.gif)](https://github.com/090TYPE/memscope)

[→ github.com/090TYPE/memscope](https://github.com/090TYPE/memscope)

---

### 🏗 BizMetrics — Multi-tenant analytics SaaS
> React 19 / TypeScript · ASP.NET Core 10 · PostgreSQL · MinIO · Stripe · Docker · Fly.io

A production-shaped SaaS: **tenant isolation via EF Core global query filters**, RBAC (Owner › Admin › Member › Viewer), Stripe billing with webhooks and trials, CSV ingestion via background workers and object storage, Google OAuth, rotating JWT refresh tokens, append-only audit log, rate limiting, Sentry observability, and Playwright e2e tests. 72 unit tests. Deployed on Fly.io.

Demo: `demo@bizmetrics.io` / `demo1234`

[→ github.com/090TYPE/BizMetrics](https://github.com/090TYPE/BizMetrics)

---

### 🛒 ShopLite — .NET 9 Microservices
> C# · .NET 9 · YARP · MassTransit · RabbitMQ · EF Core · PostgreSQL · Docker Compose

Event-driven microservices: UserService (JWT auth), OrderService (publishes `OrderCreated`), NotificationService (Worker consumer), YARP API gateway. Services never call each other over HTTP — everything goes through the message bus. Full Docker Compose setup, isolated databases per service.

[→ github.com/090TYPE/ShopLite](https://github.com/090TYPE/ShopLite)

---

### 🖥 Desktop & GUI Apps

| Project | Description | Stack |
|---------|-------------|-------|
| [**neode**](https://github.com/090TYPE/neode) | Hackable code editor — LSP autocomplete, live themes, plugin system, integrated terminal | Python · Qt6 |
| [**ClipVault**](https://github.com/090TYPE/ClipVault) | Cross-platform clipboard manager — tray app, text/image/file history, global hotkey, instant search, pin, 3 themes, LAN sync AES-256 | C# · Avalonia / .NET 10 |
| [**MeetingTranscriber**](https://github.com/090TYPE/MeetingTranscriber) | Local real-time transcription via Whisper (no cloud), AI summary via Claude/OpenAI, export TXT/PDF/SRT, SQLite history | C# · Avalonia / .NET 8 |
| [**TaskManager-To-Do**](https://github.com/090TYPE/TaskManager-To-Do-) | Desktop task management app | C# · WPF |

---

### 📈 Crypto & Finance

| Project | Description | Stack |
|---------|-------------|-------|
| [**orderbook-viz**](https://github.com/090TYPE/orderbook-viz) | Real-time crypto orderbook in the terminal — Binance, OKX, Bybit via WinHTTP WebSocket | C++ · WinHTTP |
| [**StockAnalyzer**](https://github.com/090TYPE/StockAnalyzer) | Technical analysis (RSI / MACD / Bollinger), backtesting, Telegram bot notifications | Python · Telegram Bot |
| [**CryptoAI**](https://github.com/090TYPE/CryptoAI) | AI-powered cryptocurrency analysis | C# · ML.NET |

---

### 🤖 AI & Computer Vision

| Project | Description | Stack |
|---------|-------------|-------|
| [**FaceDetector**](https://github.com/090TYPE/FaceDetector) | Real-time face & hand detection with Flask API | Python · OpenCV · MediaPipe · ONNX |
| [**FaceDetectorCLI**](https://github.com/090TYPE/FaceDetectorCLI) | Face/person detector for Siberian drone gimbal (Topotek, RTSP/UDP). Runs on PC & Raspberry Pi | Python · OpenCV |

---

### 🔧 Tools & Utilities

| Project | Description | Stack |
|---------|-------------|-------|
| [**PriceParser**](https://github.com/090TYPE/PriceParser) | Price tracker for Wildberries / Ozon / Яндекс.Маркет with Telegram alerts | Python · Selenium · SQLite · Tkinter |
| [**TaskFlow**](https://github.com/090TYPE/TaskFlow) | Full-stack Kanban board — drag-and-drop, JWT auth | React · TypeScript · ASP.NET Core 10 |
| [**Turing_machine**](https://github.com/090TYPE/Turing_machine) | Turing machine simulator | C++ |

---

## GitHub Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=090TYPE&show_icons=true&theme=midnight-purple&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=090TYPE&size_weight=0.5&count_weight=0.5&show_icons=true&theme=midnight-purple&hide_border=true)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=090TYPE&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&hide_border=true)

</div>

---

<div align="center">

**Open to remote work & freelance · Drop a ⭐ on something you find useful**

</div>
