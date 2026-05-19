# Bitcoin Market Intelligence & Macroeconomic Analytics

## Project Overview

This project analyses Bitcoin’s interaction with macroeconomic indicators, public sentiment, and financial market behaviour using time-series analytics, anomaly detection, sentiment-driven analysis, and business intelligence techniques.

The objective was to investigate whether Bitcoin behaves as:
- an independent financial asset,
- a speculative risk-on asset,
- or a market-sensitive macroeconomic instrument.

The project combines:
- financial analytics,
- public sentiment analysis,
- macroeconomic modelling,
- web scraping,
- anomaly detection,
- and business intelligence reporting

to evaluate how global economic conditions, market fear, and public attention influence Bitcoin price behaviour.

---

# Business Problem

Bitcoin is frequently described as:
- “digital gold,”
- an inflation hedge,
- or an alternative safe-haven asset.

However, growing institutional adoption and global market integration raise important questions:

- Does Bitcoin behave independently from traditional markets?
- Can public sentiment predict Bitcoin volatility?
- Does Bitcoin act as a hedge during equity market downturns?
- How does the strength of the US Dollar affect Bitcoin performance?
- How do macroeconomic news events influence cryptocurrency behaviour?

This project applies analytics and business intelligence techniques to evaluate Bitcoin’s relationship with:
- the S&P 500,
- USD Index (DXY),
- Google Trends search behaviour,
- and macroeconomic news sentiment.

---

# Research Objectives

The project focused on four key analytical questions:

## 1. Public Sentiment & Volatility
Can shifts in public attention, measured using Google Trends, help explain Bitcoin price volatility?

## 2. Bitcoin as a Safe-Haven Asset
Does Bitcoin behave like a protective asset during stock market downturns?

## 3. Bitcoin & USD Relationship
How does US Dollar strength influence Bitcoin price movement?

## 4. Macroeconomic News Impact
What external macroeconomic news events influenced Bitcoin price movement during the COVID-19 period?

---

# Dataset Overview

The project integrated multiple financial and behavioural datasets including:

### Datasets Used
- Bitcoin historical market data
- S&P 500 Index data
- USD Index (DXY) data
- Google Trends search interest data
- Macroeconomic news datasets
- Web-scraped cryptocurrency news articles

### Final Analytical Dataset
- Multi-source time-series financial dataset
- Daily market observations across multiple indicators
- Structured and unstructured text datasets
- Approximately 390 macroeconomic and Bitcoin-related news articles collected through web scraping

The project involved:
- data extraction,
- preprocessing,
- standardisation,
- cleaning,
- time alignment,
- anomaly analysis,
- and financial dataset integration.

---

# Analytical Workflow

## Data Preparation
- Imported and standardised financial datasets from multiple external sources
- Cleaned and transformed market and behavioural datasets
- Aligned datasets into consistent daily time-series structures
- Performed data wrangling and feature standardisation using Python
- Merged financial and behavioural datasets using time-based joins

## External Data Sources
- Yahoo Finance
- Google Trends
- Kaggle
- CoinDesk
- CoinTelegraph
- CryptoSlate
- Bitcoin.com News
- CryptoPotato

---

# Methods & Techniques

## Correlation Analysis
Performed correlation analysis between:
- Bitcoin prices
- Bitcoin volatility
- Google search activity
- S&P 500
- USD Index

to evaluate market interdependencies and sentiment-driven behaviour.

---

## Anomaly Detection

Applied Z-score anomaly detection to identify abnormal Bitcoin return movements.

### Key Findings
- 569 Bitcoin return anomalies identified
- Major anomalies aligned with:
  - COVID-19 market panic
  - 2020 stimulus events
  - 2021 speculative rallies
  - macroeconomic shocks

---

## Sentiment & Behavioural Analysis

Used Google Trends search behaviour as a proxy for:
- market sentiment,
- public attention,
- and speculative behaviour.

The analysis identified:
- strong correlation between search interest and Bitcoin price movement,
- volatility increases during hype periods,
- and sentiment-driven market behaviour.

---

## Web Scraping & Macroeconomic News Analytics

Developed a web scraping pipeline using:
- BeautifulSoup
- feedparser
- requests

to collect cryptocurrency and macroeconomic news articles from RSS-supported financial media sources.

### Workflow Included
- article extraction
- keyword filtering
- text transformation
- macroeconomic topic filtering
- event-based analysis

Approximately 390 Bitcoin-related macroeconomic news articles were collected and processed.

---

# Key Findings

## Public Sentiment Strongly Influences Bitcoin
- Google Trends search interest showed strong correlation with Bitcoin price movement (+0.82).
- Increased public attention frequently aligned with price surges and volatility spikes.

## Bitcoin Behaves Like a Risk-On Asset
- Bitcoin showed strong positive correlation with the S&P 500 (+0.84).
- During the March 2020 COVID market crash, Bitcoin fell alongside equities rather than acting as a hedge.

## Weak Relationship with USD Index
- Bitcoin showed weak correlation with the USD Index.
- Results suggested Bitcoin does not consistently behave as a hedge against fiat currency weakness.

## Macroeconomic Events Influence Volatility
- Major Bitcoin volatility spikes aligned with:
  - COVID-19 developments
  - inflation concerns
  - stimulus announcements
  - regulatory uncertainty
  - speculative market sentiment

---

# Business Recommendations

The analysis generated several insights for investors, institutions, and policymakers:

- Monitor public sentiment and search behaviour as early indicators of cryptocurrency volatility.
- Treat Bitcoin as a speculative risk-on asset rather than a traditional safe-haven investment.
- Incorporate cryptocurrency volatility into broader macroeconomic risk models.
- Use real-time news analytics and sentiment monitoring to support crypto market intelligence systems.
- Improve regulatory clarity to reduce uncertainty-driven volatility.

---

# Tools & Technologies

## Programming & Analytics
- Python
- Power BI

## Data Analysis Techniques
- Correlation Analysis
- Time-Series Analysis
- Anomaly Detection
- Sentiment Analysis
- Behavioural Analytics

## Web Scraping & NLP
- BeautifulSoup
- requests
- feedparser

## Visualisation & Reporting
- Power BI
- Heatmaps
- Line Charts
- Z-Score Analysis
- Dashboarding

---

# Repository Structure

```bash
├── data/
│   ├── sample datasets
│   ├── processed financial datasets
│
├── notebooks/
│   ├── data cleaning
│   ├── anomaly detection
│   ├── sentiment analysis
│   ├── market analysis
│
├── web_scraping/
│   ├── scraping_scripts.py
│   ├── rss_extraction.py
│
├── dashboards/
│   ├── powerbi_dashboard.pbix
│   ├── dashboard_screenshots
│
├── visualisations/
│   ├── heatmaps
│   ├── volatility charts
│   ├── anomaly plots
│
├── reports/
│   ├── final presentation
│   ├── project insights
│
├── README.md
