# Agentic Coding Benchmarks

## A Note on Benchmarks

Benchmarks are useful for assessing the relative strength of different agentic coding tools. They provide objective, reproducible metrics that allow for comparison across different tools and models.

However, it is important to note that benchmark performance does not always map perfectly onto real-world performance. Benchmarks are typically conducted under controlled conditions with specific types of tasks, and may not fully capture the nuances of actual development workflows. Factors such as context window usage, tool integration, latency, and how well an agent handles ambiguous requirements may not be adequately reflected in benchmark scores.

Despite these limitations, benchmarks remain valuable for getting objective information about tool efficacy and tracking improvements over time.

## Common Benchmarks

### SWE-bench

**Website:** [https://www.swebench.com/](https://www.swebench.com/)

SWE-bench is one of the most widely cited benchmarks for evaluating agentic coding tools. It consists of real GitHub issues from popular Python repositories, requiring agents to understand codebases, locate relevant files, and produce working patches. The benchmark tests end-to-end software engineering capabilities rather than isolated code generation.

Variants include:
- **SWE-bench Lite**: A curated subset of 300 representative tasks
- **SWE-bench Verified**: Human-verified subset with clearer specifications

### HumanEval

**Website:** [https://github.com/openai/human-eval](https://github.com/openai/human-eval)

HumanEval is a benchmark developed by OpenAI consisting of 164 hand-written programming problems. Each problem includes a function signature, docstring, and test cases. While useful for evaluating code generation capabilities, it focuses on isolated function completion rather than agentic workflows.

### MBPP (Mostly Basic Python Problems)

**Website:** [https://github.com/google-research/google-research/tree/master/mbpp](https://github.com/google-research/google-research/tree/master/mbpp)

MBPP contains around 1,000 crowd-sourced Python programming problems designed to be solvable by entry-level programmers. It tests basic programming and standard library knowledge.

### Terminal-Bench

Evaluates agents on their ability to use terminal commands and shell scripting to accomplish tasks. Tests real-world CLI proficiency alongside code generation.

### Aider Polyglot Benchmark

**Website:** [https://aider.chat/docs/leaderboards/](https://aider.chat/docs/leaderboards/)

While Aider is a third-party tool, its polyglot benchmark has become a useful reference point for comparing coding assistant performance across multiple programming languages. It tests the ability to make targeted edits to existing codebases.

### WebArena / OSWorld

These benchmarks test agentic capabilities beyond pure code generation, including web browsing, file manipulation, and multi-step task completion in realistic environments.

## Interpreting Benchmark Results

When evaluating benchmark scores, consider:

- **Task relevance**: Does the benchmark test tasks similar to your use case?
- **Evaluation methodology**: How are solutions validated? Automated tests vs. human review?
- **Date of evaluation**: Model and tool performance can change significantly between versions
- **Cost and latency**: A higher-scoring tool may not be practical if it's significantly slower or more expensive
- **Pass@k metrics**: Some benchmarks report pass@1 (first attempt) vs. pass@k (best of k attempts)—these tell different stories about reliability vs. capability
