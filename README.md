
# 🧾 SONAR Rock vs Mine Prediction with Python 

Detecting whether the object between the submarine is a Rock or a Mine using Python, numpy, pandas and other Python libraries.

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#workflow">Workflow</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#key-findings">Key Findings</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project collects the sona data from the laboratory, then processes the data and splits it into train and test data. After that the train and test data will be fed into a Logestic Regression Model. After getting the trained Logestic Regression Model, we will use the test or some new datas to predict the outcome.This problem is a binary classification model where we find whether the object is a rock or a mine. 

---
<h2><a class="anchor" id="workflow"></a>Workflow</h2>

![Vendor Performance Workflow](https://github.com/PriomHalder/Machine_Learning_Projects/blob/b7f03e47fb398a4375bbd31d9b2f93742f7ca7cb/SONAR%20Rock%20vs%20Mine%20Prediction%20with%20Python/workflow.png)

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- Sonar data CSV files located in `/data/` folder 
- Split into Train and Test data for model training

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Microsoft Excel
- Python (Pandas, numpy, sklearn.model_selection, sklearn.metrics)
- Git
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
project plan/
│
├── collecting sonar data
├── data pre-processing 
├── train test split
├── logistic regression model train and test
│
├── project implimentation/                  # Jupyter notebooks
│   ├── import the sonar_data.ipynb
│   ├── import all the Python libraries
    ├── detecting the shape and total rock and mine counts
    ├── finding the mean value for all the rocks and mine columns
    ├── separating data and labels for model training
    ├── splitting train and test data
    ├── train logistic regression model
    ├── model evaluation by accuracy test for both train and test data
    ├── making a predictive system and testing the model using the given data and new data
│
├── publish/                    # Python scripts for ingestion and processing
│   ├── creating a new GitHub repository
│   └── pushing the project's files using Git

```

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Total number of Rows and Columns:**
- Row number: 208
- Column number: 61

**Total number of Mines and Rocks**
- Mine number: 111
- Rock number: 97

---
<h2><a class="anchor" id="key-findings"></a>Key Findings</h2>

1. **Accuracy on training data:**:   83%
2. **Accuracy on test data**: 76%
   
---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Download both sonar_data csv and the IPython notebook file

2. Load the CSVs and ingest into the database:

3. Follow the project structure(project implimentation) above.

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Might not be accurate all the time. But the process will teach you about Python libraries and functions well.
- Try importing a new dataset for a test run. 

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Priom Halder**  
  
📧 Email: priomhalder1470@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/priomhalder/)  
