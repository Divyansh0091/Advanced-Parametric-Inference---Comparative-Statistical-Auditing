# Advanced Parametric Inference & Comparative Statistical Auditing

## 📌 Executive Summary & Business Objective
This data science project executes a high-fidelity statistical audit using multiple parametric hypothesis testing frameworks. The core objective is to analyze variations in corporate operational metrics using two distinct testing strategies. 

By mapping and contrasting paired dependencies against independent group benchmarks, this project provides HR and operational leadership with clear, data-validated insights to measure the true impact of strategic initiatives (like automation rollout) and team efficiency setups.

---

## 🛠️ Tech Stack & Architecture
* **Core Language:** Python 3.x
* **Statistical Computing:** SciPy (Stats Module), NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 🧪 Statistical Framework & Core Methodology (The Critical Differences)

This project structurally splits the hypothesis testing into two separate domains to address different corporate data structures:

### 1. Paired Variable Analysis (`ttest_rel`)
* **Objective:** Measures the performance delta within the **same group of subjects** across two different timelines.
* **Corporate Application:** Analyzed individual employee metrics before and after the deployment of automation tools (`Before_Automation` vs. `After_Automation`).
* **Statistical Setup:** Evaluates if the internal mean variation is driven by the structural automation strategy or random operational noise.

### 2. Independent Summary Statistics (`ttest_ind_from_stats`)
* **Objective:** Compares the mean scores of **two entirely separate, mutually exclusive groups** where raw individual data points are unavailable, and only descriptive statistics (`mean`, `std`, `nobs`) are provided.
* **Corporate Application:** Audited the baseline performance gap between two cross-functional teams (Technical Group 1 vs. Operational Group 2).
* **Statistical Setup:** Determines whether the efficiency gap between the two separate structural tiers is statistically significant or standard variance.

---

## 📊 High-Fidelity Statistical Visualizations
To maintain institutional reporting standards, two distinct visual architectures were deployed:
1. **Pre-vs-Post Performance Distribution (Boxenplot):** Built using `sns.boxenplot` on melted dataframe metrics to expose heavy-tailed distributions and structural variance before and after automation.
2. **Cross-Functional Team Confidence Intervals (Point Error Plot):** Utilized `plt.errorbar` to cleanly plot the independent means against their corresponding standard deviations, mapping variance boundaries without needing raw observation arrays.# Advanced-Parametric-Inference-&-Comparative-Statistical-Auditing

