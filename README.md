# Loan_Prediction
This project will delve into analysing the factors that get a Loan approved. The goal is to provide insights into the factors that influence loan approvals to help key stakeholders in decision making. 

## Target Audience
The stakeholder is the financial institutions, and loan borrowers, who are in the business of loans. Borrowers can use this information to improve their credit worthiness to help them access loans. Financial Institutions can use the information to identify factors that can help them pick out credit worthy applicants. helps prospective homeowners

## Business Understanding (loan process)
The loan process begins with a borrower submitting an application to a lender, providing necessary documentation such as income details and credit history. The lender reviews the application, assesses the borrower's creditworthiness, and conducts underwriting to determine the risk associated with the loan. If approved, the lender offers specific loan terms, and the borrower agrees to the terms by signing a loan agreement. The closing process involves finalizing the details, and once completed, the lender disburses the funds. The borrower then repays the loan through regular installments, covering both interest and principal. The process concludes when the borrower successfully completes the repayment, and any liens or claims on collateral are released. The loan process may vary based on the type of loan and lender policies. This analysis aims to find out the factors that influence a loan approval

## Problem statement
This project aims to address the challenge of identifying the key factors influencing loan approvals by conducting an in-depth analysis of a dataset containing loan approval variables. Through this analysis, we seek to uncover patterns, trends, and relationships among the following variables: loan amount, loan status, cibil score, income amount, assets value amongst others.

## Objectives
To examine the relationship between the loan status and its features, like loan term, income amount of the applicant, cibil score amongst others. 
To identify the factors that influence loan approvals and to develop a predictive model based on the features of the loan. 
To evaluate the impact of loan amount on the loan status and to determine the optimal
To discover insights of how loans are approved
To increase the chances of credit worthy applicants getting their loans approved
## Data Understanding
The loan approval dataset is a collection of financial records and associated information used to determine the eligibility of individuals or organizations for obtaining loans from a lending institution. It includes various factors such as cibil score, income, employment status, loan term, loan amount, assets value, and loan status. This dataset is commonly used in machine learning and data analysis to develop models and algorithms that predict the likelihood of loan approval based on the given features. 

## Results
A comparison of the Decision Tree Model and Random Forest revealed the following insights.
The scores we've obtained on the test set are remarkably similar to the validation set scores, which is a positive indication that model's performance generalizes well to new and unseen data. Here's what the scores mean:

    Accuracy: Both on the validation set and the test set, we have an accuracy of around 97.3% to 97.9%. This suggests that our model is correctly classifying around 97.3% to 97.9% of instances in both datasets.

    Precision: Precision measures how many of the predicted positive instances are actually positive. With a precision of around 97.7 to 98.1 in both sets, it means that about 97.9% of the instances predicted as positive by our model are truly positive.

    Recall: Recall, also known as sensitivity or true positive rate, indicates how many of the actual positive instances our model is capturing. With a recall of around 97.6% to 98.8% in both sets, it means that our model is correctly identifying about 98.3% of the actual positive instances.

    F1 Score: The F1 score is the harmonic mean of precision and recall and provides a balanced view of a model's performance. With an F1 score of around 97.8% to 98.2% in both sets, it indicates that the model is achieving a balanced trade-off between precision and recall.

    The fact that these metrics are very consistent between the validation and test sets is a great sign. It suggests that the model is not overfitting to the validation set and that it's likely to perform similarly well on new, unseen data.
    Overall, the Decision Tree model seems to have achieved a solid and robust performance on both the validation and test sets, demonstrating its capability to make accurate predictions across different datasets.



## Conclusion

Our analysis revealed several important insights:

 
i.) Loan Amount and Annual Income: We found a strong positive correlation between loan amount and annual income. As expected, individuals with higher annual incomes were more likely to secure larger loan amounts. This underscores the importance of a borrower's financial capacity in determining loan approval.

   
ii.)Loan Term and Approval Rate: Shorter loan terms, particularly 2 and 4 years, exhibited higher approval rates compared to longer terms. This suggests that borrowers opting for shorter loan durations are perceived as lower risk by lenders.

   
Iii.) Asset Values and Income: Luxury asset values and bank asset values demonstrated stronger positive correlations with annual income compared to residential and commercial asset values. This suggests that higher-income individuals are more likely to possess luxury items and maintain larger bank assets.

    
Iv.)Categorical Variables: Our ANOVA tests examined the relationships between categorical variables (no_of_dependents, education, self_employed) and loan amount. While some variables showed minor effects on loan amount, none exhibited statistically significant relationships.

  
V.) Machine Learning model: We used Random Forest model, which has ability to handle non-linearity, interactions between variables, and potential outliers, correctly predicted approximately 97% ~ 98% loan applications. This model allowed us to identify the most influential features in predicting loan approvals and made predictive performance remain reliable across various scenarios. While the model performs well, there's always room for improvement by gathering more data, refine features, and fine-tune model parameters to enhance predictive accuracy further.





## Next Steps

In light of these findings, it's clear that loan approval decisions are driven by a combination of financial factors, including income, loan amount, and loan term. While certain categorical variables appeared to have limited impact on loan amount, the overall focus should remain on financial indicators.

    It's important to note that our analysis is subject to certain limitations. The dataset may not capture all relevant factors affecting loan approval, and outliers or data inaccuracies could influence results. Additionally, causation cannot be established through correlation alone.

    Moving forward, this analysis provides valuable insights for lenders and borrowers alike. Lenders can use these findings to refine their loan approval criteria, while borrowers can better understand the factors influencing their chances of approval.

    Suggestion:
        Further research could delve deeper into qualitative aspects such as loan purpose, borrower credit history, and economic conditions. Additionally, considering a wider range of features and employing advanced machine learning techniques could provide a more nuanced understanding of loan approval dynamics.

In conclusion, this analysis sheds light on the intricate relationships between various factors and loan approval outcomes. The insights gained can guide data-driven decision-making in the lending industry
