![Workflow thumbnail](assets/thumbnail.webp)

![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Audio Transcription & Chat Bot with AssemblyAI, Gemini, and Pinecone RAG

Advanced n8n automation for Audio Transcription & Chat Bot with AssemblyAI, Gemini, and Pinecone RAG.

## Overview
- Category: Document Extraction, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Transform audio files into searchable knowledge with automated transcription, summaries, and AI chat. Organize, track, and retrieve audio easilylearn more!

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `@n8n/n8n-nodes-langchain.embeddingsGoogleGemini`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `@n8n/n8n-nodes-langchain.vectorStorePinecone`
- `n8n-nodes-base.convertToFile`
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.googleSheets`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.if`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.wait`

## Author

Murtaza Baig

## Screenshots

![Screenshot](assets/10404-export-icon-metadata-from-iconfinder-to-html---csv-with-previews.webp)
![Screenshot](assets/5449-automate-sales-cold-calling-pipeline-with-apify--gpt-4o--and-whatsapp.webp)
![Screenshot](assets/Screenshot_2025_06_29_at_15_43_00_b539ee8b6f.png)
![Screenshot](assets/n8nworfklows.webp)
![Screenshot](assets/thumbnail.webp)

## License
MIT License. See `LICENSE`.