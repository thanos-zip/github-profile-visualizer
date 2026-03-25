# GitHub Profile Visualizer

> Enter any GitHub username and get a beautiful visual breakdown of their activity, languages and repositories.

## What You Will Learn
- How to work with a real world REST API
- How to handle and display complex data in React
- How to build clean data visualizations with Recharts
- How to deploy a React app on Vercel

## Tech Stack
- React
- GitHub REST API
- TailwindCSS
- Recharts
- Vercel (deployment)

## Getting Started

### Prerequisites
- Node.js 18+ installed

### Installation
```bash
git clone https://github.com/thanos.zip/github-profile-visualizer
cd github-profile-visualizer
npm install
cp .env.example .env
# Add your GitHub personal access token to .env
npm run dev
```

## Project Structure
```
github-profile-visualizer/
├── src/
│   ├── App.jsx                    # Main app component
│   ├── api/
│   │   └── github.js             # All GitHub API calls here
│   ├── components/
│   │   ├── SearchBar.jsx         # Username input here
│   │   ├── ProfileCard.jsx       # Avatar, name, bio, stats here
│   │   ├── RepoList.jsx          # Repository cards here
│   │   ├── LanguageChart.jsx     # Pie chart of languages here
│   │   └── ContributionGraph.jsx # Activity over time here
│   └── index.css
├── .env.example
├── package.json
└── README.md
```

## What To Build
- Search bar — accept a GitHub username and trigger API call
- Fetch user profile — avatar, name, bio, followers, following, public repos
- Fetch all repositories — name, stars, forks, primary language
- Build a language breakdown pie chart with Recharts
- Display top 6 repos by stars
- Show total stars across all repos
- Deploy on Vercel

## Stretch Goals
- Add contribution streak data
- Let users compare two GitHub profiles side by side
- Add a share button that generates a shareable profile card image

## Resources
- https://docs.github.com/en/rest
- https://recharts.org/en-US/guide
- https://tailwindcss.com/docs

---
Built for [@thanos.zip](https://instagram.com/thanos.zip) followers.
