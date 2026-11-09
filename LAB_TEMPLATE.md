# Lab Template — Cybersecurity Learning Portfolio

> **How to use this template:** Copy this file into the lab directory as `README.md` and replace every placeholder in square brackets with the actual information for the lab. Delete any section that does not apply and note why it was omitted. Never invent terminal output, test results, findings, or screenshots — record only what was actually observed. Sanitize all evidence before publishing: remove credentials, private keys, API tokens, personal information, and sensitive network details (public IP addresses, internal hostnames, MAC addresses) from commands, outputs, screenshots, and captures.

## 1. Lab Overview

| Field | Value |
| --- | --- |
| Lab Title | [Title] |
| Lab ID | [e.g., P01-LAB-01] |
| Phase | [e.g., Phase 01 — Linux, Networking & Foundations] |
| Category | [e.g., Linux Administration / Networking / Blue Team] |
| Status | [Not started / In progress / Completed] |
| Date | [YYYY-MM-DD] |
| Author | [Name] |
| Scope / Target | [Authorized target or controlled laboratory environment] |
| Authorization | [Personal lab / Explicitly authorized environment] |

> **Scope / Target** identifies the systems, networks, or applications included in the laboratory. **Authorization** establishes the context — a personal lab or an explicitly authorized environment — and encourages responsible, controlled security testing. Both fields apply across Linux, networking, OSINT, Blue Team, Red Team, and other cybersecurity exercises.

### Description

[1–3 sentences: what this lab covers and why it matters.]

## 2. Objectives

- [Objective 1 — specific, technical, and verifiable]
- [Objective 2]
- [Objective 3]

## 3. Laboratory Environment

| Component | Details |
| --- | --- |
| Host OS | [e.g., Windows 11 / macOS] |
| Hypervisor / VM Platform | [e.g., VirtualBox 7.x / VMware Workstation] |
| Guest OS | [e.g., Ubuntu 24.04 LTS] |
| Guest OS (Additional) | [e.g., Rocky Linux 9.x] |
| Network Configuration | [e.g., NAT / Host-only / Bridged; subnet, gateway] |
| Tools | [e.g., Wireshark 4.x, Nmap 7.9x] |

> Add or remove rows as needed. Record exact tool versions from `tool --version` output in the procedure, not from memory.

## 4. Technical Background

[Explain the concepts required to understand the lab: operating system concepts, protocols, security mechanisms, and technical terminology. Define terms a reader may not know. Keep this section focused on what the procedure actually uses.]

- **[Concept 1]:** [Definition and relevance to this lab.]
- **[Concept 2]:** [Definition and relevance to this lab.]

## 5. Laboratory Procedure

> Record steps chronologically. For each step, clearly distinguish five elements: **Commands Executed** (the exact commands actually executed during the laboratory), **Command Explanation** (purpose, flags, arguments, and expected behavior), **Expected Output** (expected results, when relevant and known), **Actual Observed Output** (real output obtained from the environment), and **Technical Interpretation** (what the observed output demonstrates). Never present expected output as actual evidence.

### Step 1: [Step Title]

**Purpose:** [Why this step is performed.]

**Commands Executed:**

```bash
[exact commands actually executed]
```

**Command Explanation:** [Purpose, flags, arguments, and expected behavior.]

**Expected Output:**

```text
[Insert expected output, when relevant and known]
```

**Actual Observed Output:**

```text
[Insert actual terminal output]
```

**Technical Interpretation:** [What the observed output demonstrates.]

### Step 2: [Step Title]

**Purpose:** [Why this step is performed.]

**Commands Executed:**

```bash
[exact commands actually executed]
```

**Command Explanation:** [Purpose, flags, arguments, and expected behavior.]

**Expected Output:**

```text
[Insert expected output, when relevant and known]
```

**Actual Observed Output:**

```text
[Insert actual terminal output]
```

**Technical Interpretation:** [What the observed output demonstrates.]

> Repeat the structure above for each additional step.

## 6. Commands & Technical Analysis

