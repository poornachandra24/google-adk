# Google-adk Multi-Tool Agent


The **Multi-Tool Agent** is a Python-based application designed to provide weather and time information for specified cities. It leverages modular tools to handle user queries effectively.

## Features

- **Weather Information**: Retrieve current weather reports for supported cities.
- **Time Information**: Get the current time in supported cities.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd multi_tool_agent

2. Create a virtual environment and activate it:

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies:

```
pip install -r requirements.txt
```

## Usage
The agent is implemented in multi_tool_agent/agent.py. It provides two main tools:

1. Weather Tool: Use the get_weather function to retrieve weather information.
2. Time Tool: Use the get_current_time function to get the current time.