# Security Homelab

A documented collection of hands-on cybersecurity labs conducted in an isolated virtual environment. This repo covers offensive techniques, vulnerability exploitation, credential analysis, and detection — built as a practical learning resource and portfolio artifact.

---

## Lab Environment

| Component | Details |
|---|---|
| Host Machine | Intel i5-12400F, 16GB DDR4, Windows 11 |
| Hypervisor | VMware Workstation Pro 26H1 |
| Network | VMware VMnet1 — Host-only, isolated (192.168.226.0/24) |
| Attacker VM | Kali Linux 2026.2 — 192.168.226.128 |
| Target VM | Metasploitable2 (Ubuntu 8.04) — 192.168.226.129 |

All labs are conducted on an isolated host-only virtual network with no internet access. No external systems are targeted.

---

## Labs

| # | Title | Techniques | CVE |
|---|---|---|---|
| 01 | [VSFTPd 2.3.4 Backdoor](labs/01-vsftpd-backdoor.md) | Exploitation, Post-Exploitation, Credential Cracking | CVE-2011-2523 |

*More labs in progress.*

---

## Tools Used

- **nmap** — Network reconnaissance and service version detection
- **Metasploit Framework** — Exploitation and post-exploitation
- **John the Ripper** — Offline password hash cracking
- **Wireshark** — Network traffic analysis *(planned)*
- **Wazuh** — SIEM and log analysis *(planned)*

---

## Structure

```
security-homelab/
├── README.md
├── labs/
│   ├── 01-vsftpd-backdoor.md
│   └── ...
├── screenshots/
│   └── ...
└── notes/
    └── metasploitable2-services.md
```

---

## Goals

- Build practical offensive and defensive security skills
- Document methodology in a format readable by both technical and non-technical audiences
- Develop a verifiable portfolio of hands-on security work
- Practice the full attack chain: reconnaissance → exploitation → post-exploitation → detection

---

## Disclaimer

All activity in this repo is conducted against intentionally vulnerable virtual machines in a fully isolated lab environment. No real systems, networks, or third-party infrastructure are targeted. This work is for educational purposes only.

---

## License

MIT License — see [LICENSE](LICENSE) for details.
