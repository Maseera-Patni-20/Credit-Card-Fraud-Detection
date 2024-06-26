<!DOCTYPE html>
<html>
<body>
    <h1>Credit Card Fraud Detection</h1>
    <p>This project analyzes and predicts fraudulent credit card transactions using the <code>creditcard.csv</code> dataset. The notebook includes exploratory data analysis, model building with logistic regression, and evaluation using metrics like confusion matrix, F1 score, and recall.</p>
    <h2>Dataset</h2>
    <p>The dataset <code>creditcard.csv</code> contains credit card transactions, where the feature <code>Class</code> is the target variable indicating whether a transaction is fraudulent (1) or not (0).</p>
    <p>Due to its large size, the dataset is hosted on Google Drive. To download the dataset, follow these steps:</p>
    <pre><code>pip install gdown</code></pre>
    <p>Download the dataset using the following code:</p>
    <pre><code>import gdown

file_id = '1JOR4WJw-oYkC5oibEDUk38eie3xXHydN'
url = f'https://drive.google.com/uc?id={file_id}'
output = 'creditcard.csv'
gdown.download(url, output, quiet=False)

df = pd.read_csv(output)</code></pre>
    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>pandas</li>
        <li>numpy</li>
        <li>matplotlib</li>
        <li>seaborn</li>
        <li>scikit-learn</li>
        <li>gdown</li>
    </ul>
    <h2>Installation</h2>
    <pre><code>pip install pandas numpy matplotlib seaborn scikit-learn gdown</code></pre>
    <h2>Usage</h2>
    <p>Run the notebook to perform data analysis, visualize data distributions, and build the logistic regression model. The notebook evaluates the model using a confusion matrix and calculates F1 score and recall.</p>
    <h2>Code Structure</h2>
    <ol>
        <li>Data Loading and Initial Exploration</li>
        <li>Data Visualization</li>
        <li>Data Preprocessing</li>
        <li>Model Training</li>
        <li>Model Evaluation</li>
    </ol>
    <h2>Model Evaluation</h2>
    <p>The logistic regression model's performance is evaluated using the following metrics:</p>
    <ul>
        <li>Confusion Matrix</li>
        <li>F1 Score</li>
        <li>Recall</li>
    </ul>
    <h2>Author</h2>
    <p>Maseera Patni</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
