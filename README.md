# Browserbase MCP Server

![cover](assets/cover-mcp.png)

[The Model Context Protocol (MCP)](https://modelcontextprotocol.io/introduction) is an open protocol that enables seamless integration between LLM applications and external data sources and tools. Whether you’re building an AI-powered IDE, enhancing a chat interface, or creating custom AI workflows, MCP provides a standardized way to connect LLMs with the context they need.

This server provides cloud browser automation capabilities using [Browserbase](https://www.browserbase.com/), [Puppeteer](https://pptr.dev/), and [Stagehand](https://github.com/browserbase/stagehand) (Coming Soon). This server enables LLMs to interact with web pages, take screenshots, and execute JavaScript in a cloud browser environment.

## Getting Started with available MCPs

🌐 **Browserbase MCP** - Located in [`browserbase/`](./browserbase/)

| Feature | Description |
|---------|-------------|
| Browser Automation | Control and orchestrate cloud browsers |
| Data Extraction | Extract structured data from any webpage |
| Console Monitoring | Track and analyze browser console logs |
| Screenshots | Capture full-page and element screenshots |
| JavaScript | Execute custom JS in the browser context |
| Web Interaction | Navigate, click, and fill forms with ease |

### Installing

To install the Browserbase MCP server for Claude Desktop automatically via [Smithery](https://smithery.ai/package/@browserbasehq/mcp-browserbase):

```bash
npx @smithery/cli install @browserbasehq/mcp-browserbase --client claude
```

🤘 **Stagehand MCP** - Located in [`stagehand/`](./stagehand/) *(Coming Soon)*

| Feature | Description |
|---------|-------------|
| Atomic Instructions | Execute precise actions like `act("click the login button")` or `extract("find the red shoes")` |
| Model Flexibility | Supports multiple models, including OpenAI's GPT-4 and Anthropic's Claude-3.5 Sonnet |
| Modular Design | Easily integrate new models with minimal changes |
| Vision Support | Use annotated screenshots for complex DOMs |
| Open Source | Contribute to the project and join the [Slack community](https://join.slack.com/t/stagehand-dev/shared_invite/zt-2uvuobu50-~wVSx2Si75CPa3332hwVEw) for support |

### Installing

To install the Stagehand MCP server for Claude Desktop automatically via [Smithery](https://smithery.ai/package/@browserbasehq/mcp-stagehand):

```bash
npx @smithery/cli install @browserbasehq/mcp-stagehand --client claude
```
