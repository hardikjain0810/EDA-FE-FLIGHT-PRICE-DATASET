<h1>✈️ Flight Price Prediction – EDA & Feature Engineering</h1>
<h3>📌 Project Overview</h3>

This project focuses on Exploratory Data Analysis (EDA) and Feature Engineering for a Flight Price Prediction problem. The goal is to clean, transform, and prepare raw flight booking data so it can be effectively used for machine learning models.

The notebook walks through real-world data preprocessing steps such as handling dates & times, extracting useful features, encoding categorical variables, and preparing a final model-ready dataset.

<h3>🔍 Exploratory Data Analysis (EDA)</h3>

The EDA process includes:
<ul>
<li>Inspecting dataset shape and data types</li>
<li>Checking missing values and handling them</li>
<li>Understanding categorical vs numerical features</li>
<li>Visual exploration using Matplotlib and Seaborn</li>
</ul>

<h3>🛠️ Feature Engineering Steps</h3>
<ol>
1️⃣ Date & Time Feature Extraction
    <ul>
        <li>Extracted day and month from Date_of_Journey</li>
        <li>Converted Dep_Time and Arrival_Time into hours and minutes</li>
        <li>Dropped original date/time columns after extraction</li>
    </ul>
2️⃣ Duration Processing
<ul>
        <li>Converted flight duration (hours & minutes) into numerical format</li>
        <li>Created separate features for duration hours and minutes</li>
</ul>

3️⃣ Handling Categorical Variables
<ul>
        <li>Applied One‑Hot Encoding for categorical features such as:</li>
        <ul>
          <li>Airline</li>
          <li>Source</li>
          <li>Destination</li>
          <li>Route</li>
        </ul>
        <li>Removed unnecessary or redundant columns after encoding</li>
</ul>
4️⃣ Column Removal

Dropped columns that were no longer required after feature extraction:
<ul>
<li>Airline</li>

<li>Source</li>

<li>Destination</li>


<li>Additional_Info</li>

Raw Date & Time columns
</ul>
</ol>
<h3>📊 Output</h3>

<ul>
    <li>A cleaned and transformed dataset ready for machine learning models</li>

<li>Improved feature representation for better prediction performance</li>
</ul>

<h3>Next Steps</h3>
<ul>
    <li>Apply regression models (Linear Regression, Random Forest, XGBoost, etc.)</li>
    <li>Perform feature selection</li>
    <li>Hyperparameter tuning</li>
    <li>Model evaluation and comparison</li>
</ul>
