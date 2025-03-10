# 🌐 Crisis Event Analysis from Reddit Data

This repository contains a comprehensive pipeline for analyzing Reddit posts to identify, classify, and visualize crisis events. The project is divided into three main tasks:

1. **Data Extraction and Filtering**
2. **Sentiment and Risk Classification**
3. **Geolocation and Crisis Mapping**

---

## 📂 Project Structure

```
.
├── Task_1/               # Data Extraction and Filtering
│    ├── task1_notebook.ipynb
│    └── filtered_reddit_posts.csv
│
├── Task_2/               # Sentiment and Risk Classification
│    ├── task2_notebook.ipynb
│    ├── classified_reddit_posts.csv
│    ├── sentiment_analysis_graph.png
│    └── risk_analysis_graph.png
│
└── Task_3/               # Geolocation and Crisis Mapping
     ├── task3_notebook.ipynb
     ├── crisis_heatmap.png
     └── top_crisis_locations.png
```

---

## 📝 Task Descriptions

### 📊 Task 1: Data Extraction and Filtering
- **Objective:** Extract and preprocess Reddit posts relevant to crisis events.
- **Outputs:**
    - `filtered_reddit_posts.csv`: Contains cleaned and filtered Reddit data.

### 📈 Task 2: Sentiment and Risk Classification
- **Objective:** Classify Reddit posts based on sentiment (positive/neutral/negative) and risk levels (low/medium/high).
- **Outputs:**
    - `classified_reddit_posts.csv`: Annotated dataset with sentiment and risk levels.
    - `sentiment_analysis_graph.png`: Visualizes sentiment distribution.
    - `risk_analysis_graph.png`: Displays the distribution of risk levels.

### 🌍 Task 3: Geolocation and Crisis Mapping
- **Objective:** Extract location information from the posts and visualize crisis hotspots.
- **Outputs:**
    - `crisis_heatmap.png`: A heatmap indicating crisis-prone areas.
    - `top_crisis_locations.png`: Bar graph of the most mentioned crisis locations.

---

## 📊 How to Run the Notebooks
### Step 1: Clone the Repository
### Step 2: Set Up the Environment
### Step 3: Run Each Notebook

Execute the notebooks in order:

1. Navigate to each task folder.
2. Open and run the Jupyter Notebook.

---

## 📌 Dependencies

Ensure the following libraries are installed:

- pandas
- numpy
- matplotlib
- seaborn
- spaCy
- folium
- geopy
---

## 📊 Results and Insights

- **Data Insights:** Identified patterns in sentiment and risk levels across different crisis categories.
- **Geolocation Insights:** Mapped high-risk areas based on extracted locations from Reddit posts.

---
