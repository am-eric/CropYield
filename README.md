<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    
</head>

<body>
    <div class="container">
        <h1>Crop Recommendation System</h1>
        <p>A machine learning project for crop recommendation based on various factors.</p>
        <h2>Overview</h2>
        <p>This project utilizes machine learning algorithms, including Decision Trees, Naive Bayes, SVM, Logistic Regression, Random Forest, and XGBoost, to recommend suitable crops based on environmental factors such as temperature, humidity, pH, and rainfall.</p>
        <h2>Dataset</h2>
        <p>The dataset used in this project is available in the file <code>Crop_recommendation.csv</code>.</p>
        <h2>Models</h2>
        <p>The following machine learning models were trained and evaluated:</p>
        <ul>
            <li>Decision Tree</li>
            <li>Naive Bayes</li>
            <li>SVM</li>
            <li>Logistic Regression</li>
            <li>Random Forest</li>
            <li>XGBoost</li>
        </ul>
        <h2>Accuracy Comparison</h2>
        <p>Accuracy comparison of different models:</p>
        <h2>Usage</h2>
        <p>To use the trained models for crop prediction, you can load the saved model files (e.g., DecisionTree.pkl, NBClassifier.pkl, etc.) and input the relevant environmental factors for prediction.</p>
        <h2>Example Prediction</h2>
        <p>An example prediction using the Random Forest model:</p>
        <pre>
            <code>
data = np.array([[104, 18, 30, 23.603016, 60.3, 6.7, 140.91]])
prediction = RF.predict(data)
print(prediction)
            </code>
        </pre>
        <h2>License</h2>
        <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
    </div>

</body>

</html>
