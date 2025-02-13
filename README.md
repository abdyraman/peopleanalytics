Cleaning Data
•	The dataset consists of 100 rows and 23 columns, including 3 text-based features and 20 numeric features.
•	There is one row with two missing values in the dataset, under ID 79, where the cells for 'Level' and 'Tenure' are empty.
•	I corrected the typo in the value name 'Individual Contrbutor,' changing it to 'Individual Contributor in the "Level" column. Additionally, I resolved the inconsistency in the spelling in the "Tenure" column where '5-10 years' appeared in two variations. Both cases have been unified to ensure consistent spelling.
Descriptive Analysis
I combined two datasets in the "ID" column. The responses show that 53% of staff are based in Canada, 24% in the USA and 23% in Europe. Regarding tenure, 35% of staff were with OMERS for less than a year, 23% each for 1-5 and 5-10 years, and 18% have been with OMERS for more than 10 years. In terms of roles,  53% of staff are individual contributors, 23% are managers, 14% are directors, and 10% hold VP or higher positions.
Statistical analysis
The engagement index 50% of the values (the median) fall within the interquartile range (25% to 75%) of 3.15 to 4.05. The median (50%) value of the engagement index is 3.6.
The engagement index is calculated as the mean of five variables. Three of these variables show a right-skewed distribution, with 50% of respondents giving high ratings of 4 or 5. These variables are:
•	'I am proud to work for this company.'
•	'I rarely think about looking for a new job with another company.'
•	'I would recommend this company to people I know as a great place to work.'
The remaining two variables follow a normal distribution:
•	'My work gives me a feeling of personal accomplishment.'
•	'This company motivates me to contribute more than is normally required to complete my work.'
The remaining 14 variables pertain to employee experience. A notable concern is the variable "There is open and honest communication at this company." Both the mean (2.710) and median (3.0) values are relatively low, suggesting that many respondents have a negative perception of communication within the company.

In contrast, some variables receive higher ratings, indicating positive evaluations from respondents. These include:
•	"I trust my manager"
•	"My manager supports my efforts to balance my work and personal life"
•	"My manager encourages collaboration on my team"
These higher scores reflect strong positive sentiments regarding managerial support and trust.
Other variables exhibit a normal distribution, indicating a balanced range of responses across these areas.
Machine Learning 
I used numerical analysis to gain deeper insights into the data. By applying the k-nearest neighbors algorithm and the elbow method, I determined that the dataset, which has 20 dimensions, can be effectively clustered into three distinct groups. Following this, I performed Principal Component Analysis (PCA) to identify the key features driving the clustering. The main features influencing the clusters are:
•	Component 1: The most important feature is "I rarely think about looking for a new job with another company."
•	Component 2: The most important feature is "I am proud to work for this company."
•	Component 3: The most important feature is "There is open and honest communication at this company."
Overall machine learning supports the findings of the statistical analysis.
Insights and recommendations
1.	Communication Issues: The low ratings for communication suggest that improving openness and transparency could be a critical focus for enhancing overall employee experience.
2.	Managerial Support: High ratings in managerial support and trust are positive indicators and suggest areas where the organization is performing well.
3.	Normal Distribution: Most other variables are normally distributed, indicating a balanced range of responses.
Addressing the communication concerns while maintaining the positive aspects of managerial support could lead to a more comprehensive improvement in employee experience.

![image](https://github.com/user-attachments/assets/73d1586b-6afc-4cf6-9f58-32c1d12f7497)
