# AI Search & Media Recency Tracker

## Project Overview
If a brand is invisible in the news, it becomes invisible in AI search. Large Language Models (LLMs) like ChatGPT and Perplexity rely heavily on recent, authoritative, third-party news sources to generate brand recommendations and answer market queries. 

This Python-based data analysis tool pulls targeted RSS feeds from Google News to track the media "Share of Voice" (SOV) and article recency across specific domains (e.g., Australian Retail/Supermarkets, EVs, Fintech). By filtering out noise and categorizing news hits into 7-day, 14-day, and 30-day windows, PR and Marketing teams can visually assess their real-time media momentum and optimize for Answer Engine Optimization (AEO).

## Features
* **Automated Data Scraping:** Fetches real-time news data from Google News via RSS using precise Boolean search queries.
* **Domain-Specific Filtering:** Uses keyword matching to filter out irrelevant noise (e.g., filtering for purely grocery/supermarket headlines in retail, or battery/charging headlines in EVs).
* **Recency Analytics:** Calculates article age from publication dates and bins them into actionable timeframes (Last 7, 14, and 30 Days).
* **Automated Visualizations:** Generates a visually intuitive, independently scaled heatmap showing the recency of media coverage for competitive analysis.
* **Exportable Data:** Outputs raw article links and aggregated summary tables to CSV for further LLM prompting or dashboarding.
