# Claude Deep Research

Set environment variables in the `claude-dr` script appropriately, then run `./claude-dr`.


## MCPs we use and where to get your API keys

- [`@modelcontextprotocol/server-filesystem`](https://www.npmjs.com/package/@modelcontextprotocol/server-filesystem): Node.js server implementing Model Context Protocol (MCP) for filesystem operations.
- [`@modelcontextprotocol/server-brave-search`](https://www.npmjs.com/package/@modelcontextprotocol/server-brave-search): An MCP server implementation that integrates the Brave Search API, providing both web and local search capabilities.
  - Sign up for a [Brave Search API account](https://brave.com/search/api/)
  - Choose a plan (Free tier available with 2,000 queries/month)
  - Generate your API key [from the developer dashboard](https://api.search.brave.com/app/keys)
- [`@e2b/mcp-server`](https://www.npmjs.com/package/@e2b/mcp-server): A Model Context Protocol server for running code in a secure sandbox by E2B.
  - Go to [your e2b dashboard](https://e2b.dev/dashboard)
  - create a new API key
- [`mcp-server-fetch`](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch): Web content fetching and conversion for efficient LLM usage
