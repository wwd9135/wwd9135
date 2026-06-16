# Will Richardson

Security engineer on an industrial placement at the Met Office, currently in the detection and SecOps team. Final year of a Networks and Cyber Security BSc at Northumbria, graduating 2027. SC cleared.

Most of my work is detection engineering and endpoint security across an estate of around 4,500 devices: writing and tuning detections, investigating alerts across the Microsoft security stack, and building tooling to take some of the manual work out of analysis.

> Defensive by training, but I spend a fair amount of time on the offensive side too. It is hard to write a good detection for an attack you have never had to carry out yourself.

## Projects

- **[WFTAF-v2](https://github.com/wwd9135/WFTAF-v2):** Windows Forensic Triage and Analysis Framework. A detection-as-code pipeline that collects Windows persistence artefacts with PowerShell, normalises them to the OSSEM schema in Python, and runs Sigma rules over the output. Built so it does not need a SIEM behind it to be useful.
- **[Detection-Engineering](https://github.com/wwd9135/Detection-Engineering):** Sigma and KQL detections grouped by ATT&CK tactic. Authored in Sigma, compiled to KQL for Sentinel, and validated in a home lab before it goes in. Each ships with the rule, the compiled query, test notes, and any tuning that went into reducing false positives.
- **[Security-Portfolio](https://github.com/wwd9135/Security-Portfolio):** The smaller stuff. A Windows Event Log parser, a set of Python utilities, SC-200 attack-simulation write-ups run against a live Azure tenant, and Unveil, a steganography tool built on an encryption routine I wrote myself.

## Stack

`Python` `PowerShell` `KQL` `Sigma` `Microsoft Sentinel` `Defender` `Azure` `MITRE ATT&CK`

## Currently

- Working towards AZ-500, focused on Azure-native detection and attack-surface analysis.
- A fair amount of what is here is still in progress, so it sits somewhere between a finished portfolio and a set of working notes.

## Elsewhere

Newcastle / Exeter · [LinkedIn](https://www.linkedin.com/in/william-richardson-379ab328b/) · willrichardson20025@gmail.com
