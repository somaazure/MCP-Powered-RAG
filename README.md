# Build an MCP server for RAG over comple real world docs

This server leverages [GroundX](https://eyelevel.ai/)'s state-of-the-art document search and retrieval capabilities.

You can quickly test it on your own complex docs [here](https://eyelevel.ai/).

### Setup

To sync dependencies, run:

```sh
uv sync
```

### Environment Variables

You need to set up the following environment variables:

```sh
GROUNDX_API_KEY=...
```
[Get your GroundX API keys here](https://eyelevel.ai/)

Ensure these variables are configured correctly before running the application use `.env.example` as reference and create your own `.env` file.
