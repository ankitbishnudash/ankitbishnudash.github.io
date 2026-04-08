# 🚀 Portfolio Setup Guide — ankitbishnudash.github.io

## Step 1 — Add Your Photos

Save and rename each photo, then place them all in the `assets/` folder:

| File name | Which photo it is |
|---|---|
| `profile.jpg` | Your professional headshot (the one you shared) |
| `award-netcore-q1.jpg` | Netcore Certificate of Achievement — Star Performer Q1 (July 2023) |
| `award-netcore-appreciation.jpg` | Netcore Certificate of Appreciation (December 2023) |
| `award-netcore-q4.jpg` | Netcore Certificate of Achievement — Star Performer Q4 (April 2024) |
| `award-bankai-trophy.jpg` | Bankai/MobiFin Collaborative Trailblazer Award (certificate + trophy photo) |
| `award-ceremony.jpg` | Award ceremony photo (receiving the award on stage) |
| `photo-presenting.jpg` | Presenting MobiFin Social Media Brand Transition at event |

Your final `assets/` folder should look like:
```
assets/
├── profile.jpg
├── Ankit_Bishnu_Dash_ATS_CV.docx
├── award-netcore-q1.jpg
├── award-netcore-appreciation.jpg
├── award-netcore-q4.jpg
├── award-bankai-trophy.jpg
├── award-ceremony.jpg
└── photo-presenting.jpg
```

## Step 2 — Create the GitHub Repository

1. Go to [github.com](https://github.com) → **New repository**
2. Name it exactly: **`ankitbishnudash.github.io`**
3. Set to **Public** → **Create repository**

## Step 3 — Upload Files

Upload everything in the `ankitbishnudash.github.io/` folder:
```
ankitbishnudash.github.io/
├── index.html
└── assets/       ← all files from Step 1
```

**Option A — GitHub Web UI** (easiest)
1. In your repo click **"uploading an existing file"**
2. Drag and drop `index.html`
3. Create the `assets/` folder and upload all image/CV files

**Option B — Git CLI**
```bash
git init
git add .
git commit -m "Launch portfolio ✨"
git remote add origin https://github.com/ankitbishnudash/ankitbishnudash.github.io.git
git push -u origin main
```

## Step 4 — Enable GitHub Pages

Repo → **Settings** → **Pages** → Source: **Deploy from branch** → Branch: **main** → **/** (root) → **Save**

## Step 5 — Visit your portfolio! 🎉

**https://ankitbishnudash.github.io** (live in ~2 minutes after push)

---

## What's on the portfolio

- **Hero** — "Hello" animates through 14 languages in Comic Sans style, with your photo in an animated blob shape
- **Company Logos** — Animated carousel of all 8 companies you've worked with (auto-fetches logos)
- **Impact Numbers** — Animated counters for all key metrics
- **Experience** — Full 8-role career timeline
- **Projects (20 total)** — Filterable grid by: ABM, Content & SEO, Employer Branding, Strategy, Creative — each links to your Notion page
- **3 Deep Case Studies** — City Bank, Walmart, Halon
- **"The Proof Is in the People"** — 9-quote auto-scrolling recommendations carousel with stats (22 recommendations, 4 continents)
- **Awards & Gallery** — 6 award cards + photo gallery of your certificates and award moments
- **Skills** — Claude Code, Claude Cowork + 12 other AI tools prominently featured
- **Contact** — Email, LinkedIn, CV download (all mailto: linked)
