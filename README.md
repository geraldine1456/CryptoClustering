# **CryptoClustering**

This challenge utilizes **K-Means clustering** to analyze cryptocurrency price trends over **24 hours** and **7 days**, effectively grouping assets based on similarities in their price movements.  **Principal Component Analysis (PCA)** is applied to reduce dimensions while preserving key data for clustering.

## **Key Libraries**  
- **pandas** – For data handling and manipulation  
- **hvplot.pandas** – For interactive visualizations 
- **sklearn** – For clustering, dimensionality reduction (PCA), and data normalization  

## **Steps Performed**  
1. **Data Preprocessing:** Normalize price change data for better clustering.  
2. **K-Means Clustering:** Group cryptocurrencies based on price movement.  
3. **PCA Dimensionality Reduction:** Reduce features while keeping key trends.  
4. **Cluster Comparison:** Visualize clusters **before and after PCA**.  

## **Usage**  
### **Clone the GitHub Repository**  
```bash
git clone https://github.com/geraldine1456/CryptoClustering.git
```  
### **Install Dependencies**  
```bash
pip install pandas hvplot scikit-learn
``` 

## **References**  
- **StandardScaler Documentation**: (https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)  
- **Elbow Method Guide**: (https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/)  
- **PCA Explained Guide**: (https://www.geeksforgeeks.org/principal-component-analysis-pca/)  
- **Composing Plots Documentation**: (https://holoviz.org/tutorial/Composing_Plots.html)  
- **Microsoft Copilot**: (https://www.microsoft.com/en-us/copilot)  