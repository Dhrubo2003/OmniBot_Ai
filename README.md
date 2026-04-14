# 🤖 OmniBot — Multi-Modal Local AI Co-Pilot for Web Applications

OmniBot is a privacy-first, fully local AI assistant designed to seamlessly integrate into web applications. It combines cutting-edge language and vision models with real-time screen awareness to deliver an intelligent, interactive co-pilot experience — all without sending data to external servers.

---

## 🚀 Features

### 🧠 Local Multi-Modal AI
- Powered by **Llama3 (LLM)** and **LLaVA (Vision-Language Model)**
- Runs entirely via **Ollama** for 100% local inference  
- Ensures **data privacy** and zero external API dependency  

### 👁️ Visual Context Engine
- Built using **WebRTC** and `getDisplayMedia`
- Enables real-time screen capture and contextual understanding  
- Provides continuous visual reasoning to the AI  

### ⚙️ Function Calling (Tool Use)
- Autonomous execution of client-side actions  
- AI can:
  - Interact with UI elements  
  - Modify DOM dynamically  
  - Trigger workflows within the host application  

### 🔍 Circle to Search
- Inspired by modern mobile UX patterns  
- Select any on-screen region to analyze  
- Implemented using:
  - `html-to-image`  
  - Canvas API  
  - Vision-language processing via **LLaVA**  

### 🎯 Seamless UX
- Draggable, physics-based widget using **Framer Motion**  
- Global keyboard shortcuts for instant access  
- Lightweight and reusable React component  
