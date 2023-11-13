# Credit-Card-Default-Prediction

Project Scope 
The goal of this project is to make a user-interactive application that will allow a user to input information regarding their credit usage and payments and predict if they are likely to default on their payments in the future.

Domain:
Financial Risk assessment

Literature Review:
SMOTE technique
https://ieeexplore.ieee.org/abstract/document/8717766


Data Sources:
The primary data source for this project can be found here:
http://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
This data set consists of 30,000 entries each of which has 24 features.

Domain-specific Challenges:
In a real-world scenario models regarding Banking and Finance have specific challenges due to strict regulations put in place by governments. Primarily these regulations are in regards to building models that do not have unfair biases towards any groups. Due to the nature of this project however and the model not being used in a production environment there are not any specific challenges that need to be addressed.

KPI's:
KPIs to be used are accuracy, recall, as well as MSE. Additionally, ease of use for the end user is a consideration in this project.

AWS Tools to use:

Amazon S3:Store the dataset securely.

Amazon SageMaker: Data Preprocessing,Model Training, Model Evaluation, Model Deployment

Amazon QuickSight: Visualize model performance, feature importance, and potentially identify trends or patterns in defaults.
