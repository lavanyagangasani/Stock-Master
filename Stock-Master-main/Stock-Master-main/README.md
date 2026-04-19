**Stock Master & Stock Dash**

**A Comprehensive Suite for Stock Market Tracking, Analytics, and Portfolio Management (Built with Next.js)**
This repository features two robust stock market applications, meticulously crafted using Next.js, React, Tailwind CSS, and integrated with real-time stock APIs. Together, they serve as an indispensable toolkit for investors seeking to analyse stocks, manage their portfolios, and gain valuable insights.

### **Core Features**
- **Stock Searching:** Quickly find any stock using our intuitive search functionalities.
- **Real-time Price Monitoring:** Stay updated with live stock prices and market movements.
- **Portfolio Management:** Effortlessly manage your investment portfolio.
- **Dashboard-style Analytics:** Access comprehensive analytics in a visually appealing format.
- **Investment Insights:** Make informed decisions backed by data.

**Included Applications**

1. **Stock Master [WEBSITE]**

Stock Master is a real-time stock tracking and portfolio management web application. It allows users to search for live stock prices, view market changes, and maintain a personalized investment portfolio. The interface is designed to be clean, modern, and easy to navigate, offering two primary sections: Search Stocks and Portfolio.

In the Search Stocks section, users can enter any stock symbol to instantly fetch the latest price, percentage change, and timestamped market data. A quick-add panel on the right enables users to rapidly insert a stock into their portfolio by specifying the symbol, quantity, and purchase price. The system provides immediate feedback by displaying the searched stock data in a detailed card format.
The Portfolio page gives users a clear overview of all their investments. Each entry displays the stock symbol, quantity owned, price per stock, and total value. Users can also delete individual portfolio items through an intuitive action button. This section updates dynamically to ensure that the displayed values always reflect accurate, real-time stock information.

Overall, Stock Master serves as a simple yet effective tool for learning stock tracking, integrating APIs, managing state, and building a responsive user interface. It is ideal for students, developers, and hobbyists who want to explore stock data and create a functional portfolio management system.

2. **Stock Dash [APP]**
   
Project Description: The stock market can be intimidating for beginners. Existing apps often show complex prices without providing guidance, leading new traders to make decisions based on unreliable advice from friends or social media. Stock Dash is a cross-platform application that acts as a personal stock consultant for new investors. It leverages the Finnhub live market API to translate complex financial data into simple, actionable guidance. The app is built as a Progressive Web App (PWA), making it accessible on both desktop and mobile devices.

Key Features Global Portfolio Management: Users can add stocks from any worldwide exchange by entering the ticker symbol, number of shares, and purchase price. Real-Time Data: The app provides live prices and daily change percentages sourced directly from the Finnhub API. Risk Insights: Each stock holding is tagged with a risk level (low, medium, or high) based on volatility and trend analysis. Actionable Advice: The app automatically generates recommendations, such as "Reduce exposure to high-beta IT stocks" or "Add defensive sectors to diversify". Portfolio Comparison: Interactive graphs allow users to visually compare the performance of multiple portfolios. Usage Tracking & Billing: The application is integrated with Flexprice to track and display usage, such as the number of portfolio analyses or advice reports generated. Technology Stack Frontend: Next.js, Tailwind CSS, React, PWA manifest, and service worker. Backend: Node.js (Express) or serverless functions. Data Source: Finnhub API (for quotes, profiles, and symbol lookup). Visuals: Recharts or Chart.js for rendering portfolio comparison graphs. Billing: Flexprice SDK/webhook for usage tracking and billing.

Getting Started To get a local copy up and running, follow these simple steps. Prerequisites: Node.js installed An API key from Finnhub Installation: Clone the repository: git clone [repository_url] Navigate to the project directory: cd stock-dash Install dependencies: npm install Create a .env file and add your Finnhub API key: FINNHUB_API_KEY=your_api_key Run the application: npm run dev



**Technology Stack (Common to Both Applications)**
- **Next.js 14+ (App Router):** The primary framework for seamless application structure and routing.
- **React:** Utilised for efficient component rendering.
- **Tailwind CSS:** Implemented for modern and responsive styling.
- **APIs:** Integrated with Yahoo Finance, Finnhub, and AlphaVantage for real-time stock data access.
- **LocalStorage or API Backend:** For secure portfolio saving and state management.

This collection represents a powerful solution for anyone interested in the stock market, offering both functionality and aesthetic appeal to enhance the user experience. Dive into stock tracking and analysis with these innovative applications!

Website Image:

<img width="1898" height="1107" alt="image" src="https://github.com/user-attachments/assets/2ef96c61-457b-42d1-a4b8-05539465cee4" />


APP Image:

<img width="326" height="712" alt="image" src="https://github.com/user-attachments/assets/90a20eb6-c16d-4af0-82b1-ad888e72eb94" />

