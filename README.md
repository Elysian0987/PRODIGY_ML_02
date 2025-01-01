# PRODIGY_ML_02

# Task 02: K-Means Clustering for Customer Segmentation  

## Overview  
The goal of this task is to group customers into distinct clusters based on their **age**, **annual income**, and **spending score**. The project demonstrates the use of unsupervised learning techniques for customer segmentation.  

## Dataset  
The dataset used is from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python), which includes details such as customer ID, gender, age, annual income, and spending score.  

## Key Steps  
### 1. Data Preprocessing  
- Standardized features using `StandardScaler` for effective clustering.  
- Ensured data cleanliness and consistency.  

### 2. Model Implementation  
- Determined the optimal number of clusters using the Elbow Method.  
- Applied K-Means clustering with 5 clusters as the optimal choice.  

### 3. Visualization  
- Scatter plots were used to represent clusters visually based on annual income and spending score.  

### 4. Evaluation  
- Calculated the Silhouette Score (0.41) to evaluate the clustering performance.  

## Results  
- Customers were segmented into five distinct clusters, each representing unique purchasing behavior.  
- Visualizations provide insights into the characteristics of each customer group.  

## How to Use  
### 1. Clone this repository:  
```bash  
git clone https://github.com/Elysian0987/PRODIGY_ML_02.git  
cd PRODIGY_ML_02  
```  

### 2. Install dependencies:  
```bash  
pip install -r requirements.txt  
```  

### 3. Run the code:  
```bash  
python kmeans_clustering.py  
```  

## Tools and Libraries  
- **Python**  
- **Pandas**: For data handling and analysis.  
- **NumPy**: For numerical computations.  
- **Matplotlib & Seaborn**: For data visualization.  
- **Scikit-learn**: For scaling and clustering.  

## What I Learned  
- Practical use of clustering for customer segmentation.  
- Working with the Elbow Method and Silhouette Score.  
- Improving data preprocessing and visualization techniques.  

## References  
- Dataset: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- Documentation: [Scikit-learn Clustering](https://scikit-learn.org/stable/modules/clustering.html)  

Feel free to use and build upon this work. Contributions are welcome!  
