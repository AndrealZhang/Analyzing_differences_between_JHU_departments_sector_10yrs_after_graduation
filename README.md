# Background
How are different departments at JHU related in regards to what sectors people work in 10 years after graduation? Looking at the [NGLS Coalition PhD and Postdoc data](https://provost.jhu.edu/wp-content/uploads/sites/4/2019/02/Career-Outcome-ADA-Tables-Final.pdf), I analyzed the sector 10 years after graduation data because most people would have found a secure job after 10 years.

# Cluster Analysis
I first converted the PDF data into an Excel file using Tabula. After cleaning up the data, I set up my cluster analysis by calculating the z-scores, distance squared, and min distance squared for each department and sector. Using the solver to minimize the sum of the minimum squared distance, I found the departments that were the center of the three clusters:

![alt_link](https://github.com/AndrealZhang/Analyzing_differences_between_JHU_departments_sector_10yrs_after_graduation/blob/master/cluster_centers.png)

The departments at the center of the three clusters:
1. Biomedical Engineering → average academia/for-profit/gov, slightly higher non profit
2. Cellular and Molecular Physiology → average academia/for-profit, low gov and non-profit
3. Human Genetics and Molecular Biology → average eacademia/for-profit/non-profit, higher gov

![alt_link](https://github.com/AndrealZhang/Analyzing_differences_between_JHU_departments_sector_10yrs_after_graduation/blob/master/cluster_groups.png)

# Summary and Implications
1. Half of the departments fall under cluster 1, which is: average percent of people with academia and for-profit jobs, and a slightly higher percentage in non-profit jobs.
2. If the career center at Hopkins wants to help students in certain departments with finding potential jobs for the future, it would be best to recommend a sector that aligns with the cluster the department belongs in.
