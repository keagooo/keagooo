<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:020617,45:0f766e,100:7c3aed&text=Keagan%20Hulet&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=Systems%20Engineer%20%7C%20AI%20Agent%20Infrastructure%20%7C%20Homelab&descSize=16&descAlignY=58&animation=fadeIn" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=800&lines=Building+Nyx+%E2%80%94+a+self-hosted+autonomous+AI+agent;Automating+Microsoft+365%2C+Entra%2C+and+Intune+at+scale;Running+a+27-service+Proxmox+homelab;Orchestrating+local+%2B+cloud+LLMs+with+LiteLLM" />

<br>

<a href="https://hulet.dev"><img src="https://img.shields.io/badge/hulet.dev-0f172a?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=keagoo&style=for-the-badge&color=0891b2" />

</div>

---

## `whoami`

```powershell
PS> Get-OperatorProfile

Name        : Keagan Hulet
Role        : IT Systems Engineer, Price Brothers Management
Stack       : Hybrid on-prem AD + Azure AD (Entra), Intune, M365
SideProject : Nyx — autonomous agent running on a 767GB Proxmox rig
CurrentMode : Wiring local LLMs into a real agent, not a chatbot demo
```

## Nyx — what I'm actually building

Nyx is a self-hosted, JARVIS-style AI agent that runs on my own hardware — not a wrapper around a chat window. It maintains persistent memory, pulls live context from Zendesk/email/calendar, and executes autonomous tasks through Telegram.

<table>
<tr>
<td width="50%" valign="top">

**Core stack**
- OpenClaw gateway (agent runtime)
- LiteLLM proxy — routes between local models and Claude/GPT
- Honcho — long-term memory layer
- Langfuse — full observability/tracing
- n8n — automation pipelines

</td>
<td width="50%" valign="top">

**Inference**
- Local models across 4 nodes (RTX 3090Ti, RTX 2080, dual-Xeon MoE rig)
- Custom MCP server exposing internal tools (Zendesk, email, calendar) to the agent
- Forge — spawns isolated subagents per task in Docker
- Hermes (in dev) — delegation layer routing coding work to Claude Code / Codex

</td>
</tr>
</table>

## Day job

Migrating ~200 property-office endpoints off Meraki SM and onto Intune, replacing legacy Office installs with Microsoft 365 Apps via a custom Win32 package, in a hybrid on-prem AD / Entra environment with Seamless SSO. If you've ever fought `WamDefaultSet ERROR 0x80070520`, we should talk.

## Tech

<div align="center">

<img src="https://skillicons.dev/icons?i=powershell,python,typescript,docker,git,github,linux,debian,azure,bash" />

<br><br>

<img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Entra%20ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Intune-2563eb?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />

</div>

## GitHub stats

<div align="center">
<img height="165em" src="https://github-readme-stats.vercel.app/api?username=keagoo&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=A78BFA&text_color=E5E7EB&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=keagoo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=E5E7EB" />
</div>

<div align="center">
<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=keagoo&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=22D3EE&line=A78BFA&point=FFFFFF" />
</div>

## Find me

<div align="center">
<a href="https://hulet.dev"><img src="https://img.shields.io/badge/Portfolio-hulet.dev-22c55e?style=for-the-badge&logo=firefoxbrowser&logoColor=white" /></a>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:7c3aed,50:0f766e,100:020617" />
