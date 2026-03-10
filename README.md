**MCP-document-agent**

A conversational AI agent built with Anthropic's Model Context Protocol (MCP) that reads and edits documents through natural language, powered by Claude.


What It Does
Chat naturally with your documents. Ask Claude to read, summarize, reformat, or edit any document — it uses MCP tools and resources under the hood to get it done.

**Features**

MCP Tools — read_doc_contents, edit_document

MCP Resources — docs://documents (list all docs), docs://documents/{doc_id} (fetch a doc)

MCP Prompts — reformat a doc in markdown, summarize a doc

CLI Chat Interface — interactive terminal chat with @mention support for documents

Claude-powered — full agentic loop with tool use via Anthropic API

**Setup**

1. Clone the repo
bashgit clone https://github.com/YOUR_USERNAME/mcp-document-agent
cd mcp-document-agent

2. Create and activate a virtual environment
bashuv venv
# Windows:
.venv\Scripts\activate

3. Install dependencies
bashuv pip install -r requirements.txt --index-url https://pypi.org/simple