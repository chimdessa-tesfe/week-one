# week-one
User Overview analysis
provide answers for the folowing questions
For the actual telecom dataset, you‘re expected to conduct a full User Overview analysis & the following sub-tasks are your guidance: 
Start by identifying the top 10 handsets used by the customers.
Then, identify the top 3 handset manufacturers
Next, identify the top 5 handsets per top 3 handset manufacturer
Make a short interpretation and recommendation to marketing teams

In telecommunication, CDR or Call Detail Record is the voice channel and XDR is the data channel equivalent. So here, consider xDR as data sessions Detail Record. In xDR, user behavior can be tracked through the following applications:  Social Media, Google, Email, Youtube, Netflix, Gaming, Other . 
Task 1.1 - Your employer wants to have an overview of the users’ behavior on those applications.   
Aggregate per user the following information in the column  
number of xDR sessions
Session duration
the total download (DL) and upload (UL) data
the total data volume (in Bytes) during this session for each application

Task 1.2 - Conduct an exploratory data analysis on those data & communicate useful insights. Ensure that you identify and treat all missing values and outliers in the dataset by replacing by the mean of the corresponding column.
You’re expected to report about the following using  python script and slide  :
Describe all  relevant variables and associated data types (slide). 
Analyze the basic metrics (mean, median, etc) in the Dataset (explain) & their importance for the global objective.
Conduct a Non-Graphical Univariate Analysis by computing dispersion parameters for each quantitative variable and provide useful interpretation. 
Conduct a Graphical Univariate Analysis by identifying the most suitable plotting options for each variable and interpret your findings.
Bivariate Analysis – explore the relationship between each application & the total DL+UL data using appropriate methods and interpret your findings. 
Variable transformations – segment the users into top five decile classes based on the total duration for all sessions and compute the total data (DL+UL) per decile class. 
Correlation Analysis – compute a correlation matrix for the following variables and interpret your findings: Social Media data, Google data, Email data, Youtube data, Netflix data, Gaming data, Other data 
Dimensionality Reduction – perform a principal component analysis to reduce the dimensions of your data and provide a useful interpretation of the results (Provide your interpretation in four (4) bullet points-maximum). 
