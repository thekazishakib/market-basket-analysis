# 🛒 Market Basket Analysis: 2.6M+ E-commerce Transactions

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/MLxtend-FFB000?style=for-the-badge&logo=jupyter&logoColor=white" alt="MLxtend" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License" />
</p>

### 🌌 Project Overview
This project focuses on uncovering hidden consumer purchasing patterns within a massive e-commerce dataset. By implementing the **Apriori Algorithm**, I identified significant association rules that can drive strategic decisions in cross-selling, inventory management, and personalized marketing.

---

## 💎 High-Impact Results
* **Scalable Data Mining:** Successfully processed and analyzed **2.6 Million+** transaction rows.
* **Statistical Discovery:** Extracted **8 high-confidence association rules** from a pool of **91,619 unique users**.
* **Category Intelligence:** Insights mapped across **13 distinct product categories** to understand cross-category behavior.

---

## 🛠️ Tech Stack & Methodology
| Domain | Tools & Frameworks |
| :--- | :--- |
| **Core Engine** | Python 3.x, Pandas, NumPy |
| **Logic Layer** | Apriori Algorithm (Association Rule Mining) |
| **Key Library** | MLxtend (Machine Learning Extensions) |
| **Visualization** | Matplotlib, Seaborn |

---

## 📈 Analysis Framework
To ensure the reliability of the discovered rules, I utilized three core metrics:
* **Support:** Measures the popularity of an itemset.
* **Confidence:** Calculates the likelihood that item Y is purchased when item X is purchased.
* **Lift:** Determines the strength of the association (Lift > 1 indicates a high positive correlation).

---

## 📑 Project Resources (Quick Access)

| Asset | Link | Format |
| :--- | :--- | :--- |
| **Analysis Notebook** | [🚀 Open Notebook](./notebooks/market_basket_analysis.ipynb) | `.ipynb` |
| **Technical Report** | [📂 Download Report](./documentation/MBA_Report_Final.docx) | `.docx` |
| **Executive Presentation** | [📊 View Slides](./documentation/MBA_Presentation_Final.pptx) | `.pptx` |
| **Kaggle Dataset** | [📥 Download via Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-purchase-history-from-electronics-store) | `External` |

> **Note:** Due to the large file size (**259MB**), the `kz.csv` file is hosted externally on Kaggle.

---

## 📂 Repository Structure
```bash
market-basket-analysis/
├── assets/         # High-resolution charts and visuals
├── data/           # Dataset link and source information
├── documentation/  # Professional reports and presentation decks
├── notebooks/      # Clean, commented Jupyter Notebook (Analysis_Main.ipynb)
└── README.md       # Project documentation
---

