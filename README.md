# Reddit Scraper Demo (n8n Workflow)

This repository contains an n8n workflow that scrapes posts from the `r/n8n` subreddit based on selected keywords like `n8n`, `workflow examples`, and `best practices`. It filters posts with at least 10 upvotes and uses OpenAI to classify whether they are useful for learning n8n real-world use cases. Approved posts are then sent to a Discord channel via webhook.

📹 [Loom Video Walkthrough](https://www.loom.com/share/d885ed7a31564d64823852cbfe52abfe)

## Files
- `Reddit_Scraper_Demo.json`: The n8n workflow export file.

## How to Use
1. Import the JSON file into your n8n instance.
2. Configure Reddit and OpenAI credentials.
3. Set up a Discord webhook for sending messages.
4. Trigger the workflow manually or set it on a schedule.
