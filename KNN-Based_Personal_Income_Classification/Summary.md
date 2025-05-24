<h1>KNN-Based Personal Income Classification</h1>

<h2>Summary</h2>
<p>
The objective of this case study is to classify individuals' personal income using the K-Nearest Neighbors (KNN) algorithm. 
The dataset consists of income-related features, and the goal is to predict whether an individual's income is greater than or less than $50,000.
</p>

<h2>Steps Followed</h2>

<h3>Data Preprocessing</h3>
<ul>
  <li>Loaded the dataset and handled missing values.</li>
  <li>Removed rows with missing <code>JobType</code> and <code>Occupation</code> values.</li>
  <li>Encoded categorical variables using one-hot encoding.</li>
  <li>Converted income labels (<code>SalStat</code>) into binary format:
    <ul>
      <li>0: ≤ 50K</li>
      <li>1: > 50K</li>
    </ul>
  </li>
  <li>Split the dataset into training and testing sets.</li>
</ul>

<h3>Model Implementation</h3>
<ul>
  <li>Used K-Nearest Neighbors (KNN) for classification.</li>
  <li>Trained the model using <code>K = 5</code>.</li>
  <li>Evaluated performance using accuracy score and confusion matrix.</li>
  <li>Analyzed misclassified samples.</li>
</ul>

<h3>Effect of K on Classification</h3>
<ul>
  <li>Tested multiple values of K (from 1 to 20) to observe misclassification rates.</li>
</ul>

<h2>Libraries Used</h2>
<ul>
  <li><code>pandas</code> – Data handling</li>
  <li><code>numpy</code> – Numerical operations</li>
  <li><code>seaborn</code> – Data visualization</li>
  <li><code>sklearn.model_selection</code> – Data splitting</li>
  <li><code>sklearn.neighbors</code> – KNN classification</li>
  <li><code>sklearn.metrics</code> – Model evaluation (accuracy score and confusion matrix)</li>
</ul>

<h2>Conclusion</h2>
<p>
This KNN-based approach helps in simplifying subsidy allocation by predicting income levels efficiently 
with a well-optimized model, contributing to better planning and misuse prevention.
</p>
