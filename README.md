# 💊 Pharmacy Data Analytics & Drug Classification Projects

## 📌 This repository contains two interconnected pharmaceutical data projects:
- ✅ **Drug Classification Prediction Model using RXList data**
- ✅ **Netmeds Web Scraping & Analytics for medicine information**

---

## 🏥 1. Drug Classification Prediction

### 🔍 Overview
This project builds a machine learning model to predict drug classifications based on brand and generic names. The data was scraped from RXList, processed, and used to train a **Random Forest Classifier model achieving 86.91% accuracy**.

### ✨ Features
- 🏷 **Web scraping** of pharmaceutical drug information from RXList
- 🔄 **Data preprocessing and cleaning**
- 📊 **TF-IDF vectorization** for text feature extraction
- 🤖 **Random Forest Classifier** for drug class prediction
- 💾 **Model serialization** for future use

### 🛠 Technologies
- 🐍 **Python**
- 🌐 **BeautifulSoup & Requests** (web scraping)
- 📈 **scikit-learn** (machine learning)
- 🗂 **joblib** (model serialization)

### 🔬 Process
1. 📥 **Data Collection:** Scraping RXList website alphabetically (A-Z) for drug information
2. 🔍 **Data Extraction:** Gathering brand names, generic names, and drug classifications
3. 🛠 **Preprocessing:** Combining text features and vectorizing with TF-IDF
4. 🎯 **Model Training:** Implementing and training a Random Forest Classifier (80/20 train/test split)
5. 📊 **Evaluation:** Achieving **86.91%** classification accuracy
6. 💾 **Model Persistence:** Saving the model, vectorizer, and encoder for future predictions

### 🖼 Screenshots
![image](https://github.com/user-attachments/assets/fc9227ec-a2b5-4ffa-9a22-340b0d0f30f3)


---

## 💻 2. Netmeds Web Scraping & Analysis

### 🔍 Overview
This project involved extracting extensive medicine data from Netmeds online pharmacy, with **optimization techniques reducing execution time from 15+ hours to just a few hours**.

### ✨ Features
- 🏷 **Comprehensive medicine data extraction**
- 🚀 **Performance optimization through multithreading**
- 🔄 **Error handling and logging system**
- 💾 **Checkpoint system for data preservation**
- 📊 **SQL analysis and data visualization**

### 🛠 Technologies
- 🐍 **Python**
- 🌐 **Requests & BeautifulSoup** (web scraping)
- ⚡ **ThreadPoolExecutor** (parallel processing)
- 📊 **SQL** (data analysis)
- 📑 **Excel** (interactive dashboard creation)

### 🔬 Process
1. 🔍 **Category Discovery:** Extracting all medicine category links
2. 🔗 **Medicine Link Collection:** Gathering individual medicine URLs from each category
3. 📋 **Detailed Data Extraction:** Collecting metadata including:
   - 💊 **Tablet names**
   - 📜 **Prescription requirements (Rx status)**
   - 💰 **Pricing and discounts**
   - 🌍 **Country of origin**
   - 🏭 **Manufacturer information**
   - 🔬 **Detailed tablet information (dosage, composition)**

### 🚀 Performance Optimization
- ⚡ **Implementing multithreading** with thread locks
- 🛡 **Adding robust exception handling**
- 📝 **Creating a comprehensive logging system**
- 💾 **Implementing periodic data checkpoints**
- 🔄 **Utilizing asynchronous processing**

### 📊 Results
- ✅ Successfully scraped data for **27,000+ medicines**
- 🤖 Successfully built model for predicting medicine prices
- 🚀 Reduced execution time by **more than 80%** through optimization
- 📊 Created **interactive Excel dashboards** using pivot tables
- 🔎 Performed **SQL analysis with visualization**

### 🖼 Screenshots
 ![image](https://github.com/user-attachments/assets/f7fa2fc4-a097-4918-8a6d-c8c43e8a98f1)

📸 **Figure 1:** Interactive dashboard showing medicine pricing analytics  
![image](https://github.com/user-attachments/assets/aa970b68-1eff-46ea-b2ba-fca21c25e574)

📸 **Figure 2:** SQL query results with visualization charts  
![image](https://github.com/user-attachments/assets/ff56b7c6-9cc6-4074-a610-60ec6e06707b)
![image](https://github.com/user-attachments/assets/64363c2e-e757-4623-9724-23476bf80931)

---




---

## 🔮 Future Work
🏷 Expanding the model to include additional drug features

🌐 Implementing a web interface for drug classification predictions

📈 Enhancing the scraping system to track price changes over time

🏥 Creating a unified database of pharmaceutical information

🚀 Improving the model performance so that it can be implemented in real time

---

## 📩 Contact Information
### 🤝 Connect With Me
📧 **Email:** sanjaydalawai108@gmail.com
🔗 **LinkedIn:** https://www.linkedin.com/in/sanjay-dalawai-460a20216/

Feel free to reach out for **collaborations, questions, or feedback** on these projects! 🚀

