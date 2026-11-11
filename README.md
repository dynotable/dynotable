# DynoTable

The DynamoDB and OpenSearch GUI with real SQL & your AI agent.

DynoTable is a desktop app for Amazon DynamoDB and Amazon OpenSearch Service. It runs on macOS (Apple Silicon and Intel), Windows and Linux (deb, rpm, AppImage).

<a href="https://dynotable.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets.dynotable.app/docs/en-US/overview-window.dark.webp?v=db3e0777f271">
    <img alt="The DynoTable window with a DynamoDB table open in Visual mode" src="https://assets.dynotable.app/docs/en-US/overview-window.webp?v=54de7dc4bd5c">
  </picture>
</a>

- **SQL Workbench.** Run SQL with JOIN, GROUP BY and aggregates over DynamoDB tables and OpenSearch indices. One query can join a DynamoDB table to an OpenSearch index. Queries stay within DynamoDB's access-pattern rules.
- **OpenSearch on your AWS profile.** Open Amazon OpenSearch Service domains and OpenSearch Serverless collections. DynoTable signs every request with your AWS profile, SSO included.
- **Staged changes.** Review the diff of your edits, then commit all of them or only some. On OpenSearch domains, DynoTable checks the document version before it writes.
- **AI agent on your own Amazon Bedrock.** The agent stages its edits for your review. It cannot write to your tables directly.
- **Built-in MCP server.** Connect Claude Code, Codex or Cursor to your tables and indices.
- **Vector search.** Create a DynamoDB vector index and search it with a sentence, a raw vector or Find similar.
- **In your editor and terminal.** A VS Code extension and a CLI for coding agents. The agent never holds your AWS credentials.

Your table data goes only between the app and your AWS account. It never touches a DynoTable server.

## Install

Download the installer for your platform from [dynotable.com/download](https://dynotable.com/download).

On Windows, you can also install it with winget:

```
winget install DynoTable.DynoTable
```

## Links

- [Documentation](https://dynotable.com/docs)
- [Pricing](https://dynotable.com/pricing)
- [Changelog](https://dynotable.com/changelog)

## Report a bug

[Open an issue](https://github.com/dynotable/dynotable/issues/new/choose). For questions and ideas, use [Discussions](https://github.com/dynotable/dynotable/discussions). To report a security problem, read [SECURITY.md](SECURITY.md) first.

## About this repository

DynoTable is closed source. This repository holds releases, issues and discussions only.
