# 📊 TED Talk Analysis: Exploratory Data Analysis (EDA)

This project provides a comprehensive analysis of TED Talk data using Python. It explores viewership trends, speaker popularity, and audience engagement to understand what makes a TED talk successful.

## 🧐 Project Objective
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on a dataset of TED talks to extract actionable insights. By calculating engagement metrics and visualizing temporal trends, we can identify patterns in how global audiences consume educational content.

---

## 🚀 Detailed Workflow

### 1. Data Loading & Cleaning
* **Environment Setup:** Utilized `Pandas` for data manipulation and `Matplotlib/Seaborn` for visualization.
* **Feature Extraction:** Created new features from the raw data to enable deeper analysis:
    * **Date Decomposition:** Split timestamps into `Day`, `Month`, and `Year`.
    * **Engagement Ratio:** Calculated a "View-to-Like" ratio ($Views / Likes$) to identify which talks had the highest audience sentiment, rather than just raw volume.

### 2. Exploratory Data Analysis (EDA)
The analysis is broken down into five key areas:
* **Speaker Analysis:** Identifying "Power Speakers" (those with the most frequent appearances) and calculating their cumulative reach.
* **Temporal Trends:** * **Monthly Trends:** Which months see the most TED releases?
    * **Yearly Growth:** How has the volume of TED content scaled over the last decade?
* **Category/Tag Analysis:** Filtering talks by specific themes (e.g., Technology, Design, Climate) to see which topics dominate the platform.
* **Engagement Metrics:** Ranking talks not just by views, but by the "Like" density to find the most impactful content.

### 3. Search & Discovery Logic
Implemented a functional search mechanism within the notebook that allows users to:
* Search for all talks by a specific **Author**.
* Filter talks by specific **Tags** or topics.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Library (Data):** Pandas, NumPy
* **Library (Viz):** Matplotlib, Seaborn
* **Platform:** Google Colab / Jupyter Notebook

---

## 📁 Repository Structure
* `ted_talk_analysis.ipynb`: The main execution script containing all logic and visualizations.
* `data.csv`: The dataset containing metadata (Speaker, Views, Likes, Tags, etc.).
* `README.md`: Project documentation.

---

## ⚙️ How to Run This Project

1. **Clone the Repository:**
