# Running Consumer Analysis Using Clustering

## Overview
This project focuses on using **unsupervised learning techniques**, specifically clustering, to analyze survey data collected from participants regarding their running habits. The insights derived are aimed at guiding a running footwear and apparel company in making strategic decisions about their product portfolio and marketing strategies.

---

## Objective
The primary objective of this project is to:
1. Identify key consumer segments using clustering techniques.
2. Provide actionable recommendations based on identified clusters to help the company personalize its approach to target customers effectively.

---

## Deliverables
- **Clustering Analysis:** An end-to-end clustering implementation with justifications for the techniques and metrics used.
- **Recommendations:** Actionable insights on product portfolio and marketing strategies tailored to identified consumer segments.
- **Annotated Notebook:** Detailed Python notebook documenting the process, including data preparation, clustering algorithm selection, and interpretation of results.

---

## Key Steps
### 1. Data Preparation
- The provided survey dataset was cleaned and formatted to ensure it was suitable for clustering analysis.
- Steps included handling missing values, encoding categorical data, and scaling features as required.

### 2. Similarity Metric and Matrix
- Justification for selecting the similarity metric was provided based on the nature of the data.
- The similarity matrix was computed to identify relationships between survey participants.

### 3. Clustering Algorithm
- Iterative experimentation with clustering algorithms (e.g., K-Means, DBSCAN, or Hierarchical Clustering) was performed.
- The optimal algorithm was selected based on cluster evaluation metrics such as silhouette score and elbow method.

### 4. Interpretation of Results
- Consumer clusters were identified and analyzed for patterns in running habits and preferences.
- Recommendations were made to help the company:
  - Personalize marketing strategies for each consumer cluster.
  - Adjust the product portfolio to better cater to the preferences of key consumer segments.

---

## Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, seaborn, matplotlib
- **Platform:** Google Colab
- **Visualization Tools:** Charts and graphs were generated for effective presentation of results.

---

## Results and Insights
1. **Key Clusters Identified:**
   - Clusters based on running frequency, product preferences, and health goals.
   - Differentiation between casual runners, fitness enthusiasts, and competitive athletes.
2. **Recommendations:**
   - **Product Portfolio:** Focus on lightweight and durable products for competitive athletes; versatile and affordable products for casual runners.
   - **Marketing Strategies:** Personalized campaigns targeting health-conscious individuals and social media campaigns for younger runners.

---

## Dataset
- **Source:** Survey data from a pool of participants provided by the course instructor.
- **Structure:** The dataset contains responses on running habits, product preferences, and demographic details.
- **Preprocessing Steps:**
  - Handled missing data.
  - Encoded categorical variables.
  - Normalized numeric variables.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the `Sandaveni_Shubhang_Yadav_Project2.ipynb` notebook in Google Colab or Jupyter Notebook.
4. Upload the provided dataset (`survey_data.xlsx`) to the notebook environment.
5. Run all the cells in the notebook sequentially to:
   - Clean and preprocess the data.
   - Perform clustering analysis.
   - Generate visualizations and insights.

---

## Future Enhancements
- Add more demographic and behavioral attributes to improve clustering precision.
- Test advanced clustering algorithms such as Spectral Clustering and Gaussian Mixture Models.
- Build a dashboard to visualize and interact with the clustering results.
- Automate the generation of tailored recommendations based on identified consumer clusters.

---

## Contributors
- **Your Name** - Shubhang yadav sandaveni

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.


