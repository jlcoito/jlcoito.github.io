# Data Scientist

#### Technical Skills: Python, SQL, Microsoft Fabric, Microsoft PowerBI 

### Education
- Post-graduation, Data Science | UniversidadeAtlântica (_May 2021_)
- PhD, Biology | Instituto Superior de Agronomia, Universidade de Lisboa (_January 2018_)
- MSc, Cellular, Biology & Biotechnology | Faculdade de Ciências, Universidade de Lisboa (_December 2009_)
- BSc, Biology | Faculdade de Ciências, Universidade de Lisboa (_June 2007_)


### Work Experience
**Innovation Data Analyst @ Moonbeam.ai (_December 2022 - Present_)**

Seattle, WA, USA
- Developed and managed business intelligence reports to connect startups, investors, and government agencies, highlighting opportunities across diverse sectors, including AgTech, VR, Telecom, AI, and CleanTech.
- Built and maintained databases, ensuring up-to-date information on startups, investments, government funding, patents, and clinical trials. Designed and implemented a Python pipeline integrated with Microsoft Fabric to streamline data workflows.
- Refreshing dashboards on startups ecosystems and companies conducting clinical trials. Respond in a timely fashion to ad-hoc requests on technology sectors, startups maturity, geography and investors type, deals, and portfolios.
- Led data gathering, ingestion, and quality assurance processes, ensuring data accuracy and reliability. Developed dashboards for visualizing key insights, directly supporting data-driven decision-making.


**PostDoc Researcher @ Instituto Superior de Agronomia (_May 2019 - December 2022_)** 

Lisbon, Portugal
- Designed experimental frameworks and conducted data analysis, including statistical validation, to advance research in cellular and developmental biology.
- Conducted research in grapevine cluster development and possible genetic markers to identify loose clusters versus compact clusters in order to improve plant selections.
- Served as an invited lecturer and mentor, guiding students in their research projects and ensuring their understanding of complex biological data.


**Fellowship Researcher @ Instituto Superior de Agronomia (_April 2010 - April 2019)** 

Lisbon, Portugal
- Participated in a project to access the level of symbiosis between grapevines and mycorrhiza through evaluation of physiological parameters and mRNA levels.
- Developed genetic markers to identified male and female grapevine plants in order to aid plant breeding and plant improvement efforts.
- Participated in projects that developed a microarray to access environmental stress (drought and heat) in grapevines) developed reference genes to be used in qPCR on abiotic stresses studies in grapevine.
- Managed greenhouse and vineyard environments, ensuring optimal experimental conditions and reliable data collection.


### Data Science Projects

**Bank Lending Project**

![image alt](https://github.com/jlcoito/jlcoito.github.io/blob/2595022709a9e37bf5618798b84500220ce83a83/assets/img/dataset-cover.jpg)

This project is based on the Kaggle [Default of Credit Card Clients dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset?select=UCI_Credit_Card.csv) and focuses on helping a bank minimize losses due to bad lending practices. The bank incurs high costs when customers fail to pay on time, and the goal is to develop a machine learning model that can accurately predict which customers are likely to default on their loans. The key costs are:

    €1,000 for misclassifying a paying customer as a non-payer.
    €3,000 for misclassifying a non-payer as a paying customer.

As a base line for the project the cost to the bank was calculated as if the bank would consider all gustomers good paying customers with the formula:
$$totalCost = 1000∗FP+3000∗FN$$. If the bank considers all clients as good payers, it will incur a cost of €3.939.000

Models Used: Three models were tested: SVM, Random Forest, and XGBoost. Among these, XGBoost performed the best, achieving an accuracy of 0.82.
Using XGBoost, the bank's costs could be reduced to €2,415,000, a significant drop from the €3,939,000 the bank would incur if it treated all customers as good payers. Additionally, if the bank considered all customers as bad payers, the cost would rise to €4,687,000.

Disaster Tweet Analysis (under constructions)

Dog Vision (under construction)
