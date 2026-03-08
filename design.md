# Design Document

## Project: Unnat Bhartiya Krishi (AI Farmer Assistant & Decision Support System)

### System Overview

Unnat Bhartiya Krishi is an AI-powered decision support system designed to assist farmers in making informed agricultural decisions.

The platform combines:
- Machine Learning
- Generative AI
- Retrieval-Augmented Generation (RAG)
- AWS Cloud Infrastructure

To provide intelligent recommendations and information related to:
- Crop selection
- Government agricultural schemes
- Agricultural best practices
- Market and farming insights

The system is designed specifically for rural farmers with low technical literacy, ensuring:
- Simple interfaces
- Multilingual communication
- Low-bandwidth accessibility

### Detailed Architecture
![Architecture Diagram](assets/Unnat%20Bhartiya%20Krishi%20-%20Architecture.png)

### System Components
The platform is composed of several intelligent components that work together to provide decision support for farmers.

- **Farmer Interaction Interface:** This provides the primary communication channel between farmers and the AI system. It allows farmers to interact with the assistant using a simple chat-based interface and access agricultural guidance in an easy-to-understand format.

- **Crop Recommendation System:** This analyzes agricultural conditions and uses machine learning models to suggest crops that are most suitable for cultivation in the farmer’s environment.

- **Government Scheme Assistance System:** This component helps farmers discover and understand government agricultural schemes, subsidies, and welfare programs. It simplifies complex policy documents and provides relevant scheme information to farmers.

- **Agricultural Knowledge Assistant:** This enables farmers to ask questions about farming practices, crop management, soil health, irrigation, and pest control. It uses AI to generate contextual responses based on trusted agricultural knowledge sources.

**Retrieval-Augmented Knowledge Engine:** This retrieves relevant information from agricultural documents, policies, and research publications. This retrieved knowledge is used to generate accurate and contextual responses to farmer queries.

**Market Price Intelligence System:** The Market Price Intelligence System provides insights into agricultural commodity prices and market trends. It helps farmers understand the market value of crops and make better selling decisions.

**Multilingual Language Processing System:** This component enables the platform to support multiple languages, allowing farmers to communicate with the system in their native language and receive responses in a familiar linguistic format.

**Voice Interaction System (Future):** The Voice Interaction System will allow farmers to communicate with the AI assistant through voice commands. It will convert spoken queries into text and provide spoken responses for easier accessibility.


### Machine Learning Pipeline

- **Model Training:**
    Multiple ML models are trained and evaluated. The models we worked upon are:
    - Random Forest
    - Decision Tree
    - Logistic Regression
    - Naive Bayes (Gaussian)
    - Support Vector Classifier

- **Model Selection:**
    Best-performing model is selected. Models are compared based on:
    - Accuracy
    - Cross-validation performance

- **Model Storage:**
Trained models are serialized using **Pickle** and stored in **Amazon S3**.

### Technology Stack
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