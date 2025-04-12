# Weather and Time Agent

A Python-based agent that provides weather and time information for different cities. This agent uses the Google ADK (Agent Development Kit) framework and is powered by the Gemini 2.0 Flash model.

## Features

- **Weather Information**: Get current weather reports for supported cities
- **Time Information**: Get current time in different time zones
- **Natural Language Interface**: Interact with the agent using natural language queries

## Supported Cities

Currently, the agent supports the following city:
- New York

## Usage

The agent can answer questions about:
- Current weather conditions in supported cities
- Current time in supported cities

Example queries:
- "What's the weather like in New York?"
- "What time is it in New York?"

## Requirements

- Python 3.x
- Google ADK (Agent Development Kit)
- Gemini 2.0 Flash model

## Installation and Setup

1. Clone this repository
2. Create and activate a Python virtual environment:
   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment
   # On Windows:
   .\venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment with the necessary API keys and configurations

## Running the Agent

To execute the agent, run:
```bash
python agent.py
```

The agent will start and be ready to accept queries about weather and time information for supported cities.

## Note

This is a demonstration agent with limited city support. The weather data is simulated for demonstration purposes. 