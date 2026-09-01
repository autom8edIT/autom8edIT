# Joel Larsson

## Senior SRE and Infrastructure Automation Engineer

I build and troubleshoot infrastructure across the full stack: endpoint, identity,
network, operating system, automation, and the operational tooling around it.

I have nearly 20 years of professional IT experience across enterprise consulting,
legal, healthcare, research, and managed services. My background spans Windows,
Linux, macOS, Active Directory, networking, hardware, and production automation.
My current focus is closed-loop SRE:

> detect -> diagnose -> remediate safely -> verify

Based in Sweden. Open to global remote and contract opportunities.

## Core strengths

| Area | Experience |
|---|---|
| Operating systems | Windows internals, Windows Server, Linux, macOS, endpoint engineering |
| Networking | DNS, DHCP, routing, switching, VLANs, VPN, Wi-Fi, client connectivity |
| Identity and enterprise | Active Directory, Microsoft 365, Entra ID, Intune, PKI |
| Automation | PowerShell, Python, C/C++, Go, Rust, scripting and operational tooling |
| Reliability | Root-cause analysis, incident response, observability, recovery and verification |
| Infrastructure | VMware, Hyper-V, servers, storage, deployment and hardware diagnostics |
| Applied AI | Local LLMs, retrieval, tool execution, persistent operational knowledge |

## Featured engineering work

### [GodBrain](https://github.com/usrname1git/GodBrain)

A Windows-first, local SRE agent and automation system built around a native C++
control kernel.

- Runs an explicit `discover -> plan -> execute -> verify` loop.
- Keeps model output behind policy and authorization boundaries.
- Uses a Go ingestion and retrieval layer with immutable sources and reviewed
  operational knowledge.
- Exposes bounded diagnostics, host telemetry, audit history, rollback-aware local
  edits, and allowlisted remediation.
- Treats the language model as a replaceable reasoning component, not as the
  security boundary.

### [OmniContext](https://github.com/autom8edIT/OmniContext)

The architecture case study that preceded GodBrain. It documents the move from a
shared-memory prototype to a safer SRE design with explicit trust boundaries,
provenance, verification, and controlled execution.

## Selected professional evidence

- Led 20-30 technicians during an enterprise Windows migration for AstraZeneca in
  an IBM-led delivery environment.
- Participated in infrastructure work for a Swedish Tax Agency data-center project.
- Built complete Windows domains, networks, VPNs, Wi-Fi, servers, and endpoint
  environments for small and medium-sized organizations.
- Owned IT strategy and operations as the sole technical decision-maker for a law
  firm.
- Filed a detailed
  [Microsoft Intelligent Terminal bug report](https://github.com/microsoft/intelligent-terminal/issues/328)
  that the project team acknowledged as a priority defect.

## Contact

- Portfolio: [autom8ed.it](https://autom8ed.it)
- LinkedIn: [linkedin.com/in/joel-larsson](https://www.linkedin.com/in/joel-larsson-562a3121)
- Email: [joel.larsson@autom8ed.me](mailto:joel.larsson@autom8ed.me)
