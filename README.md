# Vendor-Managed AI Agent CLIs

This repository curates a list of command line interfaces for AI models that are maintained by the model vendors themselves.

## Current Vendor CLIs

[![Claude Code](https://img.shields.io/badge/Claude_Code-Anthropic-cc785c?style=for-the-badge&logo=anthropic)](https://docs.anthropic.com/en/docs/claude-code)
[![Codex](https://img.shields.io/badge/Codex-OpenAI-412991?style=for-the-badge&logo=openai)](https://openai.com/index/introducing-codex/)
[![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-Google-4285F4?style=for-the-badge&logo=google)](https://github.com/google-gemini/gemini-cli)
[![Qwen Code](https://img.shields.io/badge/Qwen_Code-Alibaba-FF6A00?style=for-the-badge&logo=alibabacloud)](https://qwenlm.github.io/)
[![Mistral CLI](https://img.shields.io/badge/Mistral_CLI-Mistral_AI-FF7000?style=for-the-badge)](https://github.com/mistralai/mistral-cli)
[![Amazon Q](https://img.shields.io/badge/Amazon_Q-AWS-232F3E?style=for-the-badge&logo=amazonaws)](https://aws.amazon.com/q/developer/)

## About

Vendor CLIs are often offered as standalone interfaces and sometimes integrated into IDEs—whether those maintained by the vendors or as official plugins for mainstream IDEs like VS Code.

A common pattern has emerged: Vendors create CLI accompaniments to their models that are primarily pitched to the developer community. The tools remain fairly elementary until they "hit it big" and develop a cult following among a loyal user base. An ecosystem begins to develop naturally around the tools. Eventually, media attention follows.

The distinction between vendor-managed and third-party CLIs is made not to suggest that vendor-created tools are necessarily inherently better than third-party tooling that leverages models via APIs. But there are specific reasons why many regard them as more significant. The most important of these is first-party access to the model upon which they are based. This close tie-in with model development often yields more reliable performance than that which can be accessed through external tooling.

Given that creating and releasing a commercial LLM with agentic tooling remains a substantial undertaking, the number of vendor-maintained CLIs is actually a fairly narrow pool.

Finally - these lists are almost certainly non-exhaustive. If you are a vendor and maintain a CLI that is "agentic" (supprots tool-use and MCP), please feel free to open a PR or drop me a line and I would be happy to update the repo. 

## What's NOT Included

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

---

*Timestamp format: DDMMYY*
