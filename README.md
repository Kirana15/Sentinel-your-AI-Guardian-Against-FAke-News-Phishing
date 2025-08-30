# Sentinel-your-AI-Guardian-Against-FAke-News-Phishing

A web application that detects malicious (phishing) URLs and fake news articles to help users stay safe from cyber threats and misinformation. The system leverages NLP, and Generative Artificial intelligence  APIs to analyze URLs and news content in real-time.

## Features
->Phishing Link Detection

Checks URLs for suspicious patterns, subdomains, and redirections
Uses SSL/TLS certificate verification, WHOIS info, and IP reputation
Integrates with Gemini APi to get better verdicts.

->Fake News Detection

Implements Gemini APi to understand the nuances better, and uses google search tool to fetch the available articles regarding the news given as input. 

->Interactive Web App

Built with Streamlit for user-friendly interaction. Simple input forms for URLs & news articles. Clear, visual output with detection results

## How it works
1 User Input

Enter a URL to check if it is phishing/malicious

Paste a news article text to check authenticity

2 Phishing Detection Pipeline

 WHOIS, certificate, domain and others features are considered to judge the link as benign or malicious.


3 Fake News Detection Pipeline

Preprocesses news text using NLP searches for the articles with same nuances and classify if the information is Real or Fake.

Output

Verdict: Safe , suspicious , phishing

├── detectors/             
│   ├── phishing.py        
│   ├── fake_news.py                         
├── appcy.py                 
├── requirements.txt      
└── README.md     
## Requirements
 streamlit,
streamlit-option-menu,
streamlit-lottie,
pillow,
requests,
beautifulsoup4,
selenium,
googlesearch-python,
webdriver-manager,
google-generativeai,
beautifulsoup4,
requests,
google-generativeai,
whois

For Web Interface
-streamlit

Tap on 'Open in Streamlikt' button to use the web application

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)]([https://krishi-jnan-mxvlhad4zmbyyb89js8twa.streamlit.app/](https://sentinel-your-ai-guardian-against-fake-news-phishing-k9uf2utqn.streamlit.app/))

## Author
Kirana BV

kiranaish15@gmail.com

linkedin.com/in/kirana-BV0106
