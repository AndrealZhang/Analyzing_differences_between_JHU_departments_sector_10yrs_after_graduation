# Background
How are different departments at JHU related in regards to what sectors people work in 10 years after graduation? Looking at the [NGLS Coalition PhD and Postdoc data](https://provost.jhu.edu/wp-content/uploads/sites/4/2019/02/Career-Outcome-ADA-Tables-Final.pdf), I analyzed the sector 10 years after graduation data because most people would have found a secure job after 10 years.

# Cluster Analysis
I first converted the PDF data into an Excel file using Tabula. After cleaning up the data, I set up my cluster analysis by calculating the z-scores, distance squared, and min distance squared for each department and sector. Using the solver to minimize the sum of the minimum squared distance, I found the departments that were the center of the three clusters:
