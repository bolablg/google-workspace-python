# 📊 Google Sheets Automation with Python + MongoDB

This repository contains a Jupyter Notebook that automates the generation and sharing of daily reports using **Python**, **Google Sheets**, and **Google Drive**.  
It’s designed for professionals who want to streamline repetitive reporting tasks using low-cost, maintainable solutions.

Data is sourced from a **MongoDB** database (which you can simulate locally using Docker), processed with **pandas**, then exported and shared via the Google APIs.

---

## 🚀 Features

- Connect to a MongoDB database
- Analyze and structure agent activity data
- Generate daily performance and payment reports
- Automatically create and fill Google Sheets
- Share files via Google Drive with optional notifications
- Archive old reports to avoid duplication and preserve history

---

## 🧰 Prerequisites

### Required Python Libraries

Install dependencies:

```bash
pip install pandas gspread pymongo google-api-python-client google-auth google-auth-oauthlib