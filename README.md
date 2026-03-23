# GitHub Wrapped

A modern web application that visualizes your GitHub activity with interactive statistics and insights. Similar to Spotify Wrapped, but for your coding journey.

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/github-wrapped.git
cd github-wrapped
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open http://localhost:3000 in your browser

## Features

- Year-based GitHub activity analysis
- Interactive 6-slide experience
- Commit statistics and trends
- Signature move detection
- Language breakdown visualization
- Streak tracking
- Dark theme with modern design

## Tech Stack

- Next.js 16 - React framework
- React 19 - UI library
- Tailwind CSS - Styling
- Framer Motion - Animations

## Project Structure

```
app/
├── page.js              # Home page
├── globals.css          # Global styles
├── layout.js            # Root layout
├── api/github/route.js  # GitHub API
└── wrapped/[username]/  # Results page
```

## Author

Made with love by Rhythm Pahwa
