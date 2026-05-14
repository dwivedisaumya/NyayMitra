# ⚖️ NyayMitra – AI-Powered Legal Intelligence System  
### *“Justice, simplified. Access, amplified.”* 🤝🇮🇳

**NyayMitra (Justice Friend)** is a **production-grade legal-tech platform** built to bridge the gap between **complex legal language** and **everyday citizens**.  
It empowers users with **instant, bilingual legal intelligence**, **actionable judicial roadmaps**, and **accessibility-first design**, tailored specifically for the **Indian legal ecosystem**.



---

## 🚀 Live Deployment

🌐 **Web Interface:**  
👉 https://nyay-mitra-frontend.vercel.app/

⚙️ **Backend API:**  
👉 https://nyay-mitra-backend.onrender.com/

---

## ✨ Core Capabilities

### 📑 Multimodal Legal Document Intelligence
- Upload **high-resolution PDFs or images**
- Native vision understanding (no manual OCR)
- Handles notices, FIRs, contracts, affidavits & court documents

---

### 🌍 Neural Bilingual Legal Engine
- Outputs in **English + Sahaj Hindi**
- Context-aware phrasing for Indian users
- Designed for clarity, not courtroom jargon

---

### 🧭 Judicial Roadmap & Timeline Generator
- Step-by-step **legal action roadmap**
- Estimated **procedural timelines**
- Case **complexity classification**: 🟢 Low | 🟡 Medium | 🔴 High

---

### 🔍 Rights Encyclopedia (BNS + Constitution)
- Real-time search for **citizen protections**
- Fully aligned with **Bharatiya Nyaya Sanhita (BNS)**
- Covers rights, sections, safeguards & obligations

---

### 🔊 Accessibility-First Design
- **Bilingual Text-to-Speech (TTS)**
- Designed for inclusivity & low-literacy access
- Mobile-friendly and assistive-tech ready

---

## 📸 Project Gallery

### 🏛️ Dashboard UI  
🔗 **Direct View:** https://nyay-mitra-frontend.vercel.app/

<img width="1900" height="827" alt="Screenshot 2026-02-17 131614" src="https://github.com/user-attachments/assets/1eea913c-d3c6-4eca-af21-8c8e0421b881" />

---

### 📤 Smart Upload  
🔗 **Document Upload Flow:** https://nyay-mitra-frontend.vercel.app/

<img width="1902" height="876" alt="Screenshot 2026-02-17 131704" src="https://github.com/user-attachments/assets/26a15ef3-fefa-4a8b-9bbd-e6e9f9e1f955" />

---

### 🧠 AI Logic & Legal Roadmap  
🔗 **AI Analysis Engine:** https://nyay-mitra-frontend.vercel.app/

<img width="1898" height="872" alt="Screenshot 2026-02-17 131811" src="https://github.com/user-attachments/assets/37617fef-5cbb-4e9f-9639-a9a0e8ecb416" />

---

### 🧭 Rights Encyclopedia  
🔗 **Rights Search:** https://nyay-mitra-frontend.vercel.app/

<img width="1900" height="863" alt="Screenshot 2026-02-17 131504" src="https://github.com/user-attachments/assets/603d3589-65a3-4d9f-94da-beaa7ca5223c" />

---

### 🦶 Footer & Accessibility  
🔗 **Footer & Navigation:** https://nyay-mitra-frontend.vercel.app/

<img width="1899" height="624" alt="Screenshot 2026-02-17 132027" src="https://github.com/user-attachments/assets/0252b4ef-e2ee-4a8a-9e1c-55decf6fcb2d" />

---

## 🛠️ Technical Uniqueness

### 🛡️ Resilient API Architecture (Gemini Free-Tier Safe)

To operate reliably under the **15 RPM quota**, NyayMitra implements:

- **🔐 Global Async Locking**  
  Backend semaphore queues requests safely

- **🔁 Exponential Backoff**  
  Smart retries on `429 Resource Exhausted` errors

- **⏱️ Frontend Debouncing**  
  Prevents accidental API flooding (1 req/sec)

---

### 🎨 Premium Aesthetic UI
- ✨ Glassmorphism dark theme with gold accents
- 🎞️ Framer Motion micro-interactions
- 📱 Fully responsive, mobile-first layout
- ⚖️ **BNS-compliant legal logic**

---

## 💻 Tech Stack

### 🖥️ Frontend
- React.js  
- Tailwind CSS  
- Framer Motion  
- Lucide-React  

### ⚙️ Backend
- FastAPI (Python)  
- AsyncIO  
- Google GenAI SDK  

### 🚀 DevOps
- GitHub Actions  
- Render (Backend)  
- Vercel (Frontend)  

---

## ⚙️ Setup & Installation

### 🔧 Backend
```bash
cd backend
pip install -r requirements.txt

# Create .env
GEMINI_API_KEY=your_api_key_here

uvicorn app.main:app --reload

cd frontend
npm install

# Create .env
REACT_APP_API_URL=backend_url_here

npm start

🤝 Connect with the Developer

👩‍💻 Saumya Dwivedi
