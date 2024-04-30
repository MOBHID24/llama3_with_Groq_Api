# Email Processing with CrewAI and LangChain
This notebook demonstrates how to use CrewAI and LangChain to process emails automatically. CrewAI is a Python library for building and orchestrating multi-agent workflows, while LangChain provides natural language processing tools.

In this notebook, we'll build a simple email processing application that categorizes, researches, and drafts responses to incoming emails. We'll use CrewAI to orchestrate the workflow and LangChain for natural language processing tasks.

## Features:
Email Categorization: Categorize incoming emails into different categories such as price inquiry, customer complaint, product inquiry, etc.
Information Research: Based on the email category, research the required information to respond to the email effectively.
Email Drafting: Draft a response email that addresses the customer's concerns or inquiries based on the categorized email and research findings.
## Components:
Agents: We'll define three types of agents:
Email Categorizer Agent
Info Researcher Agent
Email Writer Agent
## Tasks: Each task represents a step in the email processing workflow:
Categorize Email
Research Information for Email
Draft Email
## Libraries Used:
CrewAI: For building and orchestrating workflows.
LangChain: For natural language processing tasks.
DuckDuckGo Search Tool: For web search functionality.
## Usage:
Run the notebook cell by cell to see how the email processing application works.
Input the email content in the designated area.
Click the "Process Email" button to start the processing workflow.
View the output results, including categorized email, research findings, and the drafted email response.
## Note:
Make sure to set up the necessary environment variables, such as GROQ_API_KEY, before running the notebook.
Ensure you have installed the required libraries mentioned in the notebook.
Feel free to explore and modify the notebook according to your needs!
