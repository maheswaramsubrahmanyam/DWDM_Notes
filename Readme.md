# DWDM 
## Module 1
## DATA MINING FUNCTIONALITIES
## CLASSIFICATION OF DATA MINING SYSTEMS

---

# KDD LINK -> 
https://www.tutorialspoint.com/data_mining/dm_knowledge_discovery.htm

## 1. DATA MINING FUNCTIONALITIES

### 1.1 Introduction

Data mining functionalities describe the **types of patterns, relationships, and knowledge** that can be extracted from large volumes of data. In simple terms, they explain **what data mining can do**. When organizations store massive amounts of data, the real value lies not in the data itself but in the meaningful knowledge hidden inside it. Data mining functionalities provide systematic ways to discover such hidden knowledge.

These functionalities are essential for decision making, prediction, analysis, and understanding complex data behavior across different application domains such as business, healthcare, education, banking, and telecommunications.



### 1.2 Concept Description

Concept description is a data mining functionality used to **summarize and describe the general characteristics of a class of data**. It provides a compact and meaningful representation of data.

There are two important forms of concept description:

**Characterization** describes the properties of a target class of data objects. For example, describing the general characteristics of students who score above 80% marks.

**Discrimination** compares the characteristics of one class with another class. For example, comparing high-performing students with low-performing students.

Concept description helps decision makers understand data at a higher level of abstraction instead of dealing with raw data.



### 1.3 Classification

Classification is one of the most important data mining functionalities. It is the process of **assigning data objects to predefined classes** based on a set of training data.

In classification, the system first learns from historical data where class labels are already known. This phase is called the **training phase**. After learning, the model is used to classify new, unseen data. This phase is called the **testing or prediction phase**.

Since the class labels are known in advance, classification is called a **supervised learning technique**.

For example, in a banking system, loan applicants can be classified as *safe* or *risky*. In email systems, messages are classified as *spam* or *not spam*.

#### Classification Flowchart

```
Training Data (with class labels)
              ↓
       Learning Algorithm
              ↓
       Classification Model
              ↓
 New Data → Class Prediction
```

Classification helps organizations automate decision-making processes and improve accuracy.



### 1.4 Prediction

Prediction is closely related to classification but differs in the type of output it produces. While classification predicts **categorical class labels**, prediction estimates **continuous or numeric values**.

Prediction is used when the goal is to forecast future outcomes based on existing data patterns.

For example, predicting the sales amount for the next month, predicting stock prices, or estimating student marks.

Prediction models are widely used in business planning, financial forecasting, and performance analysis.



### 1.5 Clustering

Clustering is the process of grouping data objects into **clusters such that objects within the same cluster are similar**, and objects in different clusters are dissimilar.

Unlike classification, clustering does not require predefined class labels. Therefore, it is known as an **unsupervised learning technique**.

Clustering is mainly used for exploratory data analysis, where the structure of data is not known in advance.

For example, customers can be grouped based on purchasing behavior, or students can be grouped based on learning patterns.

Clustering helps organizations identify hidden structures and patterns in data.



### 1.6 Association Rule Mining

Association rule mining discovers **interesting relationships or associations among data items**. It is commonly used to identify items that frequently occur together in transactional databases.

The most popular application of association rule mining is **market basket analysis**.

For example, if customers who buy bread also tend to buy butter, the association rule can be represented as:

```
Bread → Butter
```

Association rule mining helps businesses improve marketing strategies, product placement, and cross-selling.



### 1.7 Outlier Analysis

Outlier analysis identifies **data objects that do not follow the general pattern** of the dataset. These data objects are called outliers or anomalies.

Outliers may represent important but rare events, such as fraud, system failure, or abnormal behavior.

For example, detecting unusual credit card transactions or identifying network intrusions.

Outlier analysis plays a crucial role in security, fraud detection, and quality control systems.



### 1.8 Evolution and Trend Analysis

Evolution and trend analysis focuses on **changes in data over time**. It identifies trends, sequential patterns, and periodic behaviors.

This functionality is useful for understanding long-term behavior and predicting future changes.

For example, analyzing sales growth over years or tracking student performance across semesters.



### 1.9 Summary of Data Mining Functionalities

Data mining functionalities enable the extraction of descriptive, predictive, and behavioral knowledge from data. Together, they form the foundation of intelligent data analysis and decision support systems.



## 2. CLASSIFICATION OF DATA MINING SYSTEMS

### 2.1 Introduction

Data mining systems can be classified in several ways based on **the type of data mined, the kind of knowledge discovered, the techniques used, the application areas, and system architecture**. This classification helps in understanding the scope and capabilities of different data mining systems.


### 2.2 Classification Based on the Type of Data to be Mined

Data mining systems can be classified according to the nature of the data they handle. Some systems are designed to mine relational databases, while others focus on data warehouses, transactional databases, or advanced data types.

Examples include:

* Relational data mining systems
* Data warehouse mining systems
* Transactional data mining systems
* Spatial and temporal data mining systems
* Multimedia, text, and web data mining systems

Each type requires specialized techniques due to differences in data structure and complexity.



### 2.3 Classification Based on the Kind of Knowledge to be Mined

Data mining systems are also classified based on the type of knowledge they extract. Some systems focus on classification and prediction, while others specialize in clustering, association analysis, or outlier detection.

This classification directly corresponds to data mining functionalities and helps users select appropriate systems for their objectives.



### 2.4 Classification Based on Techniques Used

Different data mining systems use different analytical techniques to extract knowledge. These techniques include statistical methods, machine learning algorithms, decision trees, neural networks, genetic algorithms, and database-oriented approaches.

