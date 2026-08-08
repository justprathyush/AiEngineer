# AI Engineer Bootcamp

> A hands-on portfolio documenting my journey to become an AI Engineer through real-world projects and labs.  


### 📖 Table of Contents

- [Introduction](#introduction)  
- [AI Engineer Roadmap](#ai-engineer-roadmap)  
- [Repository Structure](#repository-structure)  
- [Tech Stack](#tech-stack)  
- [Learning Roadmap](#learning-roadmap)  
- [Machine Learning Projects](#machine-learning-projects)  
- [Deep Learning](#deep-learning)  
- [Computer Vision](#computer-vision)  
- [Natural Language Processing](#natural-language-processing)  
- [Generative AI](#generative-ai)  
- [MLOps / Deployment](#mlops--deployment)  
- [4-Week Study Plan](#4-week-study-plan)  
- [Progress Tracker](#progress-tracker)  
- [Certifications](#certifications)  
- [License](#license)  

---

## 📖 Interview Questions 


<details>
<summary>Machine Learning</summary>
 
1. Python List vs Numpy Array
   **Python lists store mixed data types because they hold memory references (pointers) to objects, whereas NumPy arrays force a single data type because they store raw, unboxed data continuously in memory for fast mathematical processing.** [1, 2, 3]
  
3. indexing and slicing
4. Series vs DataFrame
5. Axis=0 vs Axis=1
6.  Classification vs Regression
7.  underfitting vs Overfitting
8.  Dealing Missing Values

</details>

<details>
<summary>Python</summary>

 1. Shallow copy vs Deep copy
 2. List comprehension

</details>

<details>
<summary>Stats</summary>

 1. Mean, Median & Mode

</details>

<details>
<summary>SQL</summary>

 1. 

</details>

<details>
<summary>DL</summary>

 1. Forward Proprotion vs Backward Propagation

    Forward propagation is when input data moves through the neural network to produce a prediction.

    Backpropagation is the process of sending the error backward through the network to calculate how the weights contributed to the error, so the weights can be updated and the model can improve.

</details>
 
---

## 📖 Learning

Below is a high-level study checklist. Check off items as you master them:

- **Python & Fundamentals**  
  - [x] Syntax, data types, control flow  
  - [ ] Functions, OOP, modules  
  - [ ] Advanced features (decorators, generators)  

- **Mathematics & Statistics**  
  - [ ] Linear algebra (matrices, eigenvectors)  
  - [ ] Calculus basics (derivatives)  
  - [ ] Probability & distributions (Normal, Bayes)  
  - [ ] Statistical tests (hypothesis testing)  

- **SQL & Databases**  
  - [ ] Basic queries (SELECT, JOIN)  
  - [ ] Advanced SQL (CTEs, Window functions)  
  - [ ] NoSQL fundamentals (MongoDB)  

- **Data Analysis**  
  - [ ] Data cleaning/EDA (pandas)  
  - [ ] Missing values, outlier handling  
  - [ ] Feature engineering & dimensionality reduction  

- **Machine Learning**  
  - [ ] Regression (linear, polynomial, regularized)  
  - [ ] Classification (logistic, trees, SVM, ensemble)  
  - [ ] Clustering (k-means, hierarchical)  
  - [ ] Model evaluation (cross-val, ROC, confusion matrix)  

<details>
<summary>- #AI Associates</summary>

**Goal:** Predict used car prices using regression.  
**Key tasks:** EDA, data cleaning, feature engineering, model training (Linear, Random Forest, XGBoost), hyperparam tuning, comparison.  
**Checklist:**  
## AI Foundation

AI -> ML-> DL -> NLP -> GenAI-> AI agent -> Agentic AI

AI: Machine mimic the human intelligence -> Learn, think, underland,image, make decision
ML: A subset of AI -> where learn from data & learn the pattern.
    *Supervisied Learning
    *Unsuper

DL: A subset of ML that uses artificial neural network with many language
    *ANN: Basic type of neural network Work with both classification and regressions
            cannot work with images
            Input -> hidden -> Output Layer
                        |
                     tabular
                        |
                RSC problem
    *RNN: designed to work with sequestional data (speach text)()
    *CNN: work with image
    *Lstm(long short term memory): its upadated version for rnn
    *GRU(gated recuring unit): simplefied version lstm
    *Auto Encorder: 1. An Autoencoder is a neural network that learns to:
                    2. Compress the input into a smaller representation.
    *GAN: A GAN is a deep learning model that generates new data that looks like real data.
    *Transformer: The Transformer is the architecture behind modern Large Language Models (LLMs).
    
NLP: branch of computer to understand process & generate human language
Gen AI: A type of AI That create new content 
Ai Agents: 
    *Can use multiple tool
    *Can make decision
    *Can Execute Action
Agentic AI: 
    *Advance form of AI where multi AI agents can plan work,execute task  
    
</details>

- **Deep Learning**  
  - [ ] Neural networks (activation, backprop, optimizers)  
  - [ ] CNNs (image conv layers, pooling)  
  - [ ] RNNs/LSTM (sequence data)  
  - [ ] Transformers (self-attention, BERT, GPT)  

- **Computer Vision**  
  - [ ] Image classification workflows  
  - [ ] Object detection (YOLO, SSD)  
  - [ ] Image segmentation basics  
  - [ ] OCR (text extraction)  

- **Natural Language Processing**  
  - [ ] Text preprocessing (tokenize, stem, lemmatize)  
  - [ ] Embeddings (Word2Vec, BERT vectors)  
  - [ ] Sentiment analysis, NER, topic modeling  
  - [ ] Transformer-based NLP (fine-tuning GPT/BERT)  

- **Generative AI & LLMs**  
  - [ ] Prompt engineering techniques  
  - [ ] Building a RAG system (vectors + LLM)  
  - [ ] AI agents and multi-step chains (LangChain)  

- **MLOps & Deployment**  
  - [ ] Containerization (Docker images)  
  - [ ] API development (FastAPI/Flask)  
  - [ ] CI/CD pipelines (GitHub Actions)  
  - [ ] Experiment tracking (MLflow, DVC)  

This roadmap is dynamic – items will be checked off as projects are completed.

---

## 💻 Machine Learning Projects

Below are capstone project summaries. Click each to expand details:

<details>
<summary>🚗 **Auto Price Prediction**</summary>

**Goal:** Predict used car prices using regression.  
**Key tasks:** EDA, data cleaning, feature engineering, model training (Linear, Random Forest, XGBoost), hyperparam tuning, comparison.  
**Checklist:**  
- [x] Exploratory Data Analysis (stats, visualization)  
- [x] Handle missing values/outliers  
- [x] Create features (age, mileage, brand encoding)  
- [x] Train regression models & tune hyperparameters  
- [x] Evaluate models (RMSE, R²)  
- [x] Derive business insights (pricing factors)  

</details>

<details>
<summary>✈️ **Flight Price Prediction**</summary>

**Goal:** Predict airline ticket prices from flight metadata.  
**Key features:** Airline, source, destination, stops, date/time.  
**Checklist:**  
- [x] Date-time feature engineering (day, month, time)  
- [x] Encode categorical data (Airline, Location)  
- [x] Regression models (Linear, RF, XGBoost)  
- [ ] Fine-tune best model  
- [ ] Analyze price influencers  

</details>

<details>
<summary>🏦 **Home Loan Default Prediction**</summary>

**Goal:** Classify whether a customer will default on a loan.  
**Key tasks:** Data preprocessing, handling class imbalance, feature importance, model comparison.  
**Checklist:**  
- [x] Clean data and handle missing values  
- [x] Encode categorical variables (marital status, etc.)  
- [x] Address imbalance (SMOTE or weighted loss)  
- [x] Train classifiers (Logistic, RF, XGBoost)  
- [ ] Evaluate (ROC-AUC, precision/recall)  

</details>

<details>
<summary>🏥 **Hospital Stay Prediction**</summary>

**Goal:** Predict length of hospital stay from patient info.  
**Key tasks:** Feature selection, encoding, regression models, error analysis.  
**Checklist:**  
- [x] Data analysis (check skew, distributions)  
- [x] Encode categorical (disease type, gender)  
- [x] Train regressors (Linear, RF, Gradient Boosting)  
- [ ] Analyze high-error cases (medicine, severity)  

</details>

*More projects (deep learning, CV, NLP) are in progress or coming soon.* 

---

## 🧠 Deep Learning

*(In development)* Implementations of neural networks (ANNs, CNNs, RNNs). E.g.:

- Image classifiers using CNN (MNIST, CIFAR-10)  
- NLP with RNN/LSTM on text data  
- Transfer learning with pre-trained models  

Check back for completed notebooks and writeups.

---

## 👁 Computer Vision

*(In development)* Projects for visual tasks:

- Image classification (Cats vs Dogs, etc.)  
- Object detection (YOLOv5 on custom data)  
- Semantic segmentation (using U-Net)  
- OCR pipelines  

Future sections will include datasets, model code, and results.

---

## 💬 Natural Language Processing

*(In development)* Text-based projects:

- Spam detection, sentiment analysis (classic ML/NLP pipelines)  
- Transformers: fine-tune BERT/GPT for classification or QA  
- Named Entity Recognition demos  
- Prompt engineering exercises with OpenAI APIs  

Will include code and evaluation metrics once done.

---

## 🤖 Generative AI / LLMs

*(In development)* Emphasizing large language models and agents:

- Building a Retrieval-Augmented Chatbot (LLM + vector DB)  
- Multi-step agent with LangChain (tool use)  
- Fine-tuning a small GPT model on domain data  
- Vector database experiments (FAISS, ChromaDB, Pinecone)  

Planned demos and write-ups to follow.

---


## 🏆 Certifications

- IBM AI Engineering Professional Certificate  
- Google Data Analytics Certificate  
- Microsoft Azure AI Engineer Associate  
- DeepLearning.AI TensorFlow Developer  
- OpenAI Ambassador (community recognition)  

*(Add links or badge images if desired.)*

---
