# 📺 AI Analysis of Your Favorite TV Series

This project demonstrates how to analyze your favorite TV series using Artificial Intelligence (AI), Large Language Models (LLMs), and Natural Language Processing (NLP). This project includes data scraping, theme extraction, character network creation, text classification, and chatbot development to simulate character conversations.

## 🌟 Project Overview

| Module               | Description                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------|
| 🕸️ **Data Scraping**      | Gather data from websites using Scrapy in `scrapy_spider.py`.                                  |
| 🎭 **Theme Extraction**    | Identify main themes in the series using zero-shot classification with Hugging Face.       |
| 👥 **Character Network**   | Visualize character connections using SpaCy’s NER, NetworkX, and PyViz.                     |
| 📚 **Text Classification** | Train a custom text classifier to categorize series-related content.                        |
| 🤖 **Character Chatbot**   | Simulate character conversations with a chatbot for interactive engagement.               |

## 📖 Learning Objectives

### 1. Data Scraping 🕸️

Use Scrapy to gather data from your favorite TV series' websites. Customize the spider in `scrapy_spider.py` to efficiently scrape relevant text and metadata.

### 2. Theme Extraction 🎭

Utilize Hugging Face and Transformers to implement zero-shot classification. This enables the extraction of core themes, genres, and styles from the series content.

### 3. Character Network 👥

Create a network visualization of characters, capturing relationships and interactions. Leverage SpaCy for Named Entity Recognition (NER), NetworkX for network creation, and Pyviz for visualization.

### 4. Text Classification 📚

Train a text classifier to distinguish between different types of content (e.g., plot summary, character quotes) using Hugging Face Transformers. Customize the dataset to fit the series and the type of insights desired.

### 5. Character Chatbot 🤖

Build a chatbot to simulate conversations with characters from your TV series. The chatbot uses pre-trained LLMs to mimic dialogue styles, adding a fun, interactive layer to the project.

---

## 🏗️ Project Architecture

```mermaid
graph TD
    A[Data Scraping 🕸️] --> B[Data Storage]
    B --> C[Theme Extraction 🎭]
    B --> D[Character Network 👥]
    B --> E[Text Classification 📚]
    C --> F[Visualize Themes]
    D --> G[Character Relationship Visualization]
    E --> H[Category Classification]
    F --> I[UI - Interactive Display]
    G --> I
    H --> I
    I --> J[Character Chatbot 🤖]
    J --> K[User Interaction]

