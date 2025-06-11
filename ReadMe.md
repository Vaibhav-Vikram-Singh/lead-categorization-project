ai_readiness_leadgen_tool

This project is a prototype for an acquisition intelligence tool. It scrapes homepages and standard subpages of companies' websites, extracts textual content, and assigns a likely business category using keyword matching.

Features:

Scrapes main pages and subpages like /about, /contact, /careers
Cleans and combines text from websites
Uses keyword-based scoring to assign likely business category (AI, SaaS, Fintech, Developer Tools)
Generates final scores and plots category distribution

Setup Instructions:

Clone the repository or download the files.

Install the required libraries:

pip install -r requirements.txt

Run the notebook:

Open lead_categorizer.ipynb in Jupyter or VS Code.

Output:

DataFrames with full website text
Keyword category scores
Final category label per website
Bar plot of distribution

Notes:

If requests fail, Selenium is used as a fallback.
The notebook includes hardcoded fallback text for OpenAI and Airbnb

## 📽️ Video Walkthrough

Watch the 1–2 minute demo of this project here:  
[Watch the video](https://youtu.be/860fHAZHcr8)
