Chatbot with External Tools Integration

The goal of this project is to create an intelligent chatbot using LangChain that interacts with users in natural language and can fetch real-time data from external APIs, such as weather reports, news updates, or stock prices. The chatbot will have a conversational flow, respond dynamically to queries, and optionally learn user preferences to improve recommendations or tailor responses.

Key Features:
Conversational Flow Handling (LangChain):

Use LangChain to manage the conversational aspects of the chatbot.
Implement intent detection to identify whether the user is asking about weather, news, or stock data.
Example: If a user asks "What's the weather like in San Francisco?" the bot should be able to detect intent and provide weather data.
Weather Data Integration (OpenWeatherMap API):

Allow the bot to query weather data using the OpenWeatherMap API based on user input.
Example: If the user asks, "What's the temperature in Paris?" the chatbot should fetch and display the current temperature and conditions in Paris.
News Integration (Google News API):

Enable the bot to retrieve and summarize the latest news from Google News or NewsAPI.
Example: For a query like "What's the latest tech news?" the chatbot would fetch a summary of the latest technology-related headlines.
Stock Price Integration (Alpha Vantage API):

Provide stock price data from the Alpha Vantage API.
Example: If a user asks "How's Apple stock doing?" the bot would return the latest stock price and a summary of the stock performance for the day.
User Preferences Learning (Optional):

Build a system where the chatbot can remember user preferences, such as favorite cities for weather, preferred news categories, or stocks they frequently check.
Store these preferences in a lightweight database or memory cache (e.g., SQLite or Redis).
The bot should use these preferences to provide quicker and more tailored responses in future conversations.
Natural Language Understanding:

Use pre-trained models or LangChain's conversational capabilities to ensure the chatbot understands natural language queries.
The bot should handle varied phrasings like “What’s the weather like today?” or “Give me the forecast for tomorrow in New York.”
Extendability:

Design the chatbot so that new APIs or data sources can be easily added in the future.
Example: Add an API for sports updates or a currency exchange rate tracker as an additional feature.
