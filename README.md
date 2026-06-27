# Elias El Helou portfolio

A full-stack portfolio with an embedded AI agent that answers questions about
my experience, projects, and skills in real time.

## Live Site
https://eliaselhelou.dev

## Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 15, TypeScript, Tailwind CSS, shadcn/ui |
| Backend | FastAPI, Pydantic v2, PostgreSQL, Redis |
| AI Agent | LangGraph, LangChain, Pinecone, Claude claude-sonnet-4-6 |
| DevOps | Docker, Kubernetes (GKE), Terraform, GitHub Actions |
| Observability | OpenTelemetry, Prometheus, Grafana |

## Architecture
The portfolio features a RAG (Retrieval-Augmented Generation) agent that
searches a vector database of my projects, experience, and skills to answer
recruiter and client questions with accurate, grounded responses.

## Running Locally
```bash
git clone git@github.com:Elias-El-Helou/portfolio.git
cd ai-portfolio
cp .env.example .env
docker compose up
```

## Project Status
In active development