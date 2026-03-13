# 📊 Github-Repo-Analytics-Dashboard

An **interactive 3-page Power BI dashboard** analyzing **5,500 GitHub repositories across 12 programming languages**. This project explores the relationship between **community popularity, code maintenance, and long-term project sustainability** in open-source ecosystems.

# 🚀 Project Overview

In open-source ecosystems, **stars and forks are often seen as indicators of popularity**, but they don't always represent **project health or maintainability**.

This dashboard was designed to distinguish between:

-   ⭐ **Vanity Metrics** -- stars and forks\
-   🧩 **Health Signals** -- CI/CD adoption, documentation quality,
    issue resolution, and maintenance activity

Using a dataset covering **2014 -- 2025**, the dashboard provides insights into how **open-source projects evolve over time**, highlighting patterns in **community engagement, project sustainability, and ecosystem growth**.


# 📥 Download the Dashboard

To explore the dashboard interactively:

1.  Clone the repository
2.  Open the `.pbix` file using **Power BI Desktop**

``` bash
git clone https://github.com/Nishiv15/github-repo-analytics-dashboard
```


# 🔍 Key Insights by Dashboard Page

## 1️⃣ Ecosystem Overview & Popularity

This section provides a **high-level overview of GitHub's programming ecosystem**.

### Market Share

Visualizes which programming languages dominate GitHub based on: - Repository volume - Star counts

Examples include ecosystems such as: - Python - TypeScript - Go - JavaScript

### The Utility Matrix

A **scatter plot comparing Stars vs Forks** to identify: - ⭐ Projects that are famous but rarely used - 🔧 Projects widely used as dependencies

### Licensing Landscape

Breakdown of open-source licenses including: - MIT - Apache - GPL


## 2️⃣ Maintenance & Community Health

This page focuses on **how actively projects are maintained and supported**.

### PR Pipeline

A funnel visualization showing the lifecycle of pull requests:

Opened PRs → Reviewed PRs → Merged PRs

### Documentation Audit

A **100% stacked bar chart** analyzing the presence of: - Wikis - Contributing Guides - Codes of Conduct

### Quality Benchmarks

Evaluation of: - Test coverage distribution - CI/CD adoption across tech stacks


## 3️⃣ Temporal Trends & Growth

This page analyzes **how open-source ecosystems evolve over time**.

### Velocity Tracking

Area charts visualize waves of repository creation from **2014 to 2025**.

### Project Staleness

A **heatmap matrix** identifies abandoned ecosystems based on last commit year.

### Code Complexity

Box plots comparing repository sizes (`size_kb`) to detect trends in code bloat vs efficiency.


# 🛠️ Built With

  Power BI Desktop ->  Dashboard creation and visualization
  Power Query (M)  ->  Data cleaning and transformation
  DAX              ->  Custom analytics measures
  Kaggle Dataset   ->  GitHub repository metrics dataset



# 📂 Dataset Information

*The original data was altered for visualizing it in dashboard.

  Source         ->    Kaggle -- GitHub Repo Metrics Dataset
  Author         ->    Lorenzo Scaturchio
  Link           ->    https://www.kaggle.com/datasets/lorenzoscaturchio/github-repo-metrics
  Repositories   ->    5,500
  Features       ->    29
  Timeline       ->    2014 -- 2025
  Data Type      ->    Synthetic


# 📝 How to Use

1.  Clone the repository

``` bash
git clone https://github.com/yourusername/github-ecosystem-dashboard
```

2.  Open the `.pbix` file in **Power BI Desktop**\
3.  Navigate between the **three dashboard pages**\
4.  Use the **Language Slicer** to filter insights by programming
    language.


# 📌 Key Learnings

-   Popularity metrics don't always represent **project health**
-   **Documentation and CI/CD** strongly correlate with sustainability
-   Some ecosystems show signs of **project stagnation over time**


# 👨‍💻 Author

**Nishiv Trivedi**\
Computer Science Engineering Student\
Web Development & Data Analytics Enthusiast

GitHub: https://github.com/Nishiv15


# ⭐ If you like this project

Give the repository a **star ⭐** and explore the dashboard!
