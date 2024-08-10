<h1>Breast Cancer Classification</h1>

<p>This repository contains various classification algorithms applied to a breast cancer dataset (<code>data.csv</code>). Each file includes the implementation of a different classification model, along with the confusion matrix and accuracy score for performance evaluation.</p>

<h2>Dataset</h2>
<ul>
  <li><strong>Filename:</strong> data.csv</li>
  <li><strong>Description:</strong> The dataset contains features extracted from breast cancer patients, which are used to predict the presence of cancerous cells (malignant or benign).</li>
</ul>

<h2>Classification Algorithms</h2>
<p>Below is a list of the classification algorithms implemented in this repository:</p>
<ul>
  <li><strong>Logistic Regression</strong> - <code>logistic_regression.py</code></li>
  <li><strong>Decision Tree</strong> - <code>decision_tree.py</code></li>
  <li><strong>Random Forest</strong> - <code>random_forest.py</code></li>
  <li><strong>K-Nearest Neighbors (KNN)</strong> - <code>knn.py</code></li>
  <li><strong>Support Vector Machine (SVM)</strong> - <code>svm.py</code></li>
  <li><strong>Naive Bayes</strong> - <code>naive_bayes.py</code></li>
  <li><strong>Gradient Boosting</strong> - <code>kernel_svm.py</code></li>
</ul>

<h2>Contents</h2>
<p>Each file in the repository follows a similar structure:</p>
<ul>
  <li>Data loading and preprocessing</li>
  <li>Model training and testing</li>
  <li>Confusion matrix computation and visualization</li>
  <li>Accuracy score calculation</li>
</ul>

<h2>Usage</h2>
<p>To use the code in this repository, follow the steps below:</p>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/mazimum86/breast-cancer-classification.git</code></pre>
  </li>
  <li>Navigate to the repository directory:
    <pre><code>cd breast-cancer-classification</code></pre>
  </li>
  <li>Install the required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the desired classification script:
    <pre><code>python logistic_regression.py</code></pre>
  </li>
</ol>

<h2>Dependencies</h2>
<p>All required Python packages are listed in the <code>requirements.txt</code> file. The main dependencies include:</p>
<ul>
  <li>pandas</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
</ul>

<h2>Results</h2>
<p>The results for each classification algorithm include:</p>
<ul>
  <li>Confusion Matrix: Visual representation of the model's performance.</li>
  <li>Accuracy Score: Metric indicating the proportion of correctly classified instances.</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Feel free to submit a pull request or open an issue if you have suggestions for improvements or additional features.</p>

<h2>License</h2>
<p>This repository is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>
