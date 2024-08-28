<h1>Mutual Fund Recommendation System Based on Investor's Risk Profile</h1>

<h2>Project Title: Mutual Fund Recommendation System</h2>

<h2>Project Details</h2>
<b>Github Repository URL :</b> https://github.com/DeBron10/Recommend-Mutual-Funds <br>
<b>Industry :</b> Finance and Technology<br>

<h2>Problem Statement</h2>
<p align="justify">
    Investors often struggle to identify mutual funds that align with their risk profiles. The vast number of available funds, coupled with 
    the complexity of understanding their risk-return dynamics, makes the decision-making process daunting. The objective of this project is 
    to simplify this process by developing a recommendation system that can accurately suggest mutual funds based on the investor's risk appetite.
</p>

<h2>Project Description</h2>
<p align="justify">
    This project focuses on creating a recommendation system that suggests mutual funds to investors based on their individual risk profiles. 
    And then it recommends the user the best schemes according to their preferenced category, subcategory, risk-level, on past returns, and their past return behaviours along with many calculated functionalities like sharpe_ratio, treynor_ratio ,etc.
    The system is designed to assist investors in making informed decisions by analyzing their risk tolerance and recommending suitable mutual funds.
    Two different machine learning approaches have been implemented to ensure accurate and personalized recommendations: 
    Content-Based Filtering Using Cosine Similarity and K-Nearest Neighbors (KNN) Approach.
</p>

<h2>Implemented Approaches</h2>
<h3>1. Content-Based Filtering Using Cosine Similarity</h3>
<p align="justify">
    This approach recommends mutual funds by measuring the similarity between the features of the funds and the investor's profile. 
    The cosine similarity metric is used to calculate the angle between the feature vectors of the mutual funds and the investor's 
    risk profile, allowing for accurate and personalized recommendations.
</p>
<b>Key Steps:</b>
<ul>
    <li><u>Data Preprocessing:</u> The mutual funds dataset is loaded and preprocessed to ensure data quality.</li>
    <li><u>Feature Extraction:</u> Relevant features are extracted to create a feature vector for each mutual fund.</li>
    <li><u>Similarity Calculation:</u> Cosine similarity is calculated between the investor's profile vector and the mutual fund vectors.</li>
    <li><u>Recommendation:</u> Mutual funds with the highest similarity scores are recommended to the investor.</li>
</ul>

<h3>2. K-Nearest Neighbors (KNN) Approach</h3>
<p align="justify">
    The KNN approach involves using a machine learning algorithm to classify mutual funds based on the similarity of their features 
    to those of other funds in the dataset. The KNN algorithm predicts the most suitable mutual funds for an investor by analyzing the 
    proximity of features in a multi-dimensional space.
</p>
<b>Key Steps:</b>
<ul>
    <li><u>Data Preprocessing:</u> The dataset is cleaned and preprocessed to ensure the accuracy of the analysis.</li>
    <li><u>Feature Selection:</u> Key features are selected to form the basis of the KNN model.</li>
    <li><u>Model Training:</u> The KNN model is trained, with the optimal number of neighbors (k) selected through cross-validation.</li>
    <li><u>Recommendation:</u> The model predicts the most suitable mutual funds based on the investor's risk profile.</li>
</ul>

<b>Key Features :</b>
<ul>
    <li><u>Accurate Fund Recommendation:</u> Utilizes machine learning algorithms for personalized mutual fund recommendations.</li>
    <li><u>Diverse Approaches:</u> Used content-based filtering and KNN to offer robust recommendations.</li>
    <li><u>User-Centric Design:</u> Designed to cater to the investor's risk profile for better decision-making.</li>
</ul>

<h2>Final Project Statement</h2>
<p align="justify">
    The Mutual Fund Recommendation System leverages machine learning techniques to provide investors with tailored fund suggestions based on their risk profiles. 
    By integrating both content-based filtering and KNN, the system offers robust, accurate, and user-friendly recommendations, helping investors navigate the 
    complex landscape of mutual fund investments with confidence.
</p>
