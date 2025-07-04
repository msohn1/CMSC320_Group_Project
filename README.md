# The Impact of Various Factors in Student's Lives on Academic Performance 
## Fall 2024 Data Science Project
### Names: Briana Duffy, Minjae Sohn, Mirza Kir, Yonatan Tussa

Contributions:<br>

A: Project idea - Briana, Minjae, Mirza, Yonatan<br>
B: Dataset Curation and Preprocessing - Minjae<br>
C: Data Exploration and Summary Statistics - Briana, Minjae, Mirza<br>
D: ML Algorithm Design/Development - TBA<br>
E: ML Algorithm Training and Test Data Analysis - TBA<br>
F: Visualization, Result Analysis, Conclusion - TBA<br>
G: Final Tutorial Report Creation - Yonatan<br>
H: Additional (not listed above)<br>

## Introduction
This project investigates the relationship between students' social behaviors (number of friends, hours spent on social media, extracurricular involvment, etc.) and their academic performance.
We ask:<br>

• Do extroverts tend to perform better in school?<br>
• Is social media or Netflix use associated with worse academic performance?<br>
• Are there relationships between social behavior and GPA/test scores?<br>

Answering these questions and understanding any connections can help guide student wellness, outreach programs, and advising.<br>

## Data Curation
• [Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)<br>
• [Student Habits vs. Academic Performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)<br>
• [Pschosocial Dimensions of Student Life](https://www.kaggle.com/datasets/mdismielhossenabir/psychosocial-dimensions-of-student-life)<br>

_Data transformation for analysis here (database setup and use SQL to query for data, or organize a pandas DataFrame)_<br>

## Exploratory Data Analysis
_See checkpoint2.py_<br>
Key steps:<br>
• Computed conditional probabilities using Bayes' Theorem<br>
• Investigated Spearman correlations between friend count and GPA<br>
• Conducted hypothesis testing for associates between media use and exam performance<br>

While there is a mild positive associate between social connectivity and performance, most performance variation is explained by other factors.<br>

## Primary Analysis
We framed the problem as a classification task. Can we predict whether a student performs well (e.g., good/excellent) or poorly based on their social metrics?<br>

Approach:<br>
• Binary classification using Logistic Regression<br>
• Input features: Number of friends, social hours, media use, extracurricular involvement<br>
• Evaluated using accuracy precision, recall<br>

_Model details here_

## Visualization (Plots)

## Insights and Conclusion
