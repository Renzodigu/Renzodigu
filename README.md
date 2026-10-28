# Renzo Di Guglielmo

Cybersecurity and GRC · Buenos Aires, Argentina · Spanish (native), English (C1)

I build small, deterministic security tools: they run offline, give the same answer twice, and
produce the artefacts an auditor or analyst actually works with (findings registers, risk
registers, Statements of Applicability, structured reports). AI is an optional extra, never the core.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**Tranquera**](https://github.com/Renzodigu/tranquera) | ISO/IEC 27001:2022, NIST CSF 2.0 and Argentina's Ley 25.326 gap analysis. Policy rules are tested row by row against evidence, and accuracy is measured against expected verdicts (88 % on the demo). Outputs an executive report, a findings register and a Statement of Applicability. CLI + Streamlit app. | Python, Jinja2, Streamlit |
| [**Baqueano**](https://github.com/Renzodigu/baqueano) | Security auditor for MCP servers and AI agent tooling. Findings mapped to the OWASP MCP Top 10 and ISO 27001 Annex A; baseline reconciliation catches "rug pulls" and shows them as a diff in a self-contained HTML report; works as a CI gate. | Python, zero dependencies |
| [**Tero**](https://github.com/Renzodigu/tero) | Reverse-engineering pipeline on Ghidra (pyghidra): binary → structured report → rule-based findings. Ships two crackmes written in C, their keygens and step-by-step writeups. | Python, Ghidra, C |

All three come with tests, CI and fictitious demo data (Ñandú Pagos, Yerba Labs), so they can be
run end to end without real company information.

## Background

- Higher National Diploma in Networking and Cybersecurity (BTEC Level 5), MSMK University, Madrid — with honours
- Cisco Cybersecurity Operations Fundamentals

## Contact

[LinkedIn](https://www.linkedin.com/in/renzo-di-guglielmo-ciberseguridad-redes/)
