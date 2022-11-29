# PySparkML_CustomerChurnClassification
 
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Customer churn is one of the most important metrics of any business, because the cost of acquiring a new client far exceeds the cost of retaining an existing client. In this project, we used a variety of classification algorithms from PySpark including decision trees, random forest, gradient boosting, naive bayes, and other classification algorithms in order to predict whether a customer will churn (exit) based on their features such as credit score, geography, membership, tenure, and many more. 

The numerical features were scaled with the MinMax scalar in order to normalize the range. The cateogrical features were processed with One-Hot Encoding (OHE). Then, the numerical and categorical features were assembled into a features column containing vectors.

After training all of the models, the gradient boosting model was selected because it had the highest F1 score and area under PR, selected because of the unbalanced nature of customers who exit and those who stayed. A gradient boosting model for the purpose of cross-validation was then created for hyperparameter tuning. The final model had an F1 score of 0.8371 and an accuracy of 0.8485.

### Built With

* []()Python


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these steps.

### Prerequisites

This is a list of packages that need to be installed before the notebook can be run.
* pyspark
* java


### Installation

Clone the repo: https://github.com/calvinma888/PySparkML_GradAdmissionsChance.git

### Datasets
The dataset can be found in the cloned repository.

<!-- USAGE EXAMPLES -->
## Usage

Run with Jupyter Notebook or Google Colab


<!-- CONTRIBUTING -->
## Contributing

Calvin (Yu chien) Ma

