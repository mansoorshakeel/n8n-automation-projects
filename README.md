# n8n Automation Projects

Two n8n workflows for real-world automation:

(1) Please find the Loom video where I explain the workflow Automating Book Creation using *AI & Supabase*: Architecture & Demo:      
    https://www.loom.com/share/f15b5e336a9646a598ed50593a4b7bf4 

(2) Please find the Loom video where I explain the workflow *Automating News Retrieval and Summarization Workflow with AI*:    
    https://www.loom.com/share/3de0d44c1fe04b6192152d4c849e9ada. 
    Thank you!

## 1) Advanced Book Generation with Supabase
- Use google sheet for outline notes then used serpapi for articles
- Uses AI to generate long-form book content
- Stores structured outputs (chapters/sections/metadata) in Supabase
- Generate Summary Using LLM
- 

## 2) AI News Retrieval & Summarization via WhatsApp
- Use postman to send post request to webhook and recieved output
- Retrieves news from sources (RSS/API)
- Summarizes using AI
- Sends a digest to WhatsApp

## Import into n8n
1. Open n8n → Workflows → **Import from File**
2. Select a JSON from `workflows/`
3. Set up credentials (Supabase / AI provider / WhatsApp provider)
4. Activate the workflow

## Security
Credentials and API keys are not included in this repository.
