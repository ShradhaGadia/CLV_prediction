<h1>Customer Lifetime Value (CLV) Prediction Project</h1>

<p>This project predicts the future value of a customer to a business using their past purchase history, frequency, monetary spending, and additional behavioral features. The prediction is done using various regression models with thorough feature engineering and evaluation.</p>

<h2>Project Structure</h2>
<ul>
  <li><code>CLV_Prediction.ipynb</code> — Main Jupyter Notebook with data cleaning, EDA, feature engineering, modeling, and evaluation.</li>
  <li><code>requirements.txt</code> — All Python dependencies used (including NumPy version 1.26 for compatibility with some libraries).</li>
</ul>

<h2>Dataset</h2>
<p>
  The dataset is not directly included in this repository due to its size.<br>
  You can download it from Kaggle here: 
  <a href="https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset" target="_blank">Online Retail Dataset</a>.
</p>


<h2>How to Run</h2>
<ol>
  <li>Clone this repository.</li>
  <li>Create and activate a virtual environment: 
    <pre><code>python -m venv venv
    venv\Scripts\activate     # Windows</code></pre>
  </li>
  <li>Install dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Download the dataset from the Kaggle link above and place it in the project directory.</li>
  <li>Open and run the notebook <code>CLV_Prediction.ipynb</code> step by step.</li>
</ol>

<h2>Summary of Results</h2>
<ul>
  <li>Multiple models were tested — Linear Regression, Random Forest, CatBoost, XGBoost, MLP, and ensemble methods.</li>
  <li><strong>Random Forest</strong> consistently delivered the best performance, achieving an R² of ~0.59–0.63.</li>
  <li>Extensive feature engineering (Recency, Frequency, Monetary, RFM scores, average basket size, unique products bought, ratios) was done to extract maximum predictive power.</li>
</ul>

<h2>Key Points</h2>
<ul>
  <li>This project demonstrates an end-to-end CLV prediction workflow, including data cleaning, feature engineering, model comparison, hyperparameter tuning, and final evaluation with visualizations.</li>
  <li>Some plots are included in the notebook to interpret model performance.</li>
</ul>

<h2>Notes</h2>
<p>Please ensure that you install the specified package versions (especially NumPy 1.26) inside a virtual environment to avoid compatibility issues.</p>


<p>For any clarifications or suggestions, feel free to raise an issue.</p>
