# DynoTable

The DynamoDB and OpenSearch GUI with real SQL & your AI agent.

DynoTable is a desktop app for Amazon DynamoDB and Amazon OpenSearch Service. It runs on macOS (Apple Silicon), Windows and Linux.

<a href="https://dynotable.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets.dynotable.app/docs/en-US/overview-window.dark.webp?v=db3e0777f271">
    <img alt="The DynoTable window with a DynamoDB table open in Visual mode" src="https://assets.dynotable.app/docs/en-US/overview-window.webp?v=54de7dc4bd5c">
  </picture>
</a>

- **SQL Workbench.** Run SQL with JOIN and GROUP BY over DynamoDB tables and OpenSearch indices, within DynamoDB's access-pattern rules.
- **Staged changes.** Review the diff of your edits, then commit all of them or only some.
- **AI agent on your own Amazon Bedrock.** The agent stages its edits for your review. It cannot write to your tables directly.
- **Built-in MCP server.** Connect Claude Code, Codex or Cursor to your tables and indices.

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
