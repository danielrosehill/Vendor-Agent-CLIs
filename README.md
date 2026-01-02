# Vendor-Managed AI Agent CLIs

[![Documentation](https://img.shields.io/badge/Documentation-View_List-blue?style=for-the-badge)](141225.md)

This repository curates a list of command line interfaces for AI models that are maintained by the model vendors themselves.

>
> This is not an exhaustive list. It is updated periodically, as the landscape is changing very quickly and constantly.
>
> This list only includes first-party tools that are maintained by the vendors themselves. There are many unofficial tools often coexisting with vendor tools, but this list specifically tracks the ones that the vendors maintain.
>
> If something is missing, feel free to send in corrections for inclusion.

## Current Vendor CLIs

| CLI Name | Vendor | Link |
|----------|--------|------|
| Amazon Q | AWS | [Website](https://aws.amazon.com/q/developer/) |
| Claude Code | Anthropic | [Docs](https://docs.anthropic.com/en/docs/claude-code) |
| Codex | OpenAI | [Website](https://openai.com/index/introducing-codex/) |
| Gemini CLI | Google | [GitHub](https://github.com/google-gemini/gemini-cli) |
| Groq Code CLI | Groq | [GitHub](https://github.com/build-with-groq/groq-code-cli) |
| Kimi CLI | Moonshot AI | [GitHub](https://github.com/MoonshotAI/kimi-cli) |
| Mistral CLI | Mistral AI | [GitHub](https://github.com/mistralai/mistral-cli) |
| Qwen Code | Alibaba | [Website](https://qwenlm.github.io/) |

## About

Vendor CLIs are often offered as standalone interfaces and sometimes integrated into IDEs—whether those maintained by the vendors or as official plugins for mainstream IDEs like VS Code.

A common pattern has emerged: Vendors create CLI accompaniments to their models that are primarily pitched to the developer community. The tools remain fairly elementary until they "hit it big" and develop a cult following among a loyal user base. An ecosystem begins to develop naturally around the tools. Eventually, media attention follows.

The distinction between vendor-managed and third-party CLIs is made not to suggest that vendor-created tools are necessarily inherently better than third-party tooling that leverages models via APIs. But there are specific reasons why many regard them as more significant. The most important of these is first-party access to the model upon which they are based. This close tie-in with model development often yields more reliable performance than that which can be accessed through external tooling.

Given that creating and releasing a commercial LLM with agentic tooling remains a substantial undertaking, the number of vendor-maintained CLIs is actually a fairly narrow pool.

Finally - these lists are almost certainly non-exhaustive. If you are a vendor and maintain a CLI that is "agentic" (supprots tool-use and MCP), please feel free to open a PR or drop me a line and I would be happy to update the repo. 

## Out Of Scope

This list specifically excludes:
- Third-party CLI tools (Aider, Continue, Cursor, etc.)
- IDE plugins that wrap vendor APIs
- Community-maintained forks
- Tools offering only API access without agentic capabilities

## Lists

Historical snapshots of the vendor CLI landscape:

| Date | List |
|------|------|
| December 14, 2025 | [141225.md](141225.md) |

## Additional Resources

- [benchmarks.md](benchmarks.md) - Overview of benchmarks used to evaluate agentic coding tools
- [clog.md](clog.md) - Changelog and repository purpose

## Authorship

- Readme and list population: me
- Benchmark doc: Claude Code
 
