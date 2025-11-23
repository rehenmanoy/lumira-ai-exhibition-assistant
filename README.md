# LUMIRA – QR-Activated Voice-Based AI Exhibition Assistant  
🚧 **Project Status: Under Active Development**

LUMIRA is an AI-powered, voice-interactive assistant designed for exhibitions and product expos.  
Visitors scan a **QR code** placed near a product → they are taken to a **web-based chatbot interface** → they can talk using **voice commands** and receive **AI-generated responses** based on a vector database of product information.

The goal is to provide an intuitive, hands-free experience for visitors to learn about products in real time.

Currently, this repository contains only the **backend (FastAPI + RAG logic)**.  
The frontend chatbot UI and full QR-routing workflow will be added in upcoming phases.

---

## 🔥 What LUMIRA Does

### 📱 **1. QR Code → Chatbot**
Each product/stall has a QR code.  
When scanned, the user is directed to a unique chatbot URL that loads product context.

### 🧠 **2. RAG-based AI Chat**
The chatbot uses a **Retrieval-Augmented Generation (RAG)** pipeline:
- Converts product documents into embeddings  
- Stores them in a **vector database**  
- Retrieves the most relevant chunks based on user query  
- Generates responses using an LLM (OpenAI / Claude / etc.)

### 🎤 **3. Voice Interaction**
Users can speak instead of typing.  
The assistant listens to the user and gives spoken or written responses.

### 📦 **4. Product Knowledge Engine**
The AI responds based on:
- Specs  
- Features  
- FAQs  
- Brochures  
- Product manuals  

(All converted into vector embeddings.)

---

## 📌 Current Backend Progress

✔ FastAPI backend set up  
✔ Basic bot/LLM integration scaffolded  
✔ Dataset and utilities folders organized  
✔ Requirements file added  
✔ Initial RAG structure preparation  
✔ Git/GitHub cleanup and repo ready for continued development  

Next steps include:
- Vector database integration  
- Embedding generation pipeline  
- Query → retrieval → response chain  
- Product ID mapping (via QR)  
- Chat session memory  
- Frontend integration

---

## 🧭 Development Status

LUMIRA is being built **incrementally**:

- Frontend is NOT included yet  
- QR logic is not connected yet  
- RAG is partially implemented  
- Voice UI will be added later  

Expect frequent updates as the project evolves.

---

## 🛠️ Tech Stack

### **Backend (Current)**
- Python  
- FastAPI  
- LLM API (OpenAI / Claude / Gemini – TBD)  
- PyCharm  
- Git & GitHub  

### **Planned Components**
- Vector Database (FAISS / Pinecone / Chroma)  
- Embedding generator  
- React + Vite chatbot UI  
- Voice recording + speech-to-text  
- Text-to-speech responses  
- Product management admin panel  

---

## 🤝 Contributing

This is an academic/portfolio project being developed by a single contributor.  
Contributions will be considered once the core architecture is stable.

---

## 👤 Author

**Rehen Manoy**  
B.Tech – Information Technology  
Amal Jyothi College of Engineering  

---

## 📜 License

This project is open-source and free to use for learning and academic purposes.
