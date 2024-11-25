# Predicting Sectoral Productivity Trends in New Zealand (1978–2023)

## Description
Productivity is a critical measure of economic performance, reflecting how efficiently resources are utilized to generate output. This project leverages the **Productivity Statistics: 1978–2023** dataset from Stats NZ to analyze and predict productivity trends across various economic sectors in New Zealand.

This dataset spans decades of productivity data, segmented by sector (e.g., "Agriculture, Forestry, and Fishing") and resource type (e.g., "Capital," "Labor"). Our objective is to address key questions about sectoral performance and use machine learning models to forecast future productivity.

The dataset can be accessed directly [here](https://www.stats.govt.nz/assets/Uploads/Productivity-statistics/Productivity-statistics-1978-2023/Download-data/productivity-statistics-1978-2023.csv) and was obtained from the [Stats NZ site](https://www.stats.govt.nz/large-datasets/csv-files-for-download/).

---

## Defined Problem

### Objective
Predict productivity indices for different sectors based on historical data and explore which factors contribute most to productivity growth.

---

### Use Case
1. Policymakers can use forecasts to identify sectors requiring intervention.
2. Businesses can understand trends for strategic investment and resource allocation.
3. Economists can analyze factors influencing productivity growth.

---

### Specific Questions to Answer
1. How does productivity vary across sectors over time?
2. Which sectors are most likely to see future growth or stagnation?
3. What are the key factors driving productivity in each sector?

## Midterm Project Notebook

You can find the detailed notebook for this midterm project [here](https://github.com/MathmoKiwi/machine-learning-bootcamp/blob/main/midterm-project/MidtermProject.ipynb).

## Deployment Instructions

You can find the instructions for reproducing deployment / dependencies / instrutions / etc for this midterm project [here](https://github.com/MathmoKiwi/machine-learning-bootcamp/blob/main/midterm-project/deployment.md).


## ML Zoomcamp Project Evaluation Criteria

| **Criteria**                      | **0 Points**                                                              | **1 Point**                                                                                            | **2 Points**                                                                                                                  | **3 Points**                                                                                                                                      | **Max Points** |
|------------------------------------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| **Problem description**            | Problem is not described                                                  | Problem is described in README briefly without much details                                           | Problem is described in README with enough context, so it's clear what the problem is and how the solution will be used     |                                                                                                                                                   | 2             |
| **EDA**                            | No EDA                                                                    | Basic EDA (looking at min-max values, checking for missing values)                                    | Extensive EDA (ranges of values, missing values, analysis of target variable, feature importance analysis)                  | For images: analyzing the content of the images. For texts: frequent words, word clouds, etc.                                                    | 2             |
| **Model training**                 | No model training                                                         | Trained only one model, no parameter tuning                                                           | Trained multiple models (linear and tree-based).                                                                            | Trained multiple models and tuned their parameters. For neural networks: tried multiple variations and performed tuning (learning rate, etc.)     | 3             |
| **Exporting notebook to script**   | No script for training a model                                            | The logic for training the model is exported to a separate script                                     |                                                                                                                             |                                                                                                                                                   | 1             |
| **Reproducibility**                | Not possible to execute the notebook and the training script. Data missing | It's possible to re-execute the notebook and training script without errors. Dataset is accessible.    |                                                                                                                             |                                                                                                                                                   | 1             |
| **Model deployment**               | Model is not deployed                                                     | Model is deployed (with Flask, BentoML, or a similar framework)                                       |                                                                                                                             |                                                                                                                                                   | 1             |
| **Dependency and environment management** | No dependency management                                                | Provided a file with dependencies (requirements.txt, pipfile, bentofile.yaml, etc.)                   | Provided a file with dependencies, used virtual environment, and README explains how to install and activate dependencies   |                                                                                                                                                   | 2             |
| **Containerization**               | No containerization                                                       | Dockerfile is provided or a tool that creates a Docker image is used (e.g., BentoML)                  | The application is containerized, and the README describes how to build and run the container                               |                                                                                                                                                   | 2             |
| **Cloud deployment**               | No deployment to the cloud                                                | Docs describe clearly (with code) how to deploy the service to cloud or Kubernetes cluster             | Code is provided for cloud deployment with testing URLs/screenshots/videos.                                                 |                                                                                                                                                   | 2             |
| **Total**                          |                                                                           |                                                                                                        |                                                                                                                             |                                                                                                                                                   | **16**        |
