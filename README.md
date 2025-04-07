# Healthcare Agent with LangGraph

A simple AI healthcare assistant that diagnoses conditions and provides treatment recommendations.

## Features
- Diagnoses health conditions from symptoms
- Suggests treatments for identified conditions 
- Uses LangGraph for structured conversation flow
- Integrates with LangSmith for tracking

##How it Works
The app follows a simple workflow:

1.  User asks a health-related question
2.  The AI agent analyzes the request
3.  If needed, the agent calls specialized tools:

- diagnose: Identifies conditions based on symptoms
- prescribe_treatment: Recommends treatments for diagnosed conditions


The agent provides a clear, informative response

## Setup
1. Install dependencies: `pip install langgraph langchain_anthropic`
2. Add API keys to `.env` file
3. Run the notebook

## Example Queries
- "What's the flu?"
- "What's the treatment for fever?"
