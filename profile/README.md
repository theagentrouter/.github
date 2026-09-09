<p align="center">
  <a href="https://theagentrouter.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/theagentrouter/.github/main/profile/agent-router-horizontal-dark.svg">
      <img alt="Agent Router" src="https://raw.githubusercontent.com/theagentrouter/.github/main/profile/agent-router-horizontal.svg" width="420">
    </picture>
  </a>
</p>

<h3 align="center">The open source control plane for AI and agent traffic, powered by Envoy.</h3>

<p align="center">
  <b>Agent Router configures. Envoy handles the traffic.</b><br>
  An <a href="https://aaif.io">Agentic AI Foundation</a> project · Formerly <i>Envoy AI Gateway</i>
</p>

<p align="center">
  <a href="https://theagentrouter.ai">Website</a>
  &nbsp;·&nbsp;
  <a href="https://theagentrouter.ai/docs">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://theagentrouter.ai/docs/getting-started/">Quickstart</a>
  &nbsp;·&nbsp;
  <a href="https://theagentrouter.ai/blog">Blog</a>
  &nbsp;·&nbsp;
  <a href="https://theagentrouter.ai/release-notes/">Release Notes</a>
  &nbsp;·&nbsp;
  <a href="https://discord.gg/XvSqZZty7k">Discord</a>
</p>

<p align="center">
  <a href="https://github.com/theagentrouter/agent-router/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/theagentrouter/agent-router?style=flat&logo=github&logoColor=white&color=FF5500&label=Stars"></a>
  <a href="https://github.com/theagentrouter/agent-router/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/theagentrouter/agent-router?style=flat&color=1A937F&label=Release"></a>
  <a href="https://github.com/theagentrouter/agent-router/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/theagentrouter/agent-router?style=flat&color=0B3B33&label=License"></a>
  <a href="https://discord.gg/XvSqZZty7k"><img alt="Discord" src="https://img.shields.io/badge/Discord-Join%20the%20server-5865F2?style=flat&logo=discord&logoColor=white"></a>
  <a href="https://x.com/TheAgentRouter"><img alt="X" src="https://img.shields.io/badge/X-%40TheAgentRouter-000000?style=flat&logo=x&logoColor=white"></a>
  <a href="https://agentrouter.substack.com"><img alt="Substack" src="https://img.shields.io/badge/Substack-Subscribe-FF6719?style=flat&logo=substack&logoColor=white"></a>
  <a href="https://www.linkedin.com/company/agent-router"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Follow-0A66C2?style=flat"></a>
</p>

> [!TIP]
> **Like what we're building?** A ⭐ on [`agent-router`](https://github.com/theagentrouter/agent-router) helps other platform and AI teams find the project — and it makes the maintainers' Monday. Thank you!

## What is Agent Router?

