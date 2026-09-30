## 📊 Key Findings

### 1. Most Common Drug for High BP Patients
* **DrugY** is the most frequent medication prescribed to patients with **HIGH** blood pressure, appearing **29 times** in the dataset.
* **DrugA** (23 times) and **drugB** (20 times) are also commonly prescribed for high blood pressure conditions.


### 2. Average Age per Drug Group
* **Drug B** has the highest average patient age at **61.0 years**.
* **Drug A** has the lowest average patient age at **35.7 years**.
* The remaining drugs (Drug C, Drug X, and Drug Y) cluster cleanly in the **40 to 45 year** age bracket.
  
![Average Age per Drug Chart](images/avg_age_per_drug.png)

### 3. Na_to_K Ratio is a Defining Threshold
* The distribution curve reveals that the **Sodium-to-Potassium (Na_to_K) ratio** is the single most critical factor for **Drug Y**.
* Every single patient with an `Na_to_K` ratio **greater than 15.0** is strictly prescribed **Drug Y**, regardless of age, sex, or blood pressure levels.

![Na_to_K Distribution Chart](images/na_to_k_distribution.png)
