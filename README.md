# Telecom Customer Churn

Data Source --> https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/discussion?sort=hotness

Presentation Link --> https://github.com/alecs1523/telecom_customer_churn/blob/main/customer_churn_anlaysis.pdf

--- 

Data Understanding

- Dataset showing key variables that lead to customer churn 
- Target Variable = Churn
- Key Variables
- ![top5churn](https://github.com/user-attachments/assets/c2f6acf0-7647-428b-a164-9ccbec1438bc)

# States with the highest churn
![image](https://github.com/user-attachments/assets/5e01bd1b-f4f7-4c98-a883-d64fa24633d2)

# States with the lowest churn
![image](https://github.com/user-attachments/assets/67bb0bc5-20a8-48ba-ae7d-fc446f19e6d4)

# Evaluating Colinearity w/ Matrix
![image](https://github.com/user-attachments/assets/343dc634-71df-4176-abfd-6d587317a7fc)

It seems there is no correlation between variables 

# Model Results w/ Statsmodels

![image](https://github.com/user-attachments/assets/93abc09c-cf6e-4720-801a-d0b2ac755bbd)

# Model Results w/ SciKitLearn
![image](https://github.com/user-attachments/assets/1bac2341-fbff-4fd7-a2a7-1bbd732b2ec4)

# Model Results and Next Steps
Takeaways from the Decision Classifier Model
![image](https://github.com/user-attachments/assets/c15ece75-a75e-413c-adae-9aff24870e5b)


The decision classifier model helps us predict churn by learning patterns in these selected features. Here’s what we learned:

Customer Service Calls is the Strongest Predictor:

The more frequently a customer contacts customer service, the higher the likelihood of churn. This suggests that resolving customer complaints efficiently could reduce churn. Customers with an International Plan are at Higher Risk:

These customers may be dissatisfied with the cost or quality of the international calling plan. Improving this service could improve retention. Voice Mail Plan is Predictive:

While less obvious, whether a customer has a voicemail plan or not may relate to overall service usage or satisfaction. This could be worth exploring further. Total International Calls Adds Context:

Customers making frequent international calls may represent a specific customer segment. Understanding their unique needs (e.g., better international rates or service quality) could reduce churn.





