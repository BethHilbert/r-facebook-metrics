# Linear Regression on Facebook Metrics (using R Studio)



R Studio project initially completed February 2018. Attached report and presentation were written for audience of statiticians. 

Goal
--------------------
Analyze social media's role in influencing customers by measuring the impact of status updates and advertisements on Facebook for a particular cosmetic brand. 

Data
--------------------
Dataset is available in the UCI Machine Learning Repository: http://archive.ics.uci.edu/ml/datasets/Facebook+metrics. 

Process
--------------------
"Page Total Likes" was selected as the response variable. The process included cleaning the data (using medium value for nulls), dealing with violations of LINE assumptions (transforming posts.month by centering and using higher order polynomial), variable selection (using VIF for multicollinearity and backwards elimination with Partial F Test), and then retesting LINE assumptions on final model. 


Links
--------------------
Code: https://github.com/BethHilbert/r-facebook-metrics/blob/master/Facebook%20Metrics%20Code.Rmd

Report: https://github.com/BethHilbert/r-facebook-metrics/blob/master/Facebook%20Metrics%20Report.pdf

Presentation: https://github.com/BethHilbert/r-facebook-metrics/blob/master/Facebook%20Metrics%20Presentation.pdf


