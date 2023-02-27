# Diabetes Prediction

Project developed while studying at Kyoto University

Diabetes is a chronic medical condition in which the body is unable to regulate the amount of sugar (glucose) in the blood. This is because either the pancreas is not producing enough insulin (a hormone that regulates blood sugar), or the body is not effectively using the insulin it produces. As a result, high levels of glucose in the blood can cause various health problems, including damage to the heart, blood vessels, eyes, kidneys, and nerves. There are two main types of diabetes: type 1 diabetes, which is an autoimmune disease that destroys the cells that produce insulin, and type 2 diabetes, which is caused by a combination of insulin resistance and a reduced ability to produce insulin. Both types of diabetes can be managed through lifestyle changes (such as exercise and healthy eating) and, in some cases, medications or insulin therapy.

The main goal of my project is to buid different models to predict whether the patient has diabetes or not with the help of multiple Machine Learnign algorithms and then choose the best one. Throughout the project I performed several tasks - explored the dataset to become familiar with it, showed some overall and statistical insights and ploted several graphs, prepared the data by deleting and imputing the missing values, deleted redundant properties and discarded the outliers, built a correlation heatmap to discover the most correlated with the target property properties. Finally, I have described how different models work, built different models and chose the one that performs great on the test set.

Explanation of each step in detail:

Data collection: I took a public dataset from Kaggle which contains patients with and without diabetes, there is no division by type of the diabetes, which means that classification problem is binary.

Data preprocessing: I cleaned and preprocessed the data to remove any missing or inconsistent values and ensure the data is suitable for analysis.

Feature selection: I selected the most relevant features from the health parameters to use them in the creation of models.

Model selection: Since it is a binary classification problem suitable ML algorighm should be selected such as logistic regression, decision trees, or random forests.

Model training: I trained the machine learning models and to ensure the performance on an unseed data I used cross-validation.

Model evaluation: I evaluated the performance of the models using various metrics and chose the best model based on the performance.
