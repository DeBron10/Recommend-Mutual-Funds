<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mutual Fund Recommendation System</title>
</head>
<body>
    <h1>Mutual Fund Recommendation System Based on Investor's Risk Profile</h1>
    
    <h2>Project Description</h2>
    <p>
        This project focuses on creating a recommendation system that suggests mutual funds to investors based on their individual risk profiles. 
        The system is designed to assist investors in making informed decisions by analyzing their risk tolerance and recommending suitable mutual funds. 
        Two different machine learning approaches have been implemented to ensure accurate and personalized recommendations:
    </p>
    <ul>
        <li>Content-Based Filtering Using Cosine Similarity</li>
        <li>K-Nearest Neighbors (KNN) Approach</li>
    </ul>

    <h2>Problem Statement</h2>
    <p>
        Investors often struggle to identify mutual funds that align with their risk profiles. The vast number of available funds, coupled with 
        the complexity of understanding their risk-return dynamics, makes the decision-making process daunting. The objective of this project is 
        to simplify this process by developing a recommendation system that can accurately suggest mutual funds based on the investor's risk appetite.
    </p>

    <h2>Implemented Approaches</h2>
    
    <h3>1. Content-Based Filtering Using Cosine Similarity</h3>
    <p>
        This approach recommends mutual funds by measuring the similarity between the features of the funds and the investor's profile. 
        The cosine similarity metric is used to calculate the angle between the feature vectors of the mutual funds and the investor's 
        risk profile, allowing for accurate and personalized recommendations.
    </p>
    <h4>Key Steps:</h4>
    <ul>
        <li><strong>Data Preprocessing:</strong> The mutual funds dataset is loaded and preprocessed to ensure data quality.</li>
        <li><strong>Feature Extraction:</strong> Relevant features are extracted to create a feature vector for each mutual fund.</li>
        <li><strong>Similarity Calculation:</strong> Cosine similarity is calculated between the investor's profile vector and the mutual fund vectors.</li>
        <li><strong>Recommendation:</strong> Mutual funds with the highest similarity scores are recommended to the investor.</li>
    </ul>
    
    <h3>2. K-Nearest Neighbors (KNN) Approach</h3>
    <p>
        The KNN approach involves using a machine learning algorithm to classify mutual funds based on the similarity of their features 
        to those of other funds in the dataset. The KNN algorithm predicts the most suitable mutual funds for an investor by analyzing the 
        proximity of features in a multi-dimensional space.
    </p>
    <h4>Key Steps:</h4>
    <ul>
        <li><strong>Data Preprocessing:</strong> The dataset is cleaned and preprocessed to ensure the accuracy of the analysis.</li>
        <li><strong>Feature Selection:</strong> Key features are selected to form the basis of the KNN model.</li>
        <li><strong>Model Training:</strong> The KNN model is trained, with the optimal number of neighbors (k) selected through cross-validation.</li>
        <li><strong>Recommendation:</strong> The model predicts the most suitable mutual funds based on the investor's risk profile.</li>
    </ul>

    <h2>Future Enhancements</h2>
    <p>
        There are several potential future enhancements to improve the recommendation system:
    </p>
    <ul>
        <li>Incorporating additional data points, such as historical returns, expense ratios, and sector allocation, to enhance the accuracy of the recommendations.</li>
        <li>Integrating a user feedback loop to continuously refine and improve the recommendation model.</li>
        <li>Expanding the system to recommend a diversified portfolio of funds instead of individual fund suggestions.</li>
        <li>Implementing real-time data updates to ensure that the recommendations reflect the latest market conditions.</li>
    </ul>

    <h2>Installation and Usage</h2>
    <p>
        To run the project locally:
    </p>
    <ol>
        <li><strong>Clone the repository:</strong></li>
        <pre><code>git clone https://github.com/your_username/mutual-fund-recommendation-system.git</code></pre>
        <li><strong>Navigate to the project directory:</strong></li>
        <pre><code>cd mutual-fund-recommendation-system</code></pre>
        <li><strong>Install the required dependencies:</strong></li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li><strong>Run the Jupyter Notebooks:</strong></li>
        <ul>
            <li>For the Content-Based approach: <code>Content_Based_Cosine_Similarity.ipynb</code></li>
            <li>For the KNN approach: <code>KNN_Approach.ipynb</code></li>
        </ul>
    </ol>

    <h2>Conclusion</h2>
    <p>
        This project presents a comprehensive framework for recommending mutual funds based on investors' risk profiles using two distinct approaches. 
        By combining content-based filtering with the KNN algorithm, the system offers personalized and accurate mutual fund recommendations, helping 
        investors make informed decisions tailored to their financial goals and risk tolerance.
    </p>
</body>
</html>
