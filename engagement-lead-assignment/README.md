# Engagement Lead - Technical Assignment

## Overview
Welcome! This assignment simulates a real-world scenario where you need to unify and analyze multi-channel advertising data.

While Engagement Leads don't typically build dashboards or deploy databases in day-to-day work, we want to ensure you're technical enough to understand our clients' data, speak confidently about data transformations, and tackle any challenge that comes your way.

## Data Files

- `01_facebook_ads.csv` - Facebook advertising metrics
- `02_google_ads.csv` - Google Ads campaign data
- `03_tiktok_ads.csv` - TikTok advertising engagement

## Requirements

### 1. Data Transformation

- Create a unified dataset from all three CSV files using SQL
- **You choose your approach:**
  - **Cloud database** (BigQuery, Redshift, Snowflake, etc.) - good practice for real-world scenarios
  - **Local tools** (DuckDB, SQLite, PostgreSQL on Docker) - faster setup if you prefer
  - **Python + SQL** (pandas + sqlalchemy, or polars) - if that's your comfort zone

**Important:** Regardless of your chosen tool, you must provide a SQL script showing your transformation logic. We want to see how you think about joining and unifying multi-source data.

### 2. Dashboard

Create a one-page dashboard visualizing the integrated data. Include key metrics and insights relevant for cross-channel performance analysis.

### 3. Video Walkthrough (3-5 minutes)

Record a single video where you:

**Part A - Technical Walkthrough (~2 min)**
- Show your SQL script and briefly explain your transformation logic
- Walk through how you unified the three data sources
- If using a cloud/local database tool, show the interface; if using Python/local files, show your code editor

**Part B - Dashboard Presentation (~2-3 min)**
- Present your dashboard as if you're showing it to a client
- Highlight 2-3 key insights from the data

## Deliverables

1. Link to live dashboard
2. SQL script used for data transformation
3. Video link (Loom, Google Drive, or any shareable format)

## Evaluation Criteria

| Area | What We're Assessing |
|------|---------------------|
| **Technical execution** | SQL quality, data accuracy, tool proficiency |
| **Dashboard** | Visualization clarity, relevant metrics, actionable insights |
| **Communication** | Ability to explain technical work clearly, client-ready presentation style |

## Submission

Send the dashboard link, SQL script, and video link.
