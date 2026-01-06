# Awesome Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, skills, plugins, integrations, extensions, frameworks, and other resources for developers working with Anthropic's Claude Code.

> **Read my article:** Discover the top open-source command-line AI coding agents in the wider AI ecosystem.
>
> **👉 [7 Best CLI AI Coding Agents (Open Source)](https://www.scriptbyai.com/best-cli-ai-coding-agents/)**

## Table of Contents

- [Official Resources](#official-resources)
- [Tools & Utilities](#tools--utilities)
- [Claude Skills](#claude-skills)
- [Claude Plugins](#claude-plugins)
- [Usage Tracker](#usage-Tracker)
- [Sub Agents](#sub-agents)
- [IDE & Editor Integrations](#ide--editor-integrations)
- [Custom Commands & Frameworks](#custom-commands--frameworks)
- [Agents & Agent Managers](#agents--agent-managers)
- [Proxies & Model Integrations](#proxies--model-integrations)
- [SDKs & Development Kits](#sdks--development-kits)
- [GUIs & Web UIs](#guis--web-uis)
- [GitHub Actions](#github-actions)
- [Guides & Learning Resources](#guides--learning-resources)
- [Alternatives to Claude Code](#alternatives-to-claude-code)

---

## Official Resources

- [**claude-code**](https://github.com/anthropics/claude-code): Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routines.
- [**claude-code-sdk-python**](https://github.com/anthropics/claude-code-sdk-python): The official Python SDK for Claude Code.
- [**claude-code-security-review**](https://github.com/anthropics/claude-code-security-review): An AI-powered security review GitHub Action using Claude to analyze code changes for security vulnerabilities.
- [**claude-plugins-official**](https://github.com/anthropics/claude-plugins-official): Anthropic-managed directory of high quality Claude Code Plugins.
- [**skills**](https://github.com/anthropics/skills): Public repository for Agent Skills.

---

## Tools & Utilities

- [**async-code**](https://github.com/ObservedObserver/async-code): Use Claude Code or CodeX CLI to perform multiple tasks in parallel with a Codex-style UI, functioning as a personal codex or cursor-background agent.
- [**ccmanager**](https://github.com/kbwo/ccmanager): Claude Code / Gemini CLI / Codex CLI Session Manager.
- [**cctrace**](https://github.com/jimmc414/cctrace): Export Claude Code chat sessions into markdown and XML.
- [**ccundo**](https://github.com/RonitSachdev/ccundo): Integrates seamlessly with Claude Code to provide granular undo functionality by reading directly from Claude Code's session files.
- [**claude-code-hooks-multi-agent-observability**](https://github.com/disler/claude-code-hooks-multi-agent-observability): Real-time monitoring for Claude Code agents through simple hook event tracking.
- [**claude-code-templates**](https://github.com/davila7/claude-code-templates): A CLI tool for configuring and monitoring Claude Code.
- [**claudebox**](https://github.com/RchGrav/claudebox): A Claude Code Docker Development Environment for running Claude AI's coding assistant in a fully containerized, reproducible environment.
- [**context-forge**](https://github.com/webdevtodayjason/context-forge): CLI tool that scaffolds context engineering documentation for Claude Code projects.
- [**rins_hooks**](https://github.com/rinadelph/rins_hooks): Universal Claude Code hooks collection with cross-platform installer.
- [**claude-code-spec-workflow**](https://github.com/Pimzino/claude-code-spec-workflow): Automated Kiro-style Spec workflow for Claude Code. Transform feature ideas into complete implementations through Requirements → Design → Tasks → Implementation.
- [**cc-monitor-worker**](https://github.com/cometkim/cc-monitor-worker): Claude Code monitoring with Cloudflare Workers & Workers Analytics Engine.
- [**crystal**](https://github.com/stravu/crystal): Run multiple Claude Code AI sessions in parallel git worktrees.
- [**win-claude-code**](https://github.com/somersby10ml/win-claude-code): Claude Code for Windows: No WSL. No Docker. Just code.
- [**claude-prune**](https://github.com/DannyAziz/claude-prune): A fast CLI tool for pruning Claude Code sessions.
- [**claude-code-boost**](https://github.com/yifanzz/claude-code-boost): Hook utilities for Claude Code with intelligent auto-approval.
- [**tdd-guard**](https://github.com/nizos/tdd-guard): Automated TDD enforcement for Claude Code.
- [**conductor**](https://conductor.build/): Run a bunch of Claude Codes in parallel.
- [**ccguard**](https://github.com/pomterre/ccguard): Automated enforcement of net-negative LOC, complexity constraints, and quality standards for Claude code.
- [**claude-code-specs-generator**](https://github.com/kellemar/claude-code-specs-generator): A documentation and context management system for AI-assisted development, inspired by Amazon's Kiro IDE.
- [**cc-monitor-rs**](https://github.com/ZhangHanDong/cc-monitor-rs): Real-time Claude Code usage monitor with native UI built using Rust and Makepad.
- [**claude-self-reflect**](https://github.com/ramakay/claude-self-reflect): Claude forgets everything. This fixes that.
- [**tweakcc**](https://github.com/Piebald-AI/tweakcc): Command-line tool to customize your Claude Code styling.
- [**Claude-Code-Remote**](https://github.com/JessyTsui/Claude-Code-Remote): Control Claude Code remotely via email. Start tasks locally, receive notifications when Claude completes them, and send new commands by simply replying to emails.
- [**CCPlugins**](https://github.com/brennercruvinel/CCPlugins): Claude Code Plugins that actually save time. Built by a dev tired of typing please act like a senior engineer in every conversation.
- [**cipher**](https://github.com/campfirein/cipher): An opensource memory layer specifically designed for coding agents.
- [**claude-hub**](https://github.com/claude-did-this/claude-hub): Deploy Claude Code as a fully autonomous GitHub bot.
- [**laravel-claude-code-setup**](https://github.com/laraben/laravel-claude-code-setup): One-command setup for AI-powered Laravel development with Claude Code and MCP servers.
- [**claude-code-containers**](https://github.com/ghostwriternr/claude-code-containers): Use Claude Code on Cloudflare to solve GitHub issues.
- [**claude-code-log**](https://github.com/daaain/claude-code-log): A Python CLI tool that converts Claude Code transcript JSONL files into readable HTML format.
- [**claude-setup**](https://github.com/AizenvoltPrime/claude-setup): A comprehensive configuration setup for Claude Code with Model Context Protocol (MCP) servers, custom commands, and automated workflows.
- [**claude-code-sandbox**](https://github.com/textcortex/claude-code-sandbox): Run Claude Code safely in local Docker containers without having to approve every permission.
- [**claude-code-studio**](https://github.com/arnaldo-delisio/claude-code-studio): Transform Claude Code into a complete development studio with 40+ specialized AI agents, MCP integrations, and enterprise-grade workflows.
- [**claude-powerline**](https://github.com/Owloops/claude-powerline): Beautiful vim-style powerline statusline for Claude Code.
- [**flashbacker**](https://github.com/agentsea/flashbacker): Claude Code state management with session continuity and AI personas, subagents and agent discussion.
- [**claude-code-configs**](https://github.com/Matt-Dionis/claude-code-configs): A comprehensive collection of production-grade Claude Code configurations, specialized agents, and automation workflows for optimizing AI-assisted development.
- [**run-claude-docker**](https://github.com/icanhasjonas/run-claude-docker): Run claude code in somewhat safe and isolated yolo mode.
- [**Claude Code Tamagotchi**](https://github.com/Ido-Levi/claude-code-tamagotchi): A digital friend that lives in your Claude Code statusline and keeps you company while you build cool stuff.
- [**claude-code-test-runner**](https://github.com/firstloophq/claude-code-test-runner): An automated E2E natural language test runner built on Claude Code.
- [**ccpm**](https://github.com/automazeio/ccpm): Project management system for Claude Code using GitHub Issues and Git worktrees for parallel agent execution.
- [**claude-flow**](https://github.com/ruvnet/claude-flow): An enterprise-grade AI orchestration platform that reimagines how developers build with AI.
- [**ccpm**](https://github.com/automazeio/ccpm): Project management system for Claude Code using GitHub Issues and Git worktrees for parallel agent execution.
- [**claude-code-container**](https://github.com/tintinweb/claude-code-container): A Docker container for running Claude Code in "dangerously skip permissions" mode.
- [**claude-code-voice**](https://github.com/mckaywrigley/claude-code-voice): Hands-free voice control for Claude Code on macOS.
- [**ccheckpoints**](https://github.com/p32929/ccheckpoints): A checkpoint system for Claude Code CLI that automatically tracks your coding sessions.
- [**claude-code-voice**](https://github.com/mckaywrigley/claude-code-voice): Hands-free voice control for Claude Code on macOS.
- [**cc-sessions**](https://github.com/GWUDCAP/cc-sessions): An opinionated extension set for Claude Code (hooks, subagents, commands, task/git management infrastructure)
- [**claude-code-personal-assistant**](https://github.com/c0dezli/claude-code-personal-assistant): AI personal assistant setup for Claude Code.
- [**shotgun-alpha**](https://github.com/shotgun-sh/shotgun-alpha): Codebase-aware spec engine for Cursor, Claude Code & Lovable.
- [**Superpowers**](https://github.com/obra/superpowers): Give Claude Code superpowers with a comprehensive skills library of proven techniques, patterns, and tools.
- [**claude-code-thinking-patch**](https://github.com/aleks-apostle/claude-code-thinking-patch): Make Claude Code's thinking blocks visible by default without pressing ctrl+o.
- [**claude-context-local**](https://github.com/FarhanAliRaza/claude-context-local): Code search MCP for Claude Code. Make entire codebase the context for any coding agent. Embeddings are created and stored locally. No API cost.
- [**claude-code-prompt-improver**](https://github.com/severity1/claude-code-prompt-improver): Intelligent prompt improver hook for Claude Code. Type vibes, ship precision.
- [**claude-config-editor**](https://github.com/gagarinyury/claude-config-editor): A lightweight web tool that helps you clean and optimize your Claude Code/Desktop config files (.claude.json).
- [**claudecode-macmenu**](https://github.com/PiXeL16/claudecode-macmenu): A Mac Menu for Claude Code that notifies when Claude is done and shows insights.
- [**ccmate**](https://github.com/djyde/ccmate): Configure your Claude Code without pain.
- [**Continuous Claude**](https://github.com/AnandChowdhary/continuous-claude): Run Claude Code in a continuous loop, autonomously creating PRs, waiting for checks, and merging.
- [**meridian**](https://github.com/markmdev/meridian): Zero-config Claude Code setup with enforced task scaffolding, structured memory, persistent context after compaction, plug-in code standards, optional TDD mode, and zero behavior changes for developers.
- [**ClaudeForge**](https://github.com/alirezarezvani/ClaudeForge): A CLAUDE.md Generator and Maintenance tool for for Claude Code to create high-quality CLAUDE.md instruction files — aligned with Anthropic’s best practices for Claude Code.
- [**claude-agent-server**](https://github.com/forayconsulting/gemini_cli_skill): A Claude Code skill enabling Claude to use Gemini 3 Pro via Gemini CLI.
- [**recall**](https://github.com/zippoxer/recall): Full-text search and resume for Claude/Codex conversations.
- [**claude-select**](https://github.com/aeitroc/claude-select): A unified launcher for Claude Code that lets you interactively choose which LLM backend to use.
- [**claude-code-auto-memory**](https://github.com/severity1/claude-code-auto-memory): Claude Code plugin that automatically maintains CLAUDE.md files.
- [**claude-island**](https://github.com/farouqaldori/claude-island): Claude Code notifications without the context switch.
- [**Severance**](https://github.com/blas0/Severance): A semantic memory system designed for Claude Code.
- [**claude-code-router**](https://github.com/musistudio/claude-code-router): Use Claude Code as the foundation for coding infrastructure, allowing you to decide how to interact with the model while enjoying updates from Anthropic.
- [**claude-mem**](https://github.com/thedotmack/claude-mem): A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.
- [**claude-code-transcripts**](https://github.com/simonw/claude-code-transcripts): Tools for publishing transcripts for Claude Code sessions.
- [**Continuous-Claude-v2**](https://github.com/parcadei/Continuous-Claude-v2): Context management for Claude Code. Hooks maintain state via ledgers and handoffs. MCP execution without context pollution. Agent orchestration with isolated context windows.
- [**claude-code-transcripts**](https://github.com/simonw/claude-code-transcripts): Tools for publishing transcripts for Claude Code sessions.
- [**claude-cognitive**](https://github.com/GMaN1911/claude-cognitive): Working memory for Claude Code - persistent context and multi-instance coordination.

---

## Claude Skills

- [**awesome-claude-skills**](https://github.com/ComposioHQ/awesome-claude-skills): A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows.
- [**claude-skills-supercharged**](https://github.com/jefflester/claude-skills-supercharged): A "supercharged" implementation of Claude Code Skills – using Haiku prompt analysis/critical skill scoring and skill auto-injection for friction-free, context-driven workflows.
- [**gemini_cli_skill**](https://github.com/jefflester/claude-skills-supercharged): A "supercharged" implementation of Claude Code Skills – using Haiku prompt analysis/critical skill scoring and skill auto-injection for friction-free, context-driven workflows.
- [**claude-skill-homeassistant**](https://github.com/komal-SkyNET/claude-skill-homeassistant): Claude Code skill to supercharge and manage all Home Assistant workflows.
- [**Apple-Hig-Designer**](https://github.com/axiaoge2/Apple-Hig-Designer): A Claude Code Skill for designing professional interfaces following Apple Human Interface Guidelines.
- [**SkillForge**](https://github.com/tripleyak/SkillForge): The ultimate meta-skill for generating best-in-class Claude Code skills.
- [**planning-with-files**](https://github.com/OthmanAdi/planning-with-files): Claude Code skill implementing Manus-style persistent markdown planning — the workflow pattern behind the $2B acquisition.
- [**awesome-agent-skills**](https://github.com/heilcheng/awesome-agent-skills): A curated list of skills, tools, tutorials, and capabilities for AI coding agents (Claude, Codex, Copilot, VS Code).
- [**claude-scientific-skills**](https://github.com/K-Dense-AI/claude-scientific-skills): A set of ready to use scientific skills for Claude.
- [**happy-claude-skills**](https://github.com/iamzhihuix/happy-claude-skills): A collection of practical skill plugins designed for Claude Code.

---

## Claude Plugins

- [**claude-hud**](https://github.com/jarrodwatts/claude-hud): A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress.
- [**claude-workflow-v2**](https://github.com/CloudAI-X/claude-workflow-v2): Universal Claude Code workflow plugin with agents, skills, hooks, and commands.
- [**claude-code-plugin**](https://github.com/browserbase/claude-code-plugin): Browserbase plugin for Claude Code - Use cloud browsers with Claude Code instead of local Chrome.
- [**claude-code-safety-net**](https://github.com/kenryu42/claude-code-safety-net): A Claude Code plugin that acts as a safety net, catching destructive git and filesystem commands before they execute.
- [**ensue-skill**](https://github.com/mutable-state-inc/ensue-skill): A persistent knowledge tree that grows with you - what you learn today enriches tomorrow's reasoning.

## Usage Tracker

- [**ccusage**](https://github.com/ryoppippi/ccusage): A CLI tool for analyzing Claude Code usage from local JSONL files.
- [**CCSeva**](https://github.com/Iamshankhadeep/ccseva): A beautiful macOS menu bar app for tracking your Claude Code usage in real-time.
- [**Claude-Code-Usage-Monitor**](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor): A real-time Claude Code usage monitor with predictions and warnings.
- [**claude-code-leaderboard**](https://github.com/grp06/claude-code-leaderboard): This CLI automatically monitors your token usage and posts your stats to the leaderboard after each Claude Code session.
- [**ccstatusline**](https://github.com/sirmalloc/ccstatusline): A customizable status line formatter for Claude Code CLI that displays model info, git branch, token usage, and other metrics in your terminal.
- [**CCometixLine**](https://github.com/Haleclipse/CCometixLine): A high-performance Claude Code statusline tool written in Rust with Git integration and real-time usage tracking.
- [**pyccsl**](https://github.com/wolfdenpublishing/pyccsl): Python Claude Code Status Line (PyCCSL, pronounced "pixel").
- [**cc-statusline**](https://github.com/chongdashu/cc-statusline): Transform your Claude Code experience with a beautiful, informative statusline.
- [**claude-code-usage-bar**](https://github.com/leeguooooo/claude-code-usage-bar): Real‑time statusline for Claude Code: token usage, remaining budget, burn rate, and depletion time.
- [**cccost**](https://github.com/badlogic/cccost): Instrument Claude Code to track actual token usage and cost.
- [**Claude-Monitor**](https://github.com/RISCfuture/Claude-Monitor): A menulet that tracks your Claude Code token usage.
- [**claude-code-otel**](https://github.com/ColeMurray/claude-code-otel/): A comprehensive observability solution for monitoring Claude Code usage, performance, and costs.
- [**claude-statusline**](https://github.com/luongnv89/claude-statusline): Customize the status line in Claude Code.

---

## Sub Agents

  - [**claude-agents**](https://github.com/iannuttall/claude-agents): Custom subagents to use with Claude Code.
  - [**agents**](https://github.com/wshobson/agents): A collection of production-ready subagents for Claude Code.
  - [**sub-agents**](https://github.com/webdevtodayjason/sub-agents): A simple Manager for adding Claude Code Sub Agents with hooks and custom slash commands.
  - [**claude-code-subagents-collection**](https://github.com/davepoon/claude-code-subagents-collection): A comprehensive collection of specialized AI subagents for Claude Code, designed to enhance development workflows with domain-specific expertise.
  - [**claude-code-sub-agents**](https://github.com/lst97/claude-code-sub-agents): Collection of specialized AI subagents for Claude Code for personal use.
  - [**awesome-claude-code-agents**](https://github.com/hesreallyhim/awesome-claude-code-agents): A curated list of awesome Claude Code Sub-Agents.
  - [**claude-sub-agent**](https://github.com/zhsama/claude-sub-agent): AI-driven development workflow system built on Claude Code Sub-Agents.
  - [**claude-code-subagents**](https://github.com/NicholasSpisak/claude-code-subagents): A collection of specialized AI agent personas designed to work seamlessly with Claude Code's Task tool, providing expert-level assistance across the full spectrum of software development challenges.
  - [**claude-code-subagents**](https://github.com/0xfurai/claude-code-subagents): A comprehensive collection of 100+ production-ready development subagents for Claude Code.
  - [**claude-code-unified-agents**](https://github.com/stretchcloud/claude-code-unified-agents): A comprehensive collection of specialized Claude Code sub-agents combining the best features from multiple community repositories. 

---

## IDE & Editor Integrations

- [**claude-code.el**](https://github.com/stevemolitor/claude-code.el): Claude Code Emacs integration.
- [**claude-code.nvim**](https://github.com/greggh/claude-code.nvim): Seamless integration between the Claude Code AI assistant and Neovim.
- [**Claude-Autopilot**](https://github.com/benbasha/Claude-Autopilot): VS Code/Cursor extension for automating Claude Code tasks with intelligent queuing, batch processing, and auto-resume.
- [**claudecode.nvim**](https://github.com/coder/claudecode.nvim): A Claude Code Neovim IDE Extension.
- [**getspecstory**](https://github.com/specstoryai/getspecstory): Extensions for GH Copilot, Cursor, and Claude Code.
- [**minuet-ai.nvim**](https://github.com/milanglacier/minuet-ai.nvim): Code completion as-you-type from popular LLMs including OpenAI, Gemini, Claude, Ollama.
- [**n8n-nodes-claudecode**](https://github.com/holt-web-ai/n8n-nodes-claudecode): Bring the power of Claude Code directly into your n8n automation workflows!
- [**claude-code-chat**](https://github.com/andrepimenta/claude-code-chat): Beautiful Claude Code Chat Interface for VS Code.
- [**claude-code-ide.el**](https://github.com/manzaltu/claude-code-ide.el): Claude Code IDE for Emacs provides native integration with Claude Code CLI through the Model Context Protocol (MCP).

---

## Custom Commands & Frameworks

- [**Claude-Command-Suite**](https://github.com/qdhenry/Claude-Command-Suite): Professional slash commands for Claude Code that provide structured workflows for software development tasks, including code review and feature implementation.
- [**claude-deep-research**](https://www.google.com/search?q=https://github.com/disler/claude-deep-research): Claude Deep Research config for Claude Code.
- [**claude-on-rails**](https://github.com/obie/claude-on-rails): A development framework for Ruby on Rails developers using Claude Code, inspired by SuperClaude.
- [**claude-sessions**](https://github.com/iannuttall/claude-sessions): Custom slash commands for Claude Code that provide comprehensive development session tracking and documentation.
- [**claude-simone**](https://github.com/Helmi/claude-simone): A project management framework for AI-assisted development with Claude Code.
- [**SuperClaude**](https://github.com/NomenAK/SuperClaude): A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies.
- [**claude-cmd**](https://github.com/kiliczsh/claude-cmd): Claude Code Commands Manager.
- [**claude-code-settings**](https://github.com/feiskyer/claude-code-settings): Claude Code settings and commands for vibe coding.
- [**SuperClaude_Framework**](https://github.com/SuperClaude-Org/SuperClaude_Framework): A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies.
- [**claude-commands**](https://github.com/badlogic/claude-commands): Global Claude Code commands and workflows.
- [**spec-based-claude-code**](https://github.com/papaoloba/spec-based-claude-code): Implementation of a Spec-Driven Development workflow in Claude Code using custom slash commands.
- [**claude-modular**](https://github.com/oxygen-fragment/claude-modular): Production-ready modular Claude Code framework with 30+ commands, token optimization, and MCP server integration.
- [**commands**](https://github.com/wshobson/commands): A collection of production-ready slash commands for Claude Code.

---

## Agents & Agent Managers

- [**claude-squad**](https://github.com/smtg-ai/claude-squad): Manage multiple AI terminal agents, including Claude Code, Aider, Codex, OpenCode, and Amp.
- [**claude-swarm**](https://github.com/parruda/claude-swarm): Easily launch a Claude Code session connected to a swarm of Claude Code Agents.
- [**infinite-agentic-loop**](https://github.com/disler/infinite-agentic-loop): An experimental project demonstrating Infinite Agentic Loop in a two-prompt system using Claude Code.
- [**Claude-Flow**](https://github.com/ruvnet/claude-flow): An enterprise-grade AI orchestration platform that revolutionizes how developers build with AI.
- [**ClaudeNightsWatch**](https://github.com/aniketkarne/ClaudeNightsWatch): Autonomous task execution system for Claude CLI that monitors your usage windows and executes predefined tasks automatically.
- [**claude-code-heavy**](https://github.com/gtrusler/claude-code-heavy): Multi-agent research orchestration using Claude Code.
- [**claude-user-memory**](https://github.com/irenicj/claude-user-memory): A comprehensive Claude user memory system that enables intelligent, automatic orchestration of 12 specialized AI agents for Claude Code CLI.
- [**claude_code_agent_farm**](https://github.com/Dicklesworthstone/claude_code_agent_farm): A powerful orchestration framework that runs multiple Claude Code (cc) sessions in parallel to systematically improve your codebase.
- [**Specialized AI Agents**](https://github.com/Dimillian/Claude): This directory contains specialized AI agent definitions used by Claude Code to handle complex, domain-specific tasks.
- [**awesome-claude-agents**](https://github.com/vijaythecoder/awesome-claude-agents): Supercharge Claude Code with a team of specialized AI agents that work together to build complete features, debug complex issues, and handle any technology stack with expert-level knowledge.
- [**OpenAgents**](https://github.com/OpenAgentsInc/openagents): Seamlessly integrate Claude Code's AI development capabilities across desktop and mobile with real-time synchronization.
- [**ClaudeCodeAgents**](https://github.com/darcyegb/ClaudeCodeAgents): A set of useful QA agents for Claude Code.
- [**multi-agent-squad**](https://github.com/bijutharakan/multi-agent-squad): Production-ready multi-agent orchestration framework for Claude Code.
- [**dotclaude**](https://github.com/FradSer/dotclaude): A comprehensive development environment with specialized AI agents for code review, security analysis, and technical leadership.
- [**AgentCheck**](https://github.com/devlyai/AgentCheck): Local AI-powered code review agents for Claude Code.
- [**claude-agents**](https://github.com/tddworks/claude-agents): A collection of specialized AI agents for Claude Code that enhance software development workflows with focused expertise in specific domains.
- [**claude-code-agents**](https://github.com/vizra-ai/claude-code-agents): Meet 59 specialized AI agents that supercharge your development workflow.
- [**agents**](https://github.com/contains-studio/agents): A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development.
- [**Agent-Fusion**](https://github.com/krokozyab/Agent-Fusion): A multi-agent orchestration system that enables Claude Code, Codex CLI, Amazon Q Developer, and Gemini Code Assist to collaborate bidirectionally through intelligent task routing and consensus-based decision making.
- [**visual-claude**](https://github.com/thetronjohnson/visual-claude): A browser coding agent interface for selecting elements and sending instructions directly to Claude Code.
- [**seomachine**](https://github.com/TheCraigHewitt/seomachine): A specialized Claude Code workspace for creating long-form, SEO-optimized blog content for any business.
- [**Severance**](https://github.com/blas0/Severance): A semantic memory system designed for Claude Code. 

---

## Proxies & Model Integrations

- [**agentapi**](https://github.com/coder/agentapi): An HTTP API for Claude Code, Goose, Aider, and Codex.
- [**anthropic-proxy**](https://github.com/maxnowack/anthropic-proxy): A proxy server that converts Anthropic API requests to OpenAI format and sends them to OpenRouter, used to use Claude Code with OpenRouter.
- [**Claudify**](https://github.com/neno-is-ooo/claudify): Use Claude Code as an LLM provider with your subscription flat fee instead of pay-per-token API keys.
- [**claude-gemini-mcp-slim**](https://github.com/cmdaltctr/claude-gemini-mcp-slim): A lightweight integration that brings Google's Gemini AI capabilities to Claude Code through MCP (Model Context Protocol).
- [**claude_code-gemini-mcp**](https://github.com/RaiAnsar/claude_code-gemini-mcp): Connect Claude Code with Google's Gemini AI for powerful AI collaboration.
- [**claude-code-kimi-groq**](https://github.com/fakerybakery/claude-code-kimi-groq): A basic proxy to use Kimi K2 on Claude Code through Groq.
- [**claude-code-proxy**](https://github.com/1rgs/claude-code-proxy): Run Claude Code on OpenAI models.
- [**claude-code-proxy**](https://github.com/fuergaosi233/claude-code-proxy): A Claude Code to OpenAI API Proxy.
- [**claude-code-proxy**](https://github.com/seifghazi/claude-code-proxy): Proxy that captures and visualizes in-flight Claude Code requests and conversations.
- [**claude-code-router**](https://github.com/musistudio/claude-code-router): Uses Claude Code as the foundation for coding infrastructure, allowing interaction with the model while enjoying updates.
- [**copilot-api**](https://github.com/ericc-ch/copilot-api): Turns GitHub Copilot into an OpenAI/Anthropic API compatible server, usable with Claude Code.
- [**gemini-for-claude-code**](https://github.com/coffeegrind123/gemini-for-claude-code): A Python program allowing the use of Claude Code with Google's Gemini models.
- [**kimi-cc**](https://github.com/LLM-Red-Team/kimi-cc): Use Kimi's latest model (kimi-k2-0711-preview) to drive Claude Code.
- [**y-router**](https://github.com/luohy15/y-router): A Simple Proxy enabling Claude Code to work with OpenRouter.
- [**claude-code-open**](https://github.com/Davincible/claude-code-open): Claude Code with any LLM provider (OpenRouter, Gemini, Kimi K2).
- [**claude-code-mcp**](https://github.com/steipete/claude-code-mcp): Claude Code as a one-shot MCP server to have an agent in your agent.
- [**claude-historian**](https://github.com/Vvkmnn/claude-historian): An MCP server for Claude Code conversation history.
- [**mcp-claude-code**](https://github.com/SDGLBL/mcp-claude-code): MCP implementation of Claude Code capabilities and more.
- [**zen-mcp-server**](https://github.com/BeehiveInnovations/zen-mcp-server): The power of Claude Code + Gemini / OpenAI / Grok / OpenRouter / Ollama / Custom Model working as one.
- [**codemcp**](https://github.com/ezyang/codemcp): Coding assistant MCP for Claude Desktop.
- [**claude-balancer**](https://github.com/snipeship/claude-balancer): A load balancer proxy for multiple Claude OAuth accounts with automatic failover, request tracking, and web dashboard.
- [**claude-gemini-bridge**](https://github.com/tkaufmann/claude-gemini-bridge): Intelligent integration between Claude Code and Google Gemini for large-scale code analysis.
- [**ccflare**](https://github.com/snipeship/ccflare): The ultimate Claude API proxy with intelligent load balancing across multiple accounts.
- [**claude-code-nexus**](https://github.com/KroMiose/claude-code-nexus): Seamlessly forward Claude Code requests to any OpenAI-compatible API service with smart model mapping, streaming support, deployed on Cloudflare Worker.
- [**ccNexus**](https://github.com/lich0821/ccNexus): A smart API endpoint rotation proxy for Claude Code.
- [**castari-proxy**](https://github.com/castar-ventures/castari-proxy): Use Claude Agent SDK and Claude Code with other providers/models.
- [**multi-mcp**](https://github.com/religa/multi_mcp): Multi-model orchestration MCP server for parallel code review, security audits, and AI consensus with ChatGPT, Claude, and Gemini.

---

## SDKs & Development Kits

- [**Claude-Code-Development-Kit**](https://github.com/peterkrueck/Claude-Code-Development-Kit): A personal Claude Code Development Kit.
- [**claude-code-requirements-builder**](https://github.com/rizethereum/claude-code-requirements-builder): A tool for building Claude Code requirements.
- [**dotai**](https://github.com/udecode/dotai): The ultimate AI development stack, including Claude Code, Task Master, and Curso.
- [**vibekit**](https://github.com/superagent-ai/vibekit): A simple SDK for safely running Codex, Gemini CLI, and Claude Code in a secure sandbox.
- [**claude-code-sdk-ts**](https://github.com/instantlyeasy/claude-code-sdk-ts): Configure models, enable tools, stream events, then fetch text, JSON, run details or token stats in one call via .asText() or .allowTools('Read', 'Write').
- [**claude-code-typescript-hooks**](https://github.com/bartolli/claude-code-typescript-hooks): Fast, intelligent quality checks for different project types.
- [**claude-code-api-rs**](https://github.com/ZhangHanDong/claude-code-api-rs): A high-performance Rust implementation of an OpenAI-compatible API gateway for Claude Code CLI.
- [**claude-code-typescript-hooks**](https://github.com/bartolli/claude-code-typescript-hooks): Fast, intelligent quality checks for different project types.

---

## GUIs & Web UIs

- [**claudia**](https://github.com/getAsterisk/claudia): A powerful GUI app and Toolkit for Claude Code - Create custom agents, manage interactive Claude Code sessions, run secure background agents, and more.
- [**Claude-Code-Web-GUI**](https://github.com/binggg/Claude-Code-Web-GUI): Browse, view and share your Claude Code sessions - runs entirely in browser, no server required!
- [**claude-code-webui**](https://github.com/sugyan/claude-code-webui): Web-based interface for Claude CLI with streaming chat responses.
- [**Claude-code-ChatInWindows**](https://github.com/LKbaba/Claude-code-ChatInWindows): A Native UI for Windows That Makes Claude Code Instantly Better!
- [**Claudiatron**](https://github.com/Haleclipse/Claudiatron): A Powerful Claude Code GUI Desktop Application.
- [**Sniffly**](https://github.com/chiphuyen/sniffly): Claude Code dashboard with usage stats, error analysis, and sharable feature.
- [**claudecodeui**](https://github.com/siteboon/claudecodeui): A desktop and mobile UI for Claude Code, Anthropic's official CLI for AI-assisted coding.
- [**vibe-kanban**](https://github.com/BloopAI/vibe-kanban): Get 10X more out of Claude Code, Gemini CLI, Codex, Amp and other coding agents.
- [**claude-code-costs**](https://github.com/philipp-spiess/claude-code-costs): Analyze your Claude Code conversation costs with interactive visualizations.
- [**cui**](https://github.com/BMPixel/cui): A web UI for Claude Code agents.
- [**Claude in a Box**](https://github.com/juancgarza/claude-in-a-box): A ChatGPT Canvas-style interface for Claude Code running in E2B sandboxes.
- [**happy**](https://github.com/slopus/happy): Mobile and Web client for Claude Code, with realtime voice, encryption and fully featured.
- [**claude-code-viewer**](https://github.com/d-kimuson/claude-code-viewer): A full-featured web-based Claude Code client that provides complete interactive functionality for managing Claude Code projects.
- [**ccmate-release**](https://github.com/djyde/ccmate-release): A GUI for Claude Code.
- [**claude-run**](https://github.com/kamranahmedse/claude-run): A beautiful web UI for browsing Claude Code conversation history.

---

## GitHub Integration

- [**claude-code-action**](https://github.com/anthropics/claude-code-action): A general-purpose Claude Code action for GitHub PRs and issues that can answer questions and implement code changes.
- [**claude-code-base-action**](https://github.com/anthropics/claude-code-base-action): A Claude Code base action.
- [**SuperClaude**](https://github.com/gwendall/superclaude): Supercharge your GitHub workflow with Claude AI.

---

## Guides & Learning Resources

- [**agent-rules**](https://github.com/steipete/agent-rules): Rules and knowledge to work better with agents such as Claude Code or Cursor.
- [**claude-code-guide**](https://github.com/zebbern/claude-code-guide): A full guide on Claude tips and tricks, optimizing Claude Code, and finding every command possible.
- [**claude-code-hooks-mastery**](https://github.com/disler/claude-code-hooks-mastery): A resource for mastering Claude Code hooks.
- [**claude-code-is-programmable**](https://github.com/disler/claude-code-is-programmable): Scale your compute with Claude Code as a programmable agentic coding tool.
- [**claude-code-mcpinstall**](https://github.com/undeadpickle/claude-code-mcpinstall): Easy guide to installing Claude Code MCPs globally on your machine.
- [**claude-code-system-prompt**](https://github.com/matthew-lim-matthew-lim/claude-code-system-prompt): Claude Code's system prompt.
- [**claudecode-best-practices**](https://github.com/rosmur/claudecode-best-practices): A collection of best practices and procedures for using Claude Code.

---

## Alternatives to Claude Code

- [**gemini-cli**](https://github.com/google-gemini/gemini-cli): An open-source AI agent that brings the power of Gemini directly into your terminal.
- [**openCode**](https://github.com/opencode-ai/opencode): A powerful AI coding agent built for the terminal.
- [**OpenAI Codex CLI**](https://github.com/openai/codex): Lightweight coding agent that runs in your terminal.
- [**opencoder**](https://github.com/ducan-ne/opencoder): An alternative to Claude Code.
- [**grok-cli**](https://github.com/superagent-ai/grok-cli): An open-source AI agent that brings the power of Grok directly into your terminal.
- [**qwen-code**](https://github.com/QwenLM/qwen-code): A command-line AI workflow tool adapted from Gemini CLI, optimized for Qwen3-Coder models with enhanced parser support & tool support.
- [**octofriend**](https://github.com/synthetic-lab/octofriend): An open-source coding helper. Very friendly!

---

## Contribution Guidelines

**Under Construction**
