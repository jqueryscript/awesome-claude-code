# Awesome Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, skills, plugins, integrations, extensions, frameworks, and other resources for developers working with **Anthropic's Claude Code**.

> **Read my article:** Discover the top open-source command-line AI coding agents in the wider AI ecosystem.
>
> **👉 [7 Best CLI AI Coding Agents (Open Source)](https://www.scriptbyai.com/best-cli-ai-coding-agents/)**

> **Note: Star counts are static and represent the numbers at the time the resource was recorded in this list.**

## Table of Contents

- [Official Resources](#official-resources)
- [🤖 Agents & Orchestration](#-agents--orchestration)
- [🧠 Agent Skills](#-agent-skills)
- [🔌 Claude Plugins](#-claude-plugins)
- [🛠️ Tools & Utilities](#%EF%B8%8F-tools--utilities)
- [💻 IDE & Editor Integrations](#-ide--editor-integrations)
- [🖥️ Clients & GUIs](#%EF%B8%8F-clients--guis)
- [🏗️ Infrastructure & Proxies](#%EF%B8%8F-infrastructure--proxies)
- [📊 Usage & Observability](#-usage--observability)
- [🧩 SDKs & Development Kits](#-sdks--development-kits)
- [📚 Guides & Learning](#-guides--learning)
- [Alternatives to Claude Code](#alternatives-to-claude-code)
- [Contribution Guidelines](#contribution-guidelines)
- [Changelog](#changelog)

---

## Official Resources

- [**skills**](https://github.com/anthropics/skills) - (197.5k ⭐) - Public repository for Agent Skills.
- [**claude-code**](https://github.com/anthropics/claude-code) - (156.3k ⭐) - Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routines.
- [**claude-cookbooks**](https://github.com/anthropics/claude-cookbooks) - (54.9k ⭐) - A collection of notebooks/recipes showcasing some fun and effective ways of using Claude.
- [**claude-plugins-official**](https://github.com/anthropics/claude-plugins-official) - (47.7k ⭐) - Anthropic-managed directory of high quality Claude Code Plugins.
- [**financial-services**](https://github.com/anthropics/financial-services) - (41.4k ⭐) - Reference agents, skills, and data connectors for the financial-services workflows.
- [**knowledge-work-plugins**](https://github.com/anthropics/knowledge-work-plugins) - (36.6k ⭐) - Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork & Claude Code.
- [**claude-code-sdk-python**](https://github.com/anthropics/claude-code-sdk-python) - (8.6k ⭐) - The official Python SDK for Claude Code.
- [**defending-code-reference-harness**](https://github.com/anthropics/defending-code-reference-harness) - (7.8k ⭐) - Skills for threat modeling, scanning, triage, patching, plus an autonomous scanning harness you can /customize.
- [**claude-code-security-review**](https://github.com/anthropics/claude-code-security-review) - (7.0k ⭐) - An AI-powered security review GitHub Action using Claude to analyze code changes for security vulnerabilities.

---

## 🤖 Agents & Orchestration

- [**gstack**](https://github.com/garrytan/gstack) - (142.1k ⭐) - Garry Tan's Claude Code setup with opinionated agent roles for product, design, engineering, release, documentation, and QA work.
- [**Claude-Flow**](https://github.com/ruvnet/claude-flow) - (82.1k ⭐) - An enterprise-grade AI orchestration platform that revolutionizes how developers build with AI.
- [**herdr**](https://github.com/herdrdev/herdr) - (51.8k ⭐) - Terminal and desktop runtime for keeping coding-agent sessions running across local and remote machines.
- [**herdr**](https://github.com/ogulcancelik/herdr) - (51.8k ⭐) - Agent multiplexer that lives in your terminal.
- [**agents**](https://github.com/wshobson/agents) - (42.7k ⭐) - A collection of production-ready subagents for Claude Code.
- [**oh-my-claudecode**](https://github.com/Yeachan-Heo/oh-my-claudecode) - (41.0k ⭐) - Teams-first multi-agent orchestration for Claude Code.
- [**paseo**](https://github.com/getpaseo/paseo) - (24.4k ⭐) - Self-hosted interface for running Claude Code, Codex, Copilot, OpenCode, and Pi agents from desktop or mobile.
- [**agent-orchestrator**](https://github.com/OrchestratorInc/agent-orchestrator) - (14.9k ⭐) - Workspace for planning, running, and supervising coding-agent teams across desktop, web, mobile, and cloud.
- [**agent-orchestrator**](https://github.com/Untrivial-ai/agent-orchestrator) - (14.9k ⭐) - Plan, run, and supervise coding agents with separate workspaces, live Kanban tracking, pull requests, CI runs, and reviews.
- [**agents**](https://github.com/contains-studio/agents) - (12.4k ⭐) - A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development.
- [**omnigent**](https://github.com/omnigent-ai/omnigent) - (11.4k ⭐) - A meta-harness for all your AI agents.
- [**munder-difflin**](https://github.com/chaitanyagiri/munder-difflin) - (9.6k ⭐) - Local multi-agent harness that works with existing Claude Code and Codex subscriptions to run an office of agents.
- [**OpenRig**](https://github.com/mvschwarz/openrig) - (8.9k ⭐) - Multi-agent harness for running persistent Claude Code, Codex, and Pi teams with shared context and defined roles.
- [**claude-squad**](https://github.com/smtg-ai/claude-squad) - (8.8k ⭐) - Manage multiple AI terminal agents, including Claude Code, Aider, Codex, OpenCode, and Amp.
- [**seomachine**](https://github.com/TheCraigHewitt/seomachine) - (7.6k ⭐) - A specialized Claude Code workspace for creating long-form, SEO-optimized blog content for any business.
- [**loopx**](https://github.com/loopx-project/loopx) - (6.7k ⭐) - Long-horizon agent control plane for durable, governed work across Codex, Claude Code, and other harnesses.
- [**mission-control**](https://github.com/builderz-labs/mission-control) - (6.5k ⭐) - Self-hosted control plane for dispatching agent tasks, reviewing runs, tracking token use and cost, and managing agent operations.
- [**Council of High Intelligence**](https://github.com/0xNyk/council-of-high-intelligence) - (4.9k ⭐) - Multi-agent deliberation framework for comparing perspectives on difficult decisions across coding agents.
- [**awesome-claude-agents**](https://github.com/vijaythecoder/awesome-claude-agents) - (4.4k ⭐) - Supercharge Claude Code with a team of specialized AI agents that work together to build complete features, debug complex issues, and handle any technology stack with expert-level knowledge.
- [**raptor**](https://github.com/gadievron/raptor) - (4.0k ⭐) - Turns Claude Code into a general-purpose AI offensive/defensive security agent.
- [**claude-code-subagents-collection**](https://github.com/davepoon/claude-code-subagents-collection) - (3.8k ⭐) - A comprehensive collection of specialized AI subagents for Claude Code, designed to enhance development workflows with domain-specific expertise.
- [**claude_codex_bridge**](https://github.com/SeemSeam/claude_codex_bridge) - (3.6k ⭐) - Visible multi-agent CLI workspace for mixing Codex, Claude, Gemini, Kimi, Qwen, Cursor, Copilot, Pi, OpenCode, and other AI coding agents.
- [**Maestro**](https://github.com/RunMaestro/Maestro) - (3.6k ⭐) - Desktop app for running and monitoring coding agents in parallel, with separate Git worktrees for their changes.
- [**claude-subconscious**](https://github.com/letta-ai/claude-subconscious) - (2.9k ⭐) - A background agent that whispers to Claude Code. A subconcious agent that watches your sessions, reads your files, builds up memory over time, and whispers guidance back.
- [**Memoh**](https://github.com/felinics/Memoh) - (2.8k ⭐) - Multi-agent platform that gives each agent a dedicated computer with a desktop, browser, network, and long-term memory; supports hosted Claude Code and Codex agents.
- [**myclaude**](https://github.com/stellarlinkco/myclaude) - (2.8k ⭐) - Multi-agent development workflows with task routing across Claude Code, Codex, Gemini, and OpenCode, plus planning, review, and testing commands.
- [**deepclaude**](https://github.com/aattaran/deepclaude) - (2.3k ⭐) - A Claude Code skill for generating UI in the Nothing design language. Monochrome, typographic, industrial.
- [**zeroshot**](https://github.com/the-open-engine/zeroshot) - (2.2k ⭐) - Coding-agent workflow engine with configurable independent reviews, repair loops, review gates, and retry limits across Claude Code, Codex, Pi, and Copilot.
- [**roast-room**](https://github.com/nateherkai/roast-room) - (2.2k ⭐) - Claude Code workspace where AI advisors debate business decisions, with a local visual discussion room, scored verdicts, and PDF reports.
- [**claude-agents**](https://github.com/iannuttall/claude-agents) - (2.0k ⭐) - Custom subagents to use with Claude Code.
- [**openakita**](https://github.com/openakita/openakita) - (2.0k ⭐) - Open-source AI assistant framework with skills and agent workflows.
- [**LongHorizon-Harness**](https://github.com/AMAP-ML/LongHorizon-Harness) - (1.9k ⭐) - Long-running computer-use harness for Claude Code, Codex, OpenCode, and DeepSeek Harness with checkpointed state, independent audits, and recovery across desktop and CLI tasks.
- [**roborev**](https://github.com/kenn-io/roborev) - (1.8k ⭐) - Continuous background code review database for agents, work faster and smarter with accountability for every line of generated code.
- [**agent-flow**](https://github.com/patoles/agent-flow) - (1.8k ⭐) - Real-time visualization of Claude Code agent orchestration — see your agents think, branch, and coordinate as they work.
- [**claude-code-sub-agents**](https://github.com/lst97/claude-code-sub-agents) - (1.7k ⭐) - Collection of specialized AI subagents for Claude Code for personal use.
- [**awesome-claude-code-agents**](https://github.com/hesreallyhim/awesome-claude-code-agents) - (1.4k ⭐) - A curated list of awesome Claude Code Sub-Agents.
- [**Pika-Skills**](https://github.com/Pika-Labs/Pika-Skills) - (1.2k ⭐) - A collection of open-source skills for AI coding agents (Claude Code, OpenClaw, etc.) powered by the Pika Developer API.
- [**claude-code-subagents**](https://github.com/0xfurai/claude-code-subagents) - (1.0k ⭐) - A comprehensive collection of 100+ production-ready development subagents for Claude Code.
- [**agentsys**](https://github.com/agent-sh/agentsys) - (1.0k ⭐) - Automation toolkit with plugins, agents, skills, and slash commands for Claude Code, OpenCode, Codex, Cursor, and Kiro.
- [**claude-delegator**](https://github.com/jarrodwatts/claude-delegator) - (997 ⭐) - Delegate tasks to Codex GPT 5.2 directly from within Claude Code.
- [**Citadel**](https://github.com/SethGammon/Citadel) - (930 ⭐) - An agent orchestration harness for Claude Code. It coordinates multiple AI agents in parallel, persists memory across sessions, and routes your intent to the cheapest execution path automatically.
- [**claude_code_agent_farm**](https://github.com/Dicklesworthstone/claude_code_agent_farm) - (924 ⭐) - A powerful orchestration framework that runs multiple Claude Code (cc) sessions in parallel to systematically improve your codebase.
- [**ai-maestro**](https://github.com/23blocks-OS/ai-maestro) - (855 ⭐) - Agent orchestration dashboard with memory search, code graph queries, agent-to-agent messaging, and skills support.
- [**ClaudeCodeAgents**](https://github.com/darcyegb/ClaudeCodeAgents) - (782 ⭐) - A set of useful QA agents for Claude Code.
- [**claude-code-unified-agents**](https://github.com/stretchcloud/claude-code-unified-agents) - (752 ⭐) - A comprehensive collection of specialized Claude Code sub-agents combining the best features from multiple community repositories.
- [**ralph-claude-code**](https://github.com/DmitrySolana/ralph-claude-code) - (740 ⭐) - Autonomous AI development loop for Claude Code with intelligent exit detection.
- [**pilotfish**](https://github.com/Nanako0129/pilotfish) - (717 ⭐) - Multi-model orchestration for Claude Code: a frontier model plans, lower-cost models execute, and verification checks the result.
- [**infinite-agentic-loop**](https://github.com/disler/infinite-agentic-loop) - (621 ⭐) - An experimental project demonstrating Infinite Agentic Loop in a two-prompt system using Claude Code.
- [**dotclaude**](https://github.com/FradSer/dotclaude) - (596 ⭐) - A comprehensive development environment with specialized AI agents for code review, security analysis, and technical leadership.
- [**claude-sub-agent**](https://github.com/zhsama/claude-sub-agent) - (594 ⭐) - AI-driven development workflow system built on Claude Code Sub-Agents.
- [**GLM-skills**](https://github.com/zai-org/GLM-skills) - (478 ⭐) - Official skills for the GLM family of models.
- [**bux**](https://github.com/browser-use/bux) - (465 ⭐) - A 24/7 Claude Code agent with Browser Harness, on any box you own.
- [**OpenAgents**](https://github.com/OpenAgentsInc/openagents) - (463 ⭐) - Seamlessly integrate Claude Code's AI development capabilities across desktop and mobile with real-time synchronization.
- [**ClaudeNightsWatch**](https://github.com/aniketkarne/ClaudeNightsWatch) - (371 ⭐) - Autonomous task execution system for Claude CLI that monitors your usage windows and executes predefined tasks automatically.
- [**Specialized AI Agents**](https://github.com/Dimillian/Claude) - (352 ⭐) - This directory contains specialized AI agent definitions used by Claude Code to handle complex, domain-specific tasks.
- [**visual-claude**](https://github.com/thetronjohnson/visual-claude) - (266 ⭐) - A browser coding agent interface for selecting elements and sending instructions directly to Claude Code.
- [**seo-geo-claude-skills**](https://github.com/aaron-he-zhu/seo-geo-claude-skills) - (251 ⭐) - 20 SEO & GEO skills for Claude Code, Cursor, Codex, and 35+ AI agents. Keyword research, content writing, technical audits, rank tracking.
- [**claude-user-memory**](https://github.com/irenicj/claude-user-memory) - (214 ⭐) - A comprehensive Claude user memory system that enables intelligent, automatic orchestration of 12 specialized AI agents for Claude Code CLI.
- [**claude-code-subagents**](https://github.com/NicholasSpisak/claude-code-subagents) - (213 ⭐) - A collection of specialized AI agent personas designed to work seamlessly with Claude Code's Task tool, providing expert-level assistance across the full spectrum of software development challenges.
- [**sub-agents**](https://github.com/webdevtodayjason/sub-agents) - (198 ⭐) - A simple Manager for adding Claude Code Sub Agents with hooks and custom slash commands.
- [**claude-code-agents**](https://github.com/vizra-ai/claude-code-agents) - (162 ⭐) - Meet 59 specialized AI agents that supercharge your development workflow.
- [**sub-agents.directory**](https://github.com/ayush-that/sub-agents.directory) - (150 ⭐) - A curated collection of 100+ sub-agent prompts and MCP servers for Claude Code.
- [**claude-code-merge-queue**](https://github.com/funador/claude-code-merge-queue) - (131 ⭐) - Local merge queue for coordinating parallel Claude Code agents and landing their work in a controlled order.
- [**multi-agent-squad**](https://github.com/bijutharakan/multi-agent-squad) - (88 ⭐) - Production-ready multi-agent orchestration framework for Claude Code.
- [**claude-code-heavy**](https://github.com/gtrusler/claude-code-heavy) - (78 ⭐) - Multi-agent research orchestration using Claude Code.
- [**claude-code-semantic-memory**](https://github.com/gtrusler/claude-code-heavy) - (78 ⭐) - Persistent semantic memory system for Claude Code.
- [**Agent-Fusion**](https://github.com/krokozyab/Agent-Fusion) - (74 ⭐) - A multi-agent orchestration system that enables Claude Code, Codex CLI, Amazon Q Developer, and Gemini Code Assist to collaborate bidirectionally through intelligent task routing and consensus-based decision making.
- [**Severance**](https://github.com/blas0/Severance) - (49 ⭐) - A semantic memory system designed for Claude Code.
- [**AgentCheck**](https://github.com/devlyai/AgentCheck) - (48 ⭐) - Local AI-powered code review agents for Claude Code.
- [**claude-agents**](https://github.com/tddworks/claude-agents) - (20 ⭐) - A collection of specialized AI agents for Claude Code that enhance software development workflows with focused expertise in specific domains.

---

## 🧠 Agent Skills

- [**mattpocock skills**](https://github.com/mattpocock/skills) - (327.9k ⭐) - Skills for Real Engineers.
- [**Superpowers**](https://github.com/obra/superpowers) - (321.7k ⭐) - Give Claude Code superpowers with a comprehensive skills library of proven techniques, patterns, and tools.
- [**ECC**](https://github.com/affaan-m/ECC) - (307.0k ⭐) - Agent harness optimization system with skills, memory, security practices, and research-first workflows for Claude Code, Codex, OpenCode, Cursor, and related tools.
- [**andrej-karpathy-skills**](https://github.com/forrestchang/andrej-karpathy-skills) - (234.4k ⭐) - A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.
- [**ui-ux-pro-max-skill**](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - (151.6k ⭐) - An AI SKILL that provide design intelligence for building professional UI/UX multiple platforms.
- [**graphify**](https://github.com/safishamsi/graphify) - (150.4k ⭐) - AI coding assistant skill (Claude Code, Codex, OpenCode, OpenClaw, Factory Droid, Trae).
- [**caveman**](https://github.com/JuliusBrussee/caveman) - (121.4k ⭐) - A Claude Code skill/plugin and Codex plugin that makes agent talk like caveman — cutting ~75% of output tokens while keeping full technical accuracy.
- [**agent-skills**](https://github.com/addyosmani/agent-skills) - (119.1k ⭐) - Production-grade engineering skills for AI coding agents.
- [**taste-skill**](https://github.com/Leonxlnx/taste-skill) - (118.7k ⭐) - A collection of skills that improve how AI tools write frontend code.
- [**archify**](https://github.com/tt-a1i/archify) - (97.9k ⭐) - Agent skill for generating architecture diagrams with dark and light themes plus PNG, JPEG, WebP, and SVG export.
- [**Understand-Anything**](https://github.com/Lum1104/Understand-Anything) - (93.3k ⭐) - Claude Code skills that turn any codebase into an interactive knowledge graph you can explore, search, and ask questions about (Multi-platform e.g., Codex are supported).
- [**hyperframes**](https://github.com/heygen-com/hyperframes) - (86.8k ⭐) - Write HTML. Render video. Built for agents.
- [**security-audit-skill**](https://github.com/cloudflare/security-audit-skill) - (75.6k ⭐) - Cloudflare coding-agent skill for multi-phase security audits with independently verified, machine-readable findings.
- [**humanizer**](https://github.com/blader/humanizer) - (71.1k ⭐) - A Claude Code skill that removes signs of AI-generated writing from text, making it sound more natural and human.
- [**last30days-skill**](https://github.com/mvanhorn/last30days-skill) - (70.5k ⭐) - Claude Code skill that researches any topic across Reddit + X from the last 30 days, then writes copy-paste-ready prompts.
- [**i-have-adhd**](https://github.com/ayghri/i-have-adhd) - (61.7k ⭐) - A skill that keeps coding-agent answers direct, concise, and easy to scan.
- [**marketingskills**](https://github.com/coreyhaines31/marketingskills) - (61.4k ⭐) - Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering.
- [**emilkowalski/skills**](https://github.com/emilkowalski/skills) - (58.1k ⭐) - Design engineering skills for AI coding agents.
- [**Hallmark**](https://github.com/nutlope/hallmark) - (57.8k ⭐) - Design skill and CLI for building, auditing, and redesigning interfaces with checks for common AI-generated design patterns.
- [**scientific-agent-skills**](https://github.com/K-Dense-AI/scientific-agent-skills) - (57.8k ⭐) - A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.
- [**claude-scientific-skills**](https://github.com/K-Dense-AI/claude-scientific-skills) - (57.8k ⭐) - A set of ready to use scientific skills for Claude.
- [**academic-research-skills**](https://github.com/Imbad0202/academic-research-skills) - (57.7k ⭐) - Academic Research Skills for Claude Code: research → write → review → revise → finalize.
- [**obsidian-skills**](https://github.com/obsidianmd/obsidian-skills) - (53.2k ⭐) - Official Obsidian skills for working with the Obsidian CLI, Markdown notes, Bases, and JSON Canvas files.
- [**agentic-awesome-skills**](https://github.com/sickn33/agentic-awesome-skills) - (50.0k ⭐) - A catalog of 1,900+ agentic skills with a CLI, local MCP server, plugins, and workbench for skill discovery and planning.
- [**sickn33**](https://github.com/sickn33/antigravity-awesome-skills) - (50.0k ⭐) - The Ultimate Collection of 130+ Agentic Skills for Claude Code/Antigravity/Cursor.
- [**reverse-skill**](https://github.com/zhaoxuya520/reverse-skill) - (44.9k ⭐) - Reverse engineering and authorized penetration testing skill for AI coding agents.
- [**Claude-Code-Game-Studios**](https://github.com/Donchitos/Claude-Code-Game-Studios) - (40.1k ⭐) - Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.
- [**add-skill**](https://github.com/vercel-labs/add-skill) - (40.0k ⭐) - Install agent skills onto your coding agents from any git repository.
- [**book-to-skill**](https://github.com/virgiliojr94/book-to-skill) - (38.5k ⭐) - Turn any technical book PDF into a Claude Code skill — ready to study, reference, and use while you work.
- [**Anthropic-Cybersecurity-Skills**](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - (36.4k ⭐) - 753+ structured cybersecurity skills for AI agents.
- [**agent-skills**](https://github.com/vercel-labs/agent-skills) - (34.5k ⭐) - A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.
- [**frontend-slides**](https://github.com/zarazhangrui/frontend-slides) - (32.6k ⭐) - A Claude Code skill for creating stunning, animation-rich HTML presentations.
- [**claude-seo**](https://github.com/AgriciDaniel/claude-seo) - (30.8k ⭐) - Universal SEO skill for Claude Code. Comprehensive SEO analysis for any website or business type.
- [**claude-skills**](https://github.com/alirezarezvani/claude-skills) - (30.1k ⭐) - A Collection of Skills for Claude Code and Claude AI for real-world Usage.
- [**guizang-ppt-skill**](https://github.com/op7418/guizang-ppt-skill) - (30.1k ⭐) - A Claude Code Skill that turns prompts into horizontal-swipe magazine-style HTML decks.
- [**anatomy**](https://github.com/wheresryan22/anatomy) - (28.2k ⭐) - Agent skill for building interactive isometric illustrations of machines and technical concepts with SVG, WebGL, and 3D effects.
- [**planning-with-files**](https://github.com/OthmanAdi/planning-with-files) - (28.1k ⭐) - Claude Code skill implementing Manus-style persistent markdown planning — the workflow pattern behind the $2B acquisition.
- [**watermarks-remover**](https://github.com/guillaumemeyer/watermarks-remover) - (27.8k ⭐) - Agent skill and Python service for removing AI provenance marks from text and file metadata, including C2PA, EXIF, and XMP.
- [**baoyu-skills**](https://github.com/JimLiu/baoyu-skills) - (27.7k ⭐) - A collection of 20+ skills for writing, image generation, presentations, social publishing, and other daily work with Claude Code, Codex, and compatible agents.
- [**SkillSpector**](https://github.com/NVIDIA/SkillSpector) - (26.9k ⭐) - Security scanner for AI agent skills that detects vulnerabilities and risky instructions.
- [**text-to-cad**](https://github.com/earthtojake/text-to-cad) - (26.8k ⭐) - An open source harness for generating CAD models.
- [**Google Agent Skills**](https://github.com/google/skills) - (24.4k ⭐) - Agent Skills for Google products and technologies.
- [**modern-web-guidance**](https://github.com/GoogleChrome/modern-web-guidance) - (23.2k ⭐) - Google Chrome guidance for modern web development, with a companion site for current web platform recommendations.
- [**video-shotcraft**](https://github.com/Vincentwei1021/video-shotcraft) - (21.6k ⭐) - Claude Code and Codex skill for creating cinematic product videos with Remotion shot recipes and templates.
- [**claude-video**](https://github.com/bradautomates/claude-video) - (21.3k ⭐) - An Agent Skill and Claude Code plugin that downloads video, extracts frames and captions or transcripts, and answers questions about the on-screen and audio content.
- [**notebooklm-py**](https://github.com/teng-lin/notebooklm-py) - (20.3k ⭐) - Unofficial Python API and agentic skill for Google NotebookLM, with programmatic access through Python, a CLI, and AI agents such as Claude Code, Codex, and OpenClaw.
- [**Auto-claude-code-research-in-sleep**](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) - (19.5k ⭐) - Lightweight Markdown-only skills for autonomous ML research.
- [**stop-slop**](https://github.com/hardikpandya/stop-slop) - (19.1k ⭐) - A skill file for removing AI tells from prose.
- [**gsap-skills**](https://github.com/greensock/gsap-skills) - (18.7k ⭐) - Official AI skills for GSAP. These skills teach AI coding agents how to correctly use GSAP (GreenSock Animation Platform), including best practices, common animation patterns, and plugin usage.
- [**unslop**](https://github.com/heydamir/unslop) - (18.5k ⭐) - Claude Code and Codex skill for auditing and redesigning generic AI-generated interfaces through focused passes on typography, spacing, color, layout, copy, and motion.
- [**Agent-Skills-for-Context-Engineering**](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) - (18.4k ⭐) - A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems.
- [**prompt-master**](https://github.com/nidhinjs/prompt-master) - (16.1k ⭐) - A Claude skill that writes the accurate prompts for any AI tool.
- [**ai-design-skills**](https://github.com/elayadesign/ai-design-skills) - (16.1k ⭐) - A collection of design skills for Claude Code, Cursor, Codex, Windsurf, and other tools that read Markdown rules.
- [**garden-skills**](https://github.com/ConardLi/garden-skills) - (15.5k ⭐) - ConardLi's open-source Skills collection, featuring web design, knowledge retrieval, image generation, and more.
- [**AI-research-SKILLs**](https://github.com/Orchestra-Research/AI-research-SKILLs) - (14.7k ⭐) - Visual Skills Pack for Obsidian: generate Canvas, Excalidraw, and Mermaid diagrams from text with Claude Code.
- [**memU**](https://github.com/NevaMind-AI/memU) - (14.6k ⭐) - Personal memory for agents with fast retrieval, self-evolving skills, and lower context cost.
- [**MiniMax-AI/skills**](https://github.com/MiniMax-AI/skills) - (13.9k ⭐) - Development skills for AI coding agents.
- [**no-ai-slop**](https://github.com/petergyang/no-ai-slop) - (13.6k ⭐) - Editing skill that removes 20+ AI-writing patterns while preserving the writer's voice.
- [**claude-skills**](https://github.com/Jeffallan/claude-skills) - (12.5k ⭐) - 66 Specialized Skills for Full-Stack Developers.
- [**jakubkrehel/skills**](https://github.com/jakubkrehel/skills) - (12.4k ⭐) - Agent skills for interface animation, UI polish, accessibility, and product writing.
- [**improve**](https://github.com/shadcn/improve) - (12.1k ⭐) - Use your most capable model to audit your codebase and write plans for cheaper models to execute.
- [**fireworks-tech-graph**](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) - (12.0k ⭐) - Claude Code skill for generating production-quality SVG+PNG technical diagrams.
- [**Claude-BugHunter**](https://github.com/elementalsouls/Claude-BugHunter) - (11.8k ⭐) - A Claude Code skill bundle for bug hunting and external red-team work — 71 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.
- [**geo-seo-claude**](https://github.com/zubair-trabzada/geo-seo-claude) - (11.8k ⭐) - GEO-first SEO skill for Claude Code. Comprehensive AI search optimization for any website — citability scoring, AI crawler analysis, brand authority, schema markup, platform-specific optimization, and PDF reports.
- [**huggingface skills**](https://github.com/huggingface/skills) - (11.4k ⭐) - Give your agents the power of the Hugging Face ecosystem.
- [**Claude-Red**](https://github.com/SnailSploit/Claude-Red) - (11.2k ⭐) - A curated library of offensive security skills designed for the Claude skills system.
- [**ui-skills**](https://github.com/ibelick/ui-skills) - (11.2k ⭐) - A growing set of skills to polish interfaces built by agents.
- [**slavingia/skills**](https://github.com/slavingia/skills) - (11.2k ⭐) - Claude Code skills based on The Minimalist Entrepreneur by Sahil Lavingia.
- [**autoharness**](https://github.com/tigerless-labs/autoharness) - (11.2k ⭐) - A self-learning skill layer for Claude Code that distills reusable skills from sessions, updates them over time, and prunes unused ones.
- [**visual-explainer**](https://github.com/nicobailon/visual-explainer) - (11.2k ⭐) - Agent skill + prompt templates that generate rich HTML pages for visual diff reviews, architecture overviews, plan audits, data tables, and project recaps.
- [**claude-ads**](https://github.com/AgriciDaniel/claude-ads) - (11.1k ⭐) - Comprehensive paid advertising audit & optimization skill for Claude Code.
- [**scroll-world**](https://github.com/oso95/scroll-world) - (11.1k ⭐) - A skill for turning a brand into a scrollable 3D world.
- [**drawio-skill**](https://github.com/Agents365-ai/drawio-skill) - (10.9k ⭐) - Generate draw.io diagrams from natural language — 6 presets, vision self-check + up to 5-round refinement, codebase-to-diagram, 10,000+ official shapes & 321 AI/LLM brand logos.
- [**huggingface skills**](https://github.com/numman-ali/openskills) - (10.8k ⭐) - Universal skills loader for AI coding agents.
- [**open-seo-mcp-skills**](https://github.com/Ryze-AI-Adgent/open-seo-mcp-skills) - (10.7k ⭐) - SEO and GEO skills for Claude Code, with a Ryze MCP connector for Search Console, Analytics, ads, rankings, and backlinks.
- [**BrowserSkill**](https://github.com/Tencent/BrowserSkill) - (10.6k ⭐) - CLI and browser extension that let AI agents use your logged-in browser without interrupting your work.
- [**stitch-skills**](https://github.com/google-labs-code/stitch-skills) - (10.6k ⭐) - A library of Agent Skills designed to work with the Stitch MCP server.
- [**replica-skill**](https://github.com/Jakeschincariol/replica-skill) - (9.9k ⭐) - Eleven Claude skills for examining an app, rebuilding it, testing the result, and addressing usability problems.
- [**universal-modder**](https://github.com/rehan-remade/universal-modder) - (9.8k ⭐) - Skills and tools for investigating, building, testing, and documenting mods for PC games with Claude Code.
- [**awesome-gamedev-agent-skills**](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) - (9.5k ⭐) - Game development skills for engines and frameworks including Godot, Unity, Unreal, Phaser, Bevy, and Roblox.
- [**html-ppt-skill**](https://github.com/lewislulu/html-ppt-skill) - (9.2k ⭐) - HTML PPT Studio — AgentSkill with 24 themes, 31 layouts, 20+ animations for building professional HTML presentations.
- [**android-reverse-engineering-skill**](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) - (8.8k ⭐) - Claude Code skill to support Android app's reverse engineering.
- [**day-trader-skill**](https://github.com/Jakeschincariol/day-trader-skill) - (8.7k ⭐) - Day-trading skills for chart scanning, news monitoring, trade simulations, position sizing, and risk checks, with paper trading as the default.
- [**Research-Paper-Writing-Skills**](https://github.com/Master-cai/Research-Paper-Writing-Skills) - (8.4k ⭐) - Skill package for ML/CV/NLP paper writing, curated and adapted from Prof. Peng Sida's open notes for Codex, Claude Code, and Gemini.
- [**marketing-skills**](https://github.com/irinabuht12-oss/marketing-skills) - (8.3k ⭐) - 48 free Claude marketing skills for Google Ads, Meta Ads, SEO, and AI visibility, plus Ryze MCP.
- [**skills**](https://github.com/trailofbits/skills) - (8.3k ⭐) - Trail of Bits Claude Code skills for security research, vulnerability detection, and audit workflows.
- [**axton-obsidian-visual-skills**](https://github.com/trailofbits/skills) - (8.3k ⭐) - Trail of Bits Claude Code skills for security research, vulnerability detection, and audit workflows.
- [**pixelfx**](https://github.com/patch-gg/pixelfx) - (8.2k ⭐) - Code-based pixel art effects library with sprite-sheet exports and a Claude Code skill for creating and refining custom effects through visual review.
- [**guizang-social-card-skill**](https://github.com/op7418/guizang-social-card-skill) - (8.2k ⭐) - Claude Code / Codex skill — generate Xiaohongshu carousels & WeChat 21:9+1:1 cover pairs.
- [**ffmpeg-skill**](https://github.com/kajisho5/ffmpeg-skill) - (8.2k ⭐) - Local FFmpeg Agent Skill for Claude Code, Cursor, and Codex with structured video and audio editing tools.
- [**Product-Manager-Skills**](https://github.com/deanpeters/Product-Manager-Skills) - (8.1k ⭐) - Product Management skills framework built on battle-tested methods for Claude Code, Cowork, Codex, and AI agents.
- [**codex-ppt-skill**](https://github.com/ningzimu/codex-ppt-skill) - (8.0k ⭐) - GPT-Image-2 PPT generator skill for creating image-based slide decks.
- [**Stickman Video Director**](https://github.com/kaomei/stickman-video-director) - (8.0k ⭐) - Agent skill that turns scripts into animated stick-figure videos with voiceover, captions, and sound effects.
- [**notebooklm-skill**](https://github.com/PleasePrompto/notebooklm-skill) - (7.8k ⭐) - Use this skill to enable Claude Code to communicate directly with your Google NotebookLM notebooks.
- [**MengTo Skills**](https://github.com/MengTo/Skills) - (7.8k ⭐) - Agent skills for design, web development, game development, and creative work across Claude Code, Codex, and other coding agents.
- [**architecture-diagram-generator**](https://github.com/Cocoon-AI/architecture-diagram-generator) - (7.6k ⭐) - Generate beautiful dark-themed system architecture diagrams as standalone HTML/SVG files.
- [**Waza**](https://github.com/tw93/Waza) - (7.6k ⭐) - Engineering habits you already know, turned into skills Claude can run.
- [**cheat-on-content**](https://github.com/XBuilderLAB/cheat-on-content) - (7.6k ⭐) - A skill that turns every post into a calibrated experiment.
- [**gc-minimal-zine-poster**](https://github.com/LiamGvchi/gc-minimal-zine-poster) - (7.5k ⭐) - Codex skill for generating quiet, minimal zine-style editorial poster prompts and images.
- [**remotion-dev/skills**](https://github.com/remotion-dev/skills) - (7.5k ⭐) - Official Remotion skills for creating video compositions, writing React animations, previewing projects, and rendering videos or stills.
- [**Agent Scripts**](https://github.com/steipete/agent-scripts) - (7.5k ⭐) - Shared instructions, workflow skills, scripts, and validation hooks for Claude Code and other coding agents.
- [**godogen**](https://github.com/htdt/godogen) - (7.4k ⭐) - Claude Code skills that build complete Godot 4 projects from a game description.
- [**logo-design-skill**](https://github.com/kaankiziltug/logo-design-skill) - (7.3k ⭐) - Logo design skill with guidance on visual principles, SVG production, testing, and a reference library.
- [**geo-sleuth**](https://github.com/Oldcircle/geo-sleuth) - (7.3k ⭐) - Photo geolocation skill that compares OpenStreetMap geometry, elevation skylines, satellite imagery, and street view to estimate camera position.
- [**instagram-agent-skill**](https://github.com/Jakeschincariol/instagram-agent-skill) - (7.2k ⭐) - Claude skills for Instagram Reels, carousels, captions, profile reviews, content planning, and post analysis.
- [**claude-trading-skills**](https://github.com/tradermonty/claude-trading-skills) - (7.2k ⭐) - Claude Code skills for equity investors and traders, including market research and analysis workflows.
- [**internet-court-skill**](https://github.com/internet-court/internet-court-skill) - (7.1k ⭐) - Agent Skill for natural-language mandates, delegated permissions, payments, escrow, and dispute resolution.
- [**anysearch-skill**](https://github.com/anysearch-ai/anysearch-skill) - (6.9k ⭐) - Unified real-time search engine skill for AI agents.
- [**autoresearch**](https://github.com/uditgoenka/autoresearch) - (6.8k ⭐) - Turn Claude Code into a relentless improvement engine.
- [**social-media-research-skills**](https://github.com/ScrapeCreators/social-media-research-skills) - (6.7k ⭐) - Social-media research skills for AI agents powered by ScrapeCreators.
- [**dev-browser**](https://github.com/SawyerHood/dev-browser) - (6.7k ⭐) - A Claude Skill to give your agent the ability to use a web browser.
- [**asd-ste100-skill**](https://github.com/danyuchn/asd-ste100-skill) - (6.7k ⭐) - Claude Code skill that applies ASD-STE100 Simplified Technical English rules to ambiguous instructions for agents.
- [**n8n-skills**](https://github.com/czlonkowski/n8n-skills) - (6.7k ⭐) - n8n skillset for Claude Code to build flawless n8n workflows.
- [**everything-claude-code**](https://github.com/WorldFlowAI/everything-claude-code) - (6.6k ⭐) - A Claude Code toolkit with agents, skills, hooks, commands, rules, and MCP configurations for day-to-day development.
- [**ip-as-logo-skill**](https://github.com/s1dashu/ip-as-logo-skill) - (6.6k ⭐) - Agent Skill for generating simple, rounded IP mascot logos with subtle neo-skeuomorphic styling.
- [**SwiftUI-Agent-Skill**](https://github.com/twostraws/SwiftUI-Agent-Skill) - (6.6k ⭐) - SwiftUI agent skill for Claude Code, Codex, and other AI tools.
- [**answer-me-with-html**](https://github.com/QingYunA/answer-me-with-html) - (6.6k ⭐) - Agent skill that presents complex answers as a readable, self-contained HTML page.
- [**qiaomu-anything-to-notebooklm**](https://github.com/joeseesun/qiaomu-anything-to-notebooklm) - (6.5k ⭐) - Claude skill for processing WeChat articles, web pages, YouTube videos, PDFs, Markdown, and search queries into NotebookLM-ready materials.
- [**youtube-agent-skill**](https://github.com/Jakeschincariol/youtube-agent-skill) - (6.5k ⭐) - Claude skills for YouTube scripts, title and thumbnail reviews, transcript-based edit plans, retention analysis, Shorts, and channel audits.
- [**agents-cli**](https://github.com/google/agents-cli) - (6.4k ⭐) - The CLI and skills that turn any coding assistant into an expert at creating, evaluating, and deploying AI agents on Google Cloud.
- [**GPT-Image2-Skill**](https://github.com/wuyoscar/GPT-Image2-Skill) - (6.1k ⭐) - GPT Image 2 prompt gallery, image prompt library, agentic skill, and CLI for OpenAI image generation/editing.
- [**gpt_image_2_skill**](https://github.com/wuyoscar/gpt_image_2_skill) - (6.1k ⭐) - GPT Image 2 prompt gallery, image prompt library, agentic skill, and CLI for OpenAI image generation/editing.
- [**SenseNova-Skills**](https://github.com/OpenSenseNova/SenseNova-Skills) - (6.1k ⭐) - Modular SenseNova skills for building AI-powered office assistants and productivity workflows.
- [**antfu's skills**](https://github.com/antfu/skills) - (6.1k ⭐) - Anthony Fu's curated collection of agent skills.
- [**linkedin-skills**](https://github.com/sergebulaev/linkedin-skills) - (6.1k ⭐) - Claude skills for LinkedIn: write human-sounding posts, craft comments, analyze your feed, and build a publishing cadence from the terminal.
- [**claude-design-engineer**](https://github.com/Dammyjay93/claude-design-engineer) - (6.0k ⭐) - Design engineering for Claude Code. Craft, memory, and enforcement for consistent UI.
- [**agent-sprite-forge**](https://github.com/0x0funky/agent-sprite-forge) - (5.8k ⭐) - Agent Skill for generating 2D sprite sheets and map, transparent PNG frames, and animated GIFs from prompts.
- [**codebase-to-course**](https://github.com/zarazhangrui/codebase-to-course) - (5.8k ⭐) - A Claude Code skill that turns any codebase into a beautiful, interactive single-page HTML course for non-technical vibe coders.
- [**lottie**](https://github.com/diffusionstudio/lottie) - (5.8k ⭐) - Generate production-ready Lottie animations with Claude Code or Codex.
- [**avoid-ai-writing**](https://github.com/conorbronsdon/avoid-ai-writing) - (5.7k ⭐) - Skill that audits and rewrites text to remove common signs of AI-generated writing.
- [**academic-humanizer**](https://github.com/AIScientists-Dev/academic-humanizer) - (5.6k ⭐) - Academic writing skill for revising research text into clearer, more natural prose while preserving technical meaning.
- [**obsidian-second-brain**](https://github.com/eugeniughelbur/obsidian-second-brain) - (5.4k ⭐) - Persistent memory for Claude Code and other agents in an Obsidian vault, with linked Markdown notes, semantic search, and a shared agent logbook.
- [**excalidraw-diagram-skill**](https://github.com/coleam00/excalidraw-diagram-skill) - (5.3k ⭐) - Skill to give Claude Code (and any coding agent) the ability to generate beautiful and practical Excalidraw diagrams.
- [**appllama-skills**](https://github.com/Appllama/appllama-skills) - (5.2k ⭐) - Agent skills that turn top-grossing app patterns into native-quality mobile screens.
- [**design-extract**](https://github.com/Manavarya09/design-extract) - (5.2k ⭐) - Extract a website's complete design system into design tokens, UI themes, component anatomy, and platform-specific code.
- [**HyperResearch**](https://github.com/jordan-gibbs/hyperresearch) - (4.9k ⭐) - Deep research skill for Claude Code and Codex that saves web findings in a persistent, searchable wiki.
- [**social-media-skills**](https://github.com/charlie947/social-media-skills) - (4.7k ⭐) - Agent skills for planning, writing, and managing social media content.
- [**SimpleEnglish**](https://github.com/AminBlg/SimpleEnglish) - (4.6k ⭐) - An Agent Skill that applies ASD-STE100 Simplified Technical English rules to documentation produced by Claude Code, Codex, and other compatible agents.
- [**adhd**](https://github.com/UditAkhourii/adhd) - (4.6k ⭐) - A skill for coding agents. Tree-of-thought with pruning, built on the Claude & Codex Agent SDK.
- [**seedance2-skill**](https://github.com/dexhunter/seedance2-skill) - (4.5k ⭐) - Skill to create best prompts for generating videos with seedance2.0
- [**gemini-skills**](https://github.com/google-gemini/gemini-skills) - (4.5k ⭐) - Skills for the Gemini API, SDK and model/agent interactions.
- [**unlazy**](https://github.com/Leonxlnx/unlazy) - (4.4k ⭐) - Agent skill that uses a depth-tree method to break tasks into deeper work units and counter premature completion.
- [**leanrea**](https://github.com/aicodeking/leanrea) - (4.4k ⭐) - Reverse-engineering skill that guides agents through native binaries, Electron apps, Android packages, and firmware with standard command-line tools.
- [**blender-skills**](https://github.com/arjun988/blender-skills) - (4.3k ⭐) - Blender skills for modeling, technical art, scene production, and game-engine export through Blender MCP.
- [**davidondrej/skills**](https://github.com/davidondrej/skills) - (4.3k ⭐) - Reusable Agent Skills for coding, research, workflow orchestration, documentation, operations, and skill authoring.
- [**threejs-skills**](https://github.com/CloudAI-X/threejs-skills) - (4.3k ⭐) - A curated collection of Three.js skill files that provide Claude Code with foundational knowledge for creating 3D elements and interactive experiences.
- [**NotFair**](https://github.com/nowork-studio/NotFair) - (4.3k ⭐) - Open-source Claude Code skills for SEO, GEO, Google Ads, Meta Ads.
- [**Swift-Agent-Skills**](https://github.com/nowork-studio/toprank) - (4.3k ⭐) - A curated directory of open-source AI agent skills for Swift and Apple platform development.
- [**effective-html**](https://github.com/plannotator/effective-html) - (4.3k ⭐) - Agent skill for elegant and simple html plans, architecture diagrams, or whatever else you can think of.
- [**founder-skill**](https://github.com/Jakeschincariol/founder-skill) - (4.2k ⭐) - Claude skills for evaluating business ideas, customer demand, pricing, profit margins, competitors, and launch plans.
- [**Claude Animated Shorts**](https://github.com/mromidev/claude-animated-shorts) - (4.2k ⭐) - Claude skill for creating vertical animated story shorts with 2D characters in 3D scenes, local Three.js and Remotion rendering, and procedural music and sound effects.
- [**Expo-Skills**](https://github.com/expo/skills) - (4.2k ⭐) - A collection of AI agent skills for working with Expo projects and Expo Application Services.
- [**tstack**](https://github.com/t3dotgg/tstack) - (4.2k ⭐) - Agent skills for pull request preparation, model-based code review, CI follow-up, branch maintenance, and completing existing development work.
- [**make-interfaces-feel-better**](https://github.com/jakubkrehel/make-interfaces-feel-better) - (4.2k ⭐) - Interface design skill based on the "Details that make interfaces feel better" article.
- [**NVIDIA skills**](https://github.com/NVIDIA/skills) - (4.1k ⭐) - AI agent skills published by NVIDIA.
- [**Dimillian Skills**](https://github.com/Dimillian/Skills) - (4.0k ⭐) - A collection of reusable development skills for Apple platforms, GitHub workflows, refactoring, diff review swarms, bug investigation swarms, code review, React performance work, and skill curation.
- [**sanyuan-skills**](https://github.com/sanyuan0704/sanyuan-skills) - (4.0k ⭐) - Expert code review skill: SOLID, security, performance, error handling, boundary conditions.
- [**AI-research-SKILLs**](https://github.com/sanyuan0704/code-review-expert) - (4.0k ⭐) - A comprehensive code review skill for AI agents.
- [**SwiftUI-Agent-Skill**](https://github.com/AvdLee/SwiftUI-Agent-Skill) - (3.9k ⭐) - Agent Skill guidance for building SwiftUI apps with current best practices.
- [**Scenario Agent Skills**](https://github.com/scenario-labs/skills) - (3.9k ⭐) - Skills for generating images, video, audio, and 3D assets through Scenario MCP with shared character and brand references.
- [**cc-skills-golang**](https://github.com/samber/cc-skills-golang) - (3.9k ⭐) - A collection of Golang agentic skills that works.
- [**sepia**](https://github.com/Nanako0129/sepia) - (3.9k ⭐) - A writing skill for Claude Code, Codex, Grok Build, and Antigravity that repairs narrative structure in fiction and applies venue-specific rules to professional prose.
- [**Kami**](https://github.com/ericosiu/ai-marketing-skills) - (3.9k ⭐) - Good content deserves good paper.
- [**ai-marketing-skills**](https://github.com/ericosiu/ai-marketing-skills) - (3.9k ⭐) - Open-source AI marketing skills — growth experiments, sales pipeline, content ops, outbound, SEO, and finance automation.
- [**Vibe-Skills**](https://github.com/foryourhealth111-pixel/Vibe-Skills) - (3.8k ⭐) - An all-in-one AI skills package.
- [**teardown**](https://github.com/elvarofficial/teardown) - (3.8k ⭐) - Claude Code skill for building interactive 3D machine simulators as self-contained offline HTML pages, with explorable parts, live readouts, and optional video capture.
- [**benjitaylor/skills**](https://github.com/benjitaylor/skills) - (3.8k ⭐) - Design and motion skills for coding agents, including Stageshow for React product illustrations and animated UI demos.
- [**obsidian-wiki**](https://github.com/Ar9av/obsidian-wiki) - (3.8k ⭐) - Skills for building and maintaining an Obsidian knowledge wiki, with source ingestion, linked notes, conversation capture, and queries.
- [**Browserbase Skills**](https://github.com/browserbase/skills) - (3.8k ⭐) - Browserbase's official collection of agent skills to access the web.
- [**ctf-skills**](https://github.com/ljagiello/ctf-skills) - (3.7k ⭐) - Agent skills for solving CTF challenges - web exploitation, binary pwn, crypto, reverse engineering, forensics, OSINT, and more.
- [**awesome-design-skills**](https://github.com/bergside/awesome-design-skills) - (3.7k ⭐) - Design skill directory for agentic tools, covering DESIGN.md and SKILL.md files for Claude Design, Codex, Cursor, and related AI tools.
- [**Acontext**](https://github.com/memodb-io/Acontext) - (3.7k ⭐) - Agent Skills used as a memory layer for context engineering and self-learning agent workflows.
- [**mono-color-skill**](https://github.com/yanliudesign/mono-color-skill) - (3.7k ⭐) - One-ink editorial print image skill with warm paper, halftone photography, active negative space, and restrained typography.
- [**apple-design-skill**](https://github.com/dickwu/apple-design-skill) - (3.6k ⭐) - UI design review skill based on Apple's Human Interface Guidelines, with guidance for SwiftUI, Flutter, React Native, Tauri, and Electron.
- [**finance-skills**](https://github.com/himself65/finance-skills) - (3.6k ⭐) - A collection of skills for AI financial analysis and trading.
- [**agent-toolkit-for-aws**](https://github.com/aws/agent-toolkit-for-aws) - (3.5k ⭐) - AWS-supported MCP servers, skills, and plugins for agents that build on AWS.
- [**science-skills**](https://github.com/google-deepmind/science-skills) - (3.5k ⭐) - Google DeepMind science skills for agentic scientific workflows.
- [**claudex-loop**](https://github.com/chaseai-yt/claudex-loop) - (3.5k ⭐) - Claude Code skill for hardening implementation plans through reconnaissance, focused questioning, adversarial Codex review, and cross-model build inspection.
- [**crucible**](https://github.com/chaseai-yt/crucible) - (3.5k ⭐) - Claude Code skill that hardens implementation plans through reconnaissance, focused questioning, and adversarial Codex review.
- [**markdown-viewer skills**](https://github.com/markdown-viewer/skills) - (3.4k ⭐) - Opinionated skills for AI coding agents to create stunning diagrams and visualizations directly in Markdown.
- [**designer-skills**](https://github.com/Owl-Listener/designer-skills) - (3.4k ⭐) - Designer skills, commands, and templates for agentic design workflows.
- [**vue-skills**](https://github.com/vuejs-ai/skills) - (3.4k ⭐) - Agent skills for Vue 3 development.
- [**vue-skills**](https://github.com/hyf0/vue-skills) - (3.4k ⭐) - Agent skills for Vue 3 development.
- [**automotive-skills-suite**](https://github.com/jherrodthomas/automotive-skills-suite) - (3.3k ⭐) - Installable Claude skills for automotive engineering, diagnostics, safety, and service workflows.
- [**agent-rules-books**](https://github.com/ciembor/agent-rules-books) - (3.3k ⭐) - AGENTS.md rules and skills for Codex, Cursor, Claude Code, Gemini CLI, and related coding agents.
- [**playwright-skill**](https://github.com/lackeyjb/playwright-skill) - (3.3k ⭐) - Claude Code Skill for browser automation with Playwright. Model-invoked - Claude autonomously writes and executes custom automation for testing and validation.
- [**comet**](https://github.com/rpamis/comet) - (3.3k ⭐) - Agent skill harness for phase-guarded automation from idea to implementation.
- [**chrome-cdp-skill**](https://github.com/pasky/chrome-cdp-skill) - (3.3k ⭐) - Give your AI agent access to your live Chrome session — works out of the box, connects to tabs you already have open.
- [**ShipSwift**](https://github.com/signerlabs/ShipSwift) - (3.3k ⭐) - Agent skills and a SwiftUI library for building iOS interfaces with reusable components, animations, charts, and Metal shaders.
- [**9arm-skills**](https://github.com/thananon/9arm-skills) - (3.3k ⭐) - Agent skills loaded by Claude Code.
- [**ResumeSkills**](https://github.com/Paramchoudhary/ResumeSkills) - (3.3k ⭐) - Career and job-search skills for resume writing, ATS optimization, interview preparation, and applications.
- [**loopy**](https://github.com/Forward-Future/loopy) - (3.2k ⭐) - Practical AI-agent loops and an installable skill for finding, adapting, and designing repeatable agent workflows.
- [**skills**](https://github.com/microsoft/skills) - (3.2k ⭐) - Skills, MCP servers, Custom Agents, Agents.md for SDKs to ground Coding Agents.
- [**ux-ui-agent-skills**](https://github.com/plugin87/ux-ui-agent-skills) - (3.2k ⭐) - Design workflow with DTCG tokens, 50 components, WCAG 2.2, 138 design systems, framework-agnostic code, and objective quality gates.
- [**Flutter Agent Skills**](https://github.com/flutter/skills) - (3.2k ⭐) - A collection of skills providing tailored instructions for happy path Flutter app development workflows.
- [**claude-skills-llm-council**](https://github.com/aiwithremy/claude-skills-llm-council) - (3.2k ⭐) - Claude Code skill that routes decisions through a council of AI advisors with peer review.
- [**web-quality-skills**](https://github.com/addyosmani/web-quality-skills) - (3.1k ⭐) - Agent Skills for optimizing web quality based on Lighthouse and Core Web Vitals.
- [**diagram-design**](https://github.com/supabase/agent-skills) - (3.1k ⭐) - Thirteen editorial diagram types for Claude Code. Self-contained HTML + SVG. No shadows, no Mermaid-slop.
- [**agent-skills**](https://github.com/supabase/agent-skills) - (3.1k ⭐) - Agent Skills to help developers using AI agents with Supabase.
- [**AlphaGBM/skills**](https://github.com/AlphaGBM/skills) - (3.1k ⭐) - Real-data options intelligence skills for AI agents, with Claude Code and Cursor support.
- [**Claude-OSINT**](https://github.com/elementalsouls/Claude-OSINT) - (3.1k ⭐) - Paired Claude skills for OSINT work, with recon modules, search patterns, and investigation workflows.
- [**Token Optimizer**](https://github.com/alexgreensh/token-optimizer) - (3.0k ⭐) - Claude Code skill with hooks for auditing context usage, reducing wasted tokens, preserving work across compaction, and tracking tokens, costs, and context quality in a live dashboard.
- [**seedance-prompt-skill**](https://github.com/songguoxs/seedance-prompt-skill) - (3.0k ⭐) - A Claude Code custom skill that turns Claude into a professional AI video prompt engineer for ByteDance's Seedance 2.0 (即梦) video generation platform.
- [**herk-edit-kit**](https://github.com/nateherkai/herk-edit-kit) - (3.0k ⭐) - Video-editing skills for Claude Code and Codex with transcript-based cuts, captions, story planning, and HyperFrames motion graphics.
- [**oil-motion**](https://github.com/oil-oil/oil-motion) - (2.9k ⭐) - Agent-agnostic interactive animation skill for creating smooth web motion that responds to scroll, mouse, drag, touch, or device orientation.
- [**claude-code-plugins-plus-skills**](https://github.com/jeremylongshore/claude-code-plugins-plus-skills) - (2.9k ⭐) - 270+ Claude Code plugins with 739 agent skills.
- [**ai-marketing-claude**](https://github.com/zubair-trabzada/ai-marketing-claude) - (2.9k ⭐) - A comprehensive marketing analysis and automation skill system for Claude Code.
- [**TypeSafe Agent Skills**](https://github.com/typesafe-ai/skills) - (2.9k ⭐) - Skills for building typed decision workflows with TypeSafe System One models.
- [**Claude-to-IM-skill**](https://github.com/op7418/Claude-to-IM-skill) - (2.9k ⭐) - Bridge Claude Code / Codex to IM platforms — chat with AI coding agents from Telegram, Discord, or Feishu/Lark.
- [**nothing-design-skill**](https://github.com/dominikmartn/nothing-design-skill) - (2.9k ⭐) - A Claude Code skill for generating UI in the Nothing design language. Monochrome, typographic, industrial.
- [**claude-blog**](https://github.com/AgriciDaniel/claude-blog) - (2.8k ⭐) - Claude Code blog skill suite with sub-skills, agents, and quality gates for SEO-focused and AI-citation-ready publishing workflows.
- [**SkillClaw**](https://github.com/AMAP-ML/SkillClaw) - (2.8k ⭐) - Agentic evolver for creating and improving agent skills collectively.
- [**Bang Motion**](https://github.com/bangtutorial/bang-motion) - (2.7k ⭐) - Motion graphics skill that creates openers, promos, and animated explainers as a single HTML file.
- [**wondelai/skills**](https://github.com/wondelai/skills) - (2.7k ⭐) - Agent skills for Claude Code and agentskills.io-compatible coding agents.
- [**agent-toolkit**](https://github.com/softaworks/agent-toolkit) - (2.7k ⭐) - A curated collection of skills for AI coding agents.
- [**hack-skills**](https://github.com/yaklang/hack-skills) - (2.7k ⭐) - Practical hacking skills for AI agents working on security research and offensive security workflows.
- [**mcp_excalidraw**](https://github.com/yctimlin/mcp_excalidraw) - (2.7k ⭐) - MCP server and Claude Code skill for Excalidraw — programmatic canvas toolkit to create, edit, and export diagrams via AI agents with real-time canvas sync.
- [**ex-USSR Kinship Research**](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) - (2.7k ⭐) - Genealogy research skill for Claude Code, Codex, and compatible agents, with archival search, historical jurisdiction checks, traceable evidence, and research logs for former Soviet territories.
- [**stack-diagram**](https://github.com/caru-ini/stack-diagram) - (2.6k ⭐) - Agent skill for drawing architecture diagrams from plain-language stack descriptions, with official technology logos and support for Claude Code, Codex, and Cursor.
- [**delegate-skills**](https://github.com/amElnagdy/delegate-skills) - (2.6k ⭐) - Delegate coding tasks to a separate agent CLI, review the diff, and land the commit yourself.
- [**Deep-Research-skills**](https://github.com/Weizhena/Deep-Research-skills) - (2.6k ⭐) - Structured deep research skill for Claude Code, OpenCode, and Codex, with human-in-the-loop controls for research workflows.
- [**learning-opportunities**](https://github.com/DrCatHicks/learning-opportunities) - (2.6k ⭐) - A Claude or Codex skill for deliberate skill development during AI-assisted coding.
- [**interview-coach-skill**](https://github.com/noamseg/interview-coach-skill) - (2.6k ⭐) - Claude Code interview coach for the full job-search lifecycle, from JD analysis and resume optimization through mock interviews and post-offer negotiation.
- [**story-to-handdrawn-video**](https://github.com/gnipbao/story-to-handdrawn-video) - (2.5k ⭐) - Agent skill that turns Chinese stories or ordered images into hand-drawn diary-comic animations.
- [**Apify Agent Skills**](https://github.com/apify/agent-skills) - (2.5k ⭐) - Production-grade web scraping and automation skills for AI coding agents.
- [**kotlin-footguns**](https://github.com/maxrave-dev/kotlin-footguns) - (2.5k ⭐) - Agent skills and a change scanner for common Kotlin, Compose Multiplatform, and desktop JVM pitfalls drawn from a production music app.
- [**terraform-skill**](https://github.com/antonbabenko/terraform-skill) - (2.5k ⭐) - Terraform & OpenTofu Skill for AI Agents - testing, modules, CI/CD, and production patterns.
- [**Claudeception**](https://github.com/blader/Claudeception) - (2.5k ⭐) - A Claude Code skill for autonomous skill extraction and continuous learning. Have Claude Code get smarter as it works.
- [**blader**](https://github.com/blader/claude-code-continuous-learning-skill) - (2.5k ⭐) - A Claude Code skill for autonomous skill extraction and continuous learning. Have Claude Code get smarter as it works.
- [**dream-loop**](https://github.com/achimala/dream-loop) - (2.4k ⭐) - Agent skill that builds games, apps, and scenes through image-generated targets, implementation, and AI critic feedback.
- [**translate-book**](https://github.com/deusyu/translate-book) - (2.4k ⭐) - Claude Code skill that translates full books in PDF, DOCX, or EPUB format with parallel subagents.
- [**agents-best-practices**](https://github.com/DenisSergeevitch/agents-best-practices) - (2.4k ⭐) - Provider-neutral agent skill for Codex, Claude Code, and other AI coding tools.
- [**agent-skill-creator**](https://github.com/FrancyJGLisboa/agent-skill-creator) - (2.4k ⭐) - Skill for turning repeatable workflows into reusable AI agent skills.
- [**TourMind Booking Skills**](https://github.com/tourmind-com/Tourmind-Booking-Skills) - (2.4k ⭐) - Skills for searching and comparing live hotel and flight options, then managing bookings through the TourMind API.
- [**logo-generator-skill**](https://github.com/op7418/logo-generator-skill) - (2.4k ⭐) - Professional SVG logo generator with high-end showcase presentations.
- [**agent-skills**](https://github.com/WordPress/agent-skills/) - (2.4k ⭐) - Expert-level WordPress knowledge for AI coding assistants - blocks, themes, plugins, and best practices.
- [**blender-skills**](https://github.com/EL4CTEO/blender-skills) - (2.4k ⭐) - Blender skills for modeling, UV mapping, PBR materials, baking, rigging, animation, and export checks.
- [**Youtube-clipper-skill**](https://github.com/op7418/Youtube-clipper-skill) - (2.4k ⭐) - Download videos, generate semantic chapters, clip segments, translate subtitles to bilingual format, and burn subtitles into videos.
- [**Khazix-Skills**](https://github.com/op7418/Youtube-clipper-skill) - (2.4k ⭐) - DA collection of AI Skills for managing and evolving your skill library.
- [**icm-architect**](https://github.com/RinDig/icm-architect) - (2.4k ⭐) - Claude skill for turning a process, idea, or problem into an ICM workspace organized as an agent architecture.
- [**fable-method**](https://github.com/Sahir619/fable-method) - (2.3k ⭐) - Four evidence-tested skills that guide coding agents through planning, execution, verification, and creation of domain-specific workflows.
- [**claude-real-video**](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) - (2.3k ⭐) - Claude Code skill for real-video generation workflows, including planning, prompts, and production steps.
- [**aso-skills**](https://github.com/appeeky/aso-skills) - (2.3k ⭐) - AI agent skills for App Store Optimization and app marketing, including keyword research, metadata optimization, competitor analysis, and app growth.
- [**aso-skills**](https://github.com/Eronred/aso-skills) - (2.3k ⭐) - AI agent skills for App Store Optimization and app growth workflows.
- [**MotionSites Web Builder**](https://github.com/Motionsites-AI/claude-skill) - (2.3k ⭐) - Claude skill for building landing pages with design references, cinematic media, animation recipes, detailed build specifications, and screenshot-based quality checks.
- [**code-review-skill**](https://github.com/awesome-skills/code-review-skill) - (2.3k ⭐) - Comprehensive code review skill for Claude Code, covering React, Vue, Rust, TypeScript, TanStack Query, and related stacks.
- [**dimensional-drawing**](https://github.com/enesozturk/dimensional-drawing) - (2.2k ⭐) - Skills for creating labeled technical drawings of UI components, with spacing, radii, layers, exploded views, and an optional animation workflow.
- [**animate**](https://github.com/cth9191/animate) - (2.1k ⭐) - Claude Code skill for creating procedural animated videos with Canvas, storyboard reviews, reference-based styles, and MP4 export.
- [**gateway-skills**](https://github.com/Leanmcp/gateway-skills) - (2.1k ⭐) - Skills for MCP development, model inference and training, research, and security, with AI Gateway setup for request logs and token tracking.
- [**screenwriting-skills**](https://github.com/jtydhr88/screenwriting-skills) - (2.1k ⭐) - Agent skills for screenwriting, television writing, and dramaturgy.
- [**chops**](https://github.com/Shpigford/chops) - (2.1k ⭐) - macOS app for browsing, organizing, and using AI agent skills.
- [**medical-research-skills**](https://github.com/aipoch/medical-research-skills) - (2.1k ⭐) - Agent skills for medical research tasks, including protocol design, data analysis, evidence review, and academic writing.
- [**Beautiful Rust**](https://github.com/morganlinton/BeautifulRust) - (2.1k ⭐) - Skills for writing, reviewing, and porting idiomatic Rust, with reference guidance and a Clippy configuration.
- [**claude-design-system-prompt**](https://github.com/Trystan-SA/claude-design-system-prompt) - (2.1k ⭐) - A reverse-engineered design system prompt with 14 procedural skills for accessible interface design, prototyping, review, and visual refinement.
- [**Product Engineer Skills**](https://github.com/Trystan-SA/product-engineer-skills) - (2.1k ⭐) - Agent skills for auditing user flows, setting UX budgets, instrumenting product analytics, and designing and analyzing A/B tests.
- [**Higgsfield AI Skills**](https://github.com/higgsfield-ai/skills) - (2.0k ⭐) - Agent Skills for image and video generation, product photography, marketplace assets, and website creation through Higgsfield AI.
- [**ELI5**](https://github.com/DreambigOu/ELI5) - (2.0k ⭐) - Claude Code skill that explains anything to different audiences with the right tone, vocabulary, and analogies.
- [**native-feel-skill**](https://github.com/yetone/native-feel-skill) - (2.0k ⭐) - An Agent Skill for designing cross-platform desktop apps that feel native — distilled from Raycast's 2.0 deep-dive and reverse engineering of Raycast Beta.app.
- [**trader-skill**](https://github.com/Jakeschincariol/trader-skill) - (2.0k ⭐) - Claude skills for tracking investor activity and market news, sizing positions, and reviewing orders before submission.
- [**OpenOSINT**](https://github.com/OpenOSINT/OpenOSINT) - (1.9k ⭐) - Public-source research toolkit for AI agents with a skill, MCP server, and CLI. Findings include references to the tool calls that produced them.
- [**investorskills**](https://github.com/questflowai/investorskills) - (1.9k ⭐) - A library of structured investing frameworks drawn from durable investor decision patterns, built for study and use by AI finance agents.
- [**opc-skills**](https://github.com/ReScienceLab/opc-skills) - (1.9k ⭐) - Agent Skills for solopreneur workflows, including AI tooling, SEO, GEO, and operations tasks.
- [**nano-banana-pro-prompts-recommend-skill**](https://github.com/YouMind-OpenLab/nano-banana-pro-prompts-recommend-skill) - (1.9k ⭐) - Claude Code / Cursor skill to recommend from 6000+ Nano Banana Pro image prompts.
- [**sell-sessions-skill**](https://github.com/cookiy-ai/sell-sessions-skill) - (1.9k ⭐) - Skill and local uploader for selecting Claude Code and Codex sessions to license through Cookiy, with local secret and personal-data scrubbing before upload.
- [**BAMA**](https://github.com/daveebbelaar/bama) - (1.9k ⭐) - Skill pack for designing, building, and testing native macOS apps with Swift and SwiftUI.
- [**motion-skills**](https://github.com/iart-ai/motion-skills) - (1.9k ⭐) - Agent skill packs for motion graphics and video, including kinetic typography, animated charts, explainers, and short-form clips.
- [**ai-legal-claude**](https://github.com/zubair-trabzada/ai-legal-claude) - (1.8k ⭐) - AI legal assistant skill for contract review, legal research, and compliance workflows.
- [**context-engineering-kit**](https://github.com/NeoLabHQ/context-engineering-kit) - (1.8k ⭐) - Hand-crafted Claude Code skills for improving agent output quality, with compatibility across OpenCode, Cursor, Gemini CLI, and related tools.
- [**claude-skill-aso-appstore-screenshots**](https://github.com/adamlyttleapps/claude-skill-aso-appstore-screenshots) - (1.8k ⭐) - Claude skill for planning and producing App Store screenshot sets for ASO.
- [**Eval Skills**](https://github.com/ai-evals-course/evals-skills) - (1.8k ⭐) - Skills for auditing AI evaluation pipelines, finding failure modes in traces, and building product-specific evaluators.
- [**reanimate**](https://github.com/NiazMorshed2007/reanimate) - (1.8k ⭐) - Claude Code skill for recreating animations from websites, videos, or GIFs through frame-by-frame analysis, implementation, and timing and visual comparisons.
- [**Papermorph**](https://github.com/DozenTwelve/Papermorph) - (1.8k ⭐) - Agent skill for turning books into animated, narrated, interactive web experiences.
- [**grill-me-skill**](https://github.com/RobMitt/grill-me-skill) - (1.8k ⭐) - Claude Code and Cowork skill that interviews you about a plan one question at a time to resolve open decisions.
- [**Swift-Concurrency-Agent-Skill**](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) - (1.7k ⭐) - Expert Swift Concurrency guidance for AI coding agents working on Swift projects.
- [**female-portrait-director**](https://github.com/liyue-aigc/female-portrait-director) - (1.7k ⭐) - Modular Codex Skill for developing detailed AI female-portrait prompts.
- [**callstackincubator**](https://github.com/callstackincubator/agent-skills) - (1.7k ⭐) - A collection of agent-optimized React Native skills for AI coding assistants.
- [**Arcads AI Video**](https://github.com/mrpaidsocial/arcads-claude-code-mrpaidsocial) - (1.7k ⭐) - Skill pack and prompt library for creating marketing videos and images through the Arcads API.
- [**evals-skills**](https://github.com/hamelsmu/evals-skills) - (1.7k ⭐) - Skills for AI evaluation workflows and the AI Evals for Engineers course.
- [**azure-skills**](https://github.com/microsoft/azure-skills) - (1.7k ⭐) - Microsoft agent plugin with skills and MCP server configurations for Azure development scenarios.
- [**golive-skill**](https://github.com/mikehasa/golive-skill) - (1.6k ⭐) - Agent Skill and Node CLI for planning, approving, applying, and verifying product launch setup across hosting, domains, email, and payments.
- [**design-engineer-auditor-package**](https://github.com/kylezantos/design-engineer-auditor-package) - (1.6k ⭐) - A Claude Code skill for motion design audits, trained on Emil Kowalski, Jakub Krehel, and Jhey Tompkins.
- [**keep-codex-fast**](https://github.com/vibeforge1111/keep-codex-fast) - (1.6k ⭐) - A backup-first Codex skill for inspecting and maintaining local sessions, worktrees, logs, and project state.
- [**rust-skills**](https://github.com/actionbook/rust-skills) - (1.6k ⭐) - Rust Developer AI Assistance System — Meta-Problem-Driven Knowledge Indexing.
- [**material-3-skill**](https://github.com/hamen/material-3-skill) - (1.6k ⭐) - Material Design 3 skill for Claude Code, with components, design tokens, theming, responsive layout, and MD3 audit support.
- [**Memento-Skills**](https://github.com/Memento-Teams/Memento-Skills) - (1.6k ⭐) - Agent skills that help agents design and refine other agents.
- [**Pretty-mermaid-skills**](https://github.com/imxv/Pretty-mermaid-skills) - (1.6k ⭐) - To provide AI with Mermaid chart rendering capability, supporting both SVG and ASCII output formats.
- [**skillkit**](https://github.com/rohitg00/skillkit) - (1.6k ⭐) - Portable skill toolkit for installing, translating, and sharing skills across Claude Code, Cursor, Codex, Copilot, and other coding agents.
- [**pm-claude-skills**](https://github.com/mohitagw15856/pm-claude-skills) - (1.6k ⭐) - Product-management skill pack with Agent Skills, subagents, and slash commands for Claude, ChatGPT, Gemini, Cursor, Codex, and Hermes.
- [**ai-sales-team-claude**](https://github.com/zubair-trabzada/ai-sales-team-claude) - (1.5k ⭐) - Sales workflow system for Claude Code with prospect research, lead qualification, outreach, proposals, and pipeline reports.
- [**paper2code**](https://github.com/PrathamLearnsToCode/paper2code) - (1.5k ⭐) - Agent skill for turning arXiv papers into working code implementations.
- [**claude-code-skills**](https://github.com/daymade/claude-code-skills) - (1.5k ⭐) - Marketplace-style collection of production-ready Claude Code skills for development workflows.
- [**dzhng/skills**](https://github.com/dzhng/skills) - (1.5k ⭐) - Personal collection of Claude Code skills for repeatable engineering and knowledge-work tasks.
- [**COG-second-brain**](https://github.com/huytieu/COG-second-brain) - (1.5k ⭐) - A self-evolving second brain for Claude Code, Cursor, Kiro, Gemini CLI, and Codex, with AI skills, worker agents, and a people CRM.
- [**academic-paper-skills**](https://github.com/lishix520/academic-paper-skills) - (1.5k ⭐) - Claude Code framework for planning and writing academic papers with strategist and composer skills.
- [**lenny-skills**](https://github.com/RefoundAI/lenny-skills) - (1.5k ⭐) - Product management skill collection based on Lenny's Podcast, covering hiring, user research, strategy, shipping, and related PM workflows.
- [**Better Icons**](https://github.com/better-auth/better-icons) - (1.5k ⭐) - Skill, MCP server, and CLI for finding and retrieving icons from a large collection of icon libraries.
- [**skill-codex**](https://github.com/skills-directory/skill-codex) - (1.5k ⭐) - Claude Code skill for delegating prompts to Codex.
- [**kill-ai-slop**](https://github.com/yetone/kill-ai-slop) - (1.5k ⭐) - Field guide and Agent Skill for finding and removing AI-generated visual and copywriting clichés.
- [**motion-video-kit**](https://github.com/echris6/motion-video-kit) - (1.4k ⭐) - Claude Code skills and production guidance for creating motion-led business videos.
- [**VibeSec-Skill**](https://github.com/BehiSecc/VibeSec-Skill) - (1.4k ⭐) - This skill helps Claude write secure code and prevent common vulnerabilities.
- [**app-store-preflight-skills**](https://github.com/truongduy2611/app-store-preflight-skills) - (1.4k ⭐) - AI agent skill that scans iOS and macOS projects for common App Store rejection risks before submission.
- [**tutor-skills**](https://github.com/bevibing/tutor-skills) - (1.4k ⭐) - Claude Code skill that turns PDFs, documents, and codebases into Obsidian study vaults.
- [**seo-skills**](https://github.com/Illyism/seo-skills) - (1.4k ⭐) - SEO and content skills for site checks, title optimization, blog refreshes, backlinks, customer journeys, and video transcripts.
- [**motion-graphics**](https://github.com/Barty-Bart/motion-graphics) - (1.4k ⭐) - Motion graphics skills for Claude Code and Codex.
- [**skills**](https://github.com/juliobsz/skills) - (1.4k ⭐) - Website design and review skills for coding agents, with browser-based visual checks, accessibility checks, and a jury-style site assessment.
- [**gtm-engineer-skills**](https://github.com/onvoyage-ai/gtm-engineer-skills) - (1.4k ⭐) - Claude Code skill for website AEO and GEO audits, with checks for AI search visibility, structured data, and framework-specific fixes.
- [**skills-for-fabric**](https://github.com/microsoft/skills-for-fabric) - (1.4k ⭐) - Skills and MCP systems for using Microsoft Fabric from CLI, VS Code, Claude, and related agent workflows.
- [**langchain-skills**](https://github.com/langchain-ai/langchain-skills) - (1.3k ⭐) - LangChain skills repository for agent workflows and LangChain project work.
- [**manim_skill**](https://github.com/adithya-s-k/manim_skill) - (1.3k ⭐) - Agent skills for Manim to create 3Blue1Brown style animations.
- [**codex-first-customer-finder-skill**](https://github.com/Kappaemme-git/codex-first-customer-finder-skill) - (1.3k ⭐) - A Codex skill that finds evidence-backed potential first customers from recent public signals.
- [**ios-simulator-skill**](https://github.com/conorluddy/ios-simulator-skill) - (1.3k ⭐) - iOS Simulator skill for Claude Code that helps agents build, run, and interact with apps while preserving token context.
- [**guard-skills**](https://github.com/amElnagdy/guard-skills) - (1.3k ⭐) - Quality-gate skills that catch AI-generated failure modes in code, tests, and documentation.
- [**swift-ios-skills**](https://github.com/dpearson2699/swift-ios-skills) - (1.3k ⭐) - Agent Skills for iOS, Swift, SwiftUI, and modern Apple framework development.
- [**flyai-skill**](https://github.com/alibaba-flyai/flyai-skill) - (1.3k ⭐) - FlyAI agent skill repository.
- [**webgpu-claude-skill**](https://github.com/dgreenheck/webgpu-claude-skill) - (1.3k ⭐) - A Claude skill for developing WebGPU applications with Three.js.
- [**Xcode-Build-Optimization-Agent-Skill**](https://github.com/AvdLee/Xcode-Build-Optimization-Agent-Skill) - (1.3k ⭐) - An Agent Skill helping you to optimize Xcode incremental and clean builds by running benchmarks and optimizing build settings.
- [**dotnet-skills**](https://github.com/Aaronontheweb/dotnet-skills) - (1.3k ⭐) - Claude Code skills and sub-agents for .NET developers.
- [**Axiom**](https://github.com/CharlesWiltgen/Axiom) - (1.3k ⭐) - Battle-tested Claude Code skills for modern xOS (iOS, iPadOS, watchOS, tvOS) development.
- [**moai-adk**](https://github.com/modu-ai/moai-adk) - (1.3k ⭐) - Spec-first agentic development kit for Claude Code, with agents, skills, TDD and DDD quality gates, multilingual project support, and a Go CLI.
- [**autoprompt-skill**](https://github.com/Spielewoy/autoprompt-skill) - (1.3k ⭐) - Coding-agent skill that improves prompts for agentic coding tasks.
- [**x-research-skill**](https://github.com/rohunvora/x-research-skill) - (1.2k ⭐) - X/Twitter research skill for Claude Code and OpenClaw.
- [**bioSkills**](https://github.com/GPTomics/bioSkills) - (1.2k ⭐) - SKILLS.md files for bioinformatics work with agents such as Claude Code.
- [**banana-claude**](https://github.com/AgriciDaniel/banana-claude) - (1.2k ⭐) - AI image generation skill for Claude Code with a creative-director workflow powered by Gemini.
- [**ppt-image-first**](https://github.com/NyxTides/ppt-image-first) - (1.2k ⭐) - Codex, Claude Code, and OpenCode skill for image-first PowerPoint workflows.
- [**vibe-security-skill**](https://github.com/raroque/vibe-security-skill) - (1.2k ⭐) - Security audit skill for finding common vulnerabilities in apps built with AI coding assistants.
- [**app-onboarding-questionnaire**](https://github.com/adamlyttleapps/claude-skill-app-onboarding-questionnaire) - (1.2k ⭐) - Claude Code skill for designing questionnaire-style app onboarding flows based on subscription app conversion patterns.
- [**claude-deep-research-skill**](https://github.com/199-biotechnologies/claude-deep-research-skill) - (1.2k ⭐) - Deep research skill for Claude Code with a phased pipeline, source credibility scoring, and validation checks.
- [**ai-copywriter**](https://github.com/mikiarlo3/ai-copywriter) - (1.2k ⭐) - Copywriting skill with marketing knowledge and a human tone.
- [**skillpack**](https://github.com/CreminiAI/skillpack) - (1.2k ⭐) - Tooling for packaging and deploying local AI agents and reusable skill packs for teams.
- [**inference-optimisation-skill**](https://github.com/sybil-solutions/inference-optimisation-skill) - (1.2k ⭐) - Agent skill for benchmarking and tuning local LLM serving, from startup and time to first token to decoding throughput.
- [**Filtmall Shopping Skill**](https://github.com/filtalgo/Filtmall-Shopping-Skill) - (1.2k ⭐) - Shopping skill for product search, same-product price comparisons, checkout, order tracking, and after-sales support.
- [**getsentry/skills**](https://github.com/getsentry/skills) - (1.2k ⭐) - Agent Skills used by the Sentry team for development work.
- [**aws-agent-skills**](https://github.com/itsmostafa/aws-agent-skills) - (1.2k ⭐) - AWS cloud engineering skills for Claude Code across 18 core AWS services.
- [**bolt-slides**](https://github.com/stackblitz/bolt-slides) - (1.2k ⭐) - A React presentation framework with a bundled Agent Skill for building interactive slide decks as responsive web apps.
- [**chrisbanes skills**](https://github.com/chrisbanes/skills) - (1.2k ⭐) - Skills for Kotlin, Jetpack Compose, and Android development.
- [**app-store-connect-cli-skills**](https://github.com/rorkai/app-store-connect-cli-skills) - (1.1k ⭐) - Skills for automating App Store Connect, TestFlight, deployment, and related asc CLI workflows.
- [**kotlin-agent-skills**](https://github.com/Kotlin/kotlin-agent-skills) - (1.1k ⭐) - AI agent skills for projects that use the Kotlin language.
- [**power-bi-agentic-development**](https://github.com/data-goblin/power-bi-agentic-development) - (1.1k ⭐) - Power BI and Microsoft Fabric skills, subagents, and hooks for semantic models, DAX, TMDL, reports, and dashboards.
- [**Day1Global-Skills**](https://github.com/star23/Day1Global-Skills) - (1.1k ⭐) - Agent skills for U.S. stocks, macro markets, and crypto research.
- [**line-art-animation**](https://github.com/JDhruv14/line-art-animation) - (1.1k ⭐) - Claude skill and TypeScript library for animated SVG line art, including characters that walk and react and scenes with day and night states.
- [**synalinks-skills**](https://github.com/numman-ali/n-skills) - (1.1k ⭐) - Claude skills for Synalinks.
- [**n-skills**](https://github.com/numman-ali/n-skills) - (1.1k ⭐) - Curated plugin marketplace for AI agents - works with Claude Code, Codex, and openskills.
- [**Kubai Icons**](https://github.com/kubai087/kubai-icons) - (1.0k ⭐) - Agent Skill for drawing animated icons in a consistent style, with an icon library for React, Vue, and SVG.
- [**next-skills**](https://github.com/vercel-labs/next-skills) - (992 ⭐) - Agent skills for common Next.js workflows.
- [**claude-skill-homeassistant**](https://github.com/komal-SkyNET/claude-skill-homeassistant) - (987 ⭐) - Claude Code skill to supercharge and manage all Home Assistant workflows.
- [**dashboard-design-skill**](https://github.com/abdiraimov-otabek/dashboard-design-skill) - (975 ⭐) - Dashboard design skill for web and SwiftUI interfaces, with guidance for KPI cards, charts, filters, responsive layouts, and screenshot QA.
- [**self-learning-skills**](https://github.com/Kulaxyz/self-learning-skills) - (974 ⭐) - Self-learning skill pack that helps coding agents capture lessons from past work and reuse them in later sessions.
- [**STE80 Humanizer**](https://github.com/Dodaios/ste80-humanizer) - (950 ⭐) - Editing skill that removes common AI writing patterns and applies selected Simplified Technical English rules.
- [**Claude Animation Skills**](https://github.com/artemnovitckii/claude-animation-skills) - (938 ⭐) - Six Claude Code skills for animated explainers, stick figures, line art, map routes, exploded views, and line graphs, with local rendering and review sheets.
- [**autocli-skill**](https://github.com/nashsu/autocli-skill) - (937 ⭐) - Claude Code and agent skill for fetching real-time web data across many platforms through a Chrome login session.
- [**SkillForge**](https://github.com/tripleyak/SkillForge) - (919 ⭐) - The ultimate meta-skill for generating best-in-class Claude Code skills.
- [**ui-design-brain**](https://github.com/carmahhawwari/ui-design-brain) - (909 ⭐) - UI component knowledge skill for agents, with layout patterns and design-system conventions for interface work.
- [**claude-code-skill-factory**](https://github.com/alirezarezvani/claude-code-skill-factory) - (906 ⭐) - Toolkit for building and deploying Claude Skills, code agents, slash commands, and LLM prompts.
- [**x-article-publisher-skill**](https://github.com/wshuyi/x-article-publisher-skill) - (875 ⭐) - Claude Code skill for publishing Markdown articles to X (Twitter) Articles.
- [**live-panel-skill**](https://github.com/ythx-101/live-panel-skill) - (871 ⭐) - Skill for turning JSON configurations into animated architecture diagrams as video or live web pages.
- [**rossark-motion-skill**](https://github.com/rossark0/rossark-motion-skill) - (870 ⭐) - Animation skill with React Native and SwiftUI templates for SVG artwork, character expressions, body motion, interface animation, and complete scenes.
- [**claude-motion-design**](https://github.com/howseen-ai/claude-motion-design) - (857 ⭐) - Claude Code skill for producing motion design videos with HTML, Playwright, and ffmpeg.
- [**second-brain-skills**](https://github.com/coleam00/second-brain-skills) - (849 ⭐) - Claude Skills that turn Claude Code into a second-brain workspace.
- [**claude-office-skills**](https://github.com/tfriedel/claude-office-skills) - (847 ⭐) - Office document creation and editing skills for Claude Code - PPTX, DOCX, XLSX, and PDF workflows with automation support.
- [**cc-design**](https://github.com/ZeroZ-lab/cc-design) - (831 ⭐) - High-fidelity HTML design and prototype guidance skill for AI agents.
- [**Agent-Skills**](https://github.com/MicrosoftDocs/Agent-Skills) - (815 ⭐) - Microsoft and Azure Agent Skills that give coding assistants structured expertise from Microsoft Learn documentation.
- [**cinematic-skill**](https://github.com/Moh4696/cinematic-skill) - (797 ⭐) - Agent skill for building narrated films from code, with camera moves across photos, maps, and cards timed to the voice-over.
- [**advertising-skills**](https://github.com/realkimbarrett/advertising-skills) - (790 ⭐) - Advertising Skills for Open Claw, Claude Code & AI agents.
- [**claude-code-tresor**](https://github.com/alirezarezvani/claude-code-tresor) - (788 ⭐) - Claude Code collection with autonomous skills, expert agents, slash commands, and reusable prompts for development workflows.
- [**sprite-stacking**](https://github.com/danielwh2/sprite-stacking) - (745 ⭐) - Agent skill that turns four pixel art views into a rotatable pseudo-3D sprite and exports a 16-direction sprite sheet.
- [**nuxt-skills**](https://github.com/onmax/nuxt-skills) - (729 ⭐) - Vue, Nuxt, and NuxtHub skills for AI coding assistants.
- [**cloudflare-skill**](https://github.com/dmmulroy/cloudflare-skill) - (728 ⭐) - Comprehensive Cloudflare platform reference docs for AI/LLM consumption.
- [**machine-skill**](https://github.com/AirsupHQ/machine-skill) - (717 ⭐) - Claude Code skill for building interactive 3D machine simulations in standalone HTML, with physics calculations, cutaway views, and video recording tools.
- [**qmd-skill**](https://github.com/levineam/qmd-skill) - (711 ⭐) - A Codex/Clawd skill definition for qmd (Quick Markdown Search).
- [**3dicon**](https://github.com/samyost1/3dicon) - (682 ⭐) - Claude Code skill for generating looping animated 3D icons with transparent backgrounds.
- [**SkillSpec**](https://github.com/modiqo/skillspec) - (667 ⭐) - Open-source CLI and contract format for checking, testing, and documenting how Agent Skills should run.
- [**skill.color-expert**](https://github.com/meodai/skill.color-expert) - (665 ⭐) - Agent skill for color science, accessibility checks, palette generation, pigment mixing, and historical color theory.
- [**napkin**](https://github.com/blader/napkin) - (648 ⭐) - A Claude Code skill that gives the agent persistent memory of its mistakes via a per-repo markdown scratchpad.
- [**solid-skills**](https://github.com/ramziddin/solid-skills) - (638 ⭐) - AI agent skill for writing senior-engineer quality code through SOLID principles, TDD, and clean architecture.
- [**Semia**](https://github.com/berabuddies/Semia) - (614 ⭐) - Security audit tooling for reviewing AI agent skills before they are used in agent workflows.
- [**agent-skills**](https://github.com/elastic/agent-skills) - (610 ⭐) - Official Elastic skills for AI agents that work with Elastic products and workflows.
- [**claude-code-skills**](https://github.com/levnikolaevich/claude-code-skills) - (598 ⭐) - Plugin suite and bundled MCP servers for delivery workflows, codebase audits, documentation, performance optimization, and remote SSH work.
- [**solana-dev-skill**](https://github.com/solana-foundation/solana-dev-skill) - (592 ⭐) - Claude Code skill for modern Solana development.
- [**agent-skills-standard**](https://github.com/HoangNguyen0403/agent-skills-standard) - (585 ⭐) - Agent Skills standards and best-practice packs for programming languages, frameworks, and common development workflows.
- [**elevenlabs skills**](https://github.com/elevenlabs/skills) - (578 ⭐) - ElevenLabs skill collection for building agents that work with speech, sound effects, music, transcription, and text-to-speech workflows.
- [**xss-audit**](https://github.com/songjianyang/xss-audit) - (568 ⭐) - Static XSS audit skill for React, TypeScript, and JavaScript projects, with source-to-sink analysis and reports that separate findings from manual-review cases.
- [**viserys-agent**](https://github.com/rizqinrr/viserys-agent) - (565 ⭐) - Self-contained pack of 28 Markdown workflow skills covering DEFINE, PLAN, BUILD, VERIFY, REVIEW, and SHIP.
- [**vibecosystem**](https://github.com/vibeeval/vibecosystem) - (553 ⭐) - An AI software-team system for Claude Code with agents, skills, hooks, and self-learning workflow support.
- [**PPT-Design-Skill**](https://github.com/sunchaokun/PPT-Design-Skill) - (510 ⭐) - Precision PPT design skill for OpenCode, Claude Code, and Codex, with 40,000+ styles, Build Mode control, AI image generation, and fully editable PPTX output.
- [**video-director**](https://github.com/win4r/video-director) - (500 ⭐) - Claude Code skill for planning, coding, rendering, and checking short videos built with HTML, Canvas, SVG, Three.js, GSAP, or Remotion.
- [**csv-data-summarizer-claude-skill**](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - (487 ⭐) - A Claude Skill that automatically analyzes uploaded CSV files — generating summary statistics, detecting missing data, and creating quick visualizations using Python and pandas.
- [**token-diet**](https://github.com/Kulaxyz/token-diet) - (480 ⭐) - Always-on token-efficiency skill for Claude Code, Codex, Cursor, Windsurf, and Cline.
- [**cutaway**](https://github.com/Nyxera0x/cutaway) - (465 ⭐) - Claude Code skill that rebuilds a reference image as a Three.js model and records an exploded-view animation with synchronized audio.
- [**awesome-pm-skills**](https://github.com/menkesu/awesome-pm-skills) - (464 ⭐) - Product-management skill collection for research, planning, prioritization, launch work, and stakeholder communication.
- [**antialgorithm**](https://github.com/mankidev/antialgorithm) - (456 ⭐) - Claude Code skill that explores less obvious directions for names, concepts, posters, and interface designs.
- [**blueprint-animation**](https://github.com/moguzbulbul/blueprint-animation) - (441 ⭐) - Design skill for animated before-and-after UX redesign presentations in a blueprint style.
- [**console-skill**](https://github.com/Jakeschincariol/console-skill) - (422 ⭐) - Skills for reverse-engineering and porting personally owned PlayStation 2 games through PS2Recomp, with graphics, audio, controller, and modding workflows.
- [**brand-identity-skill**](https://github.com/fatihaydost/brand-identity-skill) - (412 ⭐) - Claude Code skill for designing coordinated logos, typography, and color palettes, with comparison cards and a brand guidelines kit.
- [**Remake**](https://github.com/rubenhassid1/remake) - (376 ⭐) - Claude Code skill for recreating websites from a URL, comparing screenshots and motion, and identifying text, media, fonts, and logos to replace.
- [**content-principles**](https://github.com/aiwithremy/content-principles) - (353 ⭐) - Short-form content skill for drafting and reviewing video scripts and hooks through curiosity, specificity, and audience attention principles.
- [**skill-threat-modeling**](https://github.com/fr33d3m0n/skill-threat-modeling) - (353 ⭐) - Code-First Deep Risk Analysis Skill for Claude Code - 8-Phase Workflow with Security design review, STRIDE Threat modeling, PenTest and attack chain analysis, Software compliance assessment.
- [**pixel-path**](https://github.com/jonwheatley/pixel-path) - (332 ⭐) - Claude Code skill for building interactive pixel-art road journeys from real routes, OpenStreetMap data, elevation data, and generated scenery.
- [**awesome-dfir-skills**](https://github.com/tsale/awesome-dfir-skills) - (326 ⭐) - A curated collection of DFIR skills and workflows for InfoSec practitioners.
- [**RES**](https://github.com/alextnetto/res) - (312 ⭐) - Agent Skill that documents the screens, workflows, and design tokens of web apps you have permission to study.
- [**PID-to-Knowledge-Graph**](https://github.com/ScottDuncanAI/PID-to-Knowledge-Graph) - (304 ⭐) - Claude skill that extracts equipment connections, instruments, and control loops from scanned or digital piping and instrumentation diagrams.
- [**anima**](https://github.com/Garinmckayl/anima) - (295 ⭐) - Claude Code skill for creating interactive isometric biology figures with cited mechanisms and standalone HTML output.
- [**google-ai-mode-skill**](https://github.com/PleasePrompto/google-ai-mode-skill) - (294 ⭐) - Claude Code skill for free Google AI Mode search with citations.
- [**claude-code-skills**](https://github.com/whawkinsiv/claude-code-skills) - (265 ⭐) - Complete software development lifecycle skills optimized for non-technical founders building SaaS applications with AI tools (Lovable, Replit, Claude Code).
- [**skill-diet**](https://github.com/nicobailon/skill-diet) - (260 ⭐) - Skill for reducing instruction bloat, checking tool accuracy, and comparing task results before and after a skill rewrite.
- [**Apple-Hig-Designer**](https://github.com/axiaoge2/Apple-Hig-Designer) - (233 ⭐) - A Claude Code Skill for designing professional interfaces following Apple Human Interface Guidelines.
- [**claude-code-voice-skill**](https://github.com/abracadabra50/claude-code-voice-skill) - (173 ⭐) - Skill to talk to Claude about your projects over the phone.
- [**nano-image-generator-skill**](https://github.com/lxfater/nano-image-generator-skill) - (129 ⭐) - A Claude Code skill for generating images using Gemini 3 Pro Preview (Nano Banana Pro).
- [**solid-skills**](https://github.com/lxfater/nano-image-generator-skill) - (129 ⭐) - AI agent skill for writing senior-engineer quality code through SOLID principles, TDD, and clean architecture.
- [**claude-cs**](https://github.com/nbashaw/claude-cs) - (91 ⭐) - A Claude Code skill that helps you build custom customer support automation for your company.
- [**baoyu-design**](https://github.com/JimLiu/baoyu-design) - (67 ⭐) - Run Claude Design locally as an Agent Skill.
- [**Generative-Media-Skills**](https://github.com/SamurAIGPT/Generative-Media-Skills) - (44 ⭐) - Multi-modal Generative Media Skills for AI Agents (Claude Code, Cursor, Gemini CLI).
- [**claude-skills-supercharged**](https://github.com/jefflester/claude-skills-supercharged) - (43 ⭐) - A "supercharged" implementation of Claude Code Skills – using Haiku prompt analysis/critical skill scoring and skill auto-injection for friction-free, context-driven workflows.
- [**agentkits-marketing**](https://github.com/aitytech/agentkits-marketing) - (9 ⭐) - Marketing automation skills and agent workflows for Claude Code, Cursor, GitHub Copilot, and compatible AI assistants.
- [**BFL Agent Skills**](https://docs.bfl.ai/api_integration/skills_integration) - Reusable capabilities that teach AI agents how to work with FLUX models.
- [**Manus Skills**](https://manus.im/blog/manus-skills) - Manus' official agent skills.
- [**Firecrawl Skills**](https://docs.firecrawl.dev/sdks/cli) - An easy way for AI agents such as Claude Code, Antigravity and OpenCode to use Firecrawl through the CLI.

---

## 🔌 Claude Plugins

- [**ponytail**](https://github.com/DietrichGebert/ponytail) - (194.6k ⭐) - Makes your AI agent think like the laziest senior dev in the room.
- [**claude-hud**](https://github.com/jarrodwatts/claude-hud) - (29.3k ⭐) - A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress.
- [**compound-engineering-plugin**](https://github.com/EveryInc/compound-engineering-plugin) - (26.2k ⭐) - Official Compound Engineering plugin for Claude Code, Codex, Cursor, and other coding agents.
- [**elephant-goldfish-model**](https://github.com/google/elephant-goldfish-model) - (21.3k ⭐) - Google plugin for drafting software specifications with project context and reviewing them with fresh subagents before implementation.
- [**harness**](https://github.com/revfactory/harness) - (9.4k ⭐) - A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.
- [**fast-jev-compaction**](https://github.com/tamaratran/fast-jev-compaction) - (8.0k ⭐) - Claude Code plugin that replaces compaction summaries with fast Jev decisions while keeping retained tool results verbatim.
- [**interface-design**](https://github.com/Dammyjay93/interface-design) - (6.0k ⭐) - Design engineering for Claude Code. Craft, memory, and enforcement for consistent UI.
- [**Floorplan**](https://github.com/haydenschmitty/floorplan) - (4.9k ⭐) - Claude Code and Codex plugin for generating interactive codebase maps with plain-English labels for components, files, web requests, and their connections.
- [**claude-octopus**](https://github.com/nyldn/claude-octopus) - (4.5k ⭐) - Run multiple AI models against the same research, design, or coding task and surface disagreements before you ship.
- [**VibeWise**](https://github.com/nykooi1/vibe-wise) - (4.4k ⭐) - Claude Code plugin that asks for your approach, discusses tradeoffs, and explains code changes as you build.
- [**notfair-plugin**](https://github.com/nowork-studio/notfair-plugin) - (4.3k ⭐) - Open-source SEO, GEO, and marketing skills for AI agents.
- [**arscontexta**](https://github.com/agenticnotetaking/arscontexta) - (3.5k ⭐) - Claude Code plugin that generates individualized knowledge systems from conversation.
- [**memsearch**](https://github.com/zilliztech/memsearch) - (2.9k ⭐) - Persistent semantic memory for Claude Code and other agents, with Markdown storage, Milvus indexing, and cross-session retrieval.
- [**Claude Code Toolkit**](https://github.com/rohitg00/awesome-claude-code-toolkit) - (2.9k ⭐) - A Claude Code marketplace with plugins, agents, skills, commands, hooks, rules, templates, and MCP configurations.
- [**call-me**](https://github.com/ZeframLou/call-me) - (2.7k ⭐) - Minimal plugin that lets Claude Code call you on the phone.
- [**claude-code-safety-net**](https://github.com/kenryu42/claude-code-safety-net) - (2.1k ⭐) - A Claude Code plugin that acts as a safety net, catching destructive git and filesystem commands before they execute.
- [**unreal-engine-skills-for-claude-code-plugin**](https://github.com/EpicGames/unreal-engine-skills-for-claude-code-plugin) - (2.0k ⭐) - Epic Games plugin with skills and session hooks for controlling Unreal Editor through MCP tools for actors, Blueprints, materials, animation, and testing.
- [**pg-aiguide**](https://github.com/timescale/pg-aiguide) - (1.9k ⭐) - MCP server and Claude plugin for Postgres skills, documentation, and database guidance.
- [**claude-workflow-v2**](https://github.com/CloudAI-X/claude-workflow-v2) - (1.4k ⭐) - Universal Claude Code workflow plugin with agents, skills, hooks, and commands.
- [**hackingtool-plugin**](https://github.com/AKCodez/hackingtool-plugin) - (1.2k ⭐) - 183+ pentesting & OSINT tools from Z4nzu/hackingtool.
- [**CloudBase AI Toolkit**](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) - (1.2k ⭐) - Claude Code plugin, Agent Skills, and MCP server for using Tencent CloudBase databases, authentication, functions, storage, and deployment from coding agents.
- [**fablize**](https://github.com/fivetaku/fablize) - (891 ⭐) - Claude Code plugin that changes Opus behavior with a Fable-inspired response style.
- [**claude-forge**](https://github.com/sangrokjung/claude-forge) - (881 ⭐) - Claude Code plugin framework with agents, commands, skills, and security hooks.
- [**cartographer**](https://github.com/kingbootoshi/cartographer) - (855 ⭐) - Claude Code plugin that maps and documents codebases of any size using parallel AI subagents.
- [**plugins-for-claude-natives**](https://github.com/team-attention/plugins-for-claude-natives) - (832 ⭐) - A collection of Claude Code plugins for power users who want to extend Claude Code's capabilities beyond the defaults.
- [**design-plugin**](https://github.com/0xdesign/design-plugin) - (785 ⭐) - A Claude Code plugin that helps you make confident UI design decisions through rapid iteration.
- [**ralph-wiggum-marketer**](https://github.com/muratcankoylan/ralph-wiggum-marketer) - (781 ⭐) - A Claude Code Plugin that provides an autonomous AI copywriter.
- [**claude-code**](https://github.com/laravel/claude-code) - (741 ⭐) - A collection of Claude Code plugins tailored for PHP / Laravel development.
- [**claude-review-loop**](https://github.com/hamelsmu/claude-review-loop) - (734 ⭐) - Claude Code plugin: automated code review loop with Codex.
- [**hello2cc**](https://github.com/hellowind777/hello2cc) - (688 ⭐) - Native-first Claude Code plugin for third-party models with silent Agent model injection and output styles.
- [**claude-dashboard**](https://github.com/uppinote20/claude-dashboard) - (589 ⭐) - Comprehensive status line plugin for Claude Code with context usage, API rate limits, and cost tracking
- [**adversarial-spec**](https://github.com/zscole/adversarial-spec) - (559 ⭐) - A Claude Code plugin that iteratively refines product specifications by debating between multiple LLMs until all models reach consensus.
- [**cc-stretch**](https://github.com/pro-vi/cc-stretch) - (439 ⭐) - Claude Code plugin that presents short replies with clickable phrases that expand and collapse in place.
- [**ensue-skill**](https://github.com/mutable-state-inc/ensue-skill) - (421 ⭐) - A persistent knowledge tree that grows with you - what you learn today enriches tomorrow's reasoning.
- [**homunculus**](https://github.com/humanplane/homunculus) - (398 ⭐) - A Claude Code plugin that watches how you work, learns your patterns, and evolves itself to help you better.
- [**claude-show-your-work**](https://github.com/iamumeransari/claude-show-your-work) - (313 ⭐) - Claude Code plugin for displaying images, videos, and visual QA results in compatible terminals, with Playwright recordings and before-and-after comparisons.
- [**compact-plus**](https://github.com/u-ichi/compact-plus) - (211 ⭐) - Claude Code plugin that preserves and restores working state around <code>/compact</code>.
- [**claude-super-sidebar**](https://github.com/Zafer-Liu/claude-super-sidebar) - (156 ⭐) - Sidebar plugin for viewing Claude agent relationships, execution status, and conversation task flows, with a separate local session dashboard for Codex.
- [**auto-handoff**](https://github.com/obie/auto-handoff) - (106 ⭐) - Claude Code plugin that saves a handoff document after an idle period so a fresh session can resume the work.
- [**claude-code-plugin**](https://github.com/browserbase/claude-code-plugin) - (74 ⭐) - Browserbase plugin for Claude Code - Use cloud browsers with Claude Code instead of local Chrome.
- [**claude-toons**](https://github.com/achimala/claude-toons) - (39 ⭐) - Claude Code plugin that shows animated task-themed cartoons beneath the status spinner.

---

## 🛠️ Tools & Utilities

- [**claude-mem**](https://github.com/thedotmack/claude-mem) - (118.3k ⭐) - A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.
- [**Understand-Anything**](https://github.com/Egonex-AI/Understand-Anything) - (93.3k ⭐) - Codebase understanding tool that turns repositories into searchable, explainable knowledge graphs.
- [**claude-flow**](https://github.com/ruvnet/claude-flow) - (82.1k ⭐) - An enterprise-grade AI orchestration platform that reimagines how developers build with AI.
- [**OpenMontage**](https://github.com/OpenMontageInc/OpenMontage) - (81.7k ⭐) - Open-source video production system with agent workflows for scripting, asset generation, editing, and rendering.
- [**headroom**](https://github.com/headroomlabs-ai/headroom) - (80.1k ⭐) - Compresses tool outputs, logs, files, and retrieval chunks before they reach the language model.
- [**headroom**](https://github.com/chopratejas/headroom) - (80.1k ⭐) - Compresses tool outputs, logs, files, and retrieval chunks before they enter an agent context.
- [**codegraph**](https://github.com/colbymchenry/codegraph) - (78.1k ⭐) - Local code knowledge graph for Claude Code, Codex, Gemini, Cursor, OpenCode, Antigravity, Kiro, and Hermes Agent.
- [**claude-code-router**](https://github.com/musistudio/claude-code-router) - (38.2k ⭐) - Use Claude Code as the foundation for coding infrastructure, allowing you to decide how to interact with the model while enjoying updates from Anthropic.
- [**context-mode**](https://github.com/mksglu/context-mode) - (34.3k ⭐) - MCP server that reduces context usage by sandboxing tool output, indexing session memory, and routing work across coding agents.
- [**claude-context-mode**](https://github.com/mksglu/claude-context-mode) - (34.3k ⭐) - An MCP server that sits between Claude Code and these outputs. 315 KB becomes 5.4 KB. 98% reduction.
- [**claude-code-templates**](https://github.com/davila7/claude-code-templates) - (34.0k ⭐) - A CLI tool for configuring and monitoring Claude Code.
- [**TencentDB Agent Memory**](https://github.com/TencentCloud/TencentDB-Agent-Memory) - (31.0k ⭐) - Shared memory hub for agent teams that stores conversations, reusable skills, knowledge wikis, and code graphs across agent frameworks.
- [**SuperClaude**](https://github.com/NomenAK/SuperClaude) - (23.9k ⭐) - A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies.
- [**SuperClaude_Framework**](https://github.com/SuperClaude-Org/SuperClaude_Framework) - (23.9k ⭐) - A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies.
- [**claude-obsidian**](https://github.com/AgriciDaniel/claude-obsidian) - (16.6k ⭐) - Claude + Obsidian knowledge companion. A running notetaker that builds and maintains a persistent, compounding wiki vault.
- [**camofox-browser**](https://github.com/jo-inc/camofox-browser) - (12.4k ⭐) - Headless browser for agent-driven web automation, with anti-detection features and Playwright-style integration.
- [**Trail-Code**](https://github.com/trailhq/Trail-Code) - (11.3k ⭐) - Codebase context tool that maps functions and call relationships and saves team decisions and lessons for Claude Code and other coding agents.
- [**Graft**](https://github.com/trailhq/Graft) - (11.3k ⭐) - Codebase-aware context and code graph tool for Claude Code, Cursor, Codex, Gemini, and other coding agents.
- [**Graft**](https://github.com/NanoNets/Graft) - (11.3k ⭐) - Codebase-aware developer tool for Claude Code, Cursor, Codex, Gemini, and other coding agents.
- [**openskills**](https://github.com/numman-ali/openskills) - (10.8k ⭐) - Universal skills loader for AI coding agents.
- [**claude-code-action**](https://github.com/anthropics/claude-code-action) - (10.0k ⭐) - A general-purpose Claude Code action for GitHub PRs and issues that can answer questions and implement code changes.
- [**ccpm**](https://github.com/automazeio/ccpm) - (8.5k ⭐) - Project management system for Claude Code using GitHub Issues and Git worktrees for parallel agent execution.
- [**manifest**](https://github.com/mnfst/manifest) - (7.6k ⭐) - Connects agents and coding harnesses with different model providers through one manifest.
- [**skills-manager**](https://github.com/xingkongliang/skills-manager) - (7.6k ⭐) - A lightweight desktop app to manage, sync, and organize AI agent skills across 15+ coding tools.
- [**claude-token-efficient**](https://github.com/drona23/claude-token-efficient) - (6.2k ⭐) - One CLAUDE.md file. Keeps Claude responses terse. Reduces output verbosity on heavy workflows. Drop-in, no code changes.
- [**obsidian-mind**](https://github.com/breferrari/obsidian-mind) - (5.5k ⭐) - Self-organizing Obsidian vault that gives Claude Code, Codex CLI, and Gemini CLI persistent memory.
- [**earshot**](https://github.com/Leonxlnx/earshot) - (5.2k ⭐) - Local audio analysis and synthesis toolkit for coding agents, available as a CLI, Python API, and MCP server for sound descriptions, matching, and video audio review.
- [**peon-ping**](https://github.com/PeonPing/peon-ping) - (5.1k ⭐) - Game-character voice alerts and visual notifications when Claude Code and other coding agents finish tasks or need attention.
- [**cipher**](https://github.com/campfirein/cipher) - (4.9k ⭐) - An opensource memory layer specifically designed for coding agents.
- [**vibe-tools**](https://github.com/eastlondoner/vibe-tools) - (4.8k ⭐) - Command-line toolkit that adds web search, browser automation, and repository analysis to coding agents.
- [**Agent of Empires**](https://github.com/agent-of-empires/agent-of-empires) - (4.8k ⭐) - Terminal and web dashboard for managing persistent Claude Code and other coding-agent sessions, with Git worktrees and optional container isolation.
- [**LongMemory**](https://github.com/CaviraOSS/LongMemory) - (4.6k ⭐) - Local persistent memory store for LLM applications, including Claude Desktop, GitHub Copilot, Codex, and Antigravity.
- [**agent-memory**](https://github.com/tigerless-labs/agent-memory) - (4.3k ⭐) - Local memory runtime for Claude Code and Codex with a shared Markdown store, ranked retrieval, and scheduled memory consolidation.
- [**Agentic Resource Registry**](https://github.com/AgenticResourceRegistry/AgenticResourceRegistry) - (4.3k ⭐) - Self-hosted registry for sharing and discovering skills, agent files, and MCP resources across teams, with usage insights. Formerly Observal.
- [**Continuous-Claude-v2**](https://github.com/parcadei/Continuous-Claude-v2) - (4.0k ⭐) - Context management for Claude Code. Hooks maintain state via ledgers and handoffs. MCP execution without context pollution. Agent orchestration with isolated context windows.
- [**claude-code-spec-workflow**](https://github.com/Pimzino/claude-code-spec-workflow) - (3.9k ⭐) - Automated Kiro-style Spec workflow for Claude Code. Transform feature ideas into complete implementations through Requirements → Design → Tasks → Implementation.
- [**Beacon**](https://github.com/Asymptote-Labs/agent-beacon) - (3.6k ⭐) - Shared memory layer for coding agents that captures session history and preserves workflows, corrections, and debugging knowledge across Claude Code, Codex, Cursor, and other tools.
- [**skillshare**](https://github.com/runkids/skillshare) - (3.2k ⭐) - Sync skills across all AI CLI tools with one command and simplify team sharing.
- [**crystal**](https://github.com/stravu/crystal) - (3.1k ⭐) - Run multiple Claude Code AI sessions in parallel git worktrees.
- [**CCPlugins**](https://github.com/brennercruvinel/CCPlugins) - (2.8k ⭐) - Claude Code Plugins that actually save time. Built by a dev tired of typing please act like a senior engineer in every conversation.
- [**skill-scanner**](https://github.com/cisco-ai-defense/skill-scanner) - (2.7k ⭐) - Security Scanner for Agent Skills.
- [**commands**](https://github.com/wshobson/commands) - (2.6k ⭐) - A collection of production-ready slash commands for Claude Code.
- [**tweakcc**](https://github.com/Piebald-AI/tweakcc) - (2.6k ⭐) - Command-line tool to customize your Claude Code styling.
- [**claude-island**](https://github.com/farouqaldori/claude-island) - (2.5k ⭐) - Claude Code notifications without the context switch.
- [**better-harness**](https://github.com/QoderAI/better-harness) - (2.5k ⭐) - A harness engineering platform for analyzing coding-agent workflows, identifying evidence-backed gaps, and defining verifiable improvements.
- [**PR Lens**](https://github.com/coldteadotai/pr-lens) - (2.4k ⭐) - Generates animated architecture and data-flow diagrams for pull requests through a GitHub App, Action, CLI, or coding-agent skill.
- [**tdd-guard**](https://github.com/nizos/tdd-guard) - (2.4k ⭐) - Automated TDD enforcement for Claude Code.
- [**clawgod**](https://github.com/0Chencc/clawgod) - (2.3k ⭐) - Claude Code companion tool for agent sessions, workflows, and local control.
- [**TypeUI**](https://github.com/bergside/typeui) - (2.3k ⭐) - Design skills, UI prompts, and an MCP server that supply coding agents with design systems and layout guidance for websites and applications.
- [**cc-mirror**](https://github.com/numman-ali/cc-mirror) - (2.3k ⭐) - Create multiple isolated Claude Code variants with custom providers (Z.ai, MiniMax, OpenRouter, LiteLLM)
- [**memmy-agent**](https://github.com/MemTensor/memmy-agent) - (2.2k ⭐) - A personal AI agent and shared memory hub that gives Claude Code, Codex, OpenClaw, and other agents persistent context under user control.
- [**claude-code-prompt-improver**](https://github.com/severity1/claude-code-prompt-improver) - (2.0k ⭐) - Intelligent prompt improver hook for Claude Code. Type vibes, ship precision.
- [**claude-code-transcripts**](https://github.com/simonw/claude-code-transcripts) - (1.7k ⭐) - Tools for publishing transcripts for Claude Code sessions.
- [**claude-code-settings**](https://github.com/feiskyer/claude-code-settings) - (1.7k ⭐) - Claude Code settings and commands for vibe coding.
- [**claude-code-hooks-multi-agent-observability**](https://github.com/disler/claude-code-hooks-multi-agent-observability) - (1.6k ⭐) - Real-time monitoring for Claude Code agents through simple hook event tracking.
- [**cc-sessions**](https://github.com/GWUDCAP/cc-sessions) - (1.5k ⭐) - An opinionated extension set for Claude Code (hooks, subagents, commands, task/git management infrastructure)
- [**backpass**](https://github.com/kunchenguid/backpass) - (1.5k ⭐) - Improve AGENTS.md or CLAUDE.md from evidence in local agent session transcripts, with reviewable, evidence-gated edits.
- [**claude-canvas**](https://github.com/dvdsgl/claude-canvas) - (1.5k ⭐) - A TUI toolkit that gives Claude Code its own display.
- [**engram**](https://github.com/nagisanzenin/engram) - (1.5k ⭐) - Learning engine for Claude Code and Codex that records patterns from previous sessions and turns them into reusable guidance.
- [**pireel**](https://github.com/pireel/pireel) - (1.5k ⭐) - A browser-based, backend-free video editor for talking-head footage, with captions, graphics, themes, timeline editing, export, and MCP control.
- [**ccundo**](https://github.com/RonitSachdev/ccundo) - (1.4k ⭐) - Integrates seamlessly with Claude Code to provide granular undo functionality by reading directly from Claude Code's session files.
- [**Continuous Claude**](https://github.com/AnandChowdhary/continuous-claude) - (1.4k ⭐) - Run Claude Code in a continuous loop, autonomously creating PRs, waiting for checks, and merging.
- [**Claude-Command-Suite**](https://github.com/qdhenry/Claude-Command-Suite) - (1.4k ⭐) - Professional slash commands for Claude Code that provide structured workflows for software development tasks, including code review and feature implementation.
- [**claude-memory-compiler**](https://github.com/coleam00/claude-memory-compiler) - (1.3k ⭐) - Give Claude Code a memory that evolves with your codebase.
- [**OpenContext**](https://github.com/0xranx/OpenContext) - (1.3k ⭐) - Personal context store for Codex, Claude, OpenCode, and other agents, with skills, tools, search, and a desktop GUI.
- [**Claude-Code-Remote**](https://github.com/JessyTsui/Claude-Code-Remote) - (1.3k ⭐) - Control Claude Code remotely via email. Start tasks locally, receive notifications when Claude completes them, and send new commands by simply replying to emails.
- [**ccmanager**](https://github.com/kbwo/ccmanager) - (1.3k ⭐) - Claude Code / Gemini CLI / Codex CLI Session Manager.
- [**claude-code-log**](https://github.com/daaain/claude-code-log) - (1.3k ⭐) - A Python CLI tool that converts Claude Code transcript JSONL files into readable HTML format.
- [**claude-sessions**](https://github.com/iannuttall/claude-sessions) - (1.2k ⭐) - Custom slash commands for Claude Code that provide comprehensive development session tracking and documentation.
- [**ctx**](https://github.com/ctxrs/ctx) - (1.2k ⭐) - Local search for coding-agent history across Claude Code, Codex, Cursor, and related tools.
- [**claude-powerline**](https://github.com/Owloops/claude-powerline) - (1.2k ⭐) - Beautiful vim-style powerline statusline for Claude Code.
- [**claudebox**](https://github.com/RchGrav/claudebox) - (1.2k ⭐) - A Claude Code Docker Development Environment for running Claude AI's coding assistant in a fully containerized, reproducible environment.
- [**vibecode-pro-max-kit**](https://github.com/withkynam/vibecode-pro-max-kit) - (1.2k ⭐) - Spec-driven coding harness that keeps project memory and implementation context organized for AI agents.
- [**claude-code-base-action**](https://github.com/anthropics/claude-code-base-action) - (1.1k ⭐) - A Claude Code base action.
- [**medusa**](https://github.com/Pantheon-Security/medusa) - (1.0k ⭐) - AI-first security scanner for repositories, secrets, hooks, permissions, and agent skills.
- [**asm**](https://github.com/luongnv89/asm) - (975 ⭐) - Universal skill manager for AI coding agents.
- [**ai-newtab**](https://github.com/ThariqS/ai-newtab) - (915 ⭐) - Chrome new-tab extension that uses Claude to build a personalized daily homepage from browsing history and selected page content through the Anthropic API.
- [**big-arrow-on-the-screen**](https://github.com/franzenzenhofer/big-arrow-on-the-screen) - (885 ⭐) - macOS CLI and agent skill that draws temporary arrows, boxes, and text over app windows to guide users through on-screen actions.
- [**claude-replay**](https://github.com/es617/claude-replay) - (862 ⭐) - Convert AI coding agent sessions (Claude Code, Cursor, Codex, Gemini, OpenCode) into self-contained, embeddable HTML replays.
- [**context-infrastructure**](https://github.com/grapeot/context-infrastructure) - (857 ⭐) - Context and memory system for AI coding agents with persistent memory, personal rules, skills, and scheduled observations.
- [**claude-on-rails**](https://github.com/obie/claude-on-rails) - (818 ⭐) - A development framework for Ruby on Rails developers using Claude Code, inspired by SuperClaude.
- [**claude-memory-compiler**](https://github.com/obie/claude-on-rails) - (818 ⭐) - Give Claude Code a memory that evolves with your codebase.
- [**storybloq**](https://github.com/Storybloq/storybloq) - (788 ⭐) - Cross-session context tool for Claude Code with a CLI, MCP server, and /story skill for tickets, handovers, and roadmaps.
- [**recall**](https://github.com/raiyanyahya/recall) - (770 ⭐) - Offline durable memory for Claude Code that reduces repeated project explanation across sessions.
- [**looper**](https://github.com/ksimback/looper) - (720 ⭐) - Visual planning tool for review-gated Claude Code agent loops before they run.
- [**agent-manager**](https://github.com/YoanWai/agent-manager) - (701 ⭐) - Terminal UI for managing AI coding agents with live status, quick prompts, worktrees, and diff review.
- [**ccmate**](https://github.com/djyde/ccmate) - (622 ⭐) - Configure your Claude Code without pain.
- [**claude-code-configs**](https://github.com/Matt-Dionis/claude-code-configs) - (620 ⭐) - A comprehensive collection of production-grade Claude Code configurations, specialized agents, and automation workflows for optimizing AI-assisted development.
- [**skillhub-desktop**](https://github.com/skillhub-club/skillhub-desktop) - (607 ⭐) - Desktop app for managing agent skills in one place.
- [**claude-code-hooks**](https://github.com/karanb192/claude-code-hooks) - (587 ⭐) - A growing collection of useful Claude Code hooks. Copy, paste, customize..
- [**Graphicle**](https://github.com/Graphicle-AI/graphicle) - (581 ⭐) - Local code graph and project memory that give coding agents file-and-line excerpts from source code, documentation, decisions, and past sessions through MCP.
- [**smart-ralph**](https://github.com/tzachbon/smart-ralph) - (566 ⭐) - Claude Code plugin for spec-driven development with smart compaction and Ralph-style autonomous loops.
- [**claude-simone**](https://github.com/Helmi/claude-simone) - (557 ⭐) - A project management framework for AI-assisted development with Claude Code.
- [**async-code**](https://github.com/ObservedObserver/async-code) - (534 ⭐) - Use Claude Code or CodeX CLI to perform multiple tasks in parallel with a Codex-style UI, functioning as a personal codex or cursor-background agent.
- [**claude-commands**](https://github.com/badlogic/claude-commands) - (523 ⭐) - Global Claude Code commands and workflows.
- [**Sphinx**](https://github.com/parthh01/sphinx) - (501 ⭐) - Git pre-push hook that quizzes developers on the behavior of their committed changes before a push to a protected branch.
- [**claude-hub**](https://github.com/claude-did-this/claude-hub) - (491 ⭐) - Deploy Claude Code as a fully autonomous GitHub bot.
- [**claude-cognitive**](https://github.com/GMaN1911/claude-cognitive) - (451 ⭐) - Working memory for Claude Code - persistent context and multi-instance coordination.
- [**greplica**](https://github.com/Autoloops/greplica) - (444 ⭐) - Persistent engineering memory that indexes repository structure, code, and session transcripts for Claude Code and Codex.
- [**Claude Code Tamagotchi**](https://github.com/Ido-Levi/claude-code-tamagotchi) - (438 ⭐) - A digital friend that lives in your Claude Code statusline and keeps you company while you build cool stuff.
- [**ClaudeForge**](https://github.com/alirezarezvani/ClaudeForge) - (434 ⭐) - A CLAUDE.md Generator and Maintenance tool for for Claude Code to create high-quality CLAUDE.md instruction files — aligned with Anthropic’s best practices for Claude Code.
- [**ClaudeUsageBar**](https://github.com/Artzainnn/ClaudeUsageBar) - (353 ⭐) - Track your Claude.ai usage right from your Mac menu bar.
- [**Cheap Agent**](https://github.com/muaaz9329/cheap-ag) - (337 ⭐) - MCP server that delegates code edits to a lower-cost model while Claude Code or Codex handles planning and review.
- [**SuperClaude**](https://github.com/gwendall/superclaude) - (325 ⭐) - Supercharge your GitHub workflow with Claude AI.
- [**claude-code-sandbox**](https://github.com/textcortex/claude-code-sandbox) - (324 ⭐) - Run Claude Code safely in local Docker containers without having to approve every permission.
- [**claude-cmd**](https://github.com/kiliczsh/claude-cmd) - (319 ⭐) - Claude Code Commands Manager.
- [**claude-blocker**](https://github.com/T3-Content/claude-blocker) - (300 ⭐) - Block distracting websites unless Claude Code is actively running inference.
- [**laravel-claude-code-setup**](https://github.com/laraben/laravel-claude-code-setup) - (285 ⭐) - One-command setup for AI-powered Laravel development with Claude Code and MCP servers.
- [**claude-modular**](https://github.com/oxygen-fragment/claude-modular) - (285 ⭐) - Production-ready modular Claude Code framework with 30+ commands, token optimization, and MCP server integration.
- [**claude-code-studio**](https://github.com/arnaldo-delisio/claude-code-studio) - (281 ⭐) - Transform Claude Code into a complete development studio with 40+ specialized AI agents, MCP integrations, and enterprise-grade workflows.
- [**claude-setup**](https://github.com/AizenvoltPrime/claude-setup) - (270 ⭐) - A comprehensive configuration setup for Claude Code with Model Context Protocol (MCP) servers, custom commands, and automated workflows.
- [**claude-config-editor**](https://github.com/gagarinyury/claude-config-editor) - (266 ⭐) - A lightweight web tool that helps you clean and optimize your Claude Code/Desktop config files (.claude.json).
- [**maxagent**](https://github.com/vzroslieigry/maxagent) - (258 ⭐) - Hooks that let Claude Code and other agents recall and record approaches that worked in previous sessions, with an optional Chrome bridge.
- [**claude-thermos**](https://github.com/izeigerman/claude-thermos) - (249 ⭐) - Keeps a Claude session warm between tasks.
- [**claude-code-containers**](https://github.com/ghostwriternr/claude-code-containers) - (246 ⭐) - Use Claude Code on Cloudflare to solve GitHub issues.
- [**claude-context-local**](https://github.com/FarhanAliRaza/claude-context-local) - (238 ⭐) - Code search MCP for Claude Code. Make entire codebase the context for any coding agent. Embeddings are created and stored locally. No API cost.
- [**claude-self-reflect**](https://github.com/ramakay/claude-self-reflect) - (230 ⭐) - Claude forgets everything. This fixes that.
- [**win-claude-code**](https://github.com/somersby10ml/win-claude-code) - (227 ⭐) - Claude Code for Windows: No WSL. No Docker. Just code.
- [**cctrace**](https://github.com/jimmc414/cctrace) - (199 ⭐) - Export Claude Code chat sessions into markdown and XML.
- [**recall**](https://github.com/zippoxer/recall) - (198 ⭐) - Full-text search and resume for Claude/Codex conversations.
- [**Grov**](https://github.com/TonyStef/Grov) - (192 ⭐) - Captures private AI-session context, shares it with a team memory, and injects relevant memories into later sessions.
- [**claude-agent-server**](https://github.com/forayconsulting/gemini_cli_skill) - (190 ⭐) - A Claude Code skill enabling Claude to use Gemini 3 Pro via Gemini CLI.
- [**meridian**](https://github.com/markmdev/meridian) - (188 ⭐) - Zero-config Claude Code setup with enforced task scaffolding, structured memory, persistent context after compaction, plug-in code standards, optional TDD mode, and zero behavior changes for developers.
- [**claude-code-boost**](https://github.com/yifanzz/claude-code-boost) - (165 ⭐) - Hook utilities for Claude Code with intelligent auto-approval.
- [**claude-code-auto-memory**](https://github.com/severity1/claude-code-auto-memory) - (160 ⭐) - Claude Code plugin that automatically maintains CLAUDE.md files.
- [**context-forge**](https://github.com/webdevtodayjason/context-forge) - (148 ⭐) - CLI tool that scaffolds context engineering documentation for Claude Code projects.
- [**spec-based-claude-code**](https://github.com/papaoloba/spec-based-claude-code) - (140 ⭐) - Implementation of a Spec-Driven Development workflow in Claude Code using custom slash commands.
- [**claude-code-personal-assistant**](https://github.com/c0dezli/claude-code-personal-assistant) - (136 ⭐) - AI personal assistant setup for Claude Code.
- [**rins_hooks**](https://github.com/rinadelph/rins_hooks) - (107 ⭐) - Universal Claude Code hooks collection with cross-platform installer.
- [**claude-select**](https://github.com/aeitroc/claude-select) - (100 ⭐) - A unified launcher for Claude Code that lets you interactively choose which LLM backend to use.
- [**claude-code-container**](https://github.com/tintinweb/claude-code-container) - (98 ⭐) - A Docker container for running Claude Code in "dangerously skip permissions" mode.
- [**run-claude-docker**](https://github.com/icanhasjonas/run-claude-docker) - (84 ⭐) - Run claude code in somewhat safe and isolated yolo mode.
- [**claude-prune**](https://github.com/DannyAziz/claude-prune) - (82 ⭐) - A fast CLI tool for pruning Claude Code sessions.
- [**claude-code-thinking-patch**](https://github.com/aleks-apostle/claude-code-thinking-patch) - (67 ⭐) - Make Claude Code's thinking blocks visible by default without pressing ctrl+o.
- [**flashbacker**](https://github.com/agentsea/flashbacker) - (57 ⭐) - Claude Code state management with session continuity and AI personas, subagents and agent discussion.
- [**Severance**](https://github.com/blas0/Severance) - (49 ⭐) - A semantic memory system designed for Claude Code.
- [**ccguard**](https://github.com/pomterre/ccguard) - (45 ⭐) - Automated enforcement of net-negative LOC, complexity constraints, and quality standards for Claude code.
- [**claude-code-specs-generator**](https://github.com/kellemar/claude-code-specs-generator) - (42 ⭐) - A documentation and context management system for AI-assisted development, inspired by Amazon's Kiro IDE.
- [**claude-code-voice**](https://github.com/mckaywrigley/claude-code-voice) - (41 ⭐) - Hands-free voice control for Claude Code on macOS.
- [**claudecode-macmenu**](https://github.com/PiXeL16/claudecode-macmenu) - (35 ⭐) - A Mac Menu for Claude Code that notifies when Claude is done and shows insights.
- [**ccheckpoints**](https://github.com/p32929/ccheckpoints) - (35 ⭐) - A checkpoint system for Claude Code CLI that automatically tracks your coding sessions.
- [**cc-monitor-rs**](https://github.com/ZhangHanDong/cc-monitor-rs) - (24 ⭐) - Real-time Claude Code usage monitor with native UI built using Rust and Makepad.
- [**claude-code-test-runner**](https://github.com/firstloophq/claude-code-test-runner) - (24 ⭐) - An automated E2E natural language test runner built on Claude Code.
- [**cc-monitor-worker**](https://github.com/cometkim/cc-monitor-worker) - (23 ⭐) - Claude Code monitoring with Cloudflare Workers & Workers Analytics Engine.
- [**shotgun-alpha**](https://github.com/shotgun-sh/shotgun-alpha) - (3 ⭐) - Codebase-aware spec engine for Cursor, Claude Code & Lovable.
- [**conductor**](https://conductor.build/) - Run a bunch of Claude Codes in parallel.

---

## 💻 IDE & Editor Integrations

- [**CC GUI**](https://github.com/zhukunpenglinyutong/jetbrains-cc-gui) - (7.7k ⭐) - IntelliJ IDEA plugin with a visual interface for Claude Code, OpenAI Codex, and other AI coding CLIs.
- [**claudecode.nvim**](https://github.com/coder/claudecode.nvim) - (3.2k ⭐) - A Claude Code Neovim IDE Extension.
- [**claude-code.nvim**](https://github.com/greggh/claude-code.nvim) - (2.1k ⭐) - Seamless integration between the Claude Code AI assistant and Neovim.
- [**claude-code-ide.el**](https://github.com/manzaltu/claude-code-ide.el) - (1.7k ⭐) - Claude Code IDE for Emacs provides native integration with Claude Code CLI through the Model Context Protocol (MCP).
- [**minuet-ai.nvim**](https://github.com/milanglacier/minuet-ai.nvim) - (1.5k ⭐) - Code completion as-you-type from popular LLMs including OpenAI, Gemini, Claude, Ollama.
- [**getspecstory**](https://github.com/specstoryai/getspecstory) - (1.4k ⭐) - Extensions for GH Copilot, Cursor, and Claude Code.
- [**claude-code-chat**](https://github.com/andrepimenta/claude-code-chat) - (1.1k ⭐) - Beautiful Claude Code Chat Interface for VS Code.
- [**claude-code.el**](https://github.com/stevemolitor/claude-code.el) - (749 ⭐) - Claude Code Emacs integration.
- [**Claude-Autopilot**](https://github.com/benbasha/Claude-Autopilot) - (249 ⭐) - VS Code/Cursor extension for automating Claude Code tasks with intelligent queuing, batch processing, and auto-resume.
- [**n8n-nodes-claudecode**](https://github.com/holt-web-ai/n8n-nodes-claudecode) - (99 ⭐) - Bring the power of Claude Code directly into your n8n automation workflows!

---

## 🖥️ Clients & GUIs

- [**cc-switch**](https://github.com/farion1231/cc-switch) - (155.7k ⭐) - Cross-platform desktop assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build, and Hermes Agent.
- [**t3code**](https://github.com/pingdotgg/t3code) - (65.9k ⭐) - A minimal web GUI for coding agents.
- [**vibe-kanban**](https://github.com/BloopAI/vibe-kanban) - (28.7k ⭐) - Get 10X more out of Claude Code, Gemini CLI, Codex, Amp and other coding agents.
- [**happy**](https://github.com/slopus/happy) - (24.7k ⭐) - Mobile and Web client for Claude Code, with realtime voice, encryption and fully featured.
- [**claudia**](https://github.com/getAsterisk/claudia) - (22.5k ⭐) - A powerful GUI app and Toolkit for Claude Code - Create custom agents, manage interactive Claude Code sessions, run secure background agents, and more.
- [**cc-haha**](https://github.com/NanmiCoder/cc-haha) - (15.5k ⭐) - Local-first cross-platform desktop workspace for Claude Code and other agents, with multi-agent sessions, Git worktrees, code diffs, and a skill marketplace.
- [**claudecodeui**](https://github.com/siteboon/claudecodeui) - (14.7k ⭐) - A desktop and mobile UI for Claude Code, Anthropic's official CLI for AI-assisted coding.
- [**Atlas**](https://github.com/tryatlas/atlas) - (9.2k ⭐) - Desktop and terminal workspace for running coding agents and tracing Git commits back to the sessions that produced them.
- [**Coucou**](https://github.com/Louis-CFM/coucou) - (7.3k ⭐) - Mac notch and iPhone companion for watching coding-agent activity and approving requests.
- [**clawd-on-desk**](https://github.com/rullerzhou-afk/clawd-on-desk) - (6.8k ⭐) - Pixel desktop pet that reacts to Claude Code, Codex, Cursor, and other AI coding agents as they work.
- [**tuios**](https://github.com/Gaurav-Gosain/tuios) - (6.6k ⭐) - Terminal window manager with tiling panes, persistent workspaces, and a shared inbox for coding agents.
- [**CodePilot**](https://github.com/op7418/CodePilot) - (6.5k ⭐) - A native desktop GUI for Claude Code — chat, code, and manage projects visually.
- [**1code**](https://github.com/21st-dev/1code) - (5.6k ⭐) - Best UI for Claude Code with local and remote agent execution.
- [**hapi**](https://github.com/tiann/hapi) - (5.4k ⭐) - Mobile app for Codex, Claude Code, Pi, OpenCode, Kimi Code, and other coding agents.
- [**Codeg**](https://github.com/spacering-net/codeg) - (4.5k ⭐) - Collaborative desktop and self-hosted workspace that brings sessions from multiple coding agents into one interface.
- [**Monocode**](https://github.com/hardbeat920/monocode) - (4.1k ⭐) - Graphical interface for working with coding agents.
- [**zeron**](https://github.com/zeronsh/zeron) - (3.7k ⭐) - Native desktop control plane for coding agents, with local sessions, a headless Linux mode, and optional multi-device synchronization.
- [**EchoBird**](https://github.com/edison7009/EchoBird) - (3.6k ⭐) - Desktop app for switching ChatGPT, Codex CLI, and Claude Code accounts, tracking quotas, and routing model requests with automatic failover.
- [**companion**](https://github.com/The-Vibe-Company/companion) - (2.4k ⭐) - Open-source Claude Code / Codex Web UI.
- [**mindwalk**](https://github.com/cosmtrek/mindwalk) - (1.4k ⭐) - A visualization tool that replays coding-agent sessions on a 3D map of your codebase.
- [**claude-code-viewer**](https://github.com/d-kimuson/claude-code-viewer) - (1.3k ⭐) - A full-featured web-based Claude Code client that provides complete interactive functionality for managing Claude Code projects.
- [**Sniffly**](https://github.com/chiphuyen/sniffly) - (1.3k ⭐) - Claude Code dashboard with usage stats, error analysis, and sharable feature.
- [**clui-cc**](https://github.com/lcoutodemos/clui-cc) - (1.2k ⭐) - A lightweight, transparent desktop overlay for Claude Code on macOS. Clui CC wraps the Claude Code CLI in a floating pill interface with multi-tab sessions, a permission approval UI, voice input, and a skills marketplace.
- [**KIKUmap**](https://github.com/tang1693/KIKUmap) - (1.2k ⭐) - Native macOS menu-bar app for organizing Claude and ChatGPT chats into an interactive mind map, with activity status, desktop widgets, and Claude Code session support.
- [**cui**](https://github.com/BMPixel/cui) - (1.1k ⭐) - A web UI for Claude Code agents.
- [**Harp**](https://github.com/dominikmartn/harp) - (718 ⭐) - Unofficial Warp terminal fork with a sidebar for Claude Code and Codex sessions, agent status indicators, tab groups, and usage-limit displays.
- [**claude-run**](https://github.com/kamranahmedse/claude-run) - (677 ⭐) - A beautiful web UI for browsing Claude Code conversation history.
- [**Claude-code-ChatInWindows**](https://github.com/LKbaba/Claude-code-ChatInWindows) - (226 ⭐) - A Native UI for Windows That Makes Claude Code Instantly Better!
- [**claude-code-costs**](https://github.com/philipp-spiess/claude-code-costs) - (204 ⭐) - Analyze your Claude Code conversation costs with interactive visualizations.
- [**claude-quest**](https://github.com/Michaelliv/claude-quest) - (202 ⭐) - An RPG-style viewer that shows Claude Code sessions with pixel-art reactions to tool use.
- [**Claudiatron**](https://github.com/Haleclipse/Claudiatron) - (159 ⭐) - A Powerful Claude Code GUI Desktop Application.
- [**Claude-Code-Web-GUI**](https://github.com/binggg/Claude-Code-Web-GUI) - (71 ⭐) - Browse, view and share your Claude Code sessions - runs entirely in browser, no server required!
- [**ccmate-release**](https://github.com/djyde/ccmate-release) - (56 ⭐) - A GUI for Claude Code.
- [**Claude in a Box**](https://github.com/juancgarza/claude-in-a-box) - (51 ⭐) - A ChatGPT Canvas-style interface for Claude Code running in E2B sandboxes.

---

## 🏗️ Infrastructure & Proxies

- [**OmniRoute**](https://github.com/cheaper-inference/OmniRoute) - (90.0k ⭐) - AI gateway that gives Claude Code and other coding agents one endpoint for multiple model providers, with quota-aware routing and automatic failover.
- [**CLIProxyAPI**](https://github.com/router-for-me/CLIProxyAPI) - (59.0k ⭐) - API service that wraps Antigravity, Codex, Claude Code, and Grok Build behind OpenAI-, Gemini-, Claude-, and Codex-compatible endpoints.
- [**Magpie**](https://github.com/yetone/magpie) - (39.0k ⭐) - Menu bar and terminal app for choosing model providers for Claude Code, Codex, and other coding agents.
- [**claude-code-router**](https://github.com/musistudio/claude-code-router) - (38.2k ⭐) - Uses Claude Code as the foundation for coding infrastructure, allowing interaction with the model while enjoying updates.
- [**9router**](https://github.com/decolua/9router) - (32.6k ⭐) - Routes Claude Code, Codex, Cursor, Cline, and other coding agents to dozens of model providers with automatic fallback.
- [**opencodex**](https://github.com/lidge-jun/opencodex) - (18.7k ⭐) - A local provider proxy and dashboard that routes Codex CLI, the Codex app, SDKs, and Claude Code to multiple LLM providers.
- [**cc-connect**](https://github.com/chenhg5/cc-connect) - (16.4k ⭐) - Bridge for connecting local AI coding agents to Feishu/Lark, DingTalk, Slack, Telegram, Discord, LINE, WeChat Work, and other messaging platforms.
- [**zen-mcp-server**](https://github.com/BeehiveInnovations/zen-mcp-server) - (11.8k ⭐) - The power of Claude Code + Gemini / OpenAI / Grok / OpenRouter / Ollama / Custom Model working as one.
- [**open-connector**](https://github.com/oomol-lab/open-connector) - (6.3k ⭐) - Auth gateway that connects SaaS APIs to AI agents through SDK, CLI, MCP, HTTP, and OpenAPI access.
- [**devspace**](https://github.com/Waishnav/devspace) - (5.5k ⭐) - Self-hosted MCP server that gives ChatGPT, Claude, and other clients access to approved local projects for file edits, code search, and shell commands.
- [**copilot-api**](https://github.com/ericc-ch/copilot-api) - (4.2k ⭐) - Turns GitHub Copilot into an OpenAI/Anthropic API compatible server, usable with Claude Code.
- [**claude-code-proxy**](https://github.com/1rgs/claude-code-proxy) - (3.8k ⭐) - Run Claude Code on OpenAI models.
- [**claude-code-proxy**](https://github.com/fuergaosi233/claude-code-proxy) - (2.8k ⭐) - A Claude Code to OpenAI API Proxy.
- [**kimi-cc**](https://github.com/LLM-Red-Team/kimi-cc) - (1.7k ⭐) - Use Kimi's latest model (kimi-k2-0711-preview) to drive Claude Code.
- [**codemcp**](https://github.com/ezyang/codemcp) - (1.6k ⭐) - Coding assistant MCP for Claude Desktop.
- [**agentapi**](https://github.com/coder/agentapi) - (1.5k ⭐) - An HTTP API for Claude Code, Goose, Aider, and Codex.
- [**claude-code-mcp**](https://github.com/steipete/claude-code-mcp) - (1.3k ⭐) - Claude Code as a one-shot MCP server to have an agent in your agent.
- [**claude-balancer**](https://github.com/snipeship/claude-balancer) - (1.1k ⭐) - A load balancer proxy for multiple Claude OAuth accounts with automatic failover, request tracking, and web dashboard.
- [**ccflare**](https://github.com/snipeship/ccflare) - (1.1k ⭐) - The ultimate Claude API proxy with intelligent load balancing across multiple accounts.
- [**ccNexus**](https://github.com/lich0821/ccNexus) - (970 ⭐) - A smart API endpoint rotation proxy for Claude Code.
- [**Context-Gateway**](https://github.com/Compresr-ai/Context-Gateway) - (647 ⭐) - An agentic proxy that enhances any AI agent workflow with instant history compaction and context optimization tools.
- [**claude-code-proxy**](https://github.com/seifghazi/claude-code-proxy) - (520 ⭐) - Proxy that captures and visualizes in-flight Claude Code requests and conversations.
- [**anthropic-proxy**](https://github.com/maxnowack/anthropic-proxy) - (415 ⭐) - A proxy server that converts Anthropic API requests to OpenAI format and sends them to OpenRouter, used to use Claude Code with OpenRouter.
- [**cc-remote**](https://github.com/AkaraChen/cc-remote) - (413 ⭐) - Runs Claude Code on a remote host over SSH and executes its tool calls on your local machine through an ACP client.
- [**claude-gemini-bridge**](https://github.com/tkaufmann/claude-gemini-bridge) - (409 ⭐) - Intelligent integration between Claude Code and Google Gemini for large-scale code analysis.
- [**claude-code-kimi-groq**](https://github.com/fakerybakery/claude-code-kimi-groq) - (398 ⭐) - A basic proxy to use Kimi K2 on Claude Code through Groq.
- [**y-router**](https://github.com/luohy15/y-router) - (385 ⭐) - A Simple Proxy enabling Claude Code to work with OpenRouter.
- [**gemini-for-claude-code**](https://github.com/coffeegrind123/gemini-for-claude-code) - (355 ⭐) - A Python program allowing the use of Claude Code with Google's Gemini models.
- [**mcp-claude-code**](https://github.com/SDGLBL/mcp-claude-code) - (305 ⭐) - MCP implementation of Claude Code capabilities and more.
- [**claude-code-nexus**](https://github.com/KroMiose/claude-code-nexus) - (251 ⭐) - Seamlessly forward Claude Code requests to any OpenAI-compatible API service with smart model mapping, streaming support, deployed on Cloudflare Worker.
- [**claude_code-gemini-mcp**](https://github.com/RaiAnsar/claude_code-gemini-mcp) - (250 ⭐) - Connect Claude Code with Google's Gemini AI for powerful AI collaboration.
- [**claude-gemini-mcp-slim**](https://github.com/cmdaltctr/claude-gemini-mcp-slim) - (233 ⭐) - A lightweight integration that brings Google's Gemini AI capabilities to Claude Code through MCP (Model Context Protocol).
- [**claude-historian**](https://github.com/Vvkmnn/claude-historian) - (180 ⭐) - An MCP server for Claude Code conversation history.
- [**castari-proxy**](https://github.com/castar-ventures/castari-proxy) - (90 ⭐) - Use Claude Agent SDK and Claude Code with other providers/models.
- [**claude-code-open**](https://github.com/Davincible/claude-code-open) - (70 ⭐) - Claude Code with any LLM provider (OpenRouter, Gemini, Kimi K2).
- [**Claudify**](https://github.com/neno-is-ooo/claudify) - (32 ⭐) - Use Claude Code as an LLM provider with your subscription flat fee instead of pay-per-token API keys.

---

## 📊 Usage & Observability

- [**CodexBar**](https://github.com/steipete/CodexBar) - (23.2k ⭐) - Show usage stats for OpenAI Codex and Claude Code, without having to login.
- [**ccusage**](https://github.com/ryoppippi/ccusage) - (19.5k ⭐) - A CLI tool for analyzing Claude Code usage from local JSONL files.
- [**ccstatusline**](https://github.com/sirmalloc/ccstatusline) - (13.6k ⭐) - A customizable status line formatter for Claude Code CLI that displays model info, git branch, token usage, and other metrics in your terminal.
- [**codeburn**](https://github.com/getagentseal/codeburn) - (11.9k ⭐) - See where your AI coding tokens go. Interactive TUI dashboard for Claude Code, Codex, and Cursor cost observability.
- [**codeburn**](https://github.com/AgentSeal/codeburn) - (11.9k ⭐) - See where your AI coding tokens go. Interactive TUI dashboard for Claude Code, Codex, and Cursor cost observability.
- [**failproofai**](https://github.com/FailproofAI/failproofai) - (9.8k ⭐) - Observability and policy enforcement for AI agent harnesses, with run capture and runtime reliability checks.
- [**Claude-Code-Usage-Monitor**](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) - (8.8k ⭐) - A real-time Claude Code usage monitor with predictions and warnings.
- [**agentsview**](https://github.com/kenn-io/agentsview) - (6.5k ⭐) - Local-first session search, analytics, insights, and token-use statistics for Claude Code, Codex, and more than 20 coding agents.
- [**tokscale**](https://github.com/junhoyeo/tokscale) - (5.9k ⭐) - Terminal token-usage tracker for AI coding agents with interactive reports, model and project breakdowns, and a global leaderboard.
- [**cost-xray**](https://github.com/tigerless-labs/cost-xray) - (5.8k ⭐) - Local API traffic viewer that attributes Claude Code and Codex token costs to prompts, tools, cache activity, and other request parts.
- [**openusage**](https://github.com/robinebers/openusage) - (4.6k ⭐) - macOS menu bar app for tracking Claude, Codex, and other AI coding subscriptions, with usage limits, reset times, credits, and spend.
- [**abtop**](https://github.com/graykode/abtop) - (3.9k ⭐) - Terminal monitor for coding-agent sessions, token use, context windows, rate limits, and ports.
- [**token-monitor**](https://github.com/Javis603/token-monitor) - (3.7k ⭐) - Desktop widget for tracking token usage, costs, limits, and session activity across Claude Code and other coding tools, with multi-device synchronization.
- [**CCometixLine**](https://github.com/Haleclipse/CCometixLine) - (3.6k ⭐) - A high-performance Claude Code statusline tool written in Rust with Git integration and real-time usage tracking.
- [**claude-tap**](https://github.com/liaohch3/claude-tap) - (3.4k ⭐) - Local proxy and trace viewer for inspecting coding-agent API requests, prompts, tool calls, streaming responses, and token usage.
- [**codenotch**](https://github.com/vinzdg/codenotch) - (3.1k ⭐) - Desktop app that displays coding-assistant usage limits, reset times, and session status in a screen-edge notch, with macOS and Windows versions.
- [**claude-usage**](https://github.com/phuryn/claude-usage) - (2.3k ⭐) - A local dashboard for tracking your Claude Code token usage, costs, and session history.
- [**zoetrope**](https://github.com/furkankly/zoetrope) - (1.2k ⭐) - A read-only terminal and browser flow graph for following live Claude Code sessions or replaying saved transcripts.
- [**agenttrail**](https://github.com/sodiumsun/agenttrail) - (1.0k ⭐) - Local observability map for Claude Code, Codex, and Cursor that tracks plans, tool calls, file changes, and progress in real time.
- [**lot-map**](https://github.com/alexeyw/lot-map) - (1.0k ⭐) - Live local map of Claude Code activity that shows model steps, tool calls, hooks, skills, and subagents.
- [**ccglass**](https://github.com/jianshuo/ccglass) - (988 ⭐) - See what your coding agent (Claude Code, Codex, Kimi) sends to the model — local proxy + web dashboard.
- [**Tracely-ai**](https://github.com/jwuthri-cloud/Tracely-ai) - (947 ⭐) - Self-hostable agent observability and regression-testing platform that grades traces, groups failures, and replays recorded cases in CI to detect regressions.
- [**tokentap**](https://github.com/jmuncor/tokentap) - (812 ⭐) - Intercept LLM API traffic and visualize token usage in a real-time terminal dashboard.
- [**CCSeva**](https://github.com/Iamshankhadeep/ccseva) - (808 ⭐) - A beautiful macOS menu bar app for tracking your Claude Code usage in real-time.
- [**claude-task-viewer**](https://github.com/L1AD/claude-task-viewer) - (770 ⭐) - A web-based Kanban board for viewing Claude Code tasks.
- [**agentacct**](https://github.com/mikehasa/agentacct) - (757 ⭐) - Local-first work intelligence for coding agents, based on read-only session logs.
- [**cc-statusline**](https://github.com/chongdashu/cc-statusline) - (646 ⭐) - Transform your Claude Code experience with a beautiful, informative statusline.
- [**ClaudeCodeStatusLine**](https://github.com/daniel3303/ClaudeCodeStatusLine) - (622 ⭐) - Custom status line for Claude Code showing model, tokens, rate limits, and git info in real-time.
- [**claude-doctor**](https://github.com/millionco/claude-doctor) - (621 ⭐) - Diagnostic tool for reviewing Claude Code sessions and finding problems in local agent workflows.
- [**agentlytics**](https://github.com/f/agentlytics) - (597 ⭐) - Analytics dashboard for AI coding agents including Claude Code, Cursor, Windsurf, VS Code Copilot, Zed, Antigravity, OpenCode, and Command Code.
- [**claude-code-otel**](https://github.com/ColeMurray/claude-code-otel/) - (525 ⭐) - A comprehensive observability solution for monitoring Claude Code usage, performance, and costs.
- [**claude-code-ui**](https://github.com/KyleAMathews/claude-code-ui) - (417 ⭐) - A real-time dashboard for monitoring Claude Code sessions across multiple projects.
- [**whatsmyagentdoing**](https://github.com/Charonyuu/whatsmyagentdoing) - (407 ⭐) - Local activity dashboard for Claude Code, Codex, and other coding agents, with live session states, approval alerts, resume commands, and animated 2D or 3D office views.
- [**claude-code-usage-bar**](https://github.com/leeguooooo/claude-code-usage-bar) - (394 ⭐) - Real‑time statusline for Claude Code: token usage, remaining budget, burn rate, and depletion time.
- [**agent-standup**](https://github.com/Atoll92/agent-standup) - (382 ⭐) - Local animated view of Claude Code, Codex, and Mistral Vibe sessions that shows which agents are working, waiting, or need input.
- [**agentplay**](https://github.com/Entelligence-AI/agentplay) - (371 ⭐) - Replays coding-agent sessions on a map and timeline so you can follow each step of a run.
- [**claude-code-monitor**](https://github.com/onikan27/claude-code-monitor) - (315 ⭐) - Real-time dashboard for monitoring multiple Claude Code sessions from a CLI and mobile web UI on macOS.
- [**claude-pulse**](https://github.com/nikitadoudikov/claude-pulse) - (247 ⭐) - Live Claude Code dashboard for token use, context health, tool calls, session recovery, and mobile approvals.
- [**opensync**](https://github.com/LKbaba/Claude-code-ChatInWindows) - (226 ⭐) - Dashboards for OpenCode, Claude Code, Codex, Factory Droid and more.
- [**claude-code-leaderboard**](https://github.com/grp06/claude-code-leaderboard) - (189 ⭐) - This CLI automatically monitors your token usage and posts your stats to the leaderboard after each Claude Code session.
- [**Claude / Codex Usage Dashboard**](https://github.com/frankchiu-dev/claude-codex-usage-dashboard) - (173 ⭐) - Local dashboard for viewing Claude Code and Codex usage limits on a phone, tablet, or small display.
- [**claude-statusline**](https://github.com/luongnv89/claude-statusline) - (120 ⭐) - Customize the status line in Claude Code.
- [**inferock-bench**](https://github.com/inferock/inferock-bench) - (111 ⭐) - Local LLM cost-tracking proxy for OpenAI, Anthropic, Gemini, and pinned OpenRouter calls, with token usage, failure, and billing-integrity receipts.
- [**pyccsl**](https://github.com/wolfdenpublishing/pyccsl) - (83 ⭐) - Python Claude Code Status Line (PyCCSL, pronounced "pixel").
- [**Claude-Monitor**](https://github.com/RISCfuture/Claude-Monitor) - (43 ⭐) - A menulet that tracks your Claude Code token usage.
- [**cccost**](https://github.com/badlogic/cccost) - (26 ⭐) - Instrument Claude Code to track actual token usage and cost.

---

## 🧩 SDKs & Development Kits

- [**Exact**](https://github.com/expo/exact) - (4.7k ⭐) - Cross-platform app framework with tools for coding agents to build, inspect, and test apps on web, macOS, iOS, and Linux.
- [**vibekit**](https://github.com/superagent-ai/vibekit) - (1.9k ⭐) - A simple SDK for safely running Codex, Gemini CLI, and Claude Code in a secure sandbox.
- [**claude-code-requirements-builder**](https://github.com/rizethereum/claude-code-requirements-builder) - (1.8k ⭐) - A tool for building Claude Code requirements.
- [**Claude-Code-Development-Kit**](https://github.com/peterkrueck/Claude-Code-Development-Kit) - (1.4k ⭐) - A personal Claude Code Development Kit.
- [**dotai**](https://github.com/udecode/dotai) - (1.2k ⭐) - The ultimate AI development stack, including Claude Code, Task Master, and Curso.
- [**framefields**](https://github.com/gatewai-dev/framefields) - (525 ⭐) - TypeScript toolkit for agent-authored video, motion graphics, compositing, and 3D scenes, with native WebGPU rendering and video export.
- [**claude-code-sdk-ts**](https://github.com/instantlyeasy/claude-code-sdk-ts) - (208 ⭐) - Configure models, enable tools, stream events, then fetch text, JSON, run details or token stats in one call via .asText() or .allowTools('Read', 'Write').
- [**claude-code-typescript-hooks**](https://github.com/bartolli/claude-code-typescript-hooks) - (180 ⭐) - Fast, intelligent quality checks for different project types.
- [**claude-code-api-rs**](https://github.com/ZhangHanDong/claude-code-api-rs) - (178 ⭐) - A high-performance Rust implementation of an OpenAI-compatible API gateway for Claude Code CLI.

---

## 📚 Guides & Learning

- [**learn-claude-code**](https://github.com/shareAI-lab/learn-claude-code) - (80.6k ⭐) - A hands-on course for building a Claude Code-like agent harness from scratch.
- [**claude-code-best-practice**](https://github.com/shanraisshan/claude-code-best-practice) - (69.2k ⭐) - A practical collection of Claude Code best practices for skills, subagents, hooks, commands, and agentic workflows.
- [**claude-howto**](https://github.com/luongnv89/claude-howto) - (47.4k ⭐) - Visual Claude Code guide with copy-ready templates and a learning path from basics to advanced agents.
- [**claude-code-tips**](https://github.com/ykdojo/claude-code-tips) - (10.4k ⭐) - 45 tips for getting the most out of Claude Code, from basics to advanced - includes a custom status line script, cutting the system prompt in half, using Gemini CLI as Claude Code's minion, and Claude Code running itself in a container.
- [**claude-code-showcase**](https://github.com/ChrisWiles/claude-code-showcase) - (6.1k ⭐) - Comprehensive Claude Code project configuration example with hooks, skills, agents, commands, and GitHub Actions workflows.
- [**agent-rules**](https://github.com/steipete/agent-rules) - (5.7k ⭐) - Rules and knowledge to work better with agents such as Claude Code or Cursor.
- [**claude-code-guide**](https://github.com/zebbern/claude-code-guide) - (4.7k ⭐) - A full guide on Claude tips and tricks, optimizing Claude Code, and finding every command possible.
- [**claude-code-hooks-mastery**](https://github.com/disler/claude-code-hooks-mastery) - (4.0k ⭐) - A resource for mastering Claude Code hooks.
- [**Claude Code: Everything You Need to Know**](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) - (3.7k ⭐) - Practical guide to Claude Code setup, prompts, slash commands, skills, hooks, subagents, agent teams, and MCP servers.
- [**Motion Prompt**](https://github.com/showheyohtaki/motion-prompt) - (2.3k ⭐) - Visual reference for motion graphics, camera moves, and web effects, with animated examples and prompts for coding agents.
- [**claude-code-mastery**](https://github.com/TheDecipherist/claude-code-mastery) - (560 ⭐) - Complete Claude Code guide covering CLAUDE.md, hooks, skills, MCP servers, and commands.
- [**claude-code-is-programmable**](https://github.com/disler/claude-code-is-programmable) - (313 ⭐) - Scale your compute with Claude Code as a programmable agentic coding tool.
- [**claude-code-mcpinstall**](https://github.com/undeadpickle/claude-code-mcpinstall) - (234 ⭐) - Easy guide to installing Claude Code MCPs globally on your machine.
- [**claude-code-system-prompt**](https://github.com/matthew-lim-matthew-lim/claude-code-system-prompt) - (154 ⭐) - Claude Code's system prompt.
- [**claudecode-best-practices**](https://github.com/rosmur/claudecode-best-practices) - (86 ⭐) - A collection of best practices and procedures for using Claude Code.

---

## Alternatives to Claude Code

- [**opencode**](https://github.com/anomalyco/opencode) - (228.0k ⭐) - The open source AI coding agent.
- [**OpenAI Codex CLI**](https://github.com/openai/codex) - (135.9k ⭐) - Lightweight coding agent that runs in your terminal.
- [**pi**](https://github.com/earendil-works/pi) - (122.9k ⭐) - A minimal terminal coding harness.
- [**gemini-cli**](https://github.com/google-gemini/gemini-cli) - (108.9k ⭐) - An open-source AI agent that brings the power of Gemini directly into your terminal.
- [**qwen-code**](https://github.com/QwenLM/qwen-code) - (30.8k ⭐) - A command-line AI workflow tool adapted from Gemini CLI, optimized for Qwen3-Coder models with enhanced parser support & tool support.
- [**crush**](https://github.com/charmbracelet/crush) - (29.1k ⭐) - The glamourous AI coding agent for your favourite terminal.
- [**grok-cli**](https://github.com/superagent-ai/grok-cli) - (3.5k ⭐) - An open-source AI agent that brings the power of Grok directly into your terminal.

---

## Contribution Guidelines

**Under Construction**

---

## Changelog

November 24, 2026

- Added six resources across Agent Skills, Agents & Orchestration, and Infrastructure & Proxies. Updated the repository links, descriptions, and star counts for Atlas and Agent of Empires.

November 19, 2026

- Added 15 resources across Agent Skills, Tools & Utilities, and Usage & Observability, and updated the Obsidian Skills repository link and star count.
- Refreshed GitHub star counts and reordered each category by stars.
- Removed 14 entries whose GitHub repository links returned 404.

November 10, 2026

- Added 17 resources across Agent Skills, Tools & Utilities, Infrastructure & Proxies, SDKs & Development Kits, and Guides & Learning.

November 4, 2026

- Added 16 resources across Agent Skills, Claude Plugins, Tools & Utilities, Clients & GUIs, and Usage & Observability.

October 29, 2026

- Added 20 Agent Skills and related resources, and updated Remotion Skills and Agentic Resource Registry (formerly Observal) with GitHub links and star counts.

October 22, 2026

- Added 24 Agent Skills and related resources across agents, plugins, tools, clients, observability, and development kits.

October 15, 2026

- Added 15 Agent Skills and related Claude Code resources, and refreshed peon-ping's description and GitHub star count.

October 7, 2026

- Added 24 Agent Skills and related Claude Code resources.

September 28, 2026

- Added 13 resources across Agent Skills and related Claude Code categories, and refreshed Hallmark and app-store-preflight-skills star counts.

September 21, 2026

- Added 18 resources across Agent Skills and related Claude Code categories, and refreshed BrowserSkill's GitHub star count.

September 15, 2026

- Added 16 Agent Skills and related Claude Code resources.

September 10, 2026

- Added 9 Agent Skills and related Claude Code resources.

August 30, 2026

- Added 7 Agent Skills and related Claude Code resources.

August 23, 2026

- Added 13 Agent Skills and related Claude Code resources.

August 20, 2026

- Added 9 Agent Skills and related Claude Code resources.

August 9, 2026

- Added 13 Agent Skills and related Claude Code resources.

July 28, 2026

- Added 16 Agent Skills and related Claude Code resources.

July 8, 2026

- Added more Agent Skills and related Claude Code resources.

June 29, 2026

- Added more Agent Skills and related Claude Code resources.

June 26, 2026

- Added more Agent Skills and related Claude Code resources.

June 24, 2026

- Added more Agent Skills and related Claude Code resources.

June 23, 2026

- Added more Agent Skills.

June 17, 2026

- Added more plugins & agent skills.

June 16, 2026

- Added more plugins & agent skills.

June 14, 2026

- Updated GitHub star counts.
