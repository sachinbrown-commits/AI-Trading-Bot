# Maxxwell

> **Analyze. Explain. Execute.**

Maxxwell is an AI-powered trading assistant designed to help traders make informed, disciplined, and data-driven decisions across **Forex**, **Cryptocurrency**, **Gold**, and **Indices** markets.

Unlike traditional trading bots that rely solely on indicators or black-box automation, Maxxwell combines structured technical analysis, AI-assisted trade explanations, configurable risk management, and optional automated execution into one intelligent trading platform.

The platform follows a professionally defined trading methodology built around market structure, anchored parallel channels, confluence-based confirmations, and strict risk management principles.

---

## Table of Contents

- Project Overview
- Vision
- Key Features
- Supported Markets
- Trading Methodology
- Core Principles
- Technology Stack
- System Architecture
- Project Structure
- Development Roadmap
- Documentation
- Installation
- Running the Project
- Testing Strategy
- Future Enhancements
- Contributing
- License

---

# Project Overview

Maxxwell is more than a trading bot.

It is an intelligent trading platform designed to assist traders throughout the complete trading process.

The platform analyses live market data, identifies high-probability trading opportunities using a predefined professional strategy, explains every recommendation using AI, and allows traders to decide how those opportunities should be managed.

Users remain in complete control at all times.

Maxxwell never removes the trader from the decision-making process.

---

# Vision

To build the world's most transparent AI-powered trading assistant that helps traders become more disciplined, consistent, and confident while maintaining full control over every trading decision.

---

# Mission

Deliver institutional-quality market analysis through intelligent automation while ensuring every trading decision is explainable, measurable, and fully auditable.

---

# Key Features

## Market Analysis

- Market Structure Detection
- Trend Identification
- Parallel Channel Detection
- 50% Median Line Analysis
- Fibonacci Analysis
- EMA 9 / EMA 21 Confirmation
- RSI Divergence Detection
- Multi-Timeframe Analysis
- Support & Resistance Detection

---

## AI Assistant

- AI Trade Explanations
- Natural Language Chat
- Trading Education
- Strategy Explanations
- Market Analysis
- Risk Assessment
- Voice Commands *(Planned)*

---

## Trading Engine

- Manual Trading
- Confirmation Before Execution
- Fully Automated Trading
- Paper Trading
- Strategy Confidence Score
- AI Confidence Assessment

---

## Risk Management

- Dynamic Position Sizing
- Fixed Risk-to-Reward Ratios
- Stop Loss Suggestions
- Take Profit Suggestions
- Daily Loss Limits
- Maximum Risk Controls

---

## Dashboard

- Live Market Prices
- Portfolio Overview
- Open Trades
- Trade History
- Performance Analytics
- Risk Metrics
- Trading Journal

---

# Supported Markets

Maxxwell is designed to analyse multiple financial markets.

### Forex

- EUR/USD
- GBP/USD
- USD/JPY
- AUD/USD
- USD/CAD
- NZD/USD
- Major Cross Pairs

### Cryptocurrency

- Bitcoin
- Ethereum
- Solana
- XRP
- Major Crypto Assets

### Commodities

- Gold (XAU/USD)
- Silver (Future Release)

### Indices

- NASDAQ
- S&P 500
- US30
- DAX
- FTSE
- Other major indices

---

# Trading Methodology

Maxxwell follows one refined trading strategy instead of attempting to combine dozens of unrelated systems.

## Strategy Workflow

### 1. Trend Identification

The platform first identifies the dominant market trend using market structure.

Uptrend

- Higher Highs
- Higher Lows

Downtrend

- Lower Highs
- Lower Lows

If no trend exists,

**No Trade.**

---

### 2. Parallel Channel Construction

A professionally anchored parallel channel is created around the active trend.

The channel contains:

- Upper Boundary
- Lower Boundary
- 50% Median Line

The median line acts as the primary structural decision point.

---

### 3. Breakout Confirmation

A valid signal requires price to close beyond the channel's 50% median line.

The breakout confirms that market momentum has shifted in favour of buyers or sellers.

---

### 4. Technical Confluence

Maxxwell evaluates multiple confirmations including:

