

# 🛡️ Security Policy

## 🔒 Supported Versions

We actively maintain security support and patch releases for the following **ASIOS™** channels:

| Channel             | Supported Releases  |
|---------------------|---------------------|
| **Stable**          | v1.0.x, v1.1.x      |
| **Enterprise LTS**  | v1.0 LTS            |

> *Edge* and *Beta* channels receive updates on a **best-effort** basis but are **not covered by our SLA**.

---

## 📣 Reporting a Vulnerability

If you discover a security vulnerability in **ASIOS™**, please:

1. **Email the Security Team**  
   Include proof-of-concept, exploit steps, affected versions, and any relevant logs or patches.  
   Send to `security@karlex.ai`.

2. **Acknowledgment & Timeline**  
   - Acknowledge receipt within **48 hours**  
   - Provide initial assessment within **5 business days**  
   - Public disclosure after patches are available

3. **Coordinated Disclosure**  
   Work with us to agree on a safe disclosure schedule. Advisories will appear at  
   <https://asios.ai/security/advisories>.

---

## 🎯 Severity Classification

| Severity     | Description                                                          |
|--------------|----------------------------------------------------------------------|
| **Critical** | Remote code execution, privilege escalation, kernel panic            |
| **High**     | API bypass, sensitive data leakage, major denial-of-service          |
| **Medium**   | Local privilege bypass, minor information disclosure, limited DoS    |
| **Low**      | Non-critical (e.g., missing headers, documentation typos)            |

---

## 🛠️ Release Process

1. Patch in private [asi-os/security-patches](https://github.com/asi-os/security-patches) repo  
2. Review & QA on x86_64 and ARM64  
3. Publish advisory with release notes  
4. Backport to Stable & Enterprise LTS

---

## ✅ Responsible Disclosure

We credit researchers (unless anonymous) and encourage early collaboration to minimize risk.

---

> Maintained in [`.github/SECURITY.md`](https://github.com/asi-os/.github/blob/main/SECURITY.md) and applies across all **asi-os/** repos.

© 2025 KarLex AI, Inc. — see [Legal & Governance Portal](https://asios.ai/legal)
