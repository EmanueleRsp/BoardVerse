# 🧩 BoardVerse

**BoardVerse** is a web-based platform developed as part of the _Large-Scale and Multi-Structured Databases_ course project (A.Y. 2024/2025). It aims to centralize and explore information about modern board games, integrating data from both **BoardGameGeek (BGG)** and **BoardGameArena (BGA)**.

👉🏽 [Repository with original Scraping code](https://github.com/EmanueleRsp/BGG-BGA-Scraping) 

## 📌 Features

- 🗂️ **Games Catalog**: Explore metadata of 2,000+ top-ranked board games.
- ⭐ **User Reviews**: Discover user-generated ratings and comments.
- 💬 **Forums**: Dive into community discussions with threads and messages per game.
- 🏆 **Tournaments**: Browse upcoming events and their configurations (BGA).
- 🧠 **Recommendations**: Suggest friends and games using graph-based traversal.

## 🧱 Technologies

- **MongoDB**: Stores structured document data (games, reviews, users, tournaments).
- **Neo4j**: Manages graph data for relationships and recommendations.
- **Python**: Custom scripts for data scraping, API integration, and dataset generation.
- **Java** (Spring Boot): RESTful backend exposing services for the application.

## 📊 Dataset Overview

- ~500 MB of processed data
- Collected from BGG (via XML API) and BGA (via scraping)
- Enhanced with realistic synthetic data where unavailable
- Covers: Games, Users, Reviews, Forums, Tournaments

## 🚀 Setup Instructions

> Full instructions and API documentation available in the `/docs` folder.

1. Clone the repository
2. Set up MongoDB and Neo4j instances
3. Run backend services (`/java-backend`)
4. (Optional) Launch dataset generation scripts (`/data-scripts`)

