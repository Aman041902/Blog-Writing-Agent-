# AI Blog Writing Agent

A  AI agent that autonomously researches and writes complete blog posts using LangGraph's orchestrator-worker architecture.

## How It Works

The agent follows a multi-step pipeline:
1. **Planner** — breaks the topic into parallel subtasks
2. **Router** — decides if web research is needed
3. **Workers** — multiple agents execute subtasks in parallel
4. **Reducer** — combines outputs into a final blog with citations and images

## Tech Stack
- **LangGraph / LangChain** — agent orchestration
- **OpenAI / Gemini** — LLM backends
- **Tavily** — real-time web research
- **Streamlit** — frontend interface

## Setup

```bash
git clone https://github.com/Aman041902/blog-writing-agent
cd blog-writing-agent
```

Add your API keys to a `.env` file:
