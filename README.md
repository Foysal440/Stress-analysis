## Stress-analysis
#Project Overview
This project aims to analyze factors contributing to student stress, using a comprehensive dataset on student life and well-being. The analysis covers various aspects such as psychological, physiological, environmental, academic, and social factors. By exploring these dimensions, we seek to uncover patterns and insights that can help in understanding and potentially mitigating student stress.

#Dataset
The dataset, StressLevelDataset.csv, includes a range of variables related to student life, categorized into different factors:
Psychological Factors: anxiety level, self-esteem, mental health history, depression.
Physiological Factors: headache, blood pressure, sleep quality, breathing problems.
Environmental Factors: noise level, living conditions, safety, basic needs.
Academic Factors: academic performance, study load, teacher-student relationship, future career concerns.
Social Factors: social support, peer pressure, extracurricular activities, bullying.

#Key Features
Correlation Analysis: Examines relationships between different stress-related factors.
Feature Importance: Identifies which specific features within each factor category have the most significant impact on student stress levels using a Random Forest model.
Visualizations: Includes scatter plots, KDE plots, histograms, correlation heatmaps, and box plots to provide insightful visual interpretations of the data.

#Requirements
To run this project, you will need Python along with the following libraries:
NumPy
Pandas
Matplotlib
Seaborn
scikit-learn

#Usage
To analyze the dataset, follow these steps:
Clone this repository.
Ensure you have the necessary Python packages installed.
Run the Jupyter Notebooks in the following order:
Stress_Analysis.ipynb: Main analysis notebook with all statistical tests, models, and visualizations.

#Findings
Psychological factors such as anxiety and depression are strongly correlated with academic performance.
Physiological issues like poor sleep quality are linked with higher levels of depression.
Social factors including bullying have a profound impact on students' mental health history.

#Contributing
Feel free to fork this repository and submit pull requests to contribute to this analysis. You can also open issues to discuss potential changes or enhancements.
