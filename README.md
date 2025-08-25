# bowie-cli
bowie CLI is an open-source interactive CLI tool that provides a flexible and powerful interface for AI-assisted workflows.

## Quick Start

```bash
npm i -g bowie-cli
bowie
```

## Environment Variables

### Provider Configuration

| Provider | Environment Variable | Description | Example |
|----------|---------------------|-------------|---------|
| Grok (xAI) | `XAI_API_KEY` | API key for Grok AI | `export XAI_API_KEY="your_grok_api_key"` |
| Grok (xAI) | `XAI_MODEL` | Specific Grok model to use | `export XAI_MODEL="grok-4-0709"` |
| Default Provider | `GROK_CLI_PROVIDER` | Set the default AI provider | `xai` | `export bowie_CLI_PROVIDER="xai"` |


## Examples

Once the CLI is running, you can start interacting with AI models from your shell.

You can start a project from a new directory:

```sh
cd new-project
bowie
> Write me a Discord bot that answers questions using a FAQ.md file I will provide
```

Or work with an existing project:

```sh
git clone https://github.com/stevederico/skateboard
cd skateboard
bowie
> Give me a summary of all of the changes that went in yesterday
```

### Next steps

- [Contribute or build from source](./CONTRIBUTING.md)
- [CLI Commands](./docs/cli/commands.md)
- [Troubleshooting guide](./docs/troubleshooting.md)
- [Full documentation](./docs/index.md)
- [Popular tasks](./docs/popular-tasks.md)

### Troubleshooting

Head over to the [troubleshooting](docs/troubleshooting.md) guide if you're
having issues.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Terms of Service and Privacy Notice

For details on the terms of service and privacy notice applicable to your use of bowie CLI, see the [Terms of Service and Privacy Notice](./docs/tos-privacy.md).

## Disclaimer

This project is not an official product or initiative of xAI or Grok. It is an independent endeavor and is not endorsed, sponsored, or affiliated with xAI or bowie in any way.

## Acknowledgments

