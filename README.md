# **Heart Disease UCI**

---

## *Context*
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

## *Content*

*Attribute Information:*

01. age
02. sex
03. chest pain type (4 values)
04. resting blood pressure
05. serum cholestoral in mg/dl  
06. fasting blood sugar > 120 mg/dl
07. resting electrocardiographic results (values 0,1,2)
08. maximum heart rate achieved
09. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. One file has been "processed", that one containing the Cleveland database. All four unprocessed files also exist in this directory.

To see Test Costs (donated by Peter Turney), please see the folder "Costs"

## *Acknowledgements*

*Creators:*

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor: David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

## *Inspiration*
Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).

See if you can find any other trends in heart data to predict certain cardiovascular events or find any clear indications of heart health.

## *Source*

All of the information above was provided by Kaggle, to see more content about this case visit https://www.kaggle.com/ronitf/heart-disease-uci

For more information about the dataset visit https://archive.ics.uci.edu/ml/datasets/Heart+Disease

---

This analysis was created by [Guilherme Mattos](https://www.linkedin.com/in/guilhermefmattos/)

To access the analysis and modeling please open [`heart_disease notebook`](./notebooks/heart_disease.ipynb) file inside the notebooks folder

--- 

## **Table of Contents**

- [Notebook Contents](#Notebook-Contents)
- [Main Analysis](#Main-Analysis)
- [Modeling Technique Selection](#Modeling-Technique-Selection)
- [Results Discussion](#Results-Discussion)
- [Extra Contents](#Extra-Contents)

### **Notebook Contents**

| Sections |
| ------- |
| [0. Libraries](./notebooks/heart_disease.ipynb/#0.-Libraries) |
| [1. Dataset](./notebooks/heart_disease.ipynb/#1.-Dataset) |
| [2. Exploratory Analysis](./notebooks/heart_disease.ipynb/#2.-Exploratory-Analysis) |
| [3. Feature Engineering](./notebooks/heart_disease.ipynb/#3.-Feature-Engineering) |
| [4. Modeling](./notebooks/heart_disease.ipynb/#4.-Modeling) |
| [5. Results](./notebooks/heart_disease.ipynb/#5.-Results) |

### **Main Analysis**

### **Modeling Technique Selection**

### **Results Discussion**

### **Extra Contents**