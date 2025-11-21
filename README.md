# 📚 Data Science Study Resources

> A comprehensive collection of data science study materials, tutorials, datasets, and practice resources for aspiring data scientists and ML enthusiasts.

[![GitHub](https://img.shields.io/badge/GitHub-HarshChoudhary2003-blue)](https://github.com/HarshChoudhary2003)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-November%202025-brightgreen)](#)

---

## 📖 About This Repository

This repository contains curated study materials, cheat sheets, tutorials, and datasets to help you master data science concepts from beginner to advanced level. Perfect for:
- 🎓 Students learning data science
- 💼 Professionals preparing for data science interviews
- 🚀 Anyone building their data science portfolio
- 📊 Practitioners looking for quick reference guides

---

## 📂 Repository Structure

```
Data-Science-Study-Resouces-/
├── Datasets/              # Practice datasets for various domains
├── PDF Resources/         # Study guides and tutorials
├── Notebooks/            # Jupyter notebooks and code examples
└── README.md             # This file
```

---

## 📚 Available Resources

### 📊 **Data Analysis & Visualization**
- **Power BI for Beginners** - Complete guide to Power BI
- **PowerBI e-guide** - Detailed Power BI tutorial
- **Data Analysis with Python** (.docx, .pdf) - Python data analysis guide
- **Python Seaborn** - Data visualization with Seaborn
- **Data Analysis Expressions - DAX** - Power BI DAX formulas

### 🐍 **Python Programming**
- **All Python Cheat Sheet** - Comprehensive Python reference
- **Command Pandas** - Pandas library guide
- **NumPy Cheat Sheet** - NumPy operations reference
- **Text and Image ML Projects** - ML project examples

### 🗄️ **SQL & Databases**
- **SQL JOINS** - Understanding SQL joins
- **SQL Notes for Beginners** - SQL fundamentals

### 🤖 **Machine Learning & NLP**
- **Machine Learning Interview Questions** - Common ML interview Q&A
- **Deep Learning Interview Questions** - DL concepts and questions
- **Comprehensive NLP Questions and Answers** - NLP interview prep
- **End-to-End Analytics with Examples** - Complete analytics workflows

### 📈 **Statistics & Mathematics**
- **Statistics Notes** - Core statistical concepts
- **Data Science Roadmap 2025** - Learning path guide

### 💼 **Interview Preparation**
- **220+ Power BI Interview Questions** - Comprehensive Power BI prep
- **Data Science Interview Questions** - Common DS interview topics
- **Deep Learning Interview Questions** - DL interview preparation
- **Machine Learning Interview Questions** - ML concepts for interviews

---

## 🗂️ Datasets

Check out the **[Datasets folder](./Datasets/)** for a wide variety of practice datasets including:
- Business & Sales Data
- Customer Behavior Data
- Employee & HR Data
- Healthcare Data
- Entertainment & Media Data
- And much more!

Each dataset comes with detailed descriptions and use cases. Perfect for:
- EDA (Exploratory Data Analysis)
- Machine Learning Projects
- Data Visualization Practice
- SQL Query Practice
- Portfolio Building

---

## 🎯 How to Use This Repository

### For Beginners:
1. Start with **SQL Notes for Beginners**
2. Learn Python basics from **All Python Cheat Sheet**
3. Practice with **Datasets** folder
4. Follow the **Data Science Roadmap 2025**

### For Intermediate Learners:
1. Dive into **Data Analysis with Python**
2. Master **Pandas** and **NumPy**
3. Learn visualization with **Seaborn** and **Power BI**
4. Work on projects from **Text and Image ML Projects**

### For Interview Preparation:
1. Review all **Interview Questions** PDFs
2. Practice with **Datasets**
3. Build projects for your portfolio
4. Study **End-to-End Analytics** examples

---

## 🛠️ Recommended Tools

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **IDEs**: Jupyter Notebook, VS Code, Google Colab
- **Visualization**: Power BI, Tableau, Matplotlib, Seaborn
- **Databases**: MySQL, PostgreSQL, SQLite
- **Version Control**: Git, GitHub

---

## 📖 Learning Path

```mermaid
graph TD
    Start["🎯 Start Your Data Science Journey"] --> Foundation
    
    Foundation["📚 Foundation Phase (1-2 months)"] --> SQL["🗄️ SQL Basics"]
    Foundation --> Math["📊 Statistics & Math"]
    Foundation --> Excel["📈 Excel/Power Query"]
    
    SQL --> Python
    Math --> Python
    Excel --> Python
    
    Python["🐍 Python Programming (2-3 months)"] --> Libraries
    
    Libraries["📦 Core Libraries"] --> Pandas["Pandas - Data Manipulation"]
    Libraries --> NumPy["NumPy - Numerical Computing"]
    Libraries --> Matplotlib["Matplotlib/Seaborn - Visualization"]
    
    Pandas --> DataAnalysis
    NumPy --> DataAnalysis
    Matplotlib --> DataAnalysis
    
    DataAnalysis["📊 Data Analysis & EDA (2 months)"] --> Cleaning["Data Cleaning"]
    DataAnalysis --> Exploration["Exploratory Analysis"]
    DataAnalysis --> Viz["Data Visualization"]
    
    Cleaning --> ML
    Exploration --> ML
    Viz --> BI
    
    BI["📈 Business Intelligence (1-2 months)"] --> PowerBI["Power BI"]
    BI --> Tableau["Tableau"]
    BI --> DAX["DAX Formulas"]
    
    PowerBI --> Advanced
    Tableau --> Advanced
    
    ML["🤖 Machine Learning (3-4 months)"] --> Supervised["Supervised Learning"]
    ML --> Unsupervised["Unsupervised Learning"]
    ML --> ScikitLearn["Scikit-learn"]
    
    Supervised --> Models["Linear/Logistic Regression<br/>Decision Trees<br/>Random Forest<br/>SVM"]
    Unsupervised --> Clustering["K-Means Clustering<br/>PCA<br/>Dimensionality Reduction"]
    
    Models --> Advanced
    Clustering --> Advanced
    ScikitLearn --> Advanced
    
    Advanced["🚀 Advanced Topics (2-3 months)"] --> DL["Deep Learning"]
    Advanced --> NLP["Natural Language Processing"]
    Advanced --> TimeSeries["Time Series Analysis"]
    
    DL --> DeepModels["Neural Networks<br/>CNN<br/>RNN/LSTM"]
    NLP --> NLPTools["NLTK<br/>SpaCy<br/>Transformers"]
    
    DeepModels --> Portfolio
    NLPTools --> Portfolio
    TimeSeries --> Portfolio
    DAX --> Portfolio
    
    Portfolio["💼 Portfolio Projects"] --> Project1["End-to-End ML Project"]
    Portfolio --> Project2["Dashboard/BI Project"]
    Portfolio --> Project3["NLP/Deep Learning Project"]
    
    Project1 --> Interview
    Project2 --> Interview
    Project3 --> Interview
    
    Interview["🎯 Interview Preparation"] --> Practice["Practice Datasets"]
    Interview --> MockInt["Mock Interviews"]
    Interview --> Resume["Resume Building"]
    
    Practice --> Job
    MockInt --> Job
    Resume --> Job
    
    Job["✨ Data Science Career!"]
    
    style Start fill:#4CAF50,stroke:#2E7D32,color:#fff
    style Foundation fill:#2196F3,stroke:#1565C0,color:#fff
    style Python fill:#FF9800,stroke:#E65100,color:#fff
    style DataAnalysis fill:#9C27B0,stroke:#6A1B9A,color:#fff
    style BI fill:#00BCD4,stroke:#00838F,color:#fff
    style ML fill:#F44336,stroke:#C62828,color:#fff
    style Advanced fill:#E91E63,stroke:#880E4F,color:#fff
    style Portfolio fill:#3F51B5,stroke:#1A237E,color:#fff
    style Interview fill:#FF5722,stroke:#BF360C,color:#fff
    style Job fill:#FFD700,stroke:#FFA000,color:#000
``````

---

## 🤝 Contributing

Feel free to:
- ⭐ Star this repository if you find it helpful
- 🐛 Report issues or broken links
- 📬 Suggest new resources or improvements
- 🔄 Fork and create pull requests

---

## 📫 Connect With Me

- **GitHub**: [@HarshChoudhary2003](https://github.com/HarshChoudhary2003)
- **Repository**: [Data-Science-Study-Resouces-](https://github.com/HarshChoudhary2003/Data-Science-Study-Resouces-)

---

## 📝 License

This repository is for educational purposes. All materials are collected from various free sources and are intended for learning and practice.

---

## 🔖 Quick Links

- [📂 Datasets Folder](./Datasets/)
- [📊 Power BI Resources](#data-analysis--visualization)
- [🐍 Python Resources](#python-programming)
- [💼 Interview Prep](#interview-preparation)
- [🗄️ SQL Resources](#sql--databases)

---

<div align="center">

### ⭐ If you find this repository helpful, please give it a star! ⭐

**Happy Learning! 🚀📊🤖**

*Last Updated: November 2025*

</div>
