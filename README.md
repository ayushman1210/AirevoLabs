# AeroAI — Mini AI Interview Screener

A backend service that evaluates answers using Gemini AI and ranks all candidates.

## Features
- AI scoring
- Summary & improvement tips
- In-memory ranking
- Node.js + Express backend

## Installation

```bash
npm install
Create .env
GEMINI_API_KEY=your_key_here
PORT=3000
```
## Endpoints 
- API Endpoints
- POST
api/v1/evaluate-answer :Evaluates answer and stores score.

- GET
 api/v1/rank-candidates 
Returns all scores sorted (high → low).
