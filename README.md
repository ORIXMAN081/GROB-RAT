# GrobRat

GrobRat is a web-based remote access tool that allows users to connect and control devices directly from a browser — no installation required.

---

## 🚀 Features
- Remote desktop control (mouse & keyboard)
- 📡 Live screen streaming (low-latency via WebRTC)
- Secure connection (WebRTC / encryption)
- File transfer support
- Multi-user sessions
- Simple connection via ID or link
- Real-time communication (WebSockets)

---

## 📡 Streaming

GrobRat uses WebRTC for low-latency screen streaming, allowing users to view and control remote devices in real time directly from the browser.

---

## ⚙️ Installation (Ubuntu only)

> ⚠️ Windows is not supported

### 1. Install Node.js
sudo apt update
sudo apt install -y nodejs npm

---

### 2. Clone repository
git clone https://github.com/ORIXMAN081/GROB-RAT.git
cd GROB-RAT

---

### 3. Install dependencies
npm install

---

### 4. Setup environment
cp .env.example .env.local
nano .env.local

---

### 5. Build project
npm run build

---

### 6. Start project
npm run start

---

## ⚙️ How it works
1. Start client / agent on target device  
2. Get unique session ID  
3. Open GrobRat web panel  
4. Enter ID and connect instantly  

---

## 🧠 Tech Stack
- Backend: Node.js  
- Frontend: React / Next.js  
- Realtime: WebSocket  
- Streaming: WebRTC  
- Auth: JWT  

---

## 💡 Idea
GrobRat focuses on simplicity — remote access without installing heavy software.

---

## 👤 Author
BY ORIXMAN
