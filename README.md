# Operation Ensnaris

Operation Ensnaris is a personal cybersecurity project where I’m building a deception environment using honeypots alongside a controlled adversary simulator.

The goal is to create a closed testing loop — simulate attacker behaviour, see what gets detected, then improve the defensive setup. I’m using this project to better understand how real-world detection systems behave, where alert fatigue comes from, and how deception technologies can be used more effectively.

---

## 🟣 Project Purpose (Purple Team)

Security teams deal with huge volumes of alerts, and it’s not always clear which detections are actually useful. I wanted a way to test defensive systems in a controlled environment instead of relying on random internet traffic.

This project is essentially a small purple-team lab where attacker simulation and defensive monitoring feed into each other.

---

## 🔴 Adversary Simulation (Red Team)

This component focuses on generating controlled attacker-like behaviour within an authorised lab environment.

Examples of behaviours I plan to simulate:

- Reconnaissance and scanning  
- Service probing and enumeration  
- Credential attempts against honeypots  
- Suspicious activity patterns designed to trigger detections  

The aim isn’t to “break in”, but to produce realistic signals that defensive systems should detect.

---

## 🔵 Detection & Monitoring (Blue Team)

The defensive side focuses on honeypots, logging, and alert analysis to understand:

- Which behaviours trigger alerts  
- Which alerts are useful vs noise  
- Where detection gaps exist  
- How alert fatigue can be reduced  

This is where the effectiveness of the system is actually measured.

---

## 🟣 Roadmap (Purple Team Coordination)

Planned development phases for Operation Ensnaris:

### Phase 1 — Foundation
- Deploy initial honeypot environment  
- Establish logging and monitoring pipeline  
- Validate data collection  

### Phase 2 — Adversary Simulation
- Implement controlled scanning and probing scenarios  
- Simulate attacker reconnaissance behaviours  
- Map simulated activity to MITRE ATT&CK techniques  

### Phase 3 — Detection Evaluation
- Analyse alert accuracy and usefulness  
- Identify detection gaps and false positives  
- Measure alert volume and noise  

### Phase 4 — Feedback & Improvement
- Refine honeypot configurations  
- Improve detection coverage  
- Enhance reporting and analysis capabilities  

### Future Direction
- Develop automated testing scenarios  
- Introduce AI-assisted analysis  
- Expand deception techniques  

---

## ⚠️ Ethical Use

This project is intended for authorised lab environments only and is not designed for use against systems without permission.

---

*Developed as an ongoing cybersecurity learning and portfolio project.*
