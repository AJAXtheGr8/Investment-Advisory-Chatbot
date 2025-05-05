**1. Introduction and Problem Statement**
In today’s complex and rapidly evolving financial markets, individual investors face an overwhelming volume of information and choices. With thousands of assets across different sectors, understanding how to allocate capital effectively according to one's goals, market trends, and risk appetite is a significant challenge. Traditional financial advisory services are either expensive or not personalized enough for the average investor.
The need for scalable, accessible, and intelligent financial advisory tools is more important than ever. Investors require real-time, data-driven insights that are personalized to their unique financial profiles and preferences. However, most chatbots available today are rule-based and fail to provide meaningful portfolio analysis or investment suggestions based on the user’s profile and dynamic market conditions.

**2. Project Objective**
The goal of this project is to design and implement an AI-powered investment advisor chatbot that:
● Analyzes an investor’s financial portfolio to identify key performance metrics and inefficiencies.
● Provides personalized investment suggestions based on market trends, budget constraints, and the user’s personal interests.
● Uses a generative AI language model (LLM) to generate natural, human-like responses and recommendations.
● Improves investor understanding through explainable outputs that outline why certain suggestions were made.

**3. System Architecture Overview**
The architecture consists of the following core components:
● Frontend Chat Interface (HTML/CSS): Enables natural language input from users and displays LLM-generated responses.
● Backend Server (NodeJS): Handles API routing, session management, and data preprocessing.
● Portfolio Analysis Engine: Computes key metrics from the investor’s portfolio, fetches market trends via APIs, and calculates insights.
● LLM Integration Module (OpenAI GPT-4): Accepts structured prompts containing portfolio data and generates contextual investment advice.

**Data-Sources and Methodology**
• Financial Modelling Prep API for real-time stock, crypto, and market trend data.
• User-input portfolio data including symbol, quantity, and buy price.
• Sector performance and news sentiment derived from FMP’s trend and sentiment endpoints.
• Prompt engineering for GPT-4 to generate contextual responses.
• Modular backend with separate logic for portfolio analytics, prompt construction, and market trend fetching.
