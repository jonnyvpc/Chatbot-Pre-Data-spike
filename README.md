# Financial Data Analysis for AI-Powered Chatbot Project

This project focuses on developing an AI-powered chatbot to revolutionize financial data analysis for Global Finance Corp. (GFC). The chatbot will analyze and provide insights on corporate financial performance from 10-K and 10-Q financial documents.

## Project Overview

The project involves the following steps:
1. **Data Extraction**: Extract key financial data from 10-K reports.
2. **Data Preparation**: Clean and format the extracted data.
3. **Data Analysis**: Analyze the financial data to identify trends and indicators.
4. **Data Visualization**: Create visualizations to represent the financial data.
5. **Summary and Conclusions**: Provide insights into the financial health of the analyzed companies.

## How to Extract Data from EDGAR

Follow these steps to extract 10-K and 10-Q data from the SEC's EDGAR database:

### Step 1: Navigate to the EDGAR Database

Go to the [SEC EDGAR Database](https://www.sec.gov/edgar/searchedgar/companysearch.html).

![Step 1: Navigate to EDGAR](https://github.com/jonnyvpc/Chatbot-Pre-Data-spike/blob/main/screenshots/1edgar_ss@1x.png?raw=true)

### Step 2: Search for a Company

Enter the company name or ticker symbol in the search bar and click "Search".

![Step 2: Search for Company](https://github.com/jonnyvpc/Chatbot-Pre-Data-spike/blob/main/screenshots/2edgar_search@1x.png?raw=true)

### Step 3: Select the Filing Type

Select the "10-K" or "10-Q" filing type from the filter options.

![Step 3: Select Filing Type](https://github.com/jonnyvpc/Chatbot-Pre-Data-spike/blob/main/screenshots/3edgar_Select%20the%20Filing%20Type@1x.png?raw=true)

### Step 4: Download the Report

To help you sort quicker, click the arrows near the File Type. This helps you sort the File Type names.

![Step 4: Download Report](https://github.com/jonnyvpc/Chatbot-Pre-Data-spike/blob/main/screenshots/4edgar_hover@1x.png?raw=true)

Click on the document link to download the 10-K or 10-Q report.

![Step 4: Download Report](https://github.com/jonnyvpc/Chatbot-Pre-Data-spike/blob/main/screenshots/5edgar_Click%20on%20the%20document%20link%20to%20download%20the%2010-K%20or%2010-Q%20report@1x.png?raw=true)

## Repository Contents

- `Task One.ipynb`: Jupyter Notebook containing the data analysis and visualizations.
- `Cleaned_Financial_Data.csv`: CSV file containing the cleaned financial data.
- `LICENSE`: MIT License file.

## Usage

To run the notebook:
1. Clone the repository.
2. Navigate to the repository directory.
3. Open the notebook using Jupyter Notebook.

```sh
git clone https://github.com/jonnyvpc/Chatbot-Pre-Data-spike.git
cd Chatbot-Pre-Data-spike
jupyter notebook Task\ One.ipynb
