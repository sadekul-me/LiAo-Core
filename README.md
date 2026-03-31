# 🚀 Li Ao Core

> **Next-Generation Human-Computer Interaction (HCI) System**
> Voice + Gesture + AI powered operating experience

---

## ⚠️ Project Status

🚧 **This project is currently in active development (Development Mode).**
Features are being built, tested, and improved continuously.
Expect breaking changes, incomplete modules, and ongoing updates.

---

## 🧠 Overview

**Li Ao Core** is a hybrid, high-performance system designed to redefine how humans interact with computers.

It combines:

* 🎤 Voice Control (Natural Language Commands)
* ✋ Gesture Recognition (Air Mouse / Hand Tracking)
* ⚡ High-Performance Execution Engine (C++)
* 🧠 AI Decision Layer (Python)
* 🖥️ Modern UI (React + Electron)

---

## 🏗️ Architecture

The system is built using a **modular, decoupled architecture**:

```
[ Input Layer ]
   ├── Camera (Gesture)
   └── Microphone (Voice)
          ↓
[ AI Layer (Python) ]
   ├── Vision (Hand Tracking)
   ├── Voice Processing
   └── Decision Engine
          ↓
[ Communication Layer ]
   ├── REST / WebSocket / IPC
          ↓
[ Core Engine (C++) ]
   ├── Command Execution
   ├── OS Control
          ↓
[ Output Layer ]
   ├── Desktop UI (Electron + React)
   └── System Actions (Mouse, Keyboard, Apps)
```

---

## 📁 Project Structure

```
liao-core/
│
├── apps/              # UI & applications
├── core/              # C++ execution engine
├── ai/                # Python AI layer
├── shared/            # Shared schemas & types
├── communication/     # IPC, WebSocket, REST
├── plugins/           # Extensions & integrations
├── configs/           # Configuration files
├── scripts/           # Automation scripts
├── tests/             # Testing suites
└── docs/              # Documentation
```

---

## ⚙️ Tech Stack

### Core Engine

* C++ (High-performance system control)

### AI Layer

* Python
* OpenCV, MediaPipe
* FastAPI

### Frontend

* React + TypeScript
* Electron

### Backend

* Node.js (Express)

### Communication

* WebSocket / REST / IPC

---

## 🎯 Key Features (Planned & In Progress)

* [ ] Real-time hand tracking (Air Mouse)
* [ ] Voice command execution
* [ ] AI-based intent recognition
* [ ] OS-level automation
* [ ] Plugin system (VS Code, Browser)
* [ ] Cross-platform support

---

## 🚀 Getting Started

### Prerequisites

* Node.js
* Python 3.x
* C++ Compiler (MinGW / GCC)
* Git

---

### Setup

```bash
# Clone repository
git clone <your-repo-url>

# Navigate to project
cd liao-core
```

---

### Run Modules (Example)

```bash
# Run AI server
npm run ai

# Run desktop app
npm run desktop

# Run backend API
npm run api
```

---

## 🧪 Development Notes

* The system is built using **layer separation principles**
* Each module is independently scalable
* Avoid mixing logic between:

  * AI
  * Core
  * UI

---

## 🔐 Design Philosophy

> “Think in layers, build in modules, scale without breaking.”

* Clean architecture
* High performance
* Future extensibility
* Real-world usability

---

## 📌 Roadmap

* Phase 1: Core Engine + AI Integration
* Phase 2: Gesture + Voice Control
* Phase 3: Full UI System
* Phase 4: Plugin Ecosystem
* Phase 5: Production Release

---

## 🤝 Contribution

This project is currently under active development.
Contribution guidelines will be added soon.

---

## 📄 License

License will be defined before production release.

---

## 👨‍💻 Author

**Li Ao Core** is being developed as a next-generation system aiming to push the boundaries of Human-Computer Interaction.

---

## ⚡ Final Note

This is not just a project.
This is the foundation of a **future computing experience.**

🚀
