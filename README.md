# DevDash-Developer-Dashboard
## APIs: GitHub (GraphQL), Stack Overflow, Dev.to  


## What it does: Shows user’s GitHub stats, latest StackOverflow questions, trending dev articles.  


## Why it stands out: Combines multiple dev-focused APIs into a single productivity dashboard.




# Project structure 

```
devdash/
├── client/                      # Frontend (React + TypeScript)
│   ├── src/
│   │   ├── components/          # Reusable UI components
│   │   ├── hooks/               # Custom React hooks
│   │   ├── pages/               # Page-level components/routes
│   │   ├── services/            # API clients for GitHub, StackOverflow, Dev.to
│   │   ├── App.tsx              # Root app component
│   │   └── main.tsx             # Entry point
│   ├── public/                  # Static files
│   └── package.json             # Frontend dependencies and scripts
│
├── server/                      # Backend (Node.js + Express)
│   ├── src/
│   │   ├── routes/              # API route handlers
│   │   ├── services/            # GitHub GraphQL client, other API integrations
│   │   ├── utils/               # Helper functions/utilities
│   │   ├── index.ts             # Entry point for the server
│   │   └── config/              # Env config, API keys, etc.
│   └── package.json             # Backend dependencies and scripts
│
├── .github/                     # GitHub Actions CI/CD
│   └── workflows/
│       └── ci.yml               # CI workflow for linting/testing/build
├── .env.example                 # Example env variables (do not commit real .env)
├── README.md                    # Project overview, setup instructions
└── docker-compose.yml           # Optional: containerized setup for dev
```




