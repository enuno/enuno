<p align="center">
  <img src="https://raw.githubusercontent.com/enuno/noesis-agent-stack/refs/heads/main/assets/logo/NoesisLabs.png" alt="Noesis Labs" width="300" height="300">
</p>

**Infrastructure & Systems Engineer · Open-Source Maintainer · AI-Agent Infrastructure**

I build the networks, automation, and agent systems that connect physical infrastructure to governed, intelligent operations.

I have 20 years of hands-on experience building and running ISP and telecom infrastructure. As President of Network Engineering and Operations at ServerDomes, I am responsible for fiber WAN design and datacenter networking. I also founded Ryno Crypto Mining Services, which builds modular, direct-to-chip liquid-cooled Bitcoin mining infrastructure powered by green energy.

My open-source work applies the same discipline to software: tools that let AI agents operate real networks safely, and automation that keeps those systems reproducible and reviewable.

[Portfolio](https://enuno.github.io/DynamicCareerCanvas/) · [LinkedIn](https://linkedin.com/in/elvis-nuno-5635914) · [Email](mailto:publicprofileresumec.profound075@slmail.me)

**Current focus:** MCP-based network operations with UniFi MCP Server, and Noesis — a governed multi-agent system and the Ansible code that deploys it.

## Featured open source

<h3 align="center">
  <a href="https://github.com/enuno/unifi-mcp-server">UniFi MCP Server</a>
</h3>

<p align="center">
  <img src="https://github.com/enuno/unifi-mcp-server/blob/main/assets/unifi-mcp-server-logo.png" alt="UniFi MCP Server logo" width="300" height="300">
</p>

An open-source [Model Context Protocol](https://modelcontextprotocol.io) server that gives AI agents one standard interface to UniFi infrastructure: UniFi Network, UniFi Protect, and the UniFi cloud APIs. Agents can inspect clients, devices, firewall policy, and sites, and can change configuration when the operator allows it.

- **290+ GitHub stars**, and an active community that contributes code, reports bugs, and requests features.
- **Built-in safety controls:** every write needs explicit confirmation and supports a dry-run preview. Read-only and dry-run server modes and role-based risk tiers limit what an agent can do, and a hash-chained audit log records each change.
- **Flexible deployment:** a PyPI package or multi-architecture container over stdio or Streamable HTTP, with Ansible and Helm options and an optional multi-controller fleet mode.

Python · FastMCP · Pydantic · Apache-2.0

[Repository](https://github.com/enuno/unifi-mcp-server) · [Tool reference](https://github.com/enuno/unifi-mcp-server/blob/main/API.md) · [Contributing guide](https://github.com/enuno/unifi-mcp-server/blob/main/CONTRIBUTING.md) · [Discussions](https://github.com/enuno/unifi-mcp-server/discussions)

<h3 align="center">
  <a href="https://github.com/enuno/noesis-agent-stack">Noesis Agent Stack</a>
</h3>

<p align="center">
  <img src="https://github.com/enuno/noesis-agent-stack/blob/main/assets/logo/NoesisAgentStack.png" alt="Noesis Agent Stack" width="300" height="300">
</p>

A governed multi-agent system built on Hermes Agent profiles. A central orchestrator plans work, gives each task to the specialist with the narrowest mandate, and combines the results. The orchestrator itself has no execution access.

- **Durable handoffs:** work moves as typed task contracts in an append-only ledger, not as chat history.
- **Approval boundaries:** irreversible operations wait at a human approval gate, and reviewer-only profiles audit work they did not do.

*Status:* the orchestration control plane passes its repository test suite. Production activation is phase-gated and not yet complete; the repository's [status section](https://github.com/enuno/noesis-agent-stack#status) records each gate.

[Repository](https://github.com/enuno/noesis-agent-stack) · [Workflows](https://github.com/enuno/noesis-agent-stack/blob/main/WORKFLOWS.md)

<h3 align="center">
  <a href="https://github.com/enuno/noesis-ansible">Noesis Ansible</a>
</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/enuno/noesis-ansible/refs/heads/main/assets/NoesisAnsible.png" alt="Noesis Ansible" width="300" height="300">
</p>

The infrastructure side of Noesis. The agent stack defines and coordinates agent behavior; this repository provisions and configures the services it runs on: agent and MCP registries, policy and sandboxing, memory services, agent runtimes, and observability.

- **Phased, idempotent playbooks** from host bootstrap to validation, with backup, restore, and rollback playbooks.
- **Targets in the repository today:** local Docker hosts, macOS machines over a Tailscale tailnet, and SSH production inventories, plus Helm charts for Kubernetes and K3s.

Ansible · Docker · Helm · Tailscale

[Repository](https://github.com/enuno/noesis-ansible)

## More open source

**AI agents and tooling**

- [Claude Command & Control](https://github.com/enuno/claude-command-and-control) — Manuals, templates, and practices for Claude commands, agent configuration, and multi-agent workflows.
- [Moltbot Philosopher](https://github.com/enuno/moltbot-philosopher) — A council of philosopher-persona agents that posts and debates on [Moltbook](https://www.moltbook.com/u/MoltbotPhilosopher), a social network for AI agents.

**Network, DNS, and privacy infrastructure**

- [Ansible Handshake DNS](https://github.com/enuno/ansible-handshake-dns) — Deploys a Handshake full node, Unbound with DNS-over-TLS and DNS-over-HTTPS, and Caddy for decentralized DNS resolution.
- [Ansible Anon Relay](https://github.com/enuno/ansible-anon-relay) — Deploys an Anyone Protocol anon relay in Docker.
- [Tailscale ACL](https://github.com/enuno/tailscale-acl) — Tailscale access policy managed as code, with GitOps workflows and AI coding agents.
- [yubikey-tools](https://github.com/enuno/yubikey-tools) — Scripts and a Python library for YubiKey setup and management: GPG, PIV, FIDO2, and OATH.

## Engineering domains

- **Networks & edge infrastructure** — Fiber WAN and datacenter networking, ISP and telecom operations, BGP, OSPF, VRRP, IPsec, WireGuard, DNS.
- **Systems & automation** — Linux, Ansible, Terraform, Docker, Kubernetes, KVM, Proxmox, AWS, Google Cloud, Azure, OpenStack, Prometheus.
- **AI agents & orchestration** — Model Context Protocol servers, Hermes Agent, approval-gated multi-agent workflows, Claude Code.
- **Decentralized & privacy infrastructure** — Bitcoin mining infrastructure, DePIN (Akash, Helium), decentralized storage (Filecoin, Storj), dVPN and mixnets (Sentinel, Nym, Anyone), hardware security keys.

## Writing and community

- [Community ISP Handbook](https://bsi-mt.notion.site/9391097364e84f33968423a0b0a7a230) — A guide for rural communities that want to form a local ISP.
- [Bridging the Digital Divide](https://www.youtube.com/watch?v=D0J-QLv0ZHA) — A talk on bringing broadband to rural Montana through cooperatives (2021).
- [Missoula Valley Internet Co-op launch](https://www.youtube.com/watch?v=FBwfHBQqZcs) — KPAX News coverage of the co-op's network launch (2021).
- [Nostr articles on Yakihonne](https://yakihonne.com/profile/npub1qnl45ujgr5vmkyg0vslwuq7hwsj7zytwj5jrkm09tsxajg460vks8j5z3d) — Writing on blockchain and technology.

## Connect

Bug reports, pull requests, and technical discussion are welcome in each project's issue tracker. For other conversations, use [email](mailto:publicprofileresumec.profound075@slmail.me) or [X](https://twitter.com/NunoElvis).
