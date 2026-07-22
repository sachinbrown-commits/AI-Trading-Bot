# Product Requirements Document (PRD)

## Project

**Maxxwell**

**Version:** 1.0 (MVP)

---

# Purpose

The purpose of this document is to define the functional scope, business goals, constraints, and success criteria for the Maxxwell platform.

This document serves as the primary reference for product planning, development, quality assurance, and future enhancements.

---

# Product Summary

Maxxwell is an AI-powered trading assistant that combines structured technical analysis, explainable AI, configurable automation, and professional risk management into a single trading platform.

The platform assists traders across Forex, Cryptocurrency, Gold, and Indices markets while ensuring that the trader always remains in control of execution decisions.

---

# Business Objectives

- Improve trader decision-making.
- Reduce emotional trading.
- Promote disciplined execution.
- Explain every trading recommendation.
- Support multiple financial markets.
- Build a scalable platform for future AI capabilities.

---

# Target Audience

### Beginner Traders

Require education, guidance, and confidence while learning.

---

### Intermediate Traders

Need strategy validation, consistency, and better trade management.

---

### Professional Traders

Require intelligent automation, rapid analysis, configurable workflows, and detailed performance analytics.

---

# MVP Scope

The first release (Version 1.0) focuses on delivering a reliable foundation.

Included:

- User Authentication
- Dashboard
- Market Scanner
- Live Market Data
- Strategy Engine
- AI Trade Explanations
- Confluence Scoring
- Paper Trading
- Risk Management
- Trade Journal
- Notifications

Excluded from MVP:

- Mobile Applications
- Copy Trading
- Social Trading
- Machine Learning Optimisation
- Multiple Trading Strategies
- Portfolio Management Across Multiple Accounts

---

# Supported Markets

- Forex
- Cryptocurrency
- Gold
- Indices

Future Releases:

- Stocks
- ETFs
- Commodities

---

# Core Features

## User Management

- Registration
- Login
- Profile Management
- Preferences

---

## Dashboard

- Watchlist
- Market Overview
- Open Positions
- Trade History
- Account Summary

---

## Market Scanner

Analyse live market data and identify opportunities according to the configured strategy.

---

## Strategy Engine

Responsible for:

- Trend Detection
- Parallel Channel Analysis
- Median Line Detection
- RSI Analysis
- EMA Confirmation
- Fibonacci Confluence
- Signal Generation

---

## AI Assistant

Provides:

- Trade Explanations
- Market Insights
- Educational Feedback
- Strategy Guidance
- Natural Language Chat

---

## Trade Execution

Three execution modes:

- Manual
- Confirmation Required
- Automatic

---

## Manual Override

Users may execute trades even when Maxxwell recommends waiting.

These trades are recorded as **User Override Trades** and highlighted in analytics.

---

## Risk Management

Supports:

- Stop Loss
- Take Profit
- Position Size
- Risk Percentage
- Daily Loss Limits
- Maximum Open Trades

---

## Trading Journal

Automatically records:

- Entry
- Exit
- Profit/Loss
- Strategy Confidence
- AI Confidence
- User Notes
- Override Status

---

# Non-Functional Requirements

The system should be:

- Secure
- Scalable
- Reliable
- Maintainable
- Responsive
- Explainable
- Extensible

---

# Assumptions

- Users have a basic understanding of financial markets.
- Live market data will be available through supported providers.
- AI services remain accessible during normal operation.

---

# Constraints

- One primary trading strategy for MVP.
- Cloud deployment in a later phase.
- Broker integrations released incrementally.
- Compliance with broker API limitations.

---

# Success Metrics

The MVP will be considered successful if it:

- Produces accurate strategy recommendations.
- Explains every recommendation clearly.
- Executes paper trades reliably.
- Allows safe manual override.
- Maintains responsive performance.
- Provides an intuitive user experience.

---

# Risks

Potential project risks include:

- Broker API changes
- Market data latency
- AI service availability
- High market volatility
- Regulatory changes
- Third-party integration failures

---

# Future Enhancements

Future versions may include:

- Voice Assistant
- Mobile Applications
- Strategy Marketplace
- AI Strategy Builder
- Machine Learning Optimisation
- Portfolio Analytics
- Social Trading
- Multi-Broker Support
- Multi-Strategy Support
- Institutional Dashboards

---

# Acceptance Criteria

The MVP is complete when:

- All core modules are operational.
- Users can analyse supported markets.
- Strategy signals are generated successfully.
- AI explanations are available.
- Paper trading functions correctly.
- Manual override is supported.
- Trade history is recorded.
- Core testing has passed.