# Heart-Attack-Classification
The heart attack classification project begins with loading and preprocessing the dataset. After removing the 'gender' column initially, it is reintroduced for further analysis. Key features such as age, impluse, gender, blood pressure (both high and low), glucose, KCM, and troponin levels are selected for model training. The target variable is the heart attack classification ('class').

Exploratory analysis involves visualizing the relationship between age, gender, and heart attack risk, along with a correlation heatmap showing the relationships between numerical features. The data is split into training and testing sets with 70% of the data used for training. StandardScaler is used to normalize the features, ensuring consistent model performance.

Multiple models are trained, including K-Nearest Neighbors (KNN), Gaussian Naive Bayes (GNB), and Support Vector Machines (SVM) with different kernels such as linear, radial basis function (RBF), polynomial, and sigmoid. Each model is evaluated using cross-validation techniques, with the average accuracy calculated over five folds. The classification performance is further evaluated by generating classification reports for each model on the test set.

KNN, Gaussian Naive Bayes, and various SVM models all produce accuracy scores that are cross-validated and compared. Probability predictions are generated for KNN, and a dataframe is created to compare actual versus predicted values along with prediction probabilities. The code ends by saving the trained SVM model and scaler to files for future use.









