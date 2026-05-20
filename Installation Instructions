Installation Instructions
Requirements
Node.js v18 or higher
n8n (installed via npm or Docker)
urlscan.io API key (https://urlscan.io/user/signup)
OpenAI API key (https://platform.openai.com/api-keys)
Step 1 – Install and Start n8n

Install n8n globally:

npm install -g n8n

Start n8n:

n8n start

Open in browser:

http://localhost:5678
Step 2 – Import Workflow

In the n8n interface:

Go to Workflows
Click Import from File
Upload privacy_scanner.json from this repository
Step 3 – Configure API Keys

In n8n credentials:

urlscan.io

Type: HTTP Header Auth
Header name: API-Key
Value: your urlscan.io API key

OpenAI

Add your OpenAI API key using OpenAI credentials
Step 4 – Assign Credentials

Open the workflow and assign:

urlscan.io credentials to the HTTP request node
OpenAI credentials to the AI Agent node
Step 5 – Run the Workflow
Activate the workflow (toggle top right)
Open the Chat interface in n8n
Enter a URL to start analysis
Example Input
https://bbc.co.uk
Output
Privacy risk classification
Number of trackers
AI-generated summary report
Notes
Some websites may block automated scanning
API rate limits may delay results
Ensure both API keys are valid before running the workflow
