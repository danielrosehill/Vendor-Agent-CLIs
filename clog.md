# Changelog

## Purpose

This repository tracks vendor-managed AI agent CLIs—command line interfaces for AI models that are developed and maintained by the model vendors themselves (Anthropic, OpenAI, Google, etc.), rather than third-party tools that consume models via APIs.

## Why This Distinction Matters

Vendor CLIs typically have:
- First-party access to underlying models
- Closer integration with model development cycles
- More reliable performance than external tooling
- Official support and documentation

## What This Repo Contains

- **Timestamped CLI listings**: Point-in-time snapshots of the vendor CLI landscape
- **Benchmark references**: Overview of how these tools are evaluated
- **Exclusion criteria**: We track only vendor-maintained tools, not third-party wrappers

## Exclusion Criteria

The following are explicitly **not** included:
- Third-party CLI tools (e.g., Aider, Continue, Cursor)
- IDE plugins that wrap vendor APIs
- Community-maintained forks
- Tools that only offer API access without agentic capabilities

## Versioning

Lists are timestamped in DDMMYY format to track the rapidly evolving landscape.
