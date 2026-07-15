# Skill Overview

A React app comparing the four major cloud providers — AWS, Azure, Google Cloud, and Alibaba Cloud — and their strategic investments in Saudi Arabia's digital transformation under Vision 2030.

**Live demo:** [skill-overview.onrender.com](https://skill-overview.onrender.com/) (hosted on Render's free tier, so the first load after a period of inactivity can take 30–60 seconds to wake up)

## Features

- Home page with a card grid linking out to each provider
- A dedicated page per provider (AWS, Azure, GCP, Alibaba) with an Arabic-language overview of that provider's regional presence and investments
- Client-side routing via React Router

## Tech stack

React 19, Vite, Tailwind CSS 4, React Router

## Getting started

```bash
git clone https://github.com/intisar-alosaimi/Skill-Overview.git
cd Skill-Overview
npm install
npm run dev
```

## What I'd improve

- Each provider page hardcodes its own near-identical content object — move these into a shared data file (or fetch from JSON) instead of duplicating the same card-rendering JSX four times
- Add an English/Arabic language toggle — content is currently Arabic-only while the surrounding UI chrome is English
- Add tests