| Command | Purpose | Flags / Arguments | Technical Relevance |
| --- | --- | --- | --- |
| `[command]` | [What it does] | [Flags and arguments used] | [Why it matters for this lab] |
| `[command]` | [What it does] | [Flags and arguments used] | [Why it matters for this lab] |

## 7. Results & Observations

### Findings

- [Finding 1 — what was actually observed.]
- [Finding 2]

### Expected vs. Observed Behavior

| Item | Expected | Observed | Notes |
| --- | --- | --- | --- |
| [Item] | [Expected behavior] | [Actual behavior] | [Difference and cause, if known] |

### Supporting Evidence

- [Screenshot / capture file and what it shows.]

Embed screenshots directly in the Markdown so they render on GitHub. Use descriptive filenames and reference the correct relative path from the lab directory. Screenshots must come from actual laboratory work — never use placeholder or stock images as evidence.

### ICMP Traffic Analysis
The following screenshot demonstrates the ICMP packets observed during the experiment.
![ICMP Analysis](screenshots/02-icmp-analysis.png)

## 8. Security Analysis

### Security Mechanisms

[Mechanisms observed or configured in this lab, e.g., file permissions, authentication, firewall rules.]

### Vulnerabilities & Weaknesses

[Vulnerabilities or weaknesses identified, with observed evidence. Do not claim a vulnerability without evidence.]

### Attack Surfaces & Abuse Scenarios

[How an attacker could abuse the observed configuration or behavior, described in general terms.]

### Defensive Controls & Mitigations

[Controls that prevent, detect, or limit the abuse scenarios above.]

### Real-World Relevance

[How this lab maps to real environments — SOC workflows, system hardening, incident response, or defensive operations.]

## 9. Troubleshooting & Challenges

| Issue | Diagnostics | Resolution | Status |
| --- | --- | --- | --- |
| [Problem encountered] | [Commands / checks used to diagnose it] | [Fix applied, or "Unresolved"] | [Resolved / Unresolved] |

> Record unresolved problems honestly. An unresolved issue with documented diagnostics is more valuable than a claimed fix that was never verified.

## 10. Lessons Learned

- [Technical knowledge gained.]
- [Practical skills developed.]
- [What would be done differently next time.]

## 11. References

| Source | Link |
| --- | --- |
| [Official documentation title] | [URL] |
| [Technical publication / research paper] | [URL] |
| [Security advisory] | [URL] |

> Include source titles and links. Prefer official documentation and reputable technical sources. Cite only the sources actually consulted.

## 12. Conclusion

[Summary of the investigation, objectives achieved, key findings, and potential future work.]

## 13. Evidence & Supporting Files

> Sanitize all evidence before publishing: remove credentials, private keys, API tokens, personal information, and sensitive network details.

| Filename | Description | Related Step |
| --- | --- | --- |
| `screenshots/01-initial-configuration.png` | [What the screenshot shows] | [Step #] |
| `screenshots/02-observed-results.png` | [What the screenshot shows] | [Step #] |
| `captures/example-capture.pcapng` | [What the capture contains] | [Step #] |
| `artifacts/[filename]` | [What the artifact is] | [Step #] |

### Example Practice Directory Structure

```text
practice-01-example/
├── README.md
├── screenshots/
│   ├── 01-initial-configuration.png
│   └── 02-observed-results.png
├── captures/
│   └── example-capture.pcapng
└── artifacts/
```

> This is a structural example only. Create these directories only when the lab produces the corresponding evidence.

## 14. Laboratory Completion Record

| Field | Value |
| --- | --- |
| Completion Status | [Not started / In progress / Completed] |
| Completion Date | [YYYY-MM-DD] |
| Documentation Version | [e.g., v1.0 — version of this report] |
| Author | [Name] |
| Related Phase | [e.g., Phase 01 — Linux, Networking & Foundations] |
| Related Resources | [Links to related labs, notes, or projects] |

> **Documentation Version** is the version of this Markdown report (e.g., v1.0). It is not the version of the software used. **Tool Version** — the actual software version used in the lab — is documented in Section 3, Laboratory Environment. Do not confuse documentation versioning with software versioning.
