# BioContextAI 🧬🤖

**Enabling Composable Agentic Systems for Biomedical Research**

BioContextAI is an open-source initiative that bridges the gap between Large Language Models (LLMs) and specialized biomedical knowledge. We're building the infrastructure for reliable, composable AI agents that can access validated scientific resources without hallucinations or fragmented implementations.

## 🎯 Mission

Transform biomedical research by making AI systems more reliable, interconnected, and accessible through standardized access to domain-specific knowledge bases and tools.

## 🔬 The Challenge

Current biomedical AI systems suffer from:
- **Hallucinations** and unreliable outputs
- **Fragmented solutions** limited to specific applications
- **Lack of access** to specialized databases and validated resources
- **Reinvention overhead** - developers constantly rebuilding the same integration layers

## 🛠️ Our Solution

### Model Context Protocol (MCP) Ecosystem
We leverage the emerging [Model Context Protocol](https://modelcontextprotocol.io/) standard to create composable, interoperable biomedical AI tools that can be mixed and matched across different LLM providers and applications.

### Core Components

🗂️ **[Registry](https://github.com/biocontext-ai/registry)** - Community-driven catalog of biomedical MCP servers with rich metadata, enforcing FAIR principles and open-source standards

🖥️ **[Server](https://github.com/biocontext-ai/server)** - Production-ready MCP server providing access to essential biomedical databases

💬 **[Chat](https://biocontext.ai/chat)** - Interactive interface for testing and using MCP-enabled biomedical AI assistants

🌐 **[Website](https://github.com/biocontext-ai/website)** - Documentation, tutorials, and community resources

## 🚀 Get Started

### For Researchers
- **Try our tools**: Visit [biocontext.ai](https://biocontext.ai) to explore the registry and chat interface
- **Install locally**: `uv add biocontext_server`
- **Integrate**: Add our MCP server to your existing AI workflows

### For Developers
- **Contribute servers**: Add your biomedical tools to our registry
- **Extend functionality**: Build upon our server implementation
- **Join development**: Check our [contribution guidelines](https://biocontext.ai/docs)

## 🤝 Community

We're building a collaborative ecosystem inspired by successful bioinformatics initiatives like scverse, BioCypher, and Bioconda. Join us in advancing biomedical AI:

- **Registry contributions**: Share your MCP servers with the community
- **Code contributions**: Improve our core infrastructure
- **Documentation**: Help others learn and adopt our tools
- **Feedback**: Report issues and suggest improvements

## 📊 Repository Overview

| Repository | Description | Language | Status |
|------------|-------------|----------|---------|
| [registry](https://github.com/biocontext-ai/registry) | Community MCP server catalog | Metadata/JSON | ✅ Active |
| [server](https://github.com/biocontext-ai/server) | Core biomedical MCP server | Python | ✅ Active |
| [website](https://github.com/biocontext-ai/website) | Main website and documentation | TypeScript/Next.js | ✅ Active |
| [evaluation](https://github.com/biocontext-ai/simple-mcp-evaluation) | Benchmarking scripts | Python | ✅ Active |

## 🔗 Links

- **Website**: [biocontext.ai](https://biocontext.ai)
- **Registry**: [biocontext.ai/registry](https://biocontext.ai/registry)
- **Chat Interface**: [biocontext.ai/chat](https://biocontext.ai/chat)
- **Documentation**: [biocontext.ai/docs](https://biocontext.ai/docs)
- **Remote Server**: [mcp.biocontext.ai](https://mcp.biocontext.ai)

## 📄 Citation

Tba.
