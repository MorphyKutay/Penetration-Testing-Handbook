# Offensive Security & Penetration Testing Handbook

Comprehensive vulnerability hunting and pentest guide for web application and software security testing. Each document covers mechanisms, detection techniques, bypass methods, and remediation recommendations specific to its vulnerability type.

## 📋 Contents

| Document | Description |
|----------|-------------|
| [ai.md](ai.md) | AI/LLM penetration testing — Prompt injection, jailbreak, RAG, plugin security |
| [fast-checking.md](fast-checking.md) | Fast testing checklist — Recon, auth, injection, access control |
| [fuzzing.md](fuzzing.md) | Fuzzing methodology — BlackBox, GreyBox, Snapshot, tools |
| [graphql.md](graphql.md) | GraphQL vulnerabilities — Introspection, IDOR, injection, DoS |
| [idor.md](idor.md) | Insecure Direct Object Reference — Unauthorized resource access |
| [insecure-deserialization.md](insecure-deserialization.md) | Insecure deserialization — RCE, object injection |
| [jwt.md](jwt.md) | JWT security — Algorithm confusion, header injection, brute-force |
| [oauth.md](oauth.md) | OAuth/OIDC vulnerabilities — Redirect, token, PKCE |
| [open-redirect.md](open-redirect.md) | Open redirect vulnerabilities — Phishing, SSRF triggering |
| [osint.md](osint.md) | OSINT tools — Email, social media, blockchain, infrastructure |
| [osint-method.md](osint-method.md) | OSINT methodology — Research techniques |
| [parameter-pollution.md](parameter-pollution.md) | HTTP parameter pollution — HPP, bypass |
| [race-condition.md](race-condition.md) | Race condition — TOCTOU, limit bypass |
| [req-smuggle.md](req-smuggle.md) | HTTP request smuggling — CL.TE, TE.CL, bypass |
| [sql-injection.md](sql-injection.md) | SQL injection — Union, blind, NoSQL, ORM |
| [ssrf.md](ssrf.md) | Server-Side Request Forgery — Cloud metadata, internal access |
| [ssti.md](ssti.md) | Server-Side Template Injection — SSTI exploitation |
| [waf-bypass.md](waf-bypass.md) | WAF bypass techniques — Encoding, obfuscation |
| [xss.md](xss.md) | Cross-Site Scripting — Stored, reflected, DOM, CSP bypass |
| [xxe.md](xxe.md) | XML External Entity — XXE exploitation, OOB |

## 🎯 Usage

- **Pentest projects**: Reference the relevant document for the target vulnerability type
- **Bug bounty**: Use the fast checklist and shortcut sections
- **Security training**: Study the mechanisms and bypass techniques
- **CTF / lab practice**: Leverage payload and tool recommendations

## 📁 Document Structure

Each vulnerability document typically includes:

- **Shortcut** — Quick detection steps
- **Mechanisms** — How the vulnerability occurs
- **Hunt** — Detection and discovery techniques
- **Bypass Techniques** — Protection bypass methods
- **Vulnerabilities** — Common vulnerability patterns
- **Methodologies** — Tools and testing processes
- **Remediation Recommendations** — Fix recommendations

## ⚠️ Disclaimer

These materials are intended for **educational and authorized security testing** purposes only. Unauthorized access to systems is illegal. Use only on systems you own or have written permission to test.

## 📜 License

This project is for educational purposes. Consult the project owner for terms of use.

---

*Last updated: 2025*
