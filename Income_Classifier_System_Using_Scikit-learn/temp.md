<h1>Income Classification System for Subsidy Inc.</h1>

<h2>📌 Problem Statement</h2>
<p>
"Subsidy Inc. delivers subsidies to individuals based on their income." <br>
Accurate income data is one of the hardest pieces of data to obtain across the world. <br>
Subsidy Inc. has obtained a large dataset of authenticated data on individual income, demographic parameters, and a few financial parameters.
</p>
<p>
<b>Subsidy Inc. wishes us to:</b><br>
Develop an income classifier system for individuals.
</p>

<h2>🎯 Objective</h2>
<ul>
  <li>Simplify the data system by reducing the number of variables to be studied, without sacrificing too much accuracy.</li>
  <li>Help Subsidy Inc. in planning subsidy outlay, monitoring, and preventing misuse.</li>
</ul>

<h2>🧪 Solution Summary</h2>
<ul>
  <li><b>Preprocessed the dataset:</b>
    <ul>
      <li>Handled missing values</li>
      <li>Encoded categorical features</li>
      <li>Standardized numerical data</li>
    </ul>
  </li>
  <li><b>Performed feature selection:</b>
    <ul>
      <li>Used feature importance from RandomForest</li>
    </ul>
  </li>
  <li><b>Implemented an income classifier:</b>
    <ul>
      <li>Used RandomForestClassifier</li>
    </ul>
  </li>
  <li><b>Evaluated model performance:</b>
    <ul>
      <li>Checked accuracy and generated a classification report</li>
    </ul>
  </li>
  <li><b>Visualized important features:</b>
    <ul>
      <li>Identified key factors influencing income classification</li>
    </ul>
  </li>
</ul>

<h2>📚 Libraries Used</h2>
<ul>
  <li><code>pandas</code> – Data handling</li>
  <li><code>numpy</code> – Numerical operations</li>
  <li><code>matplotlib</code> & <code>seaborn</code> – Data visualization</li>
  <li><code>sklearn.model_selection</code> – Train-test split</li>
  <li><code>sklearn.preprocessing</code> – Feature scaling & encoding</li>
  <li><code>sklearn.ensemble</code> – <code>RandomForestClassifier</code> for classification</li>
  <li><code>sklearn.metrics</code> – Model evaluation</li>
</ul>
