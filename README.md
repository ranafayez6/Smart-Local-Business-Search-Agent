# 🤖 AI-Powered Local Business Finder

An intelligent automation workflow built with **n8n**, **Google Gemini AI**, **Telegram**, **Apify**, **Google Sheets**, and **Power BI** that allows users to search for any type of business or location through a simple Telegram chat.

The system automatically extracts the user's request, collects relevant business data, stores it in Google Sheets, and makes it available for analysis and reporting.

---

## 🚀 Project Overview

This project automates local business discovery using AI and web scraping.

Users can search for:

- Restaurants
- Cafes
- Pharmacies
- Hospitals
- Hotels
- Gyms
- Shops
- Companies
- Any location-based business

The AI agent understands the user's request, extracts the search target and location, then retrieves and organizes the data automatically.

---

## ⚙️ Workflow Architecture

Telegram → Gemini AI Agent → JavaScript Processing → Google Sheets → Apify Scraper → Google Sheets → Power BI → Telegram Notification

---

## 🔥 Features

- AI-powered query understanding
- Telegram chatbot interface
- Automatic location extraction
- Dynamic business search
- Web scraping automation with Apify
- Google Sheets integration
- Automated data storage
- Power BI reporting and visualization
- Real-time notifications
- Scalable workflow for multiple business categories

---

## 🛠️ Tech Stack

- n8n
- Google Gemini AI
- Telegram Bot API
- JavaScript
- Apify
- Google Sheets API
- Power BI

---

## 📋 Workflow Steps

### 1. Telegram Trigger
Receives user requests from Telegram.

### 2. AI Agent (Gemini)
Extracts business type and location from the user's message.

### 3. JavaScript Processing
Formats and prepares search queries.

### 4. Google Sheets Creation
Creates a spreadsheet for storing collected data.

### 5. Apify Scraper
Collects business information based on the user's request.

### 6. Data Storage
Stores results automatically in Google Sheets.

### 7. Aggregation
Processes and structures collected records.

### 8. Telegram Notification
Sends the spreadsheet link back to the user.

### 9. Power BI Dashboard
Visualizes collected data for analysis and reporting.

---

## 📊 Example Queries

- Find restaurants in Cairo
- Search for pharmacies in Alexandria
- Find hotels in Dubai
- Search for gyms in Nasr City
- Find coffee shops near Dokki

---

## 📈 Power BI Analytics

The collected data can be visualized through Power BI dashboards, including:

- Businesses by category
- Businesses by city
- Contact information analysis
- Data collection statistics
- Search trends
- Geographic insights

---

## 🎯 Use Cases

- Local business discovery
- Lead generation
- Market research
- Business intelligence
- Data collection automation
- AI-powered search systems

---

## 📸 Workflow Preview

<img width="100%" alt="Workflow" src="<img width="1812" height="480" alt="Screenshot 2026-07-30 011845" src="https://github.com/user-attachments/assets/94390b8b-45f7-422a-a357-80f0327f96a5" />
">

---

## 👩‍💻 Author

**Rana Fayez**

Data Science Student | AI & Automation Enthusiast

---

## ⭐ Future Enhancements

- Multi-language support
- Interactive Telegram menus
- Location-based recommendations
- Automated reporting
- Advanced Power BI dashboards
- User search history tracking
