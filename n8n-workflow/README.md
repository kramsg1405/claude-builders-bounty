# n8n Weekly Dev Summary Workflow

Automated workflow that triggers every Friday at 5 PM, fetches merged PRs and closed issues from GitHub, calls the Claude API to generate a narrative summary, and delivers the result.

## Setup
1. Import `workflow.json` into n8n.
2. Configure your GitHub credentials and Anthropic Claude API key.
3. Set the target repository in the HTTP Request node.
