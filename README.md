# XG_Boost
This project aims to create a classifier model for data collected by a bank, to predict whether a customer will default on their card payments. The XGBoost algorithm was used for this project.
The parameters are as follows:

OUTPUT:
• default.payment.next.month: Default payment (1=yes, 0=no)

INPUTS:
• ID: ID of each client  
• LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)  
• SEX: Gender(1=male, 2=female)  
• EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)  
• MARRIAGE: Marital status (1=married, 2=single, 3=others)  
• AGE: Age in years  
• PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for twomonths, ... 8=payment delay for eight months, 9=payment delay for nine months and above)  
• PAY_2: Repayment status in August, 2005 (scale same as above)  
• PAY_3: Repayment status in July, 2005 (scale same as above)  
• PAY_4: Repayment status in June, 2005 (scale same as above)  
• PAY_5: Repayment status in May, 2005 (scale same as above)  
• PAY_6: Repayment status in April, 2005 (scale same as above)  

This was a part of my guided projects course 'Modern Artificial Intelligence Masterclass' on Udemy.
