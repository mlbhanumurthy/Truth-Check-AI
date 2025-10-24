# 🛡️ TruthGuard

**TruthGuard** is an AI-powered misinformation detection platform that analyzes digital content, verifies credibility, and classifies information based on authenticity. It helps users quickly identify false or misleading news using advanced natural-language models and real-time content analysis.

---

## 🚀 Features

- **AI-Based News Verification** – Detects potential fake or misleading news articles.  
- **Smart Categorization** – Classifies information into trusted, suspicious, or fake.  
- **Content Summarization** – Provides concise summaries of long news pieces.  
- **User-Friendly Interface** – Intuitive dashboard built with modern UI/UX principles.  
- **Cross-Platform Ready** – Modular client-server architecture for scalability.  
- **Secure & Fast** – Backend optimized for low latency and safe API communication.  

---

## 🧠 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React, TypeScript, Vite, TailwindCSS |
| **Backend** | Node.js, Express, TypeScript |
| **Database** | Drizzle ORM (SQL compatible) |
| **Styling** | PostCSS, TailwindCSS |
| **Config** | tsconfig.json, vite.config.ts, drizzle.config.ts |

---

## 📁 Project Structure

TruthGuard/
├── client/ # Frontend source (React + Vite)
├── server/ # Backend source (Node.js + Express)
├── shared/ # Shared logic, types, or constants
├── components.json # UI component registry
├── design_guidelines.md # Design and style documentation
├── drizzle.config.ts # Drizzle ORM configuration
├── postcss.config.js # PostCSS setup
├── tailwind.config.ts # TailwindCSS configuration
├── tsconfig.json # TypeScript configuration
├── vite.config.ts # Vite build configuration
└── package.json # Project dependencies and scripts


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/truthguard.git
   cd truthguard
Install dependencies


npm install
Run the development servers

Frontend


cd client
npm run dev
Backend


cd server
npm run dev
Build for production


npm run build
🧩 Usage
Upload or paste article content for verification.

View AI-based classification and confidence scores.

Access summarized reports and flagged keywords.

Integrate with APIs for automated content moderation.

🧱 Design Guidelines
For UI consistency and accessibility standards, refer to design_guidelines.md.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request with improvements.

🪪 License
This project is licensed under the MIT License – see the LICENSE file for details.

💬 Acknowledgements
OpenAI and other NLP frameworks for model APIs

TailwindCSS for the beautiful and responsive UI

Community-driven open-source libraries that power the project

TruthGuard — Empowering users with verified information.