- RSI Divergence
- EMA 9 / EMA 21 Ribbon
- Fibonacci Retracement
- Market Structure
- Parallel Channel
- Median Line Breakout

The platform calculates a **Confluence Score** to determine trade quality.

---

### 5. Risk Management

Each trade includes:

- Entry Price
- Stop Loss
- Take Profit
- Position Size
- Risk-to-Reward Ratio

Default Risk-to-Reward Ratio

```
2 : 1
```

---

### 6. Trade Recommendation

Instead of simply saying BUY or SELL,

Maxxwell explains:

- Why the trade exists
- Which confirmations were found
- Which confirmations are missing
- Overall confidence
- Risk considerations

---

### 7. Trader Decision

The trader always has the final decision.

Available execution modes:

- Manual
- Confirmation Required
- Fully Automatic

If the strategy does not recommend taking a trade, the trader may still execute it manually.

Such trades are recorded as **User Override Trades** for later review and performance analysis.

---

# Core Principles

Maxxwell is built around six principles.

### 1.

The trader always remains in control.

### 2.

AI assists the trader.

It never replaces the trader.

### 3.

Every recommendation must be explainable.

### 4.

Risk management is never optional.

### 5.

One professional strategy is better than many average strategies.

### 6.

Every decision should be measurable, testable, and reviewable.

---

# Technology Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS *(Planned)*
- React Router
- TanStack Query

## Backend

- Node.js
- Express
- TypeScript
- Prisma ORM *(Planned)*
- PostgreSQL *(Planned)*

## AI

- OpenAI API
- AI Decision Explanations
- Natural Language Chat

## Integrations

- TradingView
- MetaTrader 5
- Broker APIs
- Market Data Providers

## Testing

- Cypress
- Postman
- Jest / Vitest
- Manual Testing

---

# High-Level Architecture

```
                   Maxxwell

        React Frontend Dashboard
                  │
                  ▼
            Express REST API
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
 Strategy      AI Engine   Risk Engine
      │           │           │
      └───────────┼───────────┘
                  ▼
         Market Data Services
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
 TradingView   MetaTrader   Broker APIs
```

---

# Project Structure

```
AI-Trading-Bot/

client/
    React Application

server/
    Express API

docs/
    Project Documentation

README.md

LICENSE
```

---

# Development Roadmap

## Sprint 0

Project Planning

- Product Vision
- Product Requirements
- Architecture
- Roadmap
- Test Strategy

---

## Sprint 1

Foundation

- React
- Express
- API
- Frontend Integration

---

## Sprint 2

Market Data

- Live Prices
- Charts
- Watchlists

---

## Sprint 3

Strategy Engine

- Trend Detection
- Channel Detection
- Confluence Engine

---

## Sprint 4

AI Assistant

- AI Chat
- Trade Explanations
- Market Coaching

---

## Sprint 5

Paper Trading

- Simulated Trading
- Performance Tracking

---

## Sprint 6

Broker Integration

- TradingView
- MetaTrader
- Broker APIs

---

## Sprint 7

Automation

- Automatic Trade Execution
- Notifications
- Voice Commands

---

# Documentation

Project documentation is available inside the `/docs` directory.

- Product Vision
- Product Requirements
- Functional Requirements
- System Architecture
- API Design
- Roadmap
- Test Strategy
- User Stories

---

# Installation

Clone the repository

```bash
git clone <repository-url>
```

Install frontend dependencies

```bash
cd client
npm install
```

Install backend dependencies

```bash
cd ../server
npm install
```

---

# Running the Project

Backend

```bash
cd server
npm run dev
```

Frontend

```bash
cd client
npm run dev
```

---

# Testing Strategy

The project will include:

- Unit Testing
- API Testing
- UI Testing
- Integration Testing
- End-to-End Testing
- Performance Testing
- Manual Exploratory Testing

---

# Future Enhancements

- Voice Commands
- AI Trading Coach
- Mobile Application
- Trading Journal
- Portfolio Analytics
- Multi-Broker Support
- Cloud Deployment
- Copy Trading
- Strategy Marketplace
- Machine Learning Strategy Optimisation

---

# Contributing

This project is currently under active development.

Contribution guidelines will be published in a future release.

---

# License

This project is licensed under the MIT License.
