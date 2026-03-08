# 🌾 Unnat Bhartiya Krishi
## AI Farmer Assistant & Decision Support System

Unnat Bhartiya Krishi is an **AI-powered agricultural decision support platform** designed to assist farmers in making informed farming decisions using **Artificial Intelligence (AI)** and **Generative AI (GenAI)**.

The platform helps farmers with:
- 🌱 **Crop recommendations** based on soil and environmental conditions
- 📜 **Government scheme guidance** and farmer welfare information
- 📚 **Agricultural knowledge and best practices**
- 💬 **Natural language interaction in multiple languages**

The goal is to make **agricultural intelligence accessible to rural farmers**, especially those with limited technical knowledge and low-bandwidth internet access.

## 🚜 Problem Statement
Many farmers face challenges such as:

* Lack of awareness about **government agricultural schemes**
* Difficulty choosing the **right crop for soil and climate conditions**
* Limited access to **reliable agricultural knowledge**
* Language barriers in accessing digital agricultural resources

Unnat Bhartiya Krishi addresses these issues by providing a **simple AI-powered assistant** that delivers **personalized and reliable farming guidance**.


## 🎯 Key Features

### 🌾 Crop Recommendation System

Recommends the most suitable crops based on environmental conditions using machine learning models.

Factors considered:

* Soil nutrients (Nitrogen, Phosphorus, Potassium)
* Soil pH
* Temperature
* Rainfall
* Humidity


### 🤖 AI Knowledge Assistant (RAG)
Farmers can ask questions about:

- Government agricultural schemes
- Subsidies and financial support
- Farming techniques and practices
- Irrigation and crop management

The system uses **Retrieval-Augmented Generation (RAG)** to generate accurate responses from trusted documents.

Example queries:
* *What subsidy schemes are available for farmers?*
* *How can I apply for PM-KISAN?*
* *What crops grow best in high rainfall areas?*

### 🏛 Government Scheme Discovery
Provides simplified explanations of agricultural schemes such as:

* PM-KISAN
* Irrigation subsidy programs
* Agricultural development policies

This helps farmers **understand eligibility and benefits quickly**.


### 🌍 Multilingual Support
The platform supports communication in multiple languages to ensure accessibility for rural farmers.

- **Supported languages:**
    - Hindi
    - English

- **Future support:**
    - Punjabi
    - Bengali
    - Marathi
    - Tamil
    - Telugu
    - Gujarati

## 🏗 System Architecture
![Architecture Diagram](assets/Unnat%20Bhartiya%20Krishi%20-%20Architecture.png)


## 🧠 Technology Stack
The platform uses a combination of AI/ML technologies, cloud infrastructure, and web frameworks to build a scalable and intelligent agricultural decision support system.

- Frontend:
    - Streamlit
    - HTML / CSS
    - JavaScript

- Backend:
    - Python
    - Rest APIs

- Machine Learning
    - pandas
    - numpy
    - scikit-learn
    - pickle
    - matplotlib
    - seaborn

- Generative AI / RAG
    - Amazon Bedrock
    - Retrieval-Augmented Generation (RAG)
    - Prompt Engineering

- Cloud Infrastructure
    - Amazon Web Services
    - Amazon S3

- Language & Speech Services (Future)
    - Amazon Transcribe
    - Amazon Polly

- Data Sources
    - Government agricultural scheme documents
    - ICAR Research Documents
    - Budget and policy documents

- Development Tools
    - Git
    - GitHub
    - Jupyter Notebook
    - VSCode


## 📂 Project Structure

```
unnat-bhartiya-krishi/
│
├── assets/
│   ├── Unnat Bhartiya Krishi - Architecture.png
│
├── data/
│   ├── crop_recommendation.csv
│   └── documents/
│       ├── DfG_Analysis_2026-27-Agriculture.pdf
│       ├── doc2021112361.pdf
│       ├── doc2026217794101.pdf
│       ├── IITKA_Book_Traditional-Knowledge-in-Agriculture-English_0_0.pdf
│       ├── Inventory-of-Indigenous-Technical-Knowledge-in-Agriculture-Document-1.pdf
│       ├── Revised Operational Guidelines - PM-Kisan Scheme.pdf
│       └── Strengthening_IndiasAgriculturalBackbone_03022025.pdf
│
├── notebooks/
│   └── Crop Recommendation System.ipynb
│
├── pkl_objects/
│   ├── DecisionTree.pkl
│   ├── GaussianNB.pkl
│   ├── RandomForest.pkl
│   ├── SVC.pkl
│   └── LogisticRegression.pkl
│
├── design.md
├── LICENSE
├── README.md
└── requirements.md
```


## 📚 Knowledge Sources

The AI assistant uses trusted agricultural documents including:
- Government agricultural scheme guidelines
- Farmer welfare policies
- Agricultural research publications
- Traditional farming knowledge

References include documents from:
- Ministry of Agriculture & Farmers Welfare
- PRS Legislative Research
- ICAR (Indian Council of Agricultural Research)


## 🚀 Future Enhancements
The platform can be expanded with additional intelligent features such as:

* 🌦 Realtime Weather-based crop advisory
* 🐛 Pest and disease detection
* 📈 Market price forecasting
* 🎙 Voice-based AI assistant
* 📱 Mobile application
* 🌾 Fertilizer recommendation system


## 🌍 Impact
Unnat Bhartiya Krishi aims to:

* Improve **farmer decision making**
* Increase **agricultural productivity**
* Enhance **awareness of government schemes**
* Bridge the **digital divide in rural agriculture**

By combining **AI with agricultural knowledge**, the platform empowers farmers with **accessible and intelligent farming support**.


## 🤝 Contributors
Team Unnat Bhartiya Krishi (Developed by [Shrika Garg](https://github.com/shrikagarg1710) and [Ritwick Bhargav](https://github.com/ritwickbhargav80))


## 📜 License
This project is developed under the MIT License. See the [LICENSE](LICENSE) file for details.