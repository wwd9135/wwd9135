### Will Richardson

Security engineer on an industrial placement at the Met Office, currently in the detection and SecOps team, and in the final year of a Networks and Cyber Security BSc at Northumbria (graduating 2027).

Most of my work is detection engineering and endpoint security across an estate of around 4,500 devices: writing and tuning detections, investigating alerts across the Microsoft security stack, and building tooling to take some of the manual work out of analysis. My grounding is defensive, but I spend a fair amount of time on offensive work too, mostly because it is hard to write a decent detection for an attack you have never had to carry out yourself. SC cleared.

#### Projects

**[WFTAF-v2](https://github.com/wwd9135/WFTAF):** Windows Forensic Triage and Analysis Framework. A detection-as-code pipeline that collects Windows persistence artefacts with PowerShell, normalises them to the OSSEM schema in Python, and runs Sigma rules over the output. I built it so it does not need a SIEM behind it to be useful.

**[Detection-Engineering](https://github.com/wwd9135/Detection-Engineering):** Sigma and KQL detections grouped by ATT&CK tactic. Each one is authored in Sigma, compiled to KQL for Sentinel, and validated in a home lab before it goes in. Each ships with the rule, the compiled query, test notes, and any tuning that went into reducing false positives.

**[Security-Portfolio](https://github.com/wwd9135/Security-Portfolio):** The smaller stuff. A Windows Event Log parser, a set of Python utilities, SC-200 attack-simulation write-ups run against a live Azure tenant, and Unveil, a steganography tool built on an encryption routine I wrote myself.

#### Currently

Working towards AZ-500, and spending most of my learning time on Azure-native detection and attack-surface analysis. A fair amount of what is here is still in progress, so it sits somewhere between a finished portfolio and a set of working notes.

Python · PowerShell · KQL · Sigma · Sentinel · Defender · Azure · MITRE ATT&CK

Newcastle / Exeter · [LinkedIn](https://www.linkedin.com/in/william-richardson-379ab328b/) · willrichardson20025@gmail.com
