# Dalal Street | Real-Time Market Strategy Engine

Live Demo: https://rajveerjetly.github.io/equity-sim-india/

# 📌 Project Overview
Equity-Sim India is a technical proof-of-concept (PoC) designed to simulate the dynamics of the Indian Equity Market (NSE). This project was developed to bridge the gap between theoretical market knowledge and technical execution, providing a "Paper Trading" environment powered by real-time data streams.
The goal was to build a tool that allows for Market Strategy Testing without capital risk, focusing on how live data affects decision-making in high-volatility environments.

# Technical Stack
Frontend: HTML5, CSS3
Logic: JavaScript (ES6+)
Data API: Yahoo Finance (Real-time Market Data)
Data Persistence: Browser LocalStorage API (Ensures user portfolio data is retained across sessions without a backend database).

# Key Features & Business Logic

1. Live Market Pulse: Integrated the Yahoo Finance API to stream real-time NSE ticker data.
2. Portfolio Persistence: Engineered a system using LocalStorage to save user holdings, buy-in prices, and balance locally. This ensures a seamless user experience where progress is saved automatically on the user's hardware.
3. Live P&L Engine: JavaScript-based calculation engine that compares Average Buy Price vs. Current Market Price to provide instant ROI feedback.
4. Client-Side Efficiency: Built to run entirely in the browser, reducing server-side costs and providing high-speed responsiveness for the end-user.

# The Challenge
The Problem: During the initial build, the API response time caused a "lag" in price updates, which would lead to "Slippage" (the difference between the expected price of a trade and the price at which the trade is executed).

The Solution: I optimized the Asynchronous JavaScript logic to handle data fetching more efficiently. By managing the request-response cycle and ensuring non-blocking UI updates, I reduced the perceived latency, providing a smoother and more accurate trading experience.

# Future Roadmap
1. Persistence: Implementation of a backend (Node.js/Firebase) to support user accounts and saved portfolios.
2. Global Expansion: Launching the US-Market (NYSE/NASDAQ) version.
