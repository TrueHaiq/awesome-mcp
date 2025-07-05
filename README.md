<div align="center">

<img src="assets/banner.png" alt="Banner" />

---

[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A comprehensive collection of Model Context Protocol (MCP) servers, empowering AI models with enhanced capabilities through standardized integrations.

[Getting Started](#what-is-mcp) • [Browse Servers](#mcp-servers-list) • [Server Management](#mcp-managers)

</div>

## What is MCP?

In essence, **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/)** is a protocol designed to make LLMs more powerful by simplifying their integration with external tools and services. Instead of manually connecting different APIs and tools, MCP serves as a unified layer that simplifies the process, making LLMs more capable and scalable.

By providing a standardized way for AI models to interact with both local and remote services, MCP enables seamless integration with:

- 🔐 Secure file system access
- 📊 Database connections
- 🌐 API integrations
- 🛠️ Development tools
- 📱 Application services
- And much more...

### Local 🏠 vs Cloud ☁️ ?

- **Use Local** when the MCP server communicates with software installed locally on the system. For example, interacting with the Chrome browser or accessing files on your computer.

- **Use Cloud** when the MCP server connects to remote services or APIs. For instance, querying a database hosted on a cloud server or fetching data from an external API like a social media platform or a stock market feed.

## About this repo

This repository serves as a comprehensive, community-curated index of Model Context Protocol (MCP) servers and tools. Our goal is to help developers, AI enthusiasts, and organizations discover and leverage the growing ecosystem of MCP integrations.

Key features:

- 📚 Categorized listings of MCP servers across various domains
- ⭐ Highlighted premium and official implementations
- 🔍 Easy-to-navigate structure with clear categories
- 🤝 Active community of contributors and maintainers

Each listed server is carefully reviewed to ensure it provides value to the MCP ecosystem. While this is a community-driven list, we work closely with official implementations (like those from [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)) along with high-quality community-contributed servers that extend AI capabilities in meaningful ways.

## MCP Servers List

- 🗄️ - [Databases](#databases)
- 🌐 - [Web Automation](#web-automation)
- 💻 - [Development Tools](#development-tools)
- 📂 - [File Systems](#file-systems)
- 📝 - [Note Taking](#note-taking)
- 🗺️ - [Geography](#geography)
- 📢 - [Marketing](#marketing)
- 🔄 - [Version Control](#version-control)
- ⚙️ - [Workflow Automation](#workflow-automation)
- 🤖 - [System Automation](#system-automation)
- 📱 - [Social Media](#social-media)
- 🎮 - [Gaming](#gaming)
- 💹 - [Finance](#finance)
- 🧬 - [Research & Data](#research-data)
- 🤖 - [AI Services](#ai-services)
- 📈 - [Data Visualization](#data-visualization)
- 💬 - [Communication](#communication)
- ☁️ - [Cloud Storage](#cloud-storage)
- ⚡ - [Cloud Platforms](#cloud-platforms)

<br />

### 🗄️ <a name="databases"></a>Databases

> Secure database access with schema inspection capabilities. Enables querying and analyzing data while maintaining read-only safety by default.

- <img src="https://cdn.simpleicons.org/postgresql/5865F2" height="14"/> [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database integration with schema inspection and query capabilities
- <img src="https://cdn.simpleicons.org/sqlite/0F80CC" height="14"/> [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database operations with built-in analysis features
- <img src="https://cdn.simpleicons.org/mongodb/47A248" height="14"/> [MongoDB](https://github.com/kiliczsh/mcp-mongo-server) - A Model Context Protocol Server for querying and analyzing MongoDB collections.
- <img src="https://cdn.simpleicons.org/mongodb/47A248" height="14"/> [MongoDB Lens](https://github.com/furey/mongodb-lens) - Full featured MCP Server for MongoDB databases.
- <img src="https://cdn.simpleicons.org/mysql" height="14"/> [MySQL](https://github.com/designcomputer/mysql_mcp_server) - MySQL database integration with configurable access controls and schema inspection
- <img src="https://neon.tech/favicon.ico" height="14"/> [Neon](https://github.com/neondatabase/mcp-server-neon) - Neon MCP Server. Allows natural language interactions with Neon for database management.
- <img src="https://cdn.simpleicons.org/libreoffice/18A303" height="14"/> [Excel](https://github.com/haris-musa/excel-mcp-server) - Excel workbook manipulation including data reading/writing, worksheet management, formatting, charts, and pivot tables
- <img src="https://cdn.simpleicons.org/googlebigquery/669DF6" height="14"/> [BigQuery](https://github.com/LucasHild/mcp-server-bigquery)<sup><sup>1</sup></sup> - BigQuery database integration with schema inspection and query capabilities
- <img src="https://cdn.simpleicons.org/googlebigquery/669DF6" height="14"/> [BigQuery](https://github.com/ergut/mcp-bigquery-server)<sup><sup>2</sup></sup> - A BigQuery MCP server for read-only SQL queries and schema exploration (available on npm)
- <img src="https://cdn.simpleicons.org/airtable" height="14"/> [Airtable](https://github.com/domdomegg/airtable-mcp-server) - Read and write access to Airtable databases, with schema inspection.

<br />

### 🌍 <a name="web-automation"></a>Web Automation

> Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- <img src="https://cdn.simpleicons.org/puppeteer/00D8A2" height="14"/> [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation for web scraping and interaction
- <img src="https://cdn.simpleicons.org/brave/FB542B" height="14"/> [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Web search capabilities using Brave's Search API
- <img src="https://cdn.simpleicons.org/curl/00ADD8" height="14"/> [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Efficient web content fetching and processing for AI consumption
- <img src="https://cdn.simpleicons.org/kagi/4173FF" height="14"/> [Kagi Search](https://github.com/ac3xx/mcp-servers-kagi) - TypeScript-based MCP server that integrates the Kagi Search API
- <img src="https://www.tryleap.ai/assets/integrations/exa.svg" height="14"/> [Exa Search](https://github.com/exa-labs/exa-mcp-server)<sup><sup>⭐</sup></sup> - Integration with Exa AI Search API for real-time web information retrieval
- <img src="https://cdn.simpleicons.org/newyorktimes/E34234" height="14"/> [NYTimes](https://github.com/angheljf/nyt) - Search articles using the NYTimes API
- <img src="https://cdn.simpleicons.org/googlenews/4285F4" height="14"/> [Google News](https://github.com/ChanMeng666/server-google-news) - Google News search with automatic categorization, multi-language support, and comprehensive search options
- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Vector_search_icon.svg/800px-Vector_search_icon.svg.png" height="14"/> [Search1API](https://github.com/fatwang2/search1api-mcp) - Search via search1api (requires paid API key)
- <img src="https://tavily.com/favicon.ico" height="14"/> [Tavily](https://github.com/Tomatio13/mcp-server-tavily) - Tavily AI search API integration
- <img src="https://cdn.simpleicons.org/arxiv/B31B1B" height="14"/> [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) - Search ArXiv research papers
- <img src="https://playwright.dev/img/playwright-logo.svg" height="14"/> [Playwright](https://github.com/executeautomation/mcp-playwright) - A Model Context Protocol server that provides browser automation capabilities using Playwright.
- <img src="https://cdn.simpleicons.org/searxng" height="14"/> [Websearch](https://github.com/mnhlt/WebSearch-MCP) - Self-hosted Websearch service.

<br />

### 💻 <a name="development-tools"></a>Development Tools

> Tools and servers that assist with software development workflows. Enables integration with development-related services and APIs.

- <img src="https://www.svgrepo.com/show/107853/uranus.svg" height="14"/> [CentralMind/Gateway](https://github.com/centralmind/gateway) - MCP and MCP SSE Server that automatically generate production ready API based on database schema and data. Supports PostgreSQL, Clickhouse, MySQL, Snowflake, BigQuery, Supabase
- <img src="https://raw.githubusercontent.com/open-rpc/design/master/icons/open-rpc-logo-noText/open-rpc-logo-noText%20(PNG)/256x256.png" height="14"/> [OpenRPC](https://github.com/shanejonas/openrpc-mpc-server) - A Model Context Protocol server that provides JSON-RPC functionality through OpenRPC.
- <img src="https://cdn.simpleicons.org/postman" height="14" /> [Postman](https://github.com/delano/postman-mcp-server) - Interact with [Postman API](https://www.postman.com/postman/postman-public-workspace/).
- <img src="https://raw.githubusercontent.com/marimo-team/marimo/main/docs/_static/marimo-logotype-thick.svg" height="14" /> [marimo](https://github.com/marimo-team/codemirror-mcp)<sup><sup>⭐</sup></sup> - CodeMirror extension that implements the Model Context Protocol (MCP) for resource mentions and prompt commands.
- <img src="https://static.figma.com/app/icon/1/favicon.ico" height="14" /> [Figma](https://github.com/GLips/Figma-Context-MCP) - Paste a link to your Figma design to get its data in a ready-to-implement format.
- <img src="https://www.comet.com/favicon.ico" height="14" /> [Comet Opik](https://github.com/comet-ml/opik-mcp)<sup><sup>⭐</sup></sup> - Query and interact with LLM observability and telemetry captured by [Opik](https://github.com/comet-ml/opik) using natural language.
- <img src="https://vscode.dev/static/stable/favicon.ico" height="14" /> [VSCode Devtools](https://github.com/biegehydra/BifrostMCP) - Connect to VSCode ide and allows using semantic tools like `find_usages`

<br />

### 📂 <a name="file-systems"></a>File Systems

> Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

- <img src="https://cdn.simpleicons.org/files/4CAF50" height="14"/> [Everything Search](https://github.com/mamertofabian/mcp-everything-search) - Lightning-fast Windows file search powered by Everything SDK
- <img src="https://cdn.simpleicons.org/files/4CAF50" height="14"/> [Backup](https://github.com/hexitex/MCP-Backup-Server) - Provides file and folder backup and restoration capabilities for AI agents and code editing tools
- <img src="https://cdn.simpleicons.org/files/2196F3" height="14"/> [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)<sup><sup>1</sup></sup> - Direct local file system access
- <img src="https://cdn.simpleicons.org/files/4A90E2" height="14"/> [FileSystem](https://github.com/mark3labs/mcp-filesystem-server)<sup><sup>2</sup></sup> - Golang implementation for local file system access

<br />

### 📝 <a name="note-taking"></a>Note Taking

> Integration with note-taking applications and personal knowledge management tools. Enables access to notes, documents, and personal information stores.

- <img src="https://cdn.simpleicons.org/obsidian/7C3AED" height="14"/> [Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian)<sup><sup>1</sup></sup> - Obsidian vault integration with tools for file management, search, and content manipulation
- <img src="https://cdn.simpleicons.org/obsidian/7C3AED" height="14"/> [Obsidian](https://github.com/calclavia/mcp-obsidian)<sup><sup>2</sup></sup> - Alternative implementation for reading and searching Markdown notes
- <img src="https://cdn.simpleicons.org/notion/787878" height="14"/> [Notion](https://github.com/danhilse/notion_mcp)<sup><sup>1</sup></sup> - Notion API integration for managing personal todo lists and notes
- <img src="https://cdn.simpleicons.org/notion/787878" height="14"/> [Notion](https://github.com/suekou/mcp-notion-server)<sup><sup>2</sup></sup> - Alternative implementation for Notion API integration
- <img src="https://cdn.simpleicons.org/todoist/E44332" height="14"/> [Todoist](https://github.com/abhiz123/todoist-mcp-server) - An MCP server implementation for Todoist, enabling natural language task management.

<br />

### 🗺️ <a name="geography"></a>Geography

> Geographic and location-based services integration. Enables access to mapping data, directions, and place information.

- <img src="https://cdn.simpleicons.org/googlemaps/4285F4" height="14"/> [Google Maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Google Maps integration for location services, routing, and place details
- <img src="https://www.qgis.org/styleguide/visual/qgis-logo.svg" height="14"/> [QGIS](https://github.com/jjsantos01/qgis_mcp) - connects QGIS Desktop to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.

<br />

### 📢 <a name="marketing"></a>Marketing

> Tools that help marketers write better content and run better campaigns.

- <img src="https://openstrategypartners.com/fileadmin/Bilder/logo/OSP_logo_colors_green1.png" height="14"/> [Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools)<sup><sup>⭐</sup></sup> - a standardized editing code system, writing guidelines, web metadata generator, and product communication framework.
- <img src="https://cdn.simpleicons.org/fathom/9187FF" height="14"/> [Fathom Analytics](https://github.com/mackenly/mcp-fathom-analytics) - Access Fathom Analytics data and reports about your sites
- <img src="https://www.svgrepo.com/show/475634/amazon-color.svg" height="14"/> [Amazon Product Advertising](https://github.com/jademind/mcp-amazon-paapi) - Wraps Amazon’s Product Advertising API 5.0, providing keyword search and ASIN lookup endpoints that return products with your Associate partner-tagged URLs.

<br />

### 🔄 <a name="version-control"></a>Version Control

> Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- <img src="https://cdn.simpleicons.org/github/8A8A8A" height="14"/> [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - GitHub API integration for repository management, PRs, issues, and more
- <img src="https://cdn.simpleicons.org/gitlab/FC6D26" height="14"/> [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab platform integration for project management and CI/CD operations
- <img src="https://cdn.simpleicons.org/git/F05032" height="14"/> [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Direct Git repository operations including reading, searching, and analyzing local repositories
- <img src="https://cdn.simpleicons.org/phabricator/5865F2" height="14"/> [Phabricator](https://github.com/baba786/phabricator-mcp-server) - Phabricator API integration for repository and project management
- <img src="https://cdn.simpleicons.org/git/F05032" height="14"/> [Gitingest-MCP](https://github.com/puravparab/Gitingest-MCP) - Gitingest integration providing prompt friendly summmaries of Github repos

<br />

### ⚙️ <a name="workflow-automation"></a>Workflow Automation

> Integration with workflow automation platforms allows AI models to execute workflows and retrieve data back to their systems.

- <img src="https://www.make.com/favicon.ico" height="14"/> [Make](https://github.com/integromat/make-mcp-server)<sup><sup>⭐</sup></sup> - Turn Make scenarios into callable tools for AI assistants.

<br />

### 🤖 <a name="system-automation"></a>System Automation

> Tools for shell access, system control, and task automation. Enables AI models to execute commands and interact with the operating system.

- <img src="https://api.iconify.design/mdi:console.svg?color=%2390EE90" height="14"/> [Shell](https://github.com/rusiaaman/wcgw) - Autonomous shell execution and computer control (Mac)
- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Windows_logo_-_2021.svg/1024px-Windows_logo_-_2021.svg.png" height="14"/> [Windows CLI](https://github.com/SimonB97/win-cli-mcp-server) - Windows CLI MCP Server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells.
- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Windows_logo_-_2021.svg/1024px-Windows_logo_-_2021.svg.png" height="14"/> [Windows Control](https://github.com/Cheffromspace/nutjs-windows-control) - Windows automation MCP server providing mouse, keyboard, screen capture, clipboard, and window management capabilities using NutJS.
- <img src="https://cdn.simpleicons.org/gnometerminal/2196F3" height="14"/> [Command Line](https://github.com/phialsbasement/cmd-mcp-server) - MCP server allowing any and all command execution over CMD(BE CAREFUL).
- <img src="https://cdn.simpleicons.org/apple/999999" height="14"/> [Apple Shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) - An MCP Server Integration with Apple Shortcuts

<br />

### 📱 <a name="social-media"></a>Social Media

> Integration with social media platforms and content sharing services. Enables interaction with social networks and content platforms.

- <img src="https://cdn.simpleicons.org/youtube/FF0000" height="14"/> [YouTube](https://github.com/anaisbetts/mcp-youtube)<sup><sup>1</sup></sup> - YouTube integration using yt-dlp for subtitle downloading and video analysis
- <img src="https://cdn.simpleicons.org/youtube/FF0000" height="14"/> [YouTube](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript)<sup><sup>2</sup></sup> - Alternative implementation for fetching YouTube subtitles and transcripts
- <img src="https://cdn.simpleicons.org/spotify/1DB954" height="14"/> [Spotify](https://github.com/varunneal/spotify-mcp) - Connects with Spotify for playback control and track/album/artist/playlist management.
- <img src="https://cdn.worldvectorlogo.com/logos/tiktok-icon-2.svg" height="14"/> [TikTok](https://github.com/Seym0n/tiktok-mcp) - TikTok integration for getting post details and video's subtitles

<br />

### 🎮 <a name="gaming"></a>Gaming

> Gaming data and Game Development tools.

- <img src="https://cdn.simpleicons.org/unity/899499" height="14"/> [Unity3d](https://github.com/CoderGamester/mcp-unity) - Unity3d Game Engine integration for game development

<br />

### 💹 <a name="finance"></a>Finance

> Financial data and cryptocurrency information services.

- <img src="https://731523176-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaVUBXRZbpAgtjYf5HsvO%2Fuploads%2FaRRrVVocXCTr6GkepfCx%2Flogo_color.svg?alt=media&token=3ba24089-0ab2-421f-a9d9-41f2f94f954a" height="14"/> [Armor Crypto MCP](https://github.com/armorwallet/armor-crypto-mcp)<sup><sup>⭐</sup></sup> - MCP to interface with multiple blockchains, staking, DeFi, swap, bridging, wallet management, DCA, Limit Orders, Coin Lookup, Tracking and more.
- <img src="https://cdn.simpleicons.org/coinmarketcap/FF8C00" height="14"/> [CoinMarket](https://github.com/anjor/coinmarket-mcp-server) - Coinmarket API integration for cryptocurrency data
- <img src="https://www.chargebee.com/static/resources/brand/favicon.png" height="14"> [Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol)<sup><sup>⭐</sup></sup> - MCP Server that connects AI agents to [Chargebee platform](https://www.chargebee.com).
- <img src="https://cdn.simpleicons.org/stripe" height="14"/> [Stripe](https://github.com/stripe/agent-toolkit/tree/main)<sup><sup>⭐</sup></sup> - Allows you to integrate with Stripe APIs

<br />

### 🧬 <a name="research-data"></a>Research & Data

> Access to research papers, genetic data, and specialized datasets.

- <img src="https://cdn.simpleicons.org/arxiv/B31B1B" height="14"/> [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) - Search ArXiv research papers
- <img src="https://api.iconify.design/mdi:dna.svg?color=%23E34234" height="14"/> [Ancestry](https://github.com/reeeeemo/ancestry-mcp) - Read .ged files and genetic data

<br />

### 🤖 <a name="ai-services"></a>AI Services

> Integration with AI and machine learning services.

- <img src="https://cdn.simpleicons.org/openai/00A67E" height="14"/> [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) - Query OpenAI models directly from Claude using MCP protocol
- <img src="https://cdn.simpleicons.org/openai/00A67E" height="14"/> [OpenAI Compatible Chat](https://github.com/pyroprompts/any-chat-completions-mcp) - Chat with models from OpenAI-compatible APIs (Perplexity, Groq, xAI, etc.)
- <img src="https://cdn.simpleicons.org/perplexity" height="14"/> [Perplexity](https://github.com/tanigami/mcp-server-perplexity) Chat with Perplexity via MCP
- <img src="https://cloud.llamaindex.ai/favicon.ico" height="14"/> [LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud) - LlamaCloud MCP Server. A TypeScript-based MCP server connecting to a managed index on LlamaCloud.
- <img src="https://huggingface.co/favicon.ico" height="14"/> [HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace) - Use HuggingFace spaces from your MCP Client. Supports Images, Audio, Text and more.
- <img src="https://www.chronulus.com/favicon/chronulus-logo-blue-on-alpha-square-128x128.ico" alt="Chronulus AI Logo" height="14" width="14"> [Chronulus AI](https://github.com/ChronulusAI/chronulus-mcp) - Predict anything with Chronulus AI multimodal forecasting and prediction agents ([Watch Demos on Youtube](https://youtube.com/playlist?list=PLPLu09ZbT8KKS04V6SSm2Acjv43FKq329&si=n2YER2in4gOqwssY)).
- <img src="https://www.svgrepo.com/show/495208/data.svg" height="14"/> [ZenML](https://github.com/zenml-io/mcp-zenml) - Chat with your MLOps and LLMOps pipelines using the [ZenML](https://www.zenml.io) MCP server

<br />

### 📊 <a name="data-visualization"></a>Data Visualization

> Tools for creating and managing data visualizations. Enables generation of charts, graphs, and other visual representations of data.

- <img src="https://vega.github.io/favicon.ico" height="14"/> [VegaLite](https://github.com/isaacwasserman/mcp-vegalite-server) - Generate visualizations from fetched data using the VegaLite format and renderer

<br />

### 💬 <a name="communication"></a>Communication

> Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

- <img src="https://cdn.simpleicons.org/slack/E01E5A" height="14"/> [Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Slack workspace integration for channel management and messaging

<br />

### ☁ <a name="cloud-storage"></a>Cloud Storage

> Access and manage files stored in cloud storage platforms. Enables searching, reading, and organizing cloud-stored documents and data.

- <img src="https://cdn.simpleicons.org/googledrive/4285F4" height="14"/> [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive integration for file access, search, and management

<br />

### ⚡ <a name="cloud-platforms"></a>Cloud Platforms

> Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

- <img src="https://cdn.simpleicons.org/cloudflare/F38020" height="14"/> [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) - Integration with Cloudflare services including Workers, KV, R2, and D1
- <img src="https://cdn.simpleicons.org/kubernetes/326CE5" height="14"/> [Kubernetes](https://github.com/strowk/mcp-k8s-go) - Kubernetes cluster operations through MCP

<br />

### MCP Managers

- [mcp-get](https://github.com/michaellatman/mcp-get) - CLI tool for installing and managing MCP servers. Simplifies server installation and configuration for Claude Desktop.
- [Remote MCP](https://github.com/ssut/Remote-MCP) - Solution to Remote MCP Communication, enabling effortless integration for centralized management of Model Context

<br />

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TrueHaiq/awesome-mcp&type=Date)](https://www.star-history.com/#TrueHaiq/awesome-mcp&Date)

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.
