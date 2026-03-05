# CV Builder Pro 🇱🇰

Professional CV Builder for Sri Lanka - Age 16+ | Free | AI-Powered

## 📁 Files

```
cv-builder/
├── index.html      ← Landing page (template showcase)
├── builder.html    ← CV Builder app (main tool)
└── README.md       ← This file
```

## 🚀 How to Use

1. Open `index.html` in a browser for the landing page
2. Click "CV හදන්න" or any template to go to the builder
3. `builder.html` is the full CV builder

## ✨ Features

- ✅ 100 Templates across 5 categories (Modern, Creative, Academic, Infographic, Industry)
- ✅ AI-powered content generation (Claude API)
- ✅ A4 PDF download (html2pdf.js)
- ✅ Live CV preview with zoom
- ✅ Photo upload
- ✅ Skills tag system
- ✅ Social media sharing (WhatsApp, Facebook, LinkedIn, Twitter)
- ✅ Copy link sharing
- ✅ Cloud save (Firebase) with local fallback
- ✅ CV upload support
- ✅ All CV sections:
  - Personal Info + Photo
  - O/L & A/L Education
  - Professional Qualifications
  - Languages
  - IT Skills
  - Soft & Technical Skills (tag system)
  - Leadership & Strengths
  - Work Experience
  - Extra-Curricular Activities
  - Volunteer Work
  - Workshops & Seminars
  - Projects
  - Achievements & Certifications
  - References (Non-Related)
  - Declaration

## 🔥 Firebase Setup (Optional - for Cloud Save)

In `builder.html`, find this section and replace with your Firebase config:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID"
};
```

1. Go to https://console.firebase.google.com
2. Create a new project
3. Enable Firestore Database
4. Copy your config and paste above

## 🤖 AI Features

- AI Professional Summary generation
- AI Technical Skills suggestions
- AI CV improvement tips
- AI Job-specific advice
- Chat-based AI assistant

The AI uses Claude claude-sonnet-4-20250514 via Anthropic API.

## 📋 Template Categories

| # | Category | Templates |
|---|----------|-----------|
| 1 | Modern & Professional | 1-20 |
| 2 | Creative & Artistic | 21-40 |
| 3 | Simple & Academic | 41-60 |
| 4 | Infographic & Visual | 61-80 |
| 5 | Industry Specific | 81-100 |

## 📱 Responsive

Works on Phone, Tablet, and Computer.

## 🛠️ No Build Required

Pure HTML, CSS, JavaScript. Just open in browser!

---
Made with ❤️ for Sri Lanka | CV Builder Pro 2025
