# InvestIQ — The AI-Powered Portfolio Intelligence Platform

[![Project Status](https://img.shields.io/badge/Status-Phase%204%3A%20Maturity%20and%20Monetization-yellowgreen)](./#project-roadmap)

**InvestIQ** is a next-generation platform designed to bring clarity and intelligence to portfolio management.
It combines financial analytics, AI-driven insights, and seamless automation to help **individual investors and professional asset managers** make better decisions.

---

## 🌍 Project Overview

InvestIQ is built as a modern, cloud-native web application leveraging AI for financial intelligence.
It focuses on:

- Portfolio tracking and performance analytics
- Market data aggregation and sentiment insights
- Automated document summarization and reporting
- AI-powered portfolio assistant

---

## 🧠 Tech Highlights

| Layer      | Technology                          |
| ---------- | ----------------------------------- |
| Frontend   | Next.js + TypeScript + Tailwind CSS |
| Backend    | Cloudflare Workers (Hono)           |
| Database   | Cloudflare D1                       |
| AI         | Google Gemini API                   |
| Deployment | Vercel + Cloudflare                 |
| CI/CD      | GitHub Actions                      |

---

## 🗺️ Project Roadmap

This roadmap outlines the major phases and features planned for InvestIQ.

### **Phase 1: MVP - "Personal Portfolio Monitor"**

_Goal: User can manually input their portfolio and view its current value._
_Status: Completed!_ ✅

- Step 0: Tech Foundations ✅
- Step 1: Authentication (Clerk Integration) ✅
- Step 2: Backend - Portfolio API Endpoints ✅
- Step 3: Database - Cloudflare D1 Schema & Connection ✅
- Step 4: Secure Backend (Clerk Middleware for Auth) ✅
- Step 5: Frontend - Portfolio UI (TanStack Query Integration) ✅

### **Phase 2: Core Functionality Expansion**

_Focus: Adding key visualization, data, and user management features._
_Status: Completed!_ ✅

- Step 6: Data Visualizations and Charts ✅
- Step 7: Financial News Aggregation ✅
- Step 8: Transaction Import (from File) ✅
- Step 9: Watchlists Implementation ✅

### **Phase 3: AI-Powered Insights**

_Focus: Leveraging AI to deliver intelligent, unique value._
_Status: Completed!_ ✅

- Step 10: Document Summarization (AI) ✅
- Step 11: Market Sentiment Analysis (AI) ✅
- Step 12: Interactive Portfolio Assistant (AI) ✅

### **Phase 3.5: Smart Portfolio Analytics**

_Focus: Deeper financial analysis and risk/performance metrics._
_Status: Completed!_ ✅

- Step 13: Asset Correlation Analysis ✅
  - Correlation matrix between tickers
  - Heat map visualization
  - Detection of strong relationships
- Step 14: Portfolio Risk Metrics ✅
  - Sharpe Ratio (return/risk)
  - Beta (volatility vs market)
  - Value at Risk (VaR 95%)
  - Diversification Score
- Step 15: Sector Exposure Analysis ✅
  - Grouping by sectors
  - Allocation % chart
  - Alerts for over-concentration
  - Diversification recommendations

### **Phase 4: Maturity and Monetization (Current Phase)** ⏳

_Focus: Preparing the platform for commercial use and ensuring stability._

- Step 17: User and Team Management ⏳
- Step 18: Payment Integration (Subscriptions)
- Step 19: Advanced Reporting (PDF Export)
- Step 20: Technical Cleanup & Security
  - _Includes: Moving hardcoded keys to a secure secrets management system._

### **🚀 Phase 5: Advanced ML (Future)**

_Focus: State-of-the-art machine learning models for market prediction and optimization._

- ⬜ LSTM Price Predictions
- ⬜ Anomaly Detection
- ⬜ Portfolio Optimization (MPT)
- ⬜ Advanced Graph Models (Sheaf-GNN)
- ⬜ Technical Indicators
  - Moving Averages (SMA, EMA)
  - RSI (Relative Strength Index)
  - Support/Resistance levels
  - Trend indicators

#### **Legend**

- **✅ Completed**
- **⏳ In Progress**
- **⬜ Planned**

---

## 🛠️ Development Philosophy

InvestIQ is developed following modern best practices:

- **Monorepo architecture** (frontend, backend, and shared packages)
- **End-to-end TypeScript** for type safety
- **Serverless-first** infrastructure for scalability i low latency
- **Continuous integration** with automated testing and preview deployments

---

## 🔒 Repository Status

This repository serves as a **public project showcase** for InvestIQ.
The full application codebase resides in a **private monorepo**.

Public updates, technical articles, and documentation will be shared here as the project evolves.

If you’re a **recruiter**, **collaborator**, or **potential partner**, feel free to reach out for a project overview or demo access.

---

## 📸 Product Screenshots

Here are a few glimpses into the InvestIQ user interface and core features.

|               Home Page               |              Portfolios Dashboard              |             Holdings & Charts              |
| :-----------------------------------: | :--------------------------------------------: | :----------------------------------------: |
|  ![Welcome screen](images/home.webp)  | ![Portfolios Overview](images/portfolios.webp) | ![Portfolio Details](images/holdings.webp) |
| _Welcome screen and main navigation._ |       _Overview of all user portfolios._       |     _Details and performance metrics._     |

|            News Feed & Sentiment Analysis             |                   Watchlist & Smart Analytics                    |                    AI Document Summarizer                    |
| :---------------------------------------------------: | :--------------------------------------------------------------: | :----------------------------------------------------------: |
|           ![Latest News](images/news.webp)            |             ![Tracked Assets](images/watchlist.webp)             | ![AI-Powered Summarization](images/document_summarizer.webp) |
| _Aggregated feed of the latest relevant market news._ | _Watchlists with smart portfolio analytics (correlation, risk)._ |         _Leveraging AI for quick document insights._         |

|        Interactive Portfolio Assistant         |
| :--------------------------------------------: |
|      ![AI chat window](images/chat.webp)       |
| _AI-powered chat for quick portfolio queries._ |

---

## 👤 About the Creator

InvestIQ is being developed by a team passionate about combining **AI**, **finance**, and **clean engineering**.
Focused on building tools that help users make smarter investment decisions.

---

## 📬 Contact

📧 **[takzen.app@gmail.com](mailto:takzen.app@gmail.com)**
🌐 [investiq-ai.com](https://investiq-ai.com)

---

© 2025 InvestIQ. All rights reserved.