The choice of technique depends on the problem domain, data type, and required accuracy.



### 2.5 Classification Based on Application Areas

Some data mining systems are domain-specific and tailored for particular applications such as banking, healthcare, retail, education, bioinformatics, and telecommunications.

Application-oriented systems are optimized to handle domain-specific data and business rules.



### 2.6 Classification Based on System Architecture

From an architectural perspective, data mining systems can be classified as standalone systems or integrated systems.

Standalone systems work independently, whereas integrated systems are tightly coupled with databases or data warehouses. Modern data mining systems are usually integrated with data warehouses to improve performance and scalability.

#### Architecture Flow

```
Operational Databases
        ↓
   Data Warehouse
        ↓
   Data Mining System
        ↓
   Knowledge / Decisions
```



## 3. CONCLUSION

Data mining functionalities define what kinds of knowledge can be extracted from data, while the classification of data mining systems explains how different systems are organized and applied. Together, these concepts form the foundation of data mining and are essential for understanding advanced topics such as association analysis, classification models, and business intelligence systems.

---

Alright sir 👍
Below are **CLEAR, LARGE, EXAM-READY NOTES** on **Classification and Prediction** written in **simple language**, **step-by-step**, suitable for **teaching + student notes + exams**.
You can **directly dictate / share / convert to PDF**.

---


## 1️ CLASSIFICATION

### 1.1 Definition of Classification

**Classification is a supervised data mining technique that assigns data objects to predefined classes or categories based on historical data.**

In classification:

* The **classes are already known**
* The system is trained using **labeled data**
* New data is classified into one of the existing classes

---

### 1.2 Meaning in Simple Words

Classification means **grouping data into known categories** using past examples.

> If we already know the answers and use them to predict future answers → that is classification.

---

### 1.3 Why Classification is Needed

Classification is used to:

* Make **decisions**
* Reduce **manual effort**
* Improve **accuracy**
* Automate **business processes**

---

### 1.4 Characteristics of Classification

* Uses **training data**
* Output is **categorical**
* Based on **supervised learning**
* Produces **class labels**

---

### 1.5 Classification Process (Step-by-Step)

1. **Data Collection**
   Collect historical data with known class labels.

2. **Training Phase**
   A classification algorithm learns patterns from the data.

3. **Model Creation**
   A classification model is created.

4. **Testing Phase**
   New, unseen data is given to the model.

5. **Classification Output**
   The model assigns the data to a specific class.

---

### 1.6 Example of Classification (Student Result)

| Attendance | Study Hours | Result |
| ---------- | ----------- | ------ |
| High       | High        | Pass   |
| Low        | Low         | Fail   |
| Medium     | High        | Pass   |

If a new student has:

* Attendance = High
* Study Hours = Medium

 **Result = Pass**

---

### 1.7 Real-Life Applications of Classification

* Email filtering (Spam / Not Spam)
* Loan approval (Approved / Rejected)
* Medical diagnosis (Disease / No Disease)
* Student performance (Pass / Fail)
* Customer segmentation (Premium / Normal)

---

### 1.8 Classification Techniques (Concept Level)

* Decision Tree
* Naïve Bayes Classifier
* k-Nearest Neighbor (k-NN)
* Support Vector Machine (SVM)

*(Only names required for BBA level)*

---

### 1.9 Advantages of Classification

* Easy to understand
* Fast decision-making
* Widely used in business
* High accuracy with good data

---

### 1.10 Limitations of Classification

* Requires labeled data
* Accuracy depends on data quality
* Not suitable for unknown class discovery

---

## 2️ PREDICTION

---

### 2.1 Definition of Prediction

**Prediction is a data mining technique used to predict future or unknown numerical values based on historical data.**

Prediction focuses on **forecasting values** rather than assigning categories.

---

### 2.2 Meaning in Simple Words

Prediction means **estimating future values** using past data.

> If we want to know “how much” or “how many” → that is prediction.

---

### 2.3 Characteristics of Prediction

* Output is **numeric**
* Based on **historical data**
* Used for **forecasting**
* Continuous values

---

### 2.4 Prediction Process

1. Collect past numerical data
2. Identify relationships between variables
3. Build a prediction model
4. Apply the model to new data
5. Predict future values

---

### 2.5 Example of Prediction (Sales Forecast)

| Advertising Cost | Sales    |
| ---------------- | -------- |
| 10,000           | 1,00,000 |
| 20,000           | 2,00,000 |

If advertising cost = **15,000**
 Predicted sales = **1,50,000**

---

### 2.6 Real-Life Applications of Prediction

* Sales forecasting
* Stock market analysis
* Weather forecasting
* Demand prediction
* Salary estimation
* Exam score prediction

---

### 2.7 Prediction Techniques

* Linear Regression
* Multiple Regression
* Time Series Analysis

---

### 2.8 Advantages of Prediction

* Helps in planning
* Improves business decisions
* Reduces uncertainty
* Supports strategic management

---

### 2.9 Limitations of Prediction

* Depends on historical accuracy
* Cannot predict unexpected events
* Errors increase with poor data

---

## 3️ DIFFERENCE BETWEEN CLASSIFICATION AND PREDICTION

| Feature       | Classification  | Prediction    |
| ------------- | --------------- | ------------- |
| Output        | Category        | Numeric value |
| Type of value | Discrete        | Continuous    |
| Learning type | Supervised      | Supervised    |
| Example       | Pass / Fail     | Marks         |
| Business use  | Decision making | Forecasting   |

---

## 4️ KEY EXAM POINTS

* Classification → **categorical output**
* Prediction → **numerical output**
* Both use **supervised learning**
* Both rely on **historical data**

---



