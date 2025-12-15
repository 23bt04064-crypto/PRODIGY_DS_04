# PRODIGY_DS_04

# Prodigy InfoTech Data Science Internship Task 4:
<br><img width="1241" height="632" alt="task 4" src="https://github.com/user-attachments/assets/9bbc36c5-cd01-4887-af7b-b294c0b17a29" />

The primary objective of Prodigy InfoTech Data Science Internship Task 4 was to perform customer segmentation using the K-Means clustering algorithm on the provided customer dataset. The goal was to identify distinct groups of customers based on their shopping behavior (specifically 'Annual Income' and 'Spending Score') to enable targeted marketing strategies. A key preliminary step involved using the Elbow Method to determine the optimal number of clusters ($K$).

## Dataset

The dataset used for this task is 
<a href="https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis">
Twitter Sentiment Analysis
</a>.
 

## Tools and Libraries used

- Kaggle notebook
- Pandas
- Numpy
- Matplotlip & Seaborn for visualization



## Methodology

The methodology involved several steps to prepare the data and apply the K-Means algorithm effectively. First, the relevant features ('Annual Income' and 'Spending Score') were selected. The crucial step of finding the optimal $K$ was executed using the Elbow Method , which plots the Within-Cluster Sum of Squares (WCSS) against the number of clusters. This analysis suggested $K=5$ was the most suitable number of clusters. K-Means clustering was then applied with $K=5$, and the resulting clusters were visualized using a scatter plot  to clearly illustrate the five distinct customer segments identified in the feature space.


## Conclusion

Task 4 successfully performed customer segmentation, identifying five distinct customer groups based on income and spending habits. The visualization clearly shows segments such as: 'Careful' (Low Income, Low Spend), 'Standard' (Mid Income, Mid Spend), 'Target' (High Income, High Spend), 'Spendthrifts' (Low Income, High Spend), and 'Conservatives' (High Income, Low Spend). This segmentation provides a highly actionable framework for the marketing team, allowing them to tailor products, promotions, and communication strategies to the specific needs and value of each identified customer cluster, thereby optimizing marketing efficiency and ROI.

Thank you for reviewing my submission!

## 📬 Contact

For any inquiries or feedback regarding this project, please contact:
- Email: 23bt04064@gsfcuniversity.ac.in
