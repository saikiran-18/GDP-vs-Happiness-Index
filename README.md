# GDP-vs-Happiness-Index

### **Project Overview**

This project performs an in-depth exploratory data analysis (EDA) of the World Happiness Report data from 2017 to 2020. The primary goal is to uncover key relationships, trends, and patterns that influence a country's happiness score, with a particular focus on the relationship between GDP and happiness.

### **Key Findings**

  * **Strong Correlations**: A country's happiness score is highly correlated with its **GDP per capita**, **social support**, and **healthy life expectancy**.
  * **Time-Series Stability**: The average global happiness score remained **relatively stable** between 2017 and 2020.
  * **Economic Impact**: A clear relationship was found between economic prosperity and happiness, with countries in the highest **GDP** bracket consistently having the highest average happiness scores.

### **Dataset**

The analysis is based on the **`happiness_all_years_cleaned.csv`** dataset, which combines data from the World Happiness Reports from 2017 to 2020. The dataset includes various factors such as GDP, social support, life expectancy, freedom, and perceptions of corruption.

### **How to Run the Code**

This project is structured for a **Jupyter Notebook** or **Google Colab** environment. The code is organized into three distinct sections that can be run sequentially in separate cells.

1.  **Data Cleaning**: This section loads the raw data, renames columns, and handles missing values to prepare the dataset for analysis.
2.  **Initial EDA & Visualization**: This part generates a correlation heatmap and histograms to visualize the relationships and distributions of key variables.
3.  **Advanced Analysis**: This section performs K-Means clustering, PCA, and economic stratification to segment countries and further explore the data.

### **Required Libraries**

To run the analysis, you will need the following Python libraries. You can install them using `pip`:

```bash
pip install pandas scikit-learn seaborn matplotlib
```
### **Interactive Plots** 
<img width="1100" height="525" alt="newplot" src="https://github.com/user-attachments/assets/aa8b4cc4-bfce-4712-a0bc-8903dd38e36b" />

<img width="1112" height="525" alt="newplot (1)" src="https://github.com/user-attachments/assets/60b05b39-1918-4e93-b98b-0ae0282a1804" />
