#  GitHub Roast Machine

> Paste any GitHub username. Receive judgment.

**Live site → [githubroast.netlify.app](https://githubroast.netlify.app)**

---

## What it does

GitHub Roast Machine takes any GitHub username, fetches their public profile and repos, and generates a brutally honest AI roast + skill breakdown. Results include a downloadable share card so you can post your roast anywhere.

---

## Features

- Roasts any public GitHub profile using real repo data
- Skill scores across consistency, documentation, language depth, and community
- Downloadable PNG share card
- Zero login required

---

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla JS(becoz why make it complicated), HTML, CSS |
| Profile Data | GitHub REST API |
| AI Roast | Google Gemma 3 via OpenRouter |
| Backend / Key Hiding | Netlify Functions (serverless) |
| Hosting | Netlify |

---

## Run locally

```bash
# 1. Clone the repo
git clone https://github.com/Shasank-Bommineni/github-roast-machine

# 2. Install Netlify CLI
npm install -g netlify-cli

# 3. Add your OpenRouter API key
# Create a .env file in the root:
echo "OPENROUTER_API_KEY=your_key_here" > .env

# 4. Run locally
netlify dev
```

Get a free OpenRouter key at [openrouter.ai](https://openrouter.ai)

---

## Deploy your own

1. Fork this repo
2. Connect to [Netlify](https://netlify.com)
3. Add `OPENROUTER_API_KEY` as an environment variable
4. Deploy

---

## Built by

[Shasank Bommineni](https://github.com/Shasank-Bommineni) — CS student, Dayananda Sagar College of Engineering, Bangalore
