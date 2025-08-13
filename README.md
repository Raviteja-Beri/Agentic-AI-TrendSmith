# Agentic AI TrendSmith

## Overview
Agentic AI TrendSmith is an **autonomous multi-agent AI research and content generation pipeline** built using CrewAI.  
It leverages **OpenAI** for natural language processing and **SerperDevTool** for real-time search on AI trends, combining **automated research** and **blog content creation** in a seamless workflow.

## Key Features
- **Multi-Agent Orchestration**: AI/ML Researcher + Tech Content Strategist working in sequence.
- **Real-Time AI Trends Research**: Uses **SerperDevTool** to fetch the latest advancements.
- **Automated Content Creation**: Converts complex research into engaging, human-readable blog posts.
- **Sequential Task Execution**: Ensures structured workflow from data gathering to polished output.

## Tech Stack
- **Python**
- **CrewAI**
- **OpenAI API**
- **SerperDevTool** (Google Search API)
- **Process.sequential** execution

## Architecture
1. **Researcher Agent** → Finds & summarizes latest AI advancements.
2. **Writer Agent** → Creates blog content from research insights.
3. **Crew Orchestration** → Manages agent workflow in sequence.

## Example Use Cases
- Automated AI industry reports
- Blog content generation for tech companies
- Trend analysis for research teams

## Setup & Installation
```bash
pip install crewai
pip install "crewai[tools]"
```

## Environment Variables
```bash
export OPENAI_API_KEY="your_openai_key"
export SERPER_API_KEY="your_serper_key"
```

## Run
```bash
python main.py
```

---
## Thank You
---
