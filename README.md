# Technical Stack
Frontend: HTML5, CSS3
Logic: JavaScript (ES6+)
Data API: Yahoo Finance (Real-time Market Data)
Data Persistence: Browser LocalStorage API (Ensures user portfolio data is retained across sessions without a backend database).

# Key Features & Business Logic

Live Market Pulse: Integrated the Yahoo Finance API to stream real-time NSE ticker data.

Portfolio Persistence: Engineered a system using LocalStorage to save user holdings, buy-in prices, and balance locally. This ensures a seamless user experience where progress is saved automatically on the user's hardware.

Live P&L Engine: JavaScript-based calculation engine that compares Average Buy Price vs. Current Market Price to provide instant ROI feedback.

Client-Side Efficiency: Built to run entirely in the browser, reducing server-side costs and providing high-speed responsiveness for the end-user.
