# Detection Engineering: Detecting a MITRE ATT&CK Technique

Emulating an attacker technique and building detection logic to catch it.

## Overview
I studied a defense-evasion technique from the MITRE ATT&CK framework, emulated it on a Windows virtual machine, and built detection logic to identify the behavior - practicing the full "understand the attack, then detect it" workflow that detection engineering relies on.

## What I did
- Researched the technique (disabling Windows event logging - ATT&CK T1562.002) and how attackers use it to evade defenders
- Emulated the activity on an isolated **Windows VM**
- Configured **Sysmon** and built detection logic to surface the defense-evasion behavior
- Analyzed the results and documented how the detection works and why it matters

## Tools & Technologies
MITRE ATT&CK, Sysmon, Windows, VMware

## Skills demonstrated
Threat emulation, detection engineering, Windows telemetry and event logging, MITRE ATT&CK mapping, analysis and documentation

## Note
Summary of a controlled lab exercise for learning purposes. No malware or live exploit code is included.
