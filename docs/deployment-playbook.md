# Deployment Playbook

Use this to make projects visible to recruiters without asking them to clone code.

## Priority Order

1. Add or verify a live demo link in the GitHub repository homepage field.
2. Add a 60-90 second screen recording to the top of the project README.
3. Add 3-5 screenshots showing the main workflow.
4. Add demo credentials when the app needs login.
5. Add a short "What this proves" section written for non-technical recruiters.

## Best Hosting Choice By Project Type

| Project type | Recommended deploy target | Notes |
| --- | --- | --- |
| Next.js frontend | Vercel | Fastest for portfolio demos. Add env vars in Vercel dashboard. |
| Static HTML/CSS/JS | GitHub Pages or Vercel | GitHub Pages is enough for simple projects. |
| Express/EJS app | Render, Railway, or Fly.io | Use a health endpoint and persistent environment variables. |
| FastAPI backend | Render, Railway, Fly.io, or EC2 | Keep `/docs` available if safe; it helps technical reviewers. |
| Full-stack app with DB | Vercel frontend + Render/Railway backend + MongoDB Atlas | Split frontend/backend for reliability. |
| Mobile app | GitHub Releases + screenshots + short video | Add APK as a release asset and link it from README. |
| Web3 app | Vercel frontend + public testnet contracts | Include contract addresses and explorer links. |

## High-Impact Fixes For Current Repos

| Repo | Status | Next fix |
| --- | --- | --- |
| FlowForge | Has YouTube demo, no live app link found | Deploy frontend, keep the chat-to-API video near the top, and add screenshots. |
| GyaanSaarthi | Has EC2 demo link and YouTube demo | Keep the video link near the top in case the EC2 server sleeps or goes down. |
| ShopSage | Has Vercel demo and YouTube demo | Keep the video link near the top showing product search, cart, checkout, and PDF export. |
| Nexus Flow | Has YouTube demo | Add the source repo and live link when public. |
| Eden Haus | Has Vercel demo | Add screenshot/GIF of a market, bet slip, and settlement flow. |
| RepVote | Has Vercel demo and contract addresses | Add demo credentials/network setup and a 60-second voting walkthrough. |
| LNMIIT Carpool | Has APK release | Add real screenshots directly in README, not only a markdown placeholder. |
| Notes and Bookmarks | Has Vercel demo | Add demo credentials or public guest mode. |
| Hostel Complaint System | Has Render demo | Add screenshots of student/admin complaint workflow. |

## Vercel Quick Deploy

```bash
npm install
npm run build
```

Then import the repo in Vercel, add environment variables, and set the correct root directory if it is a monorepo.

## Render Quick Deploy For Node/EJS

```bash
npm install
npm start
```

Set the build command to `npm install`, start command to `npm start`, and add all required environment variables in Render.

## Demo Video Script

Use this exact structure for every serious project:

1. Problem in one sentence.
2. Show the live URL.
3. Complete the main user workflow.
4. Show the technical proof: architecture, database, APIs, contracts, or AI model usage.
5. End with what you would improve next.
