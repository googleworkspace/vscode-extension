# Google Workspace Developer Documentation Server

Use the tools exposed by this server to explore the latest official **Google Workspace (GWS) documentation**. This server is designed to provide the AI agent with access to technical documentation, API references, conceptual guides, tutorials, and code examples for building on the GWS platform.

---

## What is Google Workspace Development?

**Google Workspace (GWS)** is Google's suite of collaboration and productivity tools (e.g., Gmail, Docs, Sheets, Calendar).

GWS development involves building solutions to **enhance your Google Workspace development experience** and **streamline development workflows for Google Workspace APIs and integrations**. This includes:
* Writing **Google Apps Script** for automation and extension.
* Integrating external applications using **Google Workspace APIs** (like the Drive, Calendar, or Gmail APIs).
* Creating **Editor Add-ons** and **Google Workspace Add-ons**.

This extension's tools focus solely on providing the **AI agent** with the necessary official documentation to answer developer-centric questions in this domain.

---

## Provided Tools

This extension registers the following two tools with the AI agent. The agent is instructed to use these tools for any query requiring information about Google Workspace APIs, tutorials, or code examples.

### 1. `search_workspace_docs`

* **Description:** Searches the latest official Google Workspace documentation, including API references, conceptual guides, tutorials, and code examples. The agent uses this tool first to locate the most relevant documentation pages for the user's query.

### 2. `fetch_workspace_docs`

* **Description:** Fetches the full content of a Google Workspace documentation page such as those returned by the `search_workspace_docs` tool. Once a document is found, the agent uses this tool to retrieve the text content necessary to formulate a detailed, accurate answer.