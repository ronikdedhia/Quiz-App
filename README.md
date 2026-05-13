# Quiz App

A classic trivia quiz application built with React. Users answer multiple-choice questions, track their score in real time, and see a results summary at the end.

## Features

- Multiple-choice question format
- Real-time score tracking
- Timer per question (optional)
- Results screen with correct/incorrect breakdown
- Restart quiz without page reload

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 |
| State | React Hooks (useState, useEffect) |
| Styling | CSS Modules |
| Bundler | Create React App |

## Getting Started

### Prerequisites

- Node.js 16+

### Installation

```bash
git clone https://github.com/ronikdedhia/Quiz-App.git
cd Quiz-App
npm install
npm start
```

App runs at `http://localhost:3000`

## Project Structure

```
src/
├── components/       # Question, Options, ScoreBoard, Timer
├── data/             # questions.js — quiz question bank
└── App.js
```

## License

MIT
