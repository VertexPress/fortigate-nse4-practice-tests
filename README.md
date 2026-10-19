# FortiGate NSE 4 Practice Tests, companion repository

This repository is the companion to the book *FortiGate NSE 4 Practice Tests* (Exam Prep series, Vertex Press), five full-length timed practice exams for the Fortinet NSE 4 - FortiOS 7.6 Administrator exam, code NSE4_FGT_AD-7.6, on FortiOS 7.6.0.

It holds two things:

- `configs/`, the FortiGate CLI configuration extracts and command output that the scenario questions reference, reproduced as runnable files so that anything printed in a question runs as printed on FortiOS 7.6.
- `ERRATA.md`, the single canonical place for corrections to the book.

## The configuration files

The scenario and configuration-extract questions in Practice Exam 4 put real FortiOS 7.6 CLI in front of the reader to interpret. Each of those blocks is reproduced here, one file per question, named by exam and question number:

- `configs/exam4-q01-ha-hbdev.conf`, HA heartbeat device priority.
- `configs/exam4-q02-interface-allowaccess.conf`, interface administrative access.
- `configs/exam4-q13-policy-source-nat.conf`, firewall policy source NAT on the egress interface.
- `configs/exam4-q16-central-snat-map.conf`, a central SNAT map entry.
- `configs/exam4-q40-routing-table.txt`, a routing-table extract (command output, not configuration).
- `configs/exam4-q48-phase1-dialup.conf`, dial-up IPsec Phase 1.

Each file carries a short header explaining what the block shows and the answer it supports. Where a value must be supplied before the config is usable (a pre-shared key, for example), the file says so rather than leaving a masked token. These are teaching extracts, not a drop-in production configuration; apply them on a lab FortiGate, read the surrounding running config, and adapt object and interface names to your own device.

## Errata

No book is perfect and FortiOS 7.6 will receive updates over this edition's life. When an error is found, in a keyed answer, an explanation, a configuration extract, or anywhere else, it is corrected here in `ERRATA.md`, openly. A correction to a keyed answer is treated as the most urgent kind, because a practice test that trains a reader on a wrong answer is worse than none. If you believe you have found an error not listed, please open an issue so the next reader benefits.

## Independence and trademarks

This repository and the book it accompanies are independent. They are not affiliated with, authorized by, endorsed by, or sponsored by Fortinet, Inc. Fortinet, FortiGate, FortiOS, FortiGuard, FortiManager, FortiAnalyzer, FortiClient, Security Fabric, and FSSO are trademarks or registered trademarks of Fortinet, Inc., used here only descriptively to identify the exam and the product it covers. Every question in the book is original work written to Fortinet's published objectives, and no live exam item was reproduced.

Published by Vertex Press, Exam Prep series. Copyright 2026 Vertex Press.
