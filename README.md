# WeatherMind AI Agent

Hey there! Welcome to **WeatherMind**, a super cool AI agent built by Manthankumar Bagade (that’s me!). This project is all about answering your questions with a dash of humor and a lot of smarts. Whether you’re curious about what outfit to wear in Goa, the latest fashion trends in Mumbai, need a quick calculation, or want to dive into something random like machine learning, WeatherMind’s got you covered!

This project is built using **LangGraph** and features a multi-agent system (Level 4 in the notebook) with specialized agents: WeatherAgent, FashionAgent, CalculationAgent, and ResearcherAgent. They work together, coordinated by a DecisionMaker, to give you clear, fun, and accurate responses. Think of it as a team of digital buddies ready to tackle your queries!

## What’s Inside?
- **WeatherAgent**: Fetches current weather data for any city using the OpenWeatherMap API.
- **FashionAgent**: Digs up the latest fashion trends for a given location via Tavily Search.
- **CalculationAgent**: Handles math expressions like a pro.
- **ResearcherAgent**: Answers questions on any topic not covered by the others, also using Tavily Search.
- **DecisionMaker**: The mastermind that delegates tasks to the right agent and delivers witty responses.

The project is structured as a Jupyter Notebook (`Task_2.ipynb`) with four levels of complexity, from a simple calculator agent (Level 1) to a full-blown multi-agent system with memory (Level 4).


## Project Structure
- `Task_2.ipynb`: The main Jupyter Notebook with all code, organized into four levels.
- `requirements.txt`: Lists all Python dependencies and environment dependencies.
- `README.md`: This file, your guide to the project.


## Acknowledgments
- Built with love and a lot of coffee by Manthankumar Bagade.
- Thanks to [LangGraph](https://langchain-ai.github.io/langgraph/), [LangChain](https://python.langchain.com/docs/), and [Google Gemini API](https://ai.google.dev/gemini-api/docs/api-key) for powering the brains.
- Shoutout to [OpenWeatherMap](https://openweathermap.org/api) and [Tavily](https://docs.tavily.com/docs/sdks/python-sdk) for the data.
- Not to forget, these work was inspired by the code snippets from [freecodecamp Langgraph Tutorial](https://youtu.be/jGg_1h0qzaM?si=9baeKsDdCNalbbu7), [langgraph documentation](https://langchain-ai.github.io/langgraph/agents/agents/), [Langgraph Gemini API](https://python.langchain.com/docs/integrations/chat/google_generative_ai/)
, [Open Weather current weather information API Usage](https://openweathermap.org/api/one-call-3), [Open Weather Geocoding API](https://openweathermap.org/api/geocoding-api), [Tavily Search](https://docs.tavily.com/documentation/quickstart), [Memory Integration](https://harshaselvi.medium.com/building-ai-agents-using-langgraph-part-5-adding-memory-to-the-agent-d2ef16e68e67), [Prompt Templates](https://medium.com/@princekrampah/prompt-templates-in-langchain-248c015be3e0)

Have fun with WeatherMind, and may your queries be answered with wit and wisdom! Don't get offended by WeatherMind 😜.