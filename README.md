<div align="center">

# ✨ AURA AI
### *Your Intelligent Personal Assistant, Powered by Google Gemini*

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-AURA_AI-8B5CF6?style=for-the-badge&logo=vercel)](https://lnkd.in/d4NAgxif)
[![AI Engine](https://img.shields.io/badge/Gemini_2.5-Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Status](https://img.shields.io/badge/System-Online_%26_Operational-10B981?style=for-the-badge)]()
[![Contact](https://img.shields.io/badge/Email-dhurvedang4104%40gmail.com-EF4444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhurvedang4104@gmail.com)

</div>

---

## 🧭 Table of Contents
* [About The Project](#-about-the-project)
* [Key Highlights & Features](#-key-highlights--features)
* [System Preview & Snapshots](#-system-preview--snapshots)
* [System Architecture Flow](#-system-architecture-flow)
* [Tech Stack](#-tech-stack)
* [Live Experience](#-live-experience)
* [Author & Maintainer](#-author)

---

## 💡 About The Project

**AURA AI** is a state-of-the-art, productivity-driven web assistant engineered to bridge the gap between human intent and machine execution[cite: 1, 2]. Designed with a clean minimalist interface and driven by **Google’s Gemini 2.5 Flash API**, AURA AI empowers users to conduct deep research, accelerate writing workflows, brainstorm ideas, and troubleshoot problems seamlessly in real time[cite: 1, 2].

---

## ⚡ Key Highlights & Features

| Feature | Description |
| :--- | :--- |
| **💬 Dynamic Conversations** | Engage in fluid, context-aware dialogues that seamlessly track and adapt to nuanced prompts. |
| **🎯 Purpose-Built Productivity** | Tailored tools built specifically to optimize daily tasks, code debugging, research, and ideation[cite: 2]. |
| **🚀 Gemini 2.5 Flash Engine** | Leveraging Google's ultra-fast model infrastructure for high-throughput, low-latency reasoning[cite: 2]. |
| **🗂️ Unified Workspace Console** | Features a dedicated **Active Chat Sandbox** paired with an intuitive **Chat History Panel** for effortless session navigation[cite: 3]. |

---

## 📸 System Preview & Snapshots

> *A visual walkthrough of the AURA AI user interface across various states and modules.*

### 1️⃣ Landing Page & System Status Bar
*The initial welcome screen featuring quick routing, user identification, and a live Gemini 2.5 Flash status indicator.*  
<div align="center">
  <img src="assets/snapshot1.png" alt="Landing Page Preview" width="90%"/>
  <br><sub><em>*(Replace `assets/snapshot1.png` with your actual file path or image URL)*</em></sub>
</div>

---

### 2️⃣ About Core Capabilities Module
*An overview panel breaking down the foundational pillars: Natural Conversations, Purpose-Built Design, and Gemini Integration[cite: 2].*  
<div align="center">
  <img src="assets/snapshot2.png" alt="About Section Preview" width="90%"/>
  <br><sub><em>*(Replace `assets/snapshot2.png` with your actual file path or image URL)*</em></sub>
</div>

---

### 3️⃣ Interactive Workspace Console & Chat Sandbox
*The core functional workspace where users interact with the active sandbox environment and manage historical chat logs[cite: 3].*  
<div align="center">
  <img src="assets/snapshot3.png" alt="Workspace Console Preview" width="90%"/>
  <br><sub><em>*(Replace `assets/snapshot3.png` with your actual file path or image URL)*</em></sub>
</div>

---

## 📊 System Architecture & Data Flow

```mermaid
graph TD
    User([👤 User / Browser]) -->|Submits Prompt| UI[🖥️ AURA AI Frontend UI]
    UI -->|Active Chat Sandbox| Backend[⚙️ Backend Service / API]
    Backend -->|Payload Request| Gemini[🧠 Google Gemini 2.5 Flash API]
    Gemini -->|Streamed Response| Backend
    Backend -->|Persists Data| DB[(🗄️ Chat History Panel / DB)]
    Backend -->|Renders Output| UI
    UI -->|Displays Solution| User
