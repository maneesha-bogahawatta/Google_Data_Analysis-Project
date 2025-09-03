Google Trends Analysis: Time Series & Country Maps

This project analyzes search trends using Google Trends data. It allows users to explore how the popularity of keywords changes over time and across countries, and provides interactive visualizations for deeper insights.

Features

Interest Over Time: Line plots showing how search interest evolves for one or multiple keywords.

Interest by Region: Interactive choropleth maps displaying search interest by country.

Hover Details: Country names and interest scores appear on hover for better readability.

Safe Data Fetching: Implements automatic handling of Google’s “Too Many Requests (429)” errors with retries and delays.

Customizable: Users can change keywords, timeframes, and plot styles.

Technologies Used

Python – Core language for data processing and visualization

Pytrends – Python API for fetching Google Trends data

Matplotlib – For time-series visualizations

Plotly – For interactive choropleth maps

PyCountry – To convert country names to ISO-3 codes for mapping

Installation
pip install pytrends matplotlib plotly pycountry

Usage

Set your list of keywords and timeframe.

Fetch interest over time and interest by region using Pytrends.

Plot interactive line charts and choropleth maps in Jupyter Notebook.

Optional Add-on Features

Multi-keyword comparisons

Export plots as images or HTML

Automatic safe retry system for large-scale trend analysis

This project is perfect for:

Data enthusiasts exploring trends in search interest

Students learning time series analysis and geographic visualizations

Anyone interested in tracking keyword popularity over time and across countries
