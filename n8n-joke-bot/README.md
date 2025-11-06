# n8n Joke Bot Workflow

A simple n8n workflow that fetches random programming jokes using a GROQ Chat Model and an HTTP Request tool.

## How to Use

1. Download `joke_bot_workflow.json`.
2. Open n8n → click **Import Workflow**.
3. Select the JSON file and import.
4. Update the **GROQ Chat Model node** with your own GROQ API credentials.
5. Run the workflow and send a chat message like:
   `"Tell me a joke!"`

The bot will reply with a random joke fetched from the HTTP Request tool.

## Notes

* Replace the GROQ credentials with your own — the workflow won’t work with the included placeholder credentials.
* The HTTP Request tool uses a public joke API — no authentication required.
* You can customize the workflow or connect it to chat platforms like Telegram, Discord, or Slack.
