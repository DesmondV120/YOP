<h1><b>Ensemble Model and Hyperparameterization</b></h1>

<h2><b>Assignment Title:</b></h2>
<p>Build an Ensemble Model and Hyperparameterization</p>

<h2><b>Objective:</b></h2>
<p>Build a gradient boosting ensemble model using the <b>XGBoost</b> library that was installed during the activity, then perform a hyperparameter technique on the model that you created.</p>

<hr>

<h2><b>Instructions:</b></h2>

<h3><b>1. Dataset and Initial Setup</b></h3>
<ul>
    <li>https://www.figma.com/proto/SDoNtAMW9SKfmgJeZYiS6A/3D-Carousel-Hero-(Community)?node-id=0-1&t=WBMd7i7EAy1M1fpA-1</li>
    <li>The dataset contains a number of columns that are <b>not needed</b> to build the model. For example:
        <ul>
            <li>Drop anything related to <b>address</b>, <b>year sold</b>, and <b>sale type</b>.</li>
        </ul>
    </li>
</ul>

<h3><b>2. Ensemble Model</b></h3>

<h4><b>2.1 Data Exploration</b></h4>
<ul>
    <li><b>Perform any required data exploration</b> to understand the dataset:
        <ul>
            <li>Inspect the data to check for missing values, data types, and general insights about the dataset.</li>
        </ul>
    </li>
</ul>

<h4><b>2.2 Data Visualizations</b></h4>
<ul>
    <li><b>Create data visualizations</b> for all categorical features.</li>
    <li>Review the <b>mean of numerical data</b> to better understand the distribution of variables.</li>
</ul>

<h4><b>2.3 Feature Engineering</b></h4>
<ul>
    <li><b>Complete any feature engineering</b> that is necessary for the dataset:
        <ul>
            <li>Create or modify features as needed to improve model performance.</li>
        </ul>
    </li>
</ul>

<h4><b>2.4 Handle Categorical Variables and Missing Data</b></h4>
<ul>
    <li><b>Dummy code all categorical features</b> using one-hot encoding or any other appropriate method.</li>
    <li><b>Deal with missing data</b>:
        <ul>
            <li>Some columns in the dataset may have a lot of missing values, so you may need to drop these columns or use imputation techniques to handle them.</li>
        </ul>
    </li>
</ul>

<h4><b>2.5 Build the Gradient Boosting Model</b></h4>
<ul>
    <li><b>Build the ensemble model using XGBoost library</b>:
        <ul>
            <li>Initialize and train an <b>XGBoost</b> gradient boosting model on the dataset.</li>
        </ul>
    </li>
    <li><b>Note:</b> XGBoost can be computationally intensive, so it may take some time to run, especially on a complex dataset. Consider reducing the dimensions of the data or using optimization techniques if the model is taking too long to train.</li>
</ul>

<h4><b>2.6 Model Evaluation</b></h4>
<ul>
    <li><b>Evaluate the model's performance</b>:
        <ul>
            <li>Assess the model's <b>accuracy</b> and <b>precision</b>.</li>
            <li>Interpret the outcome of the model.</li>
        </ul>
    </li>
</ul>

<h3><b>3. Hyperparameterization</b></h3>

<h4><b>3.1 Hyperparameter Tuning - Estimators and Stopping Rounds</b></h4>
<ul>
    <li><b>Perform hyperparameter tuning</b> on your ensemble model:
        <ul>
            <li>Choose the <b>number of estimators</b> (also known as boosting rounds).</li>
            <li>Choose the <b>early stopping rounds</b> to prevent overfitting.</li>
        </ul>
    </li>
    <li><b>Evaluation after this step:</b> Show the model's evaluation metrics after performing this tuning.</li>
</ul>

<h4><b>3.2 Hyperparameter Tuning - Learning Rate</b></h4>
<ul>
    <li><b>Choose a learning rate</b> that optimizes the model’s performance.</li>
    <li><b>Evaluate the model after adjusting the learning rate</b> to observe any improvements.</li>
</ul>

<h3><b>4. Notebook and Documentation</b></h3>
<ul>
    <li>All work should be completed in a <b>Jupyter Notebook</b>.</li>
    <li><b>Add comments in all cells</b> that you work in to explain what each step does.</li>
    <li>You will turn in the assignment by taking <b>screenshot</b>s of your Jupyter Notebook and using the homework assignment template.</li>
</ul>
