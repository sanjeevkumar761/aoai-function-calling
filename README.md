# Azure OpenAI Function Calling
Examples to use function calling with Azure OpenAI GPT-4 model.  

Example 1: Invokes SQL Stored Procedure on Azure SQL database using Function Calling.  

You can use VS Code to run this.  

1. Create python venv using "python venv -m YOUR VENV NAME"  

2. Prepare .env file with the values for following variables:  
AZURE_OPENAI_ENDPOINT=  
AZURE_OPENAI_API_KEY=  
SQL_DB_USER=  
SQL_DB_PASSWORD=  
SQL_DB_URL=  
SQL_DB_NAME=  

3. Use pip install to install the required moduels such as openai, dotenv, pyodbc etc.


