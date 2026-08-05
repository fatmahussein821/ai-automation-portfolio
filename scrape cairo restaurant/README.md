![scrape cairo restaurant Workflow](workflow.png)

# Cairo Restaurant Scraper

## Overview
An automated data collection workflow built with **n8n**. The workflow retrieves restaurant data from Google Maps using the Apify API, cleans and filters the results, removes duplicate records, and stores only unique restaurants in Google Sheets.

## Features
- Automatically collects restaurant data from Google Maps.
- Extracts contact details and business information.
- Filters out records without phone numbers.
- Removes duplicate entries before saving.
- Appends only new restaurants to Google Sheets.

## Tech Stack
- n8n
- Apify API
- Google Maps
- Google Sheets API
- JavaScript
