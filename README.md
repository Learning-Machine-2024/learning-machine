# Website Fingerprinting on Anoymous Network
> Team Learning Machine</br>
Fall 2024 Machine Learning Project

## Project Overview
 This project aims to analyze website fingerprinting on anonymous networks and evaluate the performance of various machine learning models under different scenarios.

## Team Introduction
*  Yunwoo Choi (2176387) - Open World Multi Class Classification, Presentation Development
* Minkyung Lee (2076298) - Open World Binary Classification, Presentation Development
* Jayeong Seo (2170045) - Open World Multi Class Classification, Presenter
* Jiin Han (2276350) - Open World Binary Classification, Presenter
* YouLee Han (2271065) - Closed World Classfication, Script Writer
* Jaehee Gung (2029003) - Closed World Classfication, Script Writer

## Project Description

Website fingerprinting is an attack technique that identifies websites a client has accessed by analyzing the patterns of data flow. The project is divided into the following categories:

1. Closed World Classification: Classifying the 95 monitored websites.

2. Open World 
- Binary Classification: Distinguishing whether a user is visiting a monitored website(label 1) or an unmonitored one(label -1).

- Multi-Class Classification: Classify 95 monitored website traces with unique labes(0, 1, 2, ..., 94) against additional unmonitored websites with label -1.

## File Overview

- closed_final.ipynb: Contains the closed-world classification experiments and results, focusing on classifying traffic from a predefined set of monitored websites.

- open_binary.ipynb: Focuses on open-world binary classification, distinguishing between monitored and unmonitored websites.

- open_multi.ipynb: Includes experiments for open-world multi-classification, identifying specific monitored websites among a larger set of possible targets.

- ScalingEncoding.ipynb: Details various data scaling and encoding techniques used to improve model performance.

- WFdefense.ipynb: Evaluates different defense mechanisms against website fingerprinting attacks, aiming to mitigate the risks of these types of attacks.

## Requirements

To run the provided notebooks, you will need the following dependencies:

    Python 3.8+

    Jupyter Notebook

    NumPy

    Pandas

    Scikit-learn

    Matplotlib

### How to Run the Project

1. Clone the repository.

2. Install the dependencies listed in the requirements section using the following command:

    ```pip install -r requirements.txt```

3. Open Jupyter Notebook and load the respective .ipynb file for the experiment you want to run.

4. Follow the instructions within each notebook to run the experiments.

## Results

The results of the experiments are detailed within each respective notebook. It includes metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.








