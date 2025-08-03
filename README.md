#  Agentic Research Suite

A multi-agent research system powered by OpenAI's latest Agent SDK. Designed to simulate a complete research pipeline: planning searches, conducting deep web research, synthesizing long-form reports, and emailing outputs—all autonomously.



##  Features

-  **Search Agent**: Performs low-context, cost-optimized web searches using OpenAI WebSearchTool.
-  **Planner Agent**: Uses structured output (via Pydantic) to define multiple purposeful queries for deeper exploration.
-  **Writer Agent**: Generates long-form, structured markdown reports with summaries and follow-up topics.
-  **Email Agent**: Sends well-formatted HTML reports using SendGrid.
-  **Research Manager**: Orchestrates the flow across all agents.

##  File Structure
├── deep_research.py # Main orchestrator to plan, search, write and email reports


├── planner_agent.py # Agent generating structured search plan


├── search_agent.py # Web search agent


├── writer_agent.py # Markdown report generator


├── email_agent.py # HTML email agent (SendGrid-based)


├── research_manager.py # Optional research coordinator (e.g. UI or task flow logic)


├── requirements.txt # All Python dependencies

 Commercial Impact
This suite can be used for:
Business intelligence gathering
Competitive analysis
Trend research
Academic summaries
Content creation pipelines