Agent Router gives application teams **one OpenAI-compatible API for every model, MCP tool, and agent** — hosted providers, self-hosted inference, and MCP servers alike. Platform teams keep **credentials, routing, quotas, failover, and usage attribution** in one place, enforced by [Envoy](https://envoyproxy.io) and [Envoy Gateway](https://gateway.envoyproxy.io).

Same code, same maintainers, same Apache 2.0 license as Envoy AI Gateway. Your manifests from yesterday apply tomorrow.

Try it on your laptop in one command:

```shell
OPENAI_API_KEY=sk-your-key aigw run
```

Then point any OpenAI-compatible client at `http://localhost:1975/v1`. See the [CLI guide](https://theagentrouter.ai/docs/cli/), or the [Getting Started guide](https://theagentrouter.ai/docs/getting-started/) to deploy on Kubernetes.

## Join the community

Everything happens in the open. Pick the door that suits you:

<table>
  <tr>
    <td width="180" valign="top"><b>💬 Chat</b></td>
    <td>Ask questions, share what you're building, and meet the maintainers on the <a href="https://discord.gg/XvSqZZty7k"><b>Agent Router Discord</b></a>.</td>
  </tr>
  <tr>
    <td valign="top"><b>🗓️ Weekly meeting</b></td>
    <td>
      <b>Every Monday</b> — 8:00 am US Pacific · 11:00 am US Eastern · 4:00 pm London · 5:00 pm Central Europe<br>
      <sub>Skipped on US public holidays. Open to everyone — no invitation needed.</sub><br><br>
      📝 <a href="https://docs.google.com/document/d/10e1sfsF-3G3Du5nBHGmLjXw5GVMqqCvFDqp_O65B0_w/edit?tab=t.0"><b>Agenda &amp; meeting notes</b></a> — add your name and your topic before the call<br>
      🎥 <a href="https://zoom-lfx.platform.linuxfoundation.org/meeting/91546415944?password=61fd5a5d-41e9-4b0c-86ea-b607c4513e37"><b>Join on Zoom</b></a> (LFX)<br>
      ▶️ <a href="https://zoom-lfx.platform.linuxfoundation.org/meetings/envoy?view=list"><b>Past recordings</b></a>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>📣 Follow along</b></td>
    <td>
      <a href="https://x.com/TheAgentRouter">X / @TheAgentRouter</a> ·
      <a href="https://agentrouter.substack.com">Substack</a> (release notes, design notes, field reports) ·
      <a href="https://www.linkedin.com/company/agent-router">LinkedIn</a>
    </td>
  </tr>
  <tr>
    <td valign="top"><b>🤝 Code of conduct</b></td>
    <td>We follow the LF Projects <a href="https://github.com/theagentrouter/agent-router/blob/main/CODE_OF_CONDUCT.md">Code of Conduct</a>. Be kind; assume good intent.</td>
  </tr>
</table>

## Repositories

| Repository | What's inside |
|---|---|
| [**agent-router**](https://github.com/theagentrouter/agent-router) | The control plane, the `aigw` CLI, Helm charts, examples, and the source for [theagentrouter.ai](https://theagentrouter.ai). Start here. |
| [**.github**](https://github.com/theagentrouter/.github) | This profile and the organization's shared community health files. |

Agent Router builds on [Envoy](https://github.com/envoyproxy/envoy), [Envoy Gateway](https://github.com/envoyproxy/gateway), and the Kubernetes [Gateway API](https://github.com/kubernetes-sigs/gateway-api).

## Contribute

New contributors are welcome — code, docs, examples, and issue triage all count.

- 🚀 Read the [Contributing guide](https://github.com/theagentrouter/agent-router/blob/main/CONTRIBUTING.md) to build and test locally
- 🐣 Pick a [good first issue](https://github.com/theagentrouter/agent-router/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22) or something tagged [help wanted](https://github.com/theagentrouter/agent-router/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22)
- 🧭 See where the project is headed in [GOALS.md](https://github.com/theagentrouter/agent-router/blob/main/GOALS.md) and how releases work in [RELEASES.md](https://github.com/theagentrouter/agent-router/blob/main/RELEASES.md)
- 🛡️ Found a vulnerability? Follow the [security policy](https://github.com/theagentrouter/agent-router/blob/main/SECURITY.md) — please don't open a public issue
- 👥 Meet the [maintainers](https://github.com/theagentrouter/agent-router/blob/main/MAINTAINERS.md)

Built by [130+ contributors](https://github.com/theagentrouter/agent-router/graphs/contributors) from 20+ organizations, with maintainers from Bloomberg, Nutanix, Tencent, and Tetrate. Thank you, all of you.

<p align="center">
  <a href="https://star-history.com/#theagentrouter/agent-router&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=theagentrouter/agent-router&type=Date&theme=dark">
      <img alt="Star history of theagentrouter/agent-router" src="https://api.star-history.com/svg?repos=theagentrouter/agent-router&type=Date" width="600">
    </picture>
  </a>
</p>

---

<p align="center">
  <sub>
    Agent Router is an <a href="https://aaif.io">Agentic AI Foundation</a> project, powered by Envoy.
    Copyright © Agent Router a Series of LF Projects, LLC.
    See the <a href="https://theagentrouter.ai/trademark-policy">trademark policy</a> and <a href="https://lfprojects.org">lfprojects.org</a> for terms of use and other project policies.
  </sub>
</p>
