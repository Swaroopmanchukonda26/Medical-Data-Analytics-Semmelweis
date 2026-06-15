Historical Medical Data Analytics: The Semmelweis Handwashing Effect

A historical and statistical data analytics project reconstructing the clinical discoveries of Dr. Ignaz Semmelweis at the Vienna General Hospital (1841–1849) to prove the impact of antiseptic interventions using Python, Seaborn, and SciPy.

## 🚀 Key Architectural Discoveries
* **The Clinical Disparity:** Initial demographic grouping reveals a massive variance between maternity wards; Clinic 1 (staffed by doctors performing autopsies) had an average maternal mortality rate of **9.92%**, compared to **3.88%** in Clinic 2 (staffed by midwives).
* **The Cleanliness Shift:** Following the enforcement of mandatory chlorinated handwashing in June 1847, average monthly mortality plummeted from **10.53% down to 2.15%**—a massive 5x reduction in patient deaths.
* **Statistical Significance:** A two-sample independent t-test reveals a p-value of **0.0000002985**, meaning we reject the Null Hypothesis with over 99.999% confidence. The drop in deaths was mathematically caused by the handwashing intervention, completely eliminating random chance.

## 🛠️ Data Science Toolkit Used
* **Languages & Environments:** Python, Google Colab
* **Data Processing & Filtering:** Pandas (`.rolling()`, `.set_index()`), NumPy (`np.where()` conditional indexing arrays).
* **Distribution Shape Modeling:** Plotly Express Overlapping Histograms, Seaborn Kernel Density Estimates (`.kdeplot()`) utilizing localized physics boundary clipping.
* **Hypothesis Testing:** SciPy Stats Engine (`stats.ttest_ind`) evaluating variance and significance markers.
