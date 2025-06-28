📊 Predicting Potential Prospect Customers — Netrality Data Centers
🧠 Problem Statement
Netrality Data Centers provided us with a business challenge:

Identify and acquire potential customers from a list of prospect companies using historical billing data.

We were given four datasets:

(i) All Time Billing

(ii) Last Month Billing

(iii) Current Customers

(iv) Prospect Customers

Our goal was to build a Machine Learning model to predict and recognize ideal potential customers from the prospect list, leveraging the billing histories of current and past clients.

🛠️ Approach
To solve this problem, we used a range of Applied Machine Learning techniques:

Exploratory Data Analysis (EDA) and visualization to understand data patterns

Feature Engineering to extract meaningful predictors

Tried Regression Models (for prediction) — though results were limited

Shifted to Unsupervised Learning — applied multiple Clustering Methods:

K-Means

Birch Clustering

Spectral Clustering

Key preprocessing steps included:

Handling missing/null values

Identifying useful features like Revenue, Estimated Budget, Funding Amount

Redefining the prediction target to avoid relying solely on billing totals

✅ Results & Conclusion
Successfully identified Potential Company IDs from the Prospect list using Clustering

Clustering helped expose relationships between existing customers and potential leads

Evaluation of cluster structures confirmed strong matches and business insights

👉 Clustering techniques proved more effective than traditional regression models for this problem.

🧰 Tech Stack & Tools Used
Python (Jupyter Notebook)

pandas, numpy

matplotlib, seaborn

scikit-learn (KMeans, Birch, Spectral Clustering)

Microsoft Word & PowerPoint for documentation and presentation

📁 Files in This Repository
prospectCustomers_bestModel.ipynb – Main Jupyter Notebook

Report on Predicting Potential Prospect Customers.docx – Detailed project report

The FLASH_Project Report Sprint_Final...docx – Supplementary documentation

*.csv files – Provided datasets

.pptx (optional) – Final project presentation

👤 Author
Pranay


