# Awesome Gemini CLI Extensions

[**Gemini CLI**](https://github.com/google-gemini/gemini-cli) has a feature called "extensions" which lets you bundle custom prompts, GEMINI.md files, commands, and even themes, in a Git repository, that you can install via the `gemini extension install <url>` command.

**👉 See also: [Awesome Gemini CLI](https://github.com/Piebald-AI/awesome-gemini-cli)**

## Contents

- [Image Generation](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#image-generation)
- [Multimodal Input](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#multimodal-input)
- [Automation & Remote Access](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#automation--remote-access)
- [Databases (Google Cloud)](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#databases-google-cloud)
- [Databases (General)](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#databases-general)
  - [Observability & Monitoring](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#observability--monitoring)
- [Data & Analytics](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#data--analytics)
- [App Development](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#app-development)
- [Cloud & Dev Tools](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#cloud--dev-tools)
- [Development](https://github.com/Piebald-AI/awesome-gemini-cli-extensions?tab=readme-ov-file#development)

## Image Generation & Rendering

- [nanobanana](https://github.com/gemini-cli-extensions/nanobanana) - Generate and manipulate images using the Gemini 2.5 Flash Image model (Nano Banana).
- [Blender](https://github.com/xprilion/gemini-cli-blender-extension) - A super simple extension to enable Blender via MCP for Gemini CLI.

## Multimodal Input

- [Vision](https://github.com/automateyournetwork/GeminiCLI_Vision_Extension) - Webcam access with single frame capture and ASL modes.
- [Talk](https://github.com/automateyournetwork/GeminiCLI_Talk_Extension) - Voice input and audio output; uses OpenAI for TTS currently.

## Automation & Remote Access

- [Listen](https://github.com/automateyournetwork/GeminiCLI_Listen_Extension) - Run Gemini-CLI as a server with /listen commands.
- [Screenshare](https://github.com/automateyournetwork/GeminiCLI_ScreenShare_Extension) - Screen sharing via MCP and custom slash commands.
- [pyATS](https://github.com/automateyournetwork/pyATS_GeminiCLI_Extension) - pyATS integration for network testing.

## 3rd-Party Services

- [Figma](https://github.com/figma/figma-gemini-cli-extension) - Official Figma extension for Gemini CLI.
- [Google Fonts](https://github.com/rodydavis/google-fonts-gemini-cli-extension) - Gemini CLI extension for Google Fonts + Material Icons and Symbols.
- [GitLab](https://github.com/GitLab-Ecosystem/Gemini-CLI-Extensions) - Exposes custom `/gitlab:*` commands that map directly to GitLab's documented MCP tools for issues, merge requests, pipelines, and search.

## Development


- [Plan commands](https://github.com/jjdelorme/plan-commands) - Gemini CLI Extension with Custom Commands for plan, refine, implement.
- [Jules](https://github.com/gemini-cli-extensions/jules) - Allows you to use the Gemini CLI to orchestrate the Jules asynchronous agent to perform coding tasks like bug fixing, refactoring, and dependency updates.
- [adk-docs-ext](https://github.com/derailed-dash/adk-docs-ext) - ADK Docs Extension for Gemini CLI.
- [flutter](https://github.com/gemini-cli-extensions/flutter) - Help Gemini CLI create, build, test, and run Flutter apps.
- [Firebase](https://github.com/gemini-cli-extensions/firebase) - Give the Gemini CLI more Firebase-specific capabilities and expertise.
- [Firestore Native](https://github.com/gemini-cli-extensions/firestore-native) - Provides a set of tools to interact with Firestore databases. It allows you to manage your databases, documents, and collections directly from the Gemini CLI, using natural language prompts.

## Cloud & Dev Tools

- [gcloud](https://github.com/gemini-cli-extensions/gcloud) - gcloud Gemini CLI Extension.
- [genkit](https://github.com/gemini-cli-extensions/genkit) - Extension https://genkit.dev/.
- [MCP Toolbox](https://github.com/gemini-cli-extensions/mcp-toolbox) - Develop and query your custom tools using the power of natural language, directly from your command line through MCP Toolbox. Go from an idea to a running, invocable tool in minutes, without ever leaving your terminal.

## Databases

- [AlloyDB](https://github.com/gemini-cli-extensions/alloydb) - Instantly manage and query your AlloyDB for PostgreSQL databases.
- [Google Cloud Spanner](https://github.com/gemini-cli-extensions/spanner) - Provides a set of tools to interact with Google Cloud Spanner instances.
- [Google Cloud SQL for MySQL](https://github.com/gemini-cli-extensions/cloud-sql-mysql) - Provides a set of tools to interact with Cloud SQL for MySQL instances.
- [Google Cloud SQL for PostgreSQL](https://github.com/gemini-cli-extensions/cloud-sql-postgresql) - Provides a set of tools to interact with Cloud SQL for PostgreSQL instances.
- [Google Cloud SQL for SQL Server](https://github.com/gemini-cli-extensions/cloud-sql-sqlserver) - Provides a set of tools to interact with Cloud SQL for SQL Server instances.
- [Elasticsearch](https://github.com/elastic/gemini-cli-elasticsearch) - Official (experimental) Elasticsearch extension for Gemini CLI.
- [mysql](https://github.com/gemini-cli-extensions/mysql) - Provides a set of tools to interact with MySQL instances.
- [postgres](https://github.com/gemini-cli-extensions/postgres) - Provides a set of tools to interact with PostgreSQL instances.
- [sql-server](https://github.com/gemini-cli-extensions/sql-server) - Provides a set of tools to interact with Microsoft SQL Server instances.

### Observability & Monitoring

- [Google Cloud Observability](https://github.com/gemini-cli-extensions/observability) - Connects Gemini CLI to Cloud Observability APIs with an Model Context Protocol (MCP) server to search for logs, view metrics, return traces and view error reports.
- [AlloyDB Observability](https://github.com/gemini-cli-extensions/alloydb-observability) - Provides a set of tools to interact with AlloyDB for PostgreSQL monitoring metrics.
- [Cloud SQL for MySQL Observability](https://github.com/gemini-cli-extensions/cloud-sql-mysql-observability) - Provides a set of tools to interact with Cloud SQL for MySQL monitoring metrics.
- [Cloud SQL PostgreSQL Observability](https://github.com/gemini-cli-extensions/cloud-sql-postgresql-observability) - Provides a set of tools to interact with Cloud SQL for PostgreSQL monitoring metrics.
- [Cloud SQL SQL Server Observability](https://github.com/gemini-cli-extensions/cloud-sql-sqlserver-observability) - Provides a set of tools to interact with Cloud SQL for SQL Server monitoring metrics.

## Data & Analytics

- [BigQuery Conversational Analytics](https://github.com/gemini-cli-extensions/bigquery-conversational-analytics) - Developers can effortlessly connect, interact, and generate data insights with BigQuery datasets and data using natural language commands.
- [BigQuery Data Analytics](https://github.com/gemini-cli-extensions/bigquery-data-analytics) - Developers can effortlessly connect, interact, and generate data insights with BigQuery datasets and data using natural language commands.
- [Dataplex](https://github.com/gemini-cli-extensions/dataplex) - Provides a set of tools to interact with Dataplex instances. It allows you to manage your data lakes, zones, and assets directly from the Gemini CLI, using natural language prompts.
- [Looker](https://github.com/gemini-cli-extensions/looker) - Provides a set of tools to interact with Looker instances. It allows you to manage your Looks, dashboards, and explores directly from the Gemini CLI, using natural language prompts.

## Development

- [code-review](https://github.com/gemini-cli-extensions/code-review) - Google’s Code Review extension for the Gemini CLI that reviews your code changes.
- [security](https://github.com/gemini-cli-extensions/security) - Google’s Security extension for the Gemini CLI that finds vulnerabilities in your code changes and pull requests.
