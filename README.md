# Student Performance Analysis

## Tech Stack
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  

## Problem
The objective of this project is to analyze student performance data and identify the key factors that influence academic outcomes. The goal is to understand which variables have the strongest impact on final grades and derive meaningful insights from real-world data.

## Approach
The dataset was explored using exploratory data analysis techniques. Data was first loaded and inspected for structure, types, and missing values. Since the dataset was clean, analysis proceeded directly.

Statistical summaries and correlation analysis were performed to identify relationships between variables. Visualizations such as histograms, scatter plots, and box plots were used to analyze distributions and compare different factors affecting student performance.

## Insights
Student performance is centered around average scores, with limited failures and a smaller group of high achievers.

Academic consistency (G1, G2) is the strongest predictor of final performance, while past failures and lifestyle factors like alcohol consumption negatively impact student outcomes. Study time and parental education contribute positively but moderately.

Study time shows a positive but weak-to-moderate relationship with final grades. While higher study time tends to correlate with better performance, the spread of data suggests that other factors also significantly influence student outcomes.

Past academic failures have a strong negative impact on student performance. Students with zero prior failures consistently achieve higher final grades, while an increase in failure count significantly lowers performance, indicating that academic consistency plays a critical role in success.

Female students demonstrate a slight overall performance advantage compared to male students. The median final grade for females is higher (~12 vs ~11), and the upper quartile also indicates stronger performance among top female students. While male students show a few high-performing outliers, the overall distribution suggests that female students maintain more consistent and slightly higher academic outcomes.

Internet access shows a slight positive correlation with student performance. Students with internet access have a marginally higher median final grade and a higher upper performance range. However, the significant overlap between the two groups indicates that internet access alone is not a decisive factor. This suggests that while access to resources may provide an advantage, other factors such as study habits, consistency, and prior academic performance play a more critical role.

## Model
This project currently focuses on exploratory data analysis and does not include a predictive machine learning model. However, the dataset and insights provide a strong foundation for building regression or classification models in future work.

## Results
The analysis successfully identified key factors influencing student performance. Academic consistency and past failures were found to be the most impactful variables. Visual analysis validated relationships between study time, gender, internet access, and final grades.

## Future Improvements & Features
Implement machine learning models to predict student performance  
Perform feature engineering for better predictive accuracy  
Deploy a simple web interface for interactive analysis  
Expand dataset for broader generalization  
Add automated reporting and dashboards  

## Dataset Attribution
Dataset sourced from Kaggle:
https://www.kaggle.com/datasets/larsen0966/student-performance-data-set?resource=download

## License
This project is licensed under the MIT License.

## Usage Note
This project is open-source under the MIT License. Proper credit must be given to the original author, Mayank Raj (devempowerjs), for any use, distribution, or modification of this work.
