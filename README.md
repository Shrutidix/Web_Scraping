# 📚 Book Catalog Web Scraping & Analysis

## 📌 Project Overview

This project was developed as part of the **CodeAlpha Data Analytics Internship – Task 1: Web Scraping**.

The objective of this project is to collect structured book-related information from a publicly available website using Python web scraping techniques. The collected data is then cleaned, analyzed, and visualized to identify useful patterns and insights.

---

## 🎯 Objectives

- Extract book information from a public website.
- Understand and navigate HTML structures.
- Use Python libraries for web scraping.
- Clean and organize the collected data.
- Perform basic exploratory data analysis.
- Create visualizations to understand the dataset.
- Generate a reusable dataset in CSV format.

---

## 🌐 Data Source

**Website:** Books to Scrape

The website provides a sandbox environment specifically designed for practicing web scraping.

**Source:** https://books.toscrape.com/

A total of **1,000 book records** were collected from the available catalog pages.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Requests | Sending HTTP requests |
| BeautifulSoup | HTML parsing and data extraction |
| Pandas | Data cleaning and analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook | Development environment |

---

## 📊 Data Collected

The scraper collected the following information:

- **Title** – Name of the book
- **Price** – Book price in GBP
- **Rating** – Rating from 1 to 5
- **Availability** – Availability information
- **Stock** – Available quantity when provided by the website
- **Category** – Book category
- **URL** – Individual book webpage

---

## 🔄 Project Workflow

```text
Public Website
      ↓
HTTP Request using Requests
      ↓
HTML Response
      ↓
HTML Parsing using BeautifulSoup
      ↓
Data Extraction
      ↓
Data Cleaning using Pandas
      ↓
Exploratory Analysis
      ↓
Data Visualization
      ↓
Final CSV Dataset
