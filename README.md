# GENZ Bank — Vercel Deploy Guide

## Project Structure
```
genzbank/
├── api/
│   └── chat.js          ← KIMI AI backend (secure, API key hidden)
├── public/
│   └── index.html       ← Full banking website
├── vercel.json          ← Vercel config
└── README.md
```

## Deploy Steps (5 minutes!)

### Step 1 — Upload to GitHub
1. Go to github.com → Sign in / Sign up (free)
2. Click "New repository" → Name it `genzbank` → Create
3. Upload all files (drag & drop the folder contents)

### Step 2 — Deploy on Vercel
1. Go to vercel.com → Sign in with GitHub
2. Click "Add New Project"
3. Select your `genzbank` repository
4. Click "Deploy" (don't change any settings)

### Step 3 — Add Your API Key (IMPORTANT!)
1. In Vercel dashboard → Your project → "Settings"
2. Click "Environment Variables"
3. Add:
   - Name:  ANTHROPIC_API_KEY
   - Value: (paste your key here — starts with sk-ant-...)
4. Click "Save"
5. Go to "Deployments" → Click "Redeploy"

### Done! 🎉
Your live URL will be: https://genzbank.vercel.app (or similar)

## KIMI Chatbot Features
- Powered by Claude AI (Anthropic)
- Full GENZ Bank banking knowledge
- Tamil, Hindi, English support
- Conversation memory
- Quick reply buttons
- Typing animation
- Secure — API key never exposed to browser
