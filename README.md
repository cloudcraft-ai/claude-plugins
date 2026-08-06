# CloudCraft plugins for Claude Code

The CloudCraft AI Labs plugin marketplace — the plugin equivalent of our
[Homebrew tap](https://github.com/cloudcraft-ai/homebrew-tap): distribution
lives here, source lives in each product's own repository.

```
/plugin marketplace add cloudcraft-ai/claude-plugins
/plugin install gitreceipts@cloudcraft
```

## Plugins

| Plugin | Source | What it does |
|---|---|---|
| **gitreceipts** | [jagmeetchawla/gitreceipts](https://github.com/jagmeetchawla/gitreceipts) | See what your agent actually did — audit a Claude Code session against git history. Requires the `git-receipts` binary (`brew install cloudcraft-ai/tap/gitreceipts` or `cargo install gitreceipts`). |
