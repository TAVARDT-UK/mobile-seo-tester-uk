# Mobile SEO Tester and Responsive Compatibility Auditor

[![Mobile SEO Checker](https://img.shields.io/badge/TAVARDT-Mobile%20SEO-5b3cf5.svg)](https://tools.tavardt.com/uk/mobile-seo-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit of viewport meta tags, tap targets, font legibility, and mobile-friendly standards.

Engineered and maintained by the digital systems and search architecture team at **TAVARDT**.

***

## Mobile SEO Testing Capabilities

* **Viewport Configuration Audit**: Validation of standard `width=device-width, initial-scale=1` directives and detection of harmful zoom restrictions.
* **Responsive Layout Inspection**: Identification of fixed-width elements causing horizontal scrolling on handheld screens.
* **Tap Target Ergonomics**: Detection of undersized buttons and hyperlinks failing modern tactile spacing recommendations (minimum 48x48px).
* **Font Legibility Verification**: Analysis of static font declarations preventing comfortable reading without scaling.
* **Mobile-First Indexing Score**: Comprehensive 0 to 100 benchmark score with prioritised issue remediation logs.

***

## Installation and Execution

Requires Python 3.8+ utilising the Python standard library only.

```bash
git clone https://github.com/TAVARDT-UK/mobile-seo-tester-uk.git
cd mobile-seo-tester-uk
python mobile_seo_tester.py https://enterprise.co.uk
```

To output structured JSON data for automated build testing:

```bash
python mobile_seo_tester.py https://enterprise.co.uk -json
```

***

## Online Diagnostic Platform

For interactive rendering diagnostics and cross-device testing:

* **Official Mobile SEO Checker**
* **TAVARDT Portal**

***

## Professional Advisory

For enterprise guidance aligned with UK Government Digital Service and Google Mobile-First Indexing, contact **TAVARDT**.

***

## Governance and Sovereignty

* **Sovereign Unit**: [TAVARDT United Kingdom](https://ag.tavardt.com/uk/) (`TAVARDT-UK`)
* **Core Standards**: [00-core Governance](https://github.com/TAVARDT-UK/00-core)
* **Diagnostic Portal**: **TAVARDT UK Diagnostic Suite**
* **Enterprise Security**: [TAVARDT UK Cybersecurity](https://ag.tavardt.com/uk/cybersecurity/)

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
