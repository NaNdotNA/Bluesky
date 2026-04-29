# Bluesky Platform Analysis: Content & Network Integrity

### Project Overview
This project explores the **Bluesky social ecosystem** through data engineering, statistical modeling, and network analysis. The goal is to understand user behavior, detect patterns in content distribution, and analyze network structures—all foundational components of modern **Trust & Safety Engineering.**

### Key Technical Phases

* **Data Acquisition & NLP:** Collected and cleaned post data, handled missing values (NAs), and performed word frequency visualizations to identify trending topics or potential spam patterns.
* **Statistical Analysis:** Conducted **Hypothesis Testing** and **Chi-Square tests** to validate relationships between user metrics (e.g., comparing raw post counts vs. follower growth).
* **Network Graph Analysis:** * Built and visualized **User Interaction Graphs**.
    * Performed **Centrality Analysis** to identify influential nodes (potential bot "hubs" or high-impact accounts).
* **Clustering & Dimensionality Reduction:**
    * Transformed text data into a **TF-IDF Matrix**.
    * Applied **K-Means Clustering** to group similar users/content.
    * Used **PCA (Principal Component Analysis)** for high-dimensional data visualization.

### Tech Stack
* **Language:** R / R Markdown
* **Libraries:** `igraph` (Graph Theory), `tm`/`tidytext` (NLP), `ggplot2` (Visualization), `stats` (Statistical Modeling)

### Trust & Safety Relevance
This workflow mimics the pipeline used to detect **coordinated inauthentic behavior (CIB)**. By combining content analysis (TF-IDF/Clustering) with network structure (Centrality), we can more accurately distinguish between organic community growth and artificial manipulation.
