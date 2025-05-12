# 🛡️ AARF – Agentic AI Request Forgery (New Vulnerability Class)

**AARF (Agentic AI Request Forgery)** is a newly discovered architectural vulnerability class in **Agentic AI orchestration systems** using **MCP Server**, **MAS**, **LangChain**, and **A2A Protocols**.

> 💥 This is not injection.  
> 💥 This is not jailbreak.  
> 💥 This is **blind trust between Planner ➝ Memory ➝ Plugin chains.**  

## 🔥 Why AARF Matters

AARF lets attackers submit **benign prompts** that trigger **privileged internal actions**:
- Exfiltrate data via fallback plugin (e.g., SlackBot, EmailSender)
- Trigger unintended actions (like infrastructure shutdown or security escalations)
- Poison cross-agent memory in MAS setups
- All with **no alerts, no SIEM hits, no policy violations**

## 📄 Publication

Read the **full DEFCON-grade whitepaper (PDF):**
[➡ AARF_Agentic_AI_Request_Forgery.pdf](./AARF_Agentic_AI_Request_Forgery.pdf)

## 🎯 Key Contents:
- ✔️ Executive Summary for CISOs, AppSec, and Red Teams
- ✔️ Real-world exploitation flows (PT-confirmed on MCP & MAS)
- ✔️ Bypassed controls and defense gaps
- ✔️ Mitigation and detection strategies
- ✔️ OWASP Top 10 proposal candidate
- ✔️ Red Team simulation steps

## 💥 Threat Model Diagrams
See `/diagrams/` for validated **PlantUML** and **exploitation flows**.

## 🔐 Red Team Simulation Scenarios
See `/red-team-simulation/` for step-by-step **PT playbooks, detection gaps, and log evasion patterns.**

## 📢 OWASP Top 10 Proposal Draft
See `/OWASP_PR/` for **submission-ready OWASP Agentic AI Top 10 item proposal** for **AARF.**

## 📚 References
- IDOR (2010)
- SSRF (2012)
- ➡ AARF (2025)

## 🚨 Important Note
This repo is for **research, awareness, and responsible disclosure advocacy**.
Always get permission before running these tests in live environments.

## License
MIT License

## 🔗 Connect with the Author
**Efi Jeremiah – Red Team Leader & Agentic AI Security Researcher**

- [LinkedIn](https://www.linkedin.com/in/efi-jeremiah)
- [Website](https://nextsecurity.co)
