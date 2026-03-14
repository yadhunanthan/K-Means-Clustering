Step 1: Collect Data X = features (inputs) y = target (continuous value you want to predict) Example: wine-clustering.csv

Step 2: Split Data Divided data into: Training set (to train the model) testing set (to check performance)

step 3: from sklearn.cluster import KMeans ()

Step 4: Train the Model Teach the Model using training data: model.fit(X_train, y_train)

Step 5: Make Predictions Use the trained model to predict new values: y_pred = model.predict(X_test)

Step 6: model=KMeans(n_clusters=4,init='k-means++',random_state=42)y_means=model.fit_predict(x)print(y_means)
