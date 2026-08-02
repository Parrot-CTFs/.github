<div align="center">
  <img src="https://s3.parrot-ctfs.com/6971e9351b9956.42192844.png" width="150px" alt="Lorikeet Security" />
  <br /><br />
  <strong>Lorikeet Security</strong><br />
  <sub>Human first. AI-native. One platform for your whole security program.</sub>
  <br /><br />
  <a href="https://lorikeetsecurity.com">Website</a> &nbsp;·&nbsp;
  <a href="https://lorikeetsecurity.com/lory">Lory</a> &nbsp;·&nbsp;
  <a href="https://lorikeetsecurity.com/developers">Docs</a> &nbsp;·&nbsp;
  <a href="https://lorikeetsecurity.com/blog">Research</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/company/lorikeetsecurity">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://x.com/lorikeetsec">X</a>
</div>

---

We run human-led penetration tests and an autonomous AI pentester against the same scope, and every finding either agent produces is countersigned by a human before it reaches a client. This org is where the open-source half of that lives: the agent you install, the CLI your developers use, the labs we train on, and the tooling we build for our own engagements.

**We test the way attackers think. Then we help you fix it.**

---

### Where Lory Meets Your Code

Three surfaces, one AI pentester. Install the agent so she can reach your internal network, review findings from your terminal, or catch vulnerabilities in the editor before they ever become findings.

| Project | What it does | |
|---|---|---|
| **[lorikeet-security-agent-exporter](https://github.com/Lorikeet-Security/lorikeet-security-agent-exporter)** | The in-network agent. Host discovery, patch and vulnerability state, server and application inventory — surfaced as structured findings so Lory can test internal assets from behind your perimeter. A Python agent you install, not an appliance. | `Python` `MIT` |
| **[lory-code-security](https://github.com/Lorikeet-Security/lory-code-security)** | Findings triage in your terminal. Pull your Lorikeet findings, trace them to the offending code, ask Lory for the fix, request a retest — without leaving the shell. | `Python` `MIT` |
| **[vs-code](https://github.com/Lorikeet-Security/vs-code)** | Lory reviews your code for vulnerabilities as you write it, inside VS Code. The left shift: catch it at the keystroke, not at the pentest. | `TypeScript` |

### Learn

| Project | What it does | |
|---|---|---|
| **[owasp-top-10-labs-lamp-dockerized](https://github.com/Lorikeet-Security/owasp-top-10-labs-lamp-dockerized)** | Dockerized OWASP Top 10 lab machines. Deliberately vulnerable, deliberately reproducible — what we train our own testers on. | `PHP` |

[**Browse all repositories →**](https://github.com/orgs/Lorikeet-Security/repositories)

---

### Install the Agent

```bash
pip install lorikeet-security-agent-exporter
```

Point it at a host inside your network and Lory can reach internal assets your external scans never see. [Agent docs](https://lorikeetsecurity.com/lory#agent) · [MCP server](https://lorikeetsecurity.com/mcp-docs) · [API reference](https://lorikeetsecurity.com/developers)

---

### Security Research

**16 CVEs in FastNetMon Community Edition**, responsibly disclosed by our research team and indexed by NVD, Snyk, SentinelOne, Ubuntu, and Vulners.

Two rated 9.8 Critical — a stack buffer overflow in BGP NLRI parsing ([CVE-2026-48686](https://lorikeetsecurity.com/blog/fastnetmon-cve-2026-48686-bgp-nlri-stack-overflow)) and an off-by-one heap overflow in dynamic buffer handling ([CVE-2026-48689](https://lorikeetsecurity.com/blog/fastnetmon-cve-2026-48689-dynamic-buffer-off-by-one)) — alongside command injection in the Juniper and MikroTik plugins, an unauthenticated gRPC control API, and missing TLS certificate validation.

[**Read the full disclosure series →**](https://lorikeetsecurity.com/blog)

---

### Working With Us

Penetration testing and red team · Autonomous testing with [Lory](https://lorikeetsecurity.com/lory) · Incident response and digital forensics · MDR and SOC-as-a-Service · SOC 2, ISO 27001, PCI DSS, HIPAA, CMMC · vCISO and VC due diligence

Everything runs through [**Talon**](https://lorikeetsecurity.com/ptaas) — findings stream in as we test, with evidence, remediation, and free retesting. Every run publishes what it covered *and* what it didn't.

[See an example report](https://lorikeetsecurity.com/example-report/Lorikeet_Demo_Report.pdf) · [Our methodology](https://lorikeetsecurity.com/methodology) · [Book a scoping call](https://lorikeetsecurity.com/contact#booking)

---

### Contributing & Disclosure

Issues and pull requests are welcome on any repo here. If you'd like to fund the open-source work, we have [GitHub Sponsors](https://github.com/sponsors/Lorikeet-Security) enabled.

Found a vulnerability in something we ship? Report it to **security@lorikeetsecurity.com** — we respond within one business day and we credit researchers. See our [Trust Center](https://lorikeetsecurity.com/trust-center) for scope and policy.

---

<div align="center">
  <sub>
    <a href="mailto:sales@lorikeetsecurity.com">sales@lorikeetsecurity.com</a> &nbsp;·&nbsp;
    <a href="mailto:support@lorikeetsecurity.com">support@lorikeetsecurity.com</a> &nbsp;·&nbsp;
    <a href="https://lorikeetsecurity.com/careers">We're hiring</a>
    <br /><br />
    © 2021–2026 Lorikeet Security
  </sub>
</div>
