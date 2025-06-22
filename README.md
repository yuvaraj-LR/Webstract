# 🌐 AI-powered Content Extractor — Webstract

Transform messy webpages into clean, structured summaries using the power of AI.

---

## 🚀 Overview

**Webstract** is an AI-powered web content extraction tool that allows users to input any **public URL** and receive:

- A meaningful **title**
- A **concise summary**
- 3–5 **key points** from the web page

This application is built with a **separate frontend and backend architecture**, enabling clean modular design and scalability.

---

## 📂 Project Repositories

| Layer      | Repository Link |
|------------|------------------|
| 🔗 Backend | [View Backend Repository](https://github.com/yuvaraj-LR/Content-Extractor---Backend) |
| 🎨 Frontend | [View Frontend Repository](https://github.com/yuvaraj-LR/Content-Extractor--Frontend) |

> ⚠️ Note: This repository (the one you're viewing) only serves as a **project overview** and directory for both parts of the application.

---

## 🛠️ Tech Stack

### 🔧 Backend

- **Node.js** with **Express**
- **MongoDB** for data storage
- **Google Gemini AI API** for generating summaries and insights
- **Cheerio + Axios** for scraping website content
- **OnRender** for backend deployment

### 🎨 Frontend

- **React.js**
- **Styled Compnents** for Styling 
- **Context API** for State Management
- **React Browser DOM** for route handling
- **Toastify** for handling error
- **Fetch** for HTTP communication

---

## ✨ Features

- ✅ Enter any public URL to analyze
- 🧠 Uses **Gemini AI** for intelligent summarization
- 📌 Extracts **Title**, **Summary**, and **Key Points**
- 📄 Stores extracted data in the database
- ⚡ Beautiful, animated, and responsive frontend UI
- 🔁 Avoids duplicate work by checking if a URL is already processed

---

## 🧪 How It Works

1. User enters a valid URL.
2. Backend scrapes the web content using Cheerio.
3. Gemini AI processes the content and returns structured information.
4. If the URL was previously analyzed, returns cached results from MongoDB.
5. Frontend displays the response with modern UI animations.

---
