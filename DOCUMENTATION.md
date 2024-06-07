## AI-Powered Financial Chatbot

### Overview

This AI-powered financial chatbot provides insights into key financial metrics based on predefined queries. It leverages a simple rule-based logic to interpret user queries and return relevant financial data.

### How It Works

1. **Data Loading**: The chatbot loads financial data from a CSV file (`Cleaned_Financial_Data.csv`).
2. **Rule-Based Responses**: The chatbot uses `if-else` statements to match user queries with predefined responses.
3. **Flask Web Server**: A Flask web server is used to handle HTTP POST requests, enabling interaction with the chatbot through JSON queries.

### Predefined Queries

The chatbot can respond to the following queries:
1. **What is the total revenue?**
   - **Response**: The chatbot returns the total revenue by summing up the 'Total Revenue' column from the financial data.
   
2. **How has net income changed over the last year?**
   - **Response**: The chatbot calculates the change in net income over the last year by comparing the 'Net Income' values from the last two years in the dataset.

### Error Handling

- **Invalid Queries**: If a user asks a question that is not predefined, the chatbot responds with: "Sorry, I can only provide information on predefined queries."

### Limitations

- **Predefined Queries Only**: The chatbot can only handle a fixed set of queries. Any query outside this set will receive a generic error response.
- **Static Data**: The financial data is loaded from a static CSV file. Any changes to the data require updating the CSV file and restarting the server.

### Example Usage

**Request**:
```sh
curl -X POST http://127.0.0.1:5000/chatbot -H "Content-Type: application/json" -d '{"query": "What is the total revenue?"}'
