<div align="center">

# Awesome Security Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/Jiashuo-Zhang/Awesom-Security-Skills?style=social)](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Jiashuo-Zhang/Awesom-Security-Skills?style=social)](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/network/members)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/Jiashuo-Zhang/Awesom-Security-Skills)](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/commits/main)

**A curated list of awesome skills, MCP tools, and resources for security analysis, vulnerability detection and anything related to cyber security.**

[Report Issue](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/issues) · [Request Addition](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/pulls) · [Contribute](#contributing)

</div>

---

## Contents

- [Blogs & Articles](#blogs--articles)
- [Security Skills](#security-skills)
  - [Security Analysis](#security-analysis)
  - [Static Analysis (SAST)](#static-analysis-sast)
  - [Capture The Flag (CTF)](#capture-the-flag-ctf)
  - [Penetration Testing](#penetration-testing)
  - [Threat Modeling](#threat-modeling)
  - [Compliance & GRC](#compliance--grc)
  - [Agent Security](#agent-security)
  - [Skill Security](#skill-security)
- [Security Skills at Marketplaces](#security-skills-at-marketplaces)
- [Coding Agent Extensions for Security Analysis](#coding-agent-extensions-for-security-analysis)
- [MCP Tools for Security](#mcp-tools-for-security)
- [Skill & MCP Security Checklist](#skill--mcp-security-checklist)
- [Contributing](#contributing)

---

## Blogs & Articles

_Key reads on the frontier of AI and cybersecurity, from leading labs and practitioners._

- [Making frontier cybersecurity capabilities available to defenders](https://www.anthropic.com/news/claude-code-security) — Anthropic — How Claude Code is being deployed for defensive security operations.
- [Evaluating and mitigating the growing risk of LLM-discovered 0-days](https://red.anthropic.com/2026/zero-days/) — Anthropic — Research on LLMs autonomously finding zero-day vulnerabilities.
- [Finding bugs across the Python ecosystem with Claude and property-based testing](https://red.anthropic.com/2026/property-based-testing/) — Anthropic — Combining property-based testing with AI to surface ecosystem-wide bugs.
- [AI models are showing a greater ability to find and exploit vulnerabilities on realistic cyber ranges](https://red.anthropic.com/2026/cyber-toolkits-update/) — Anthropic — Benchmarking AI exploit capabilities on realistic environments.
- [AI agents find $4.6M in blockchain smart contract exploits](https://red.anthropic.com/2025/smart-contracts/) — Anthropic — Autonomous agents discovering high-value smart contract vulnerabilities.
- [Codex Security: now in research preview](https://openai.com/index/codex-security-now-in-research-preview/) — OpenAI — OpenAI's Codex applied to security research and vulnerability discovery.
- [Introducing EVMbench](https://openai.com/index/introducing-evmbench/) — OpenAI — A new benchmark for evaluating AI models on EVM smart contract security.
- [Why we no longer evaluate SWE-bench Verified](https://openai.com/why-we-no-longer-evaluate-swe-bench-verified/) — OpenAI — A discussion on benchmark limitations in the age of powerful AI agents.
- [Automate app deployment and security analysis with new Gemini CLI extensions](https://cloud.google.com/blog/products/ai-machine-learning/automate-app-deployment-and-security-analysis-with-new-gemini-cli-extensions?hl=en) — Google Cloud — Using Gemini CLI extensions to automate security analysis workflows.
- [Introducing CodeMender: an AI agent for code security](https://deepmind.google/blog/introducing-codemender-an-ai-agent-for-code-security/) — Google DeepMind — AI agent using Gemini to automatically identify and patch vulnerabilities; upstreamed 72 security fixes to major open-source projects.
- [EnIGMA: Interactive Agent Tools for LLM-based CTF Solving](https://arxiv.org/abs/2409.16165) — ICML 2025 — LLM agent solving 390 CTF challenges at 3× the success rate of prior AI agents, introducing interactive terminal tools for debuggers and network analyzers.

---



## Security Skills

_AI agent skills designed for security workflows._

### Security Analysis

- [trailofbits/skills](https://github.com/trailofbits/skills) ![Stars](https://img.shields.io/github/stars/trailofbits/skills?style=social) - Security analysis skills from Trail of Bits, a leading security research firm.
- [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) ![Stars](https://img.shields.io/github/stars/mukul975/Anthropic-Cybersecurity-Skills?style=social) - 753+ structured cybersecurity skills for AI agents, MITRE ATT&CK mapped, compatible with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI and more.
- [ghostsecurity/skills](https://github.com/ghostsecurity/skills) ![Stars](https://img.shields.io/github/stars/ghostsecurity/skills?style=social) - Security skills from Ghost Security for automated vulnerability detection.
- [semgrep/skills](https://github.com/semgrep/skills) ![Stars](https://img.shields.io/github/stars/semgrep/skills?style=social) - Semgrep-powered skills for automated code security review.
- [BehiSecc/VibeSec-Skill](https://github.com/BehiSecc/VibeSec-Skill) ![Stars](https://img.shields.io/github/stars/BehiSecc/VibeSec-Skill?style=social) - Skill for Claude Code to write secure code and prevent common vulnerabilities.
- [gadievron/raptor](https://github.com/gadievron/raptor) ![Stars](https://img.shields.io/github/stars/gadievron/raptor?style=social) - Turns Claude Code into a general-purpose offensive/defensive security agent using CLAUDE.md rules, sub-agents, and skills for adversarial security research.
- [transilienceai/communitytools](https://github.com/transilienceai/communitytools) ![Stars](https://img.shields.io/github/stars/transilienceai/communitytools?style=social) - Open-source Claude Code skills, agents, and slash commands for AI-powered penetration testing, bug bounty hunting, and security research.
- [codexstar69/bug-hunter](https://github.com/codexstar69/bug-hunter) ![Stars](https://img.shields.io/github/stars/codexstar69/bug-hunter?style=social) - Adversarial AI bug hunter with auto-fix skill for Claude Code, Cursor, Codex CLI and more; multi-agent pipeline finds security vulnerabilities and fixes them autonomously.
- [sanyuan0704/sanyuan-skills](https://github.com/sanyuan0704/sanyuan-skills) ![Stars](https://img.shields.io/github/stars/sanyuan0704/sanyuan-skills?style=social) - Community-contributed security analysis skills collection.
- [raroque/vibe-security-skill](https://github.com/raroque/vibe-security-skill) ![Stars](https://img.shields.io/github/stars/raroque/vibe-security-skill?style=social) - Vibe-coded security skill for rapid vulnerability triage.
- [jthack/ffuf_claude_skill](https://github.com/jthack/ffuf_claude_skill) ![Stars](https://img.shields.io/github/stars/jthack/ffuf_claude_skill?style=social) - Skill wrapping `ffuf` for AI-driven web fuzzing and directory discovery.
- [AgentSecOps/SecOpsAgentKit](https://github.com/AgentSecOps/SecOpsAgentKit) ![Stars](https://img.shields.io/github/stars/AgentSecOps/SecOpsAgentKit?style=social) - A toolkit of security operations skills for AI-powered SecOps automation.

### Static Analysis (SAST)

- [SunWeb3Sec/llm-sast-scanner](https://github.com/SunWeb3Sec/llm-sast-scanner) ![Stars](https://img.shields.io/github/stars/SunWeb3Sec/llm-sast-scanner?style=social) - LLM-powered SAST scanner for detecting vulnerabilities in smart contracts and general code.
- [utkusen/sast-skills](https://github.com/utkusen/sast-skills) ![Stars](https://img.shields.io/github/stars/utkusen/sast-skills?style=social) - Static analysis skill set for automated code vulnerability discovery.
- [agamm/claude-code-owasp](https://github.com/agamm/claude-code-owasp) ![Stars](https://img.shields.io/github/stars/agamm/claude-code-owasp?style=social) - Claude Code skill for OWASP security best practices (2025–2026), including Top 10:2025, ASVS 5.0, agentic AI security, and 20+ language-specific security quirks.
- [kadenzipfel/scv-scan](https://github.com/kadenzipfel/scv-scan) ![Stars](https://img.shields.io/github/stars/kadenzipfel/scv-scan?style=social) - Claude Code skill that scans Solidity codebases for security vulnerabilities, referencing 36 unique vulnerability types.

### Capture The Flag (CTF)

- [ljagiello/ctf-skills](https://github.com/ljagiello/ctf-skills) ![Stars](https://img.shields.io/github/stars/ljagiello/ctf-skills?style=social) - AI skills configured for Capture The Flag challenge solving (pwn, crypto, web, misc).
- [learntocloud/linux-ctfs](https://github.com/learntocloud/linux-ctfs) ![Stars](https://img.shields.io/github/stars/learntocloud/linux-ctfs?style=social) - Linux-based CTF challenges with AI-assisted skill support for learning cloud security.

### Penetration Testing

- [wgpsec/AboutSecurity](https://github.com/wgpsec/AboutSecurity) ![Stars](https://img.shields.io/github/stars/wgpsec/AboutSecurity?style=social) - Comprehensive pentest resource collection including tools, payloads, and skills.
- [Eyadkelleh/awesome-claude-skills-security](https://github.com/Eyadkelleh/awesome-claude-skills-security) ![Stars](https://img.shields.io/github/stars/Eyadkelleh/awesome-claude-skills-security?style=social) - Curated Claude skills tailored for penetration testing workflows.

### Threat Modeling

- [fr33d3m0n/threat-modeling](https://github.com/fr33d3m0n/threat-modeling) ![Stars](https://img.shields.io/github/stars/fr33d3m0n/threat-modeling?style=social) - AI-assisted threat modeling skill for analyzing architectures and generating threat reports.

### Agent Security

_Skills focused on securing or auditing AI agents themselves._

- [snyk/agent-scan](https://github.com/snyk/agent-scan) ![Stars](https://img.shields.io/github/stars/snyk/agent-scan?style=social) - Snyk's agent scanning tool for detecting vulnerabilities introduced by AI-generated code.
- [prompt-security/clawsec](https://github.com/prompt-security/clawsec) ![Stars](https://img.shields.io/github/stars/prompt-security/clawsec?style=social) - Security layer for Claude-based agents, protecting against prompt injection and abuse.
- [slowmist/slowmist-agent-security](https://github.com/slowmist/slowmist-agent-security) ![Stars](https://img.shields.io/github/stars/slowmist/slowmist-agent-security?style=social) - SlowMist's security framework for auditing and hardening AI agents in blockchain contexts.

### Skill Security

_Tools for scanning and securing skills and MCP servers themselves._

- [cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) ![Stars](https://img.shields.io/github/stars/cisco-ai-defense/skill-scanner?style=social) - Cisco's scanner for identifying security risks in deployed AI skills.
- [huifer/skill-security-scan](https://github.com/huifer/skill-security-scan) ![Stars](https://img.shields.io/github/stars/huifer/skill-security-scan?style=social) - Static analysis tool for auditing skill definitions and their security implications.

---



## MCP Tools for Security

_Model Context Protocol (MCP) servers that expose security tools and data sources to AI agents._

- [cyproxio/mcp-for-security](https://github.com/cyproxio/mcp-for-security) ![Stars](https://img.shields.io/github/stars/cyproxio/mcp-for-security?style=social) - Collection of MCP servers wrapping common security tools (nmap, nuclei, etc.).
- [FuzzingLabs/mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) ![Stars](https://img.shields.io/github/stars/FuzzingLabs/mcp-security-hub?style=social) - FuzzingLabs' hub of MCP servers for fuzzing and vulnerability research workflows.
- [frishtik/osint-tools-mcp-server](https://github.com/frishtik/osint-tools-mcp-server) ![Stars](https://img.shields.io/github/stars/frishtik/osint-tools-mcp-server?style=social) - MCP server exposing OSINT tools (whois, shodan, etc.) to AI agents.
- [FuzzingLabs/secpipe](https://github.com/FuzzingLabs/secpipe) ![Stars](https://img.shields.io/github/stars/FuzzingLabs/secpipe?style=social) - A security pipeline framework built on MCP for automated multi-stage analysis.
- [CrowdStrike/falcon-mcp](https://github.com/CrowdStrike/falcon-mcp) ![Stars](https://img.shields.io/github/stars/CrowdStrike/falcon-mcp?style=social) - CrowdStrike Falcon's official MCP integration for threat intelligence and EDR data.
- [semgrep/mcp](https://github.com/semgrep/mcp) ![Stars](https://img.shields.io/github/stars/semgrep/mcp?style=social) - Semgrep's MCP server for running SAST rules directly from AI agents.
- [google/mcp-security](https://github.com/google/mcp-security) ![Stars](https://img.shields.io/github/stars/google/mcp-security?style=social) - Google's official MCP server collection for security operations and threat analysis.
- [groovyBugify/aws-security-mcp](https://github.com/groovyBugify/aws-security-mcp) ![Stars](https://img.shields.io/github/stars/groovyBugify/aws-security-mcp?style=social) - MCP server for querying AWS security services (GuardDuty, Security Hub, IAM) from AI agents.
- [PortSwigger/mcp-server](https://github.com/PortSwigger/mcp-server) ![Stars](https://img.shields.io/github/stars/PortSwigger/mcp-server?style=social) - Official Burp Suite MCP server, enabling AI agents to drive web application security testing via Burp.
- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ![Stars](https://img.shields.io/github/stars/LaurieWired/GhidraMCP?style=social) - MCP server for Ghidra, enabling AI-assisted reverse engineering, decompilation, and binary analysis.
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) ![Stars](https://img.shields.io/github/stars/BurtTheCoder/mcp-maigret?style=social) - MCP server wrapping Maigret for OSINT username searches across hundreds of social networks.
- [addcontent/nuclei-mcp](https://github.com/addcontent/nuclei-mcp) ![Stars](https://img.shields.io/github/stars/addcontent/nuclei-mcp?style=social) - MCP server integrating the Nuclei vulnerability scanner with template management and concurrent scanning.
- [PhialsBasement/nmap-mcp-server](https://github.com/PhialsBasement/nmap-mcp-server) ![Stars](https://img.shields.io/github/stars/PhialsBasement/nmap-mcp-server?style=social) - MCP server exposing Nmap network scanning (quick scan, full port scan, version detection) to AI agents.

## 



## Security Skills & MCPs at Marketplaces

_Platforms to discover, share, and deploy security-focused AI skills._

- [skillsmp.com](https://skillsmp.com) - General skills marketplace with a growing security category.
- [mcpmarket.com/tools/skills](https://mcpmarket.com/tools/skills) - MCP-focused marketplace listing security tools and skills.
- [lobehub.com/skills](https://lobehub.com/skills) - LobeHub's skill directory featuring security analysis and pentest skills.
- [skillsllm.com](https://skillsllm.com/) - LLM-oriented skill store with curated security offerings.
- [skillstore.io](https://skillstore.io/zh-hans) - Multi-language skill platform with international security skill contributions.
- [cline.bot/mcp-marketplace](https://cline.bot/mcp-marketplace) - Cline's MCP marketplace for discovering MCP tools and integrations.


---

## Coding Agent Extensions for Security Analysis

_First-party and official extensions from major AI coding agents for security workflows._

- [Claude Code Security](https://claude.com/solutions/claude-code-security) — Anthropic's official security solution built on Claude Code for automated vulnerability detection.
- [claude-code-security-review (CLI)](https://github.com/anthropics/claude-code-security-review) ![Stars](https://img.shields.io/github/stars/anthropics/claude-code-security-review?style=social) — Open-source CLI tool from Anthropic for running security reviews via Claude Code.
- [Codex Security](https://developers.openai.com/codex/security) — OpenAI Codex's security capabilities for AI-assisted vulnerability research.
- [Codex CLI Security Features](https://developers.openai.com/codex/cli/features/) — Security-focused features in the Codex CLI for automated code review.
- [Gemini CLI Security Extension](https://github.com/gemini-cli-extensions/security/) ![Stars](https://img.shields.io/github/stars/gemini-cli-extensions/security?style=social) — Google's Gemini CLI extension for integrating AI into security analysis pipelines.

---

## Skill & MCP Security Checklist

- [OWASP Agentic Skills Top 10](https://owasp.org/www-project-agentic-skills-top-10/) — The definitive community checklist for identifying and mitigating the top 10 security risks in agentic AI skills.
- [OWASP  MCP Top 10](https://owasp.org/www-project-mcp-top-10/) — The definitive community checklist for identifying and mitigating the top 10 security risks in agentic AI MCPs.


---

## Contributing

Contributions are welcome! Feel free to open a [Pull Request](https://github.com/Jiashuo-Zhang/Awesom-Security-Skills/pulls) to add new resources.
