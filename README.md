# Aiml-repo
This repository consists of practice notebooks about machine learning and my understanding about the core ml concepts.
## Why Machine Learning?

### From Rule-Based Logic to Learning Systems

In traditional programming, we define rules explicitly.

For example:
- If root1 > root2 → choose root2  
- If root2 > root3 → choose root3  

This type of logic works well when:
- The problem is clearly defined  
- The rules are simple and deterministic  

However, this approach fails when dealing with complex real-world problems.

---

### Limitation of Rule-Based Systems

Consider problems like:
- Identifying a **cat in an image**
- Detecting **human emotions like anger**
- Understanding natural language  

In such cases:
- Writing explicit rules becomes extremely difficult  
- The number of conditions becomes too large or undefined  

👉 This is where **Machine Learning** becomes essential.

Instead of writing rules, we:
- Provide data  
- Let the model learn patterns  

---

###  Evolution of Data and Systems

Over time, the way we store and process data has evolved:

#### 1.  Early Data Storage
- Stored in spreadsheets or CSV files  
- Simple and easy to manage  
- Limited scalability  

#### 2.  Structured Data (Relational Databases)
- Use of SQL databases  
- Data stored in tables (rows and columns)  
- Well-organized and structured  

#### 3.  Unstructured & Big Data
- NoSQL databases like MongoDB  
- Handles large-scale and unstructured data  
- Examples: images, text, videos  

#### 4.  Machine Learning Era
- Instead of just storing data, we **learn from it**  
- Systems can:
  - Recognize patterns  
  - Make predictions  
  - Improve over time  

---

###  Key Insight

> Traditional programming tells the computer *what to do*.  
> Machine Learning allows the computer to *learn what to do from data*.

---
<img width="500" height="200" alt="ml" src="https://github.com/user-attachments/assets/ddf57aee-8b64-4869-af2e-97d74853991f" />

##  Types of Machine Learning

Machine Learning can be broadly divided into three main categories:

- Supervised Learning  
- Unsupervised Learning  
- Reinforcement Learning  


<img width="500" height="200" alt="types_of_ml" src="https://github.com/user-attachments/assets/53ad54ab-d417-4aec-ab89-a1263360d000" />

###  1. Supervised Learning

In supervised learning:
- The model is trained using **input data along with correct output (labels)**  
- It learns the mapping between input → output  

####  Types of Supervised Learning

**1. Classification**
- Output is **categorical**
- Example: spam vs not spam, cat vs dog  
- Model learns from labeled examples  

**2. Regression**
- Output is **continuous (numerical values)**  
- Example:  
  - Predicting salary  
  - Hiring engineers based on features like:
    - age  
    - experience  

---

###  2. Unsupervised Learning

In unsupervised learning:
- No labeled output is provided  
- The model tries to find **hidden patterns in data**

####  Types:

**1. Clustering**
- Groups similar data points together  
- Example: customer segmentation  

**2. Association**
- Finds relationships between variables  
- Example: “People who buy X also buy Y”  

---

###  3. Reinforcement Learning

- Based on **trial and error learning**  
- Uses **real-time data and feedback**  
- The model improves by:
  - rewards ✅  
  - penalties ❌  

👉 Example:
- Game playing AI  
- Self-learning systems  

---

🤖 Common Machine Learning Models

Machine Learning algorithms are often referred to as **models**.

Some commonly used models include:
- Neural Networks  
- Decision Trees  
- Support Vector Machines (SVM)  
- K-Nearest Neighbors (KNN)  

---

##  Traditional Algorithms vs Machine Learning

###  Traditional Algorithms
- A fixed set of instructions  
- Explicitly programmed by humans  

👉 Example:
- Step-by-step recipe (like cooking instructions)

---

 Machine Learning Algorithms
- Given:
  - Input data  
  - Expected (ideal) output  
- The system **learns the rules automatically**

👉 Example:
- Instead of writing a recipe, the system learns how to cook by observing examples  

---

##  Key Insight

> Traditional programming = “Rules + Data → Output”  
> Machine Learning = “Data + Output → Rules”

## 📊 Data & Machine Learning Workflow

---
##  Types of Data

###  Structured Data
- Organized in rows and columns  
- Examples: CSV files, Excel, SQL databases  

###  Unstructured Data
- No fixed format  
- Examples: images, audio, text  

### Streaming Data
- Continuously changing data  
- Example: live data feeds  

---

##  Evaluation Metrics

### Classification:
- Accuracy  
- Precision  
- Recall  

### Regression:
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  

---

## Machine Learning Workflow

1. **Problem Definition**  
2. **Data Collection**  
3. **Evaluation Criteria**  
4. **Feature Selection**  
5. **Modelling**  
6. **Experimentation**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/cc2e10f1-68be-445c-befc-12b9293e6909" />


##  Basic Tools
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Scikit-learn  

##  Key Insight

> Machine Learning is not needed for every problem.

