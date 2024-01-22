# Hugging Face ML Models Analysis
This project aims to analyze the ease of use of machine learning (ML) applications in two specific domains: "Text Classification" and "Text Generation." The analysis is based on models available in the Hugging Face ML store. The primary focus is to determine whether "Text Classification" models are easier for software developers in terms of coding and maintenance efforts compared to "Text Generation" models.

## Project Structure
The project structure is organized as follows:

* **src/:** Contains the source code for web scraping and analysis.
* **data/:** Stores the obtained CSV files containing relevant information.
* **results/:** Holds the results of the analysis.
* **README.md:** This file, explaining the project and its components.

## Implementation Details
1. **Web Scraping:**
The web scraping process involves obtaining a list of the top-20 "Text Classification" and "Text Generation" models on Hugging Face, ranked based on popularity.

2. **ML App Comparison:**
Comparison of the number of ML apps ("spaces") for each "Text Classification" and "Text Generation" model obtained in step 1.

3. **Source Code Size Comparison:**
Comparison of the source code size of the ML apps ("spaces") obtained in step 2. The source code size is extracted from the "Files" tab at the top-right of a given space's page.

4. **Results Analysis:**
Analyzing the results to confirm or reject the claim 'it is easier to develop ML applications using "Text Classification" models than applications using "Text Generation" models.

## **Assumptions and Design Choices**
1. The analysis is based on the assumption that popularity correlates with usage and developer preference.
2. The code utilizes web scraping techniques, and any changes to the structure of the Hugging Face website may require updates to the scraping logic.

## **Future Analysis**
Additional analyses that could be useful to add in the future:

1. **Performance Metrics:** Evaluate the performance metrics of the models, such as accuracy, precision, and recall.
2. **User Reviews Analysis:** Analyze user reviews or comments on Hugging Face to understand the user experience and potential issues.
3. **Training Time Comparison:** Compare the training time required for "Text Classification" and "Text Generation" models.
4. **Deployment Challenges:** Investigate deployment challenges and considerations for both types of models.

