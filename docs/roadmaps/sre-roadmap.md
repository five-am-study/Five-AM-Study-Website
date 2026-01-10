# SRE Roadmap

> This roadmap is **S** tier because it's **comprehensive, balanced, Google-specific, practical, flexible, and aligns perfectly with L3/L4 SRE goals**.

!!! note "About this roadmap"
    There's a lot of certs here. Certs are fun for me but what matters the most is the knowledge they represent and structured study path they offer.

**Start:** 4th January, 2025  
**Last update:** 10.01.2026  
Join our [discord server](https://discord.gg/JUjZJn9JmR)

---

## LeetCode Progress

**84** problems (10.01.2026)

- [ ] Silver Leetcoder: 150 problems
- [ ] Gold LeetCoder: 300 problems
- [ ] Diamond LeetCoder: 500 problems
- [ ] Master LeetCoder: 1000 problems

---

# Ground Level

## Before You Start

This section is new (as of 29.07.2025) and contains suggestions on what is good to know before you start. It's important to note that **things here might take years** to fully master so **study them to get the intuition, not the mastery of details**.

- Computer infrastructure - CSAPP book
    - chapters 2-4, 6-13

---

## Foundation

### Programming

- [ ] LeetCode 150 (NeetCode roadmap)
    - Leetcode DSA course + revisit solved questions
- [ ] Ultimate Go: Language Guide (ArdanLabs)
- [ ] Fluent Python (chapters 1-6)

### Linux & Networking

- [ ] How Linux Works by Brian Ward
- [ ] Computer Networking: Top-Down approach
    - chapters 2-5 (1 too if needed)
    - first skim, then study
- [ ] DNS
    - I'll setup CoreDNS in on my raspberry pi
- [ ] Practice tcpdump/wireshark, iptables
- (If you like certs, take CCNA)

### Git

- [ ] Implement Git (CodeCrafters)
- [ ] Learn branching strategies (like Gitflow or GitHub Flow), understand rebasing, merging, conflict resolution

### System Design

- [ ] DDIA - Part I

### Community

- [ ] 3 progress related blog posts
- [ ] 1 technical blog post

### SRE Specific

- [ ] Understanding Distributed Systems
- [ ] Site Reliability Engineering (Part I and Part II)
- [ ] Google SRE Workbook (Ch. 1-5)
- [ ] **Define SLIs/SLOs for a toy app.** (https://github.com/google/slo-generator)

---

## Certs in Foundation Phase

If you like certificates these are worthwhile at this stage.

### Kubernetes

- [x] KCNA (04.01.2025)
- [x] CKAD (25.01.2025)
- [x] KCSA (15.02.2025)

### DevOps

- [x] HashiCorp Certified: Terraform Associate (03.03.2025)
- [ ] Associate Cloud Engineer - GCP Cert (Or AWS SAA or Azure AZ-104)

---

## Alternatives in Foundation Phase

### System Design

- [Grokking the system design](https://www.designgurus.io/course/grokking-the-system-design-interview/?aff=ygh81y)
- ByteByteGo system design course (Sections 2,5,6,7,8,20,21,25)

### Programming

- C: K&R book
- Java: Effective java
- If you're curious about your specific language ask in our [discord server](https://discord.gg/JUjZJn9JmR)

**Completed:** TBA

**Rewards:**

- Ergonomic mouse - CKAD
- new PC - NeetCode 150

---

## Expansion

### Certs - Advanced Kubernetes

- [x] CKA (09.02.2025)
- [x] CKS (23.02.2025)

### Certs - DevOps

- [ ] PDE Professional Cloud DevOps Engineer - GCP

### CI/CD

- [ ] Learn github actions or gitlab ci/cd (details to come)

### Programming - Projects in Go

- [ ] **Code one real-world CLI tool**
- [ ] **Code one basic gRPC service**
- [ ] Learn Concurrent Programming with Go (James Cutajar)
- [ ] Set up Prometheus/Grafana for a toy app and track RED metrics
- [ ] Simulate 3 outages + write blameless post-mortems
- [ ] Implement (CodeCrafters) ([1 free week](https://app.codecrafters.io/r/curious-seal-755928))
    - [ ] **Redis**
    - [ ] Torrent
    - [ ] **Kafka**
    - [ ] **DNS**
    - [ ] SQLite

### Programming - Python

- [ ] Fluent Python (chapters 6-end)

### Programming - LeetCode 250 total

- Use https://algo.monster/flowchart

### Community

- [ ] 10 Blog posts
- [x] 1 Public Tech talk (2025-09-23)
- [ ] 3 documentation/bug fixes added to kubernetes project

### Books

- [ ] TCP/IP - TCP/IP Illustrated, Volume 1
    - (master Ch. 12-17 deeply)
- [ ] DDIA - Part I
- [ ] SRE Workbook (Ch. 6-end)
- [ ] Linux Observability with BPF
    - If it feels too hard start with The Linux Programming Interface (Michael Kerrisk) Chapters 1-3, 6-9, 24-26, 28
- [ ] Programming Kubernetes
- [ ] Learn concurrent programming with Go

### Linux

- [ ] QUIC, gRPC, and BGP basics
- [ ] Install gentoo in a VM
- [ ] Master Linux internals (cgroups, systemd, kernel tuning) - TODO: Add details
- [ ] Linux Performance Tuning (CPU, memory, I/O) using tools like perf, strace, ebpf. - https://www.brendangregg.com/linuxperf.html
- [ ] https://0xax.gitbooks.io/linux-insides/content/
- [ ] Project: Optimize a slow API's latency by profiling kernel syscalls.

### Kubernetes - After Certs

- [ ] read all documentation docs from [k8s docs](https://kubernetes.io/docs/home/) once
- [ ] Kubernetes The Hard Way by Kelsey Hightower
- [ ] Ultimate Go: Software Design with Kubernetes 2.0 (ArdanLabs)

**Completed:** TBA

**Rewards:**

- 65% keyboard - CKA
- Good microphone - Kubestronaut

---

## Mastery

*More incoming soon...*

### Certs - DevOps

- [ ] PCA Professional Cloud Architect - GCP

### LeetCode

- 300 total

### Programming

- [ ] Chaos Engineering - Chaos Mesh
- [ ] Kubernetes code merged to the official project
- [ ] Deploy a scalable API (Go) on GCP with Terraform, monitoring, and CI/CD.
- [ ] Ultimate Go: Advanced Engineering 2.0 (ArdanLabs)
- [ ] Ultimate Debugging (ArdanLabs)

### Books

- [ ] Software Engineering at Google
- [ ] SRE book - reread
- [ ] Systems Performance: Enterprise and the Cloud
- [ ] BPF Performance Tools
- [ ] Building Secure and Reliable Systems
- [ ] DDIA
    - [ ] Part II
    - [ ] Part III

### Interview Preparation

- [ ] Mock Interviews - 5 total
- [ ] LeetCode contests - 4 total

**Completed:** TBA

**Rewards:**

- Trip to japan - Mastery phase done

---

## Interview Ready

*More incoming soon...*

- [ ] Interview Preparation - 50h
- [ ] Mock Interviews - 30 total
- [ ] LeetCode contests - 15 total
- [ ] SRE Case Studies - Re-engineer systems
- [ ] Prepare portfolio
- [ ] Prepare a website

**Completed:** TBA

**Rewards:**

> Time to achieve the dream.

---

## Things That Need VERY Deep Understanding

1. Networking
2. Kernel internals
3. Distributed systems

---

## Extra Tips

- Aim to solve issues without rebooting
- Be fast in terminal (bash and vim)
- Don't underestimate the need to deeply understand things.
- C is a long term investment with insane ROI.

---

## To Add?

1. **NALSD Integration**: Google-specific design practice. https://sre.google/resources/
2. Cloud projects
3. Remember about diminishing returns, maybe 10% of something will net 80% of results? Just be cautious of that and update things accordingly
4. Mock communication exercises
    1. outage email to stakeholders
5. Threat modeling project
6. Kernel source code reading
    1. Learn C programming to understand kernel source code (through CTFs?)
        1. K&R book
        2. Codewars, exercism
        3. Hacking: The Art of Exploitation, 2nd Edition
        4. OverTheWire: Bandit
        5. HackTheBox
        6. VulnHub
        7. picoCTF, CTFtime
    2. Read only essential parts of Linux Source Code
        1. syscalls
        2. linux/kernel.h
        3. simple driver
        4. Documentation/ in linux kernel source code
        5. net/
        6. fs/
        7. mm/
        8. kernel/sched/, kernel/signal.c
7. The Linux Programming Interface
    1. Selective chapters – Process management, threading, and networking.
8. CI/CD
    1. Add automated canary deployments using Argo Rollouts.
9. Basic understanding of UX
    1. Google is user first
