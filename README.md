# RezMatch

**Get Past the Bots. Impress the Humans.**

RezMatch is an AI-powered resume analysis platform that helps job seekers optimize their resumes for both Applicant Tracking Systems (ATS) and human recruiters. The platform scores resumes based on key dimensions, provides actionable suggestions, and supports OpenAI integration for deeper insights.


<img width="1710" alt="截屏2025-06-04 下午11 50 44" src="https://github.com/user-attachments/assets/b43b0bec-853f-4b80-b1c2-619f8ba6db12" />


## 🔥 Features

### 🧠 **AI-Powered Resume Scoring**
- Supports **both local algorithms** and **OpenAI GPT-4** for flexible scoring
- Automatically evaluates resumes against job descriptions (JD)
- Highlights keyword overlap and relevance
- Suggests improvements for better alignment with job requirements
### 📄 Advanced Resume & JD Handling
- Upload resumes and JDs in **PDF format**
- Extract JD content from **job post URLs** using GPT-4
- Real-time **PDF text extraction with progress bar**

### 📊 Scorecard Visualization
- Multi-dimensional scoring:
  - ✅ **Keyword Match**
  - ✅ **Experience Relevance**
  - ✅ **Skills & Education Fit**
  - ✅ **Format & Structure**
  - ✅ **Contact Info Presence**
  - ✅ **Readability**
- Intuitive **color-coded badges** and **progress bars**
- **Radar chart** for quick score comparisons

### 🔒 User Authentication & Cloud Sync
- Email/password authentication via **Firebase Auth**
- Automatically saves each analysis result to **Firestore**
- Displays personal **analysis history** on the Dashboard

### 📈 Visual Dashboard
- Browse historical scores with **time stamps**
- Switch between **overall** and **dimension-based** charts
- Track performance improvement over time

### 🖥️ Modern Frontend Design
- Clean, responsive UI built with **React** and **Tailwind CSS**
- Smooth UX with animated transitions and tooltips
- Apple-style homepage design with Hero section and gradient buttons

### 💬 Analysis Insights
- Provides **personalized suggestions** for resume improvement
- GPT analysis includes **natural language explanations**
- Highlights **missing keywords** and **red flags**

### ⚙️ Developer-Friendly Architecture
- Modular React components for easy extension
- `.env` configuration for Firebase and OpenAI keys
- React Router-based navigation

## 🛠️ Tech Stack

| Layer       | Main Tools / Libraries                |
|-------------|---------------------------------------|
| Front-end   | React 18 · Vite · Tailwind CSS        |
| Auth & DB   | Firebase Auth · Firestore            |
| AI Engine   | OpenAI GPT-4 (optional)               |
| Charts      | Recharts                              |
| Deployment  | Works great on Vercel / Netlify       |

