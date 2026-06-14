# AI Interview Coach

A fully AI-powered interview preparation platform with:
- 🎤 Mock Interview with Claude AI scoring
- 📄 Resume Analysis with ATS scoring
- 🧠 Skill Quiz across 8 tech domains
- 📊 Performance analytics dashboard

## Tech Stack
- **Frontend**: Pure HTML/CSS/JS with Chart.js
- **Backend**: Flask (Python)
- **AI**: Claude Sonnet 4.6 via Anthropic API

## Deploy to Railway

1. Push this repo to GitHub
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub
3. Select your repo — Railway auto-detects Python/Flask
4. Add environment variable: `PORT` = `8080` (Railway sets this automatically)
5. Done! Your app is live.

## Run Locally

```bash
pip install -r requirements.txt
python app.py
```
Then open http://localhost:8080

## How It Works
The app is a single-page HTML application served by Flask.
The frontend calls the Anthropic Claude API directly from the browser.
No database or backend AI calls needed — fully stateless.
