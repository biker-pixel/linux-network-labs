# linux-network-labs
Hands-on labs for Linux, networking, systems, and security fundamentals. 
Structured learning roadmap with daily logs and practical engineering tasks.
This repository is part of a 6-month intensive training plan aimed at
landing a Junior Security / Systems / Cloud Engineer position.

---

## Goals

- Build strong Linux fundamentals
- Practice service hardening and sandboxing
- Understand networking, firewalling, and packet flow
- Create documented security mini-projects for portfolio

---

## Lab Environment

Two virtual machines are used throughout the labs
(this setup will evolve during training):
| VM Name      | OS                     | Purpose                    |
|--------------|------------------------|----------------------------|
| ubuntu-lab   | Ubuntu 24.04 LTS       | systemd, journald, hardening |
| fedora-lab   | Fedora Workstation     | systemd, sandboxing tests  |

---

## Repository Structure

```
.
├── .gitignore
├── LICENSE
├── README.md
├── learning-log.md
├── docs/
│   └── screenshots/
├── systemd/
│   ├── custom-services/
│   └── hardening/
├── journald/
├── networking/
└── scripts/
```
*(structure will evolve during training)*

---

## Learning Log

Daily progress, commands, observations, and conclusions are documented in
[`learning-log.md`](learning-log.md).

Each entry contains:
- date
- tasks performed
- commands used
- output / results
- personal notes

---

## Status

Week 1 — Linux fundamentals, systemd core, journald, sandboxing  
(actively developing)
