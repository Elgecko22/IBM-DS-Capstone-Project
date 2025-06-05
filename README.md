# IBM-DS-Capstone-Project
# SpaceX Falcon 9 Landing Prediction

**Predicting the success of Falcon 9 first-stage landings using historical SpaceX launch data.**

This project combines web scraping, API access, data wrangling, and machine learning to deliver actionable insights into SpaceX’s reusability strategy. It was built as part of the IBM Data Science Capstone, leveraging real-world datasets and end-to-end deployment practices.

## Problem Statement

The goal is to predict whether the **first stage of a Falcon 9 rocket will successfully land** after launch—a critical step in making space travel cost-effective. Accurate predictions support mission planning and cost estimation.

---

## Tools & Technologies

- **Python** (pandas, numpy, sklearn, plotly, seaborn)
- **API Integration**: SpaceX REST API, Wikipedia scraping via `BeautifulSoup`
- **Machine Learning**: Logistic Regression, Decision Trees, SVM, KNN, Random Forest, GridSearchCV
- **Jupyter Notebooks** for EDA, modeling, and visualization
- **Plotly Dash** for live interactive analytics

## Key Metrics
- **Best Model Accuracy:** 92% (Random Forest with GridSearchCV)
- **Feature Importance:** Launch site, booster version, payload mass, and orbit type had the greatest predictive power.
- **Precision & Recall:** Balanced across landing success and failure, making the model reliable in real use cases.

## Data Sources
- **SpaceX API:**
- **Wikipedia Web Scraping with BeautifulSoup**

## Machine Learning Models
| Model |	Accuracy | Notes |
|-------|-------|-------|
| Logistic Regression |	~84% | Fast, interpretable baseline |
| Decision Tree	| ~86% | Easy to visualize
| KNN	| ~82% | Sensitive to feature scaling |
| SVM |	~85% | Works well with smaller data |
| Random Forest (GS) | 92% | Most robust and generalizable |


## Why This Project Matters?
- **Quantifiable Skills:** End-to-end data pipeline from scraping to model deployment
- **Business Impact:** Helps SpaceX improve launch cost estimations and mission reliability
- **Real-World Relevance:** Based on actual SpaceX mission data

## Key Takeaways
- Built predictive models on real aerospace data with 90%+ accuracy
- Cleaned and transformed unstructured data from web APIs and HTML tables
- Tuned models using GridSearchCV for performance and interpretability
- Developed insights using visual analytics for business-facing insights

** Author
**Anthony Partida**  
Cal Poly, San Luis Obispo | Business Admin, Information Systems  
Passionate about data analytics and science
[Email](mailto:your.anthonypartida410@yahoo.com) | 🌐 [LinkedIn](www.linkedin.com/in/anthony-partida)

Project Completion Date (6/1/25)

