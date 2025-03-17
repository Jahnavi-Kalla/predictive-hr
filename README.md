# predictive-hr

Project Overview
Employee turnover is a major challenge for organizations, leading to increased recruitment costs, productivity loss, and knowledge gaps. This project aims to predict employee turnover at Salifort Motors using Machine Learning techniques. By analyzing various factors such as job satisfaction, tenure, salary, and performance ratings, we develop a predictive model that helps the HR team identify at-risk employees and take proactive steps to improve retention.

Dataset
The dataset used for this project comes from Salifort Motors' HR records and consists of employee-related attributes. It includes essential features such as last_evaluation, satifaction_index, tenure etc., The target variable (Left) indicates whether an employee has left the company (1 = Yes, 0 = No). Since the dataset is already clean and does not contain missing values, we were able to proceed directly with feature engineering and model training.

Data Preprocessing
Data should be made ready in order to perform further analysis. For this, One-hot Encoding, Ordinal Encoding MinMax Scaling of the columns are done ensuring the data is on the same level and there is no biasing for a specific column.

Feature Engineering and Correlation Analysis
In this phase, we evaluate the dataset by visually analyzing each column in relation to the target variable, Left, using various graphical techniques such as box plots, bar graphs, clustered charts, and histograms. These visualizations provide an overview of how different features impact employee turnover, helping us distinguish key influencing factors.
Additionally, we perform Correlation Analysis to assess the strength and direction of relationships between variables. A heatmap analysis is conducted to identify whether a particular feature has a positive or negative correlation with the target variable. This process helps in selecting the most significant factors contributing to employee turnover, enabling a more effective predictive model.

Model Training and Evaluation
For model training, the dataset is split into 80% training data and 20% testing data to ensure a balanced evaluation. Various machine learning algorithms, including Random Forest Classifier, XGBoost Classifier, and Support Vector Machine (SVM), are implemented to assess their predictive performance.
After training and testing the models, their accuracies are compared. Among the three, Random Forest Classifier achieves the highest accuracy, making it the most suitable choice for predicting employee turnover.

Results and Insights
The analysis reveals that employees with lower job satisfaction and longer tenure are more likely to leave the company. On the other hand, employees who have been recently promoted and receive higher salaries are less likely to leave.
These insights suggest that HR should implement strategic retention measures, such as improving job satisfaction, offering career growth opportunities, and ensuring competitive compensation. By addressing these key factors, organizations can effectively reduce employee turnover and enhance workforce stability.

Future Improvements
Although the model performs well, there are several ways to enhance its effectiveness. Future improvements could include integrating real-time HR data, incorporating additional features like work-life balance and commute time, and deploying the model as a web-based application or API for seamless usage.
