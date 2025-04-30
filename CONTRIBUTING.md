
---

# 🤝 Contributing to ASIOS™

Thank you for your interest in improving **ASIOS™**! We welcome bug fixes, new features, documentation updates, tests, and more. Before you start, please read this guide and the linked policies below to ensure your contributions align with our commitment to ethical AI development and safety.

---

## 1. Legal Prerequisites

All code under “Must Be Developed” (per the [ARCHITECTURE](https://github.com/asi-os/asios-docs/blob/main/ARCHITECTURE.md)) is licensed AGPL-3.0-or-later. To contribute, you must:

1. **Sign the CLA**  
   - **Individual contributors:** sign the [ICLA](https://github.com/asi-os/asios-legal/blob/main/ICLA.md) via the CLA Assistant bot (prompts automatically on your first PR).  
   - **Company contributors:** ensure your organization has signed the [CCLA](https://github.com/asi-os/asios-legal/blob/main/CCLA.md) first.
   - **Exemption for Small Changes:** If your pull request only modifies **fewer than 20 lines**, the CLA is **not required**. These minor changes may include fixes for typos, formatting adjustments, or small updates.

2. **DCO Sign-off**  
   Every commit needs a `Signed-off-by:` line.  
   ```bash
   git commit -s -m "Brief description of change"
   ```
See [CLA & DCO Help »](https://github.com/asi-os/asios-legal/blob/main/CLA-HELP.md) for details.

---

## 2. How to Submit Changes

1. **Fork** the repo and **clone** locally:  
   ```bash
   git clone https://github.com/asi-os/<repo>.git
   cd <repo>
   ```
2. **Create a branch** for your work:  
   ```bash
   git checkout -b feature/short-description
   ```
3. **Implement & test** your change. Ensure all CI checks pass, and verify that your changes comply with our ethical AI guidelines and safety requirements.
4. **Push** your branch and **open a Pull Request** against `main`.  
   - Use the [Pull Request template](https://github.com/asi-os/.github/blob/main/PULL_REQUEST_TEMPLATE.md).  
   - Link any related issues (e.g. “Closes #123”).  
   - **Explain the “why” and “what” of your changes** and how they contribute to ethical AI development, ensuring compliance with safety and ethical standards.

---

## 3. Code Style & Testing

- **Formatting:** follow `.editorconfig`; run `clang-format` or `black` where applicable.  
- **Unit tests:** aim for ≥ 80 % coverage.  
- **CI:** All tests (unit, integration, performance) must pass on both x86_64 and ARM64.  
- **Documentation:** Update relevant files in the [asios-docs](https://github.com/asi-os/asios-docs) repo if your change affects behavior or APIs, particularly when it impacts AI-related components or safety mechanisms.

---

## 4. Communication & Review

- We use GitHub **Issues** for bug reports and **Discussions** for broader design proposals.  
- For large features, consider opening an **RFC** in `asios-docs/rfcs/` first.  
- **Be responsive to review feedback**—collaboration makes us stronger!  
- **Ethical AI Compliance:** When proposing changes related to AI workloads, ensure your contributions meet ASIOS™'s ethical AI principles and AI safety guidelines. Review the [AI Safety Governance Framework](https://github.com/asi-os/asios-docs/blob/main/AI_SAFETY_GOVERNANCE_FRAMEWORK.md) for more details.

---

## 5. Need Help?

- **CLA/DCO questions:** see [CLA-HELP.md](https://github.com/asi-os/asios-legal/blob/main/CLA-HELP.md)  
- **Security issues:** see [SECURITY.md](https://github.com/asi-os/.github/blob/main/SECURITY.md)  
- **Ethical AI questions:** If you're unsure about AI safety or ethical guidelines, refer to the [AI Safety Governance Framework](https://github.com/asi-os/asios-docs/blob/main/AI_SAFETY_GOVERNANCE_FRAMEWORK.md).  
- **General support:** see [SUPPORT.md](https://github.com/asi-os/.github/blob/main/SUPPORT.md) or join us on Discord: https://discord.gg/rWuU7cWU4E  

---

> **Thank you for contributing!** Together, we’re building the ethical infrastructure for tomorrow’s AI. 🚀  
> © 2025 KarLex AI, Inc. — see [Legal & Governance Portal](https://asios.ai/legal)

---
