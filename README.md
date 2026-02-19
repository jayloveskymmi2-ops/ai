# 🎤 AI Rap Lyricist

An AI-powered rap lyrics generator built with React, Vite, and the Google Gemini API. Generate full songs with customizable style presets, rhyme complexity, flow, and more.

## 🚀 Deploy to GitHub Pages (Free)

### Step 1 – Push to GitHub

Push this project to a new GitHub repository. Your site will be at:
`https://your-username.github.io/your-repo-name/`

### Step 2 – Add Your Gemini API Key as a Secret

1. Go to your repo on GitHub → **Settings** → **Secrets and variables** → **Actions**
2. Click **New repository secret**
3. Name: `GEMINI_API_KEY`
4. Value: your Gemini API key (get one free at [aistudio.google.com](https://aistudio.google.com))
5. Click **Add secret**

### Step 3 – Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. Save

### Step 4 – Deploy

Push any commit to `main`, or go to **Actions** → **Deploy to GitHub Pages** → **Run workflow**.

Your site will be live in ~1-2 minutes! ✅

---

## 💻 Run Locally

**Prerequisites:** Node.js 18+

```bash
npm install
```

Set your API key in `.env.local`:
```
GEMINI_API_KEY=your_key_here
```

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

---

## 🛠 Tech Stack

- React 18 + TypeScript
- Vite 6
- Google Gemini API (`@google/genai`)
- GitHub Actions + GitHub Pages (free hosting)
