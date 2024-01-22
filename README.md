# Hugging Face ML Models Analysis with Selenium, Python, and SQL
This project focuses on evaluating the ease of use of machine learning (ML) applications, specifically in the domains of "Text Classification" and "Text Generation." The analysis is conducted on models available in the Hugging Face ML store. Leveraging web scraping with Selenium in Python, the project extracts relevant data from the Hugging Face website. Subsequently, SQL and PL-SQL are employed for processing and deriving meaningful insights from the acquired data.

## Project Structure
The project structure is organized as follows:

* Contains the source code for web scraping and analysis.
* Stores the obtained CSV files containing relevant information.
* Holds the results of the analysis.

## Implementation Details
1. **Web Scraping with Selenium:**
Selenium, a powerful web testing tool, is utilized for web scraping to gather information on the top-20 "Text Classification" and "Text Generation" models from Hugging Face. This step involves navigating through web pages, extracting relevant details, and storing them for further analysis.

2. **Data Processing with Python:**
Python is employed for processing the scraped data. The code is structured to handle data cleaning, manipulation, and preparation for subsequent analysis. Comments are included to provide clarity on the code logic and any assumptions made during the process.

3. **SQL and PL-SQL Analysis:**
The processed data is then loaded into a SQL database, where PL-SQL (Procedural Language-SQL) is employed to perform intricate analyses. SQL queries are crafted to compare the number of ML apps ("spaces") for each "Text Classification" and "Text Generation" model. Additionally, the source code size of the ML apps is extracted and compared, shedding light on potential differences in coding efforts.

4. **Results Interpretation:**
The final step involves interpreting the results obtained from the SQL and PL-SQL analyses. Insights are drawn to either confirm or reject the claim that 'it is easier to develop ML applications using "Text Classification" models than applications using "Text Generation" models.' The README file provides a detailed breakdown of the results and the implications of the findings.

## **Assumptions and Design Choices**
1. The analysis is based on the assumption that popularity correlates with usage and developer preference.
2. The code utilizes web scraping techniques, and any changes to the structure of the Hugging Face website may require updates to the scraping logic.

## **Future Analysis**
Additional analyses that could be useful to add in the future:

1. **Performance Metrics:** Evaluate the performance metrics of the models, such as accuracy, precision, and recall.
2. **User Reviews Analysis:** Analyze user reviews or comments on Hugging Face to understand the user experience and potential issues.
3. **Training Time Comparison:** Compare the training time required for "Text Classification" and "Text Generation" models.
4. **Deployment Challenges:** Investigate deployment challenges and considerations for both types of models.

