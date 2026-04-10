# DevBot: AI-Powered GitHub Code Reviewer (n8n)

DevBot is an automated workflow built using **n8n** that monitors GitHub Pull Requests and uses **Google Gemini AI** to provide instant, professional code reviews.

## Features
- **Real-time Monitoring:** Uses GitHub Webhooks to detect new or updated Pull Requests.
- **Automated Diff Parsing:** Fetches code changes directly from GitHub.
- **AI-Powered Insights:** Uses Gemini 1.5 Flash to identify bugs, syntax errors, and optimization opportunities.
- **Auto-Commenting:** Posts the AI review directly back to the GitHub PR discussion.

## Tech Stack
- **Automation:** n8n
- **AI Model:** Google Gemini (Generative AI)
- **API:** GitHub REST API

## How to Use
1. **Import Workflow:** Download the `workflow.json` file and import it into your n8n instance.
2. **Setup Credentials:**
   - Add your `GitHub Personal Access Token` with `repo` scope.
   - Add your `Google Gemini API Key`.
3. **Configure Webhook:** Copy the n8n Webhook URL and add it to your GitHub repository settings under 'Webhooks'.
4. **Activate:** Save and activate the workflow.
