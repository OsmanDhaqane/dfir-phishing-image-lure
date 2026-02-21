# Real-World Phishing Email Investigation (DFIR)
Real-world phishing investigation — image-only email lure abusing Microsoft SafeLinks and punycode domains.

## Overview
This repository contains a real phishing email investigation.  
The message used an image-only lure with a hidden hyperlink and Microsoft SafeLinks redirection to a punycode domain that led to an email harvesting page.

The goal of the analysis was to determine legitimacy, trace the redirect chain, identify attacker infrastructure, and extract indicators of compromise.

## Analysis Scope

- Raw .eml
- Headers
- HTML structure
- Redirect chain
- Landing page behaviour
- Infrastructure


## Key findings
- Image-only phishing email (no readable body text)
- Hidden hyperlink behind banner button
- SafeLinks redirect used to mask destination
- Punycode domain (IDN homograph technique)
- Multi-stage redirect to harvesting page
- Disposable phishing infrastructure
- No evidence of user compromise


## Analyst skills
- Email forensics
- Header analysis
- SafeLinks investigation
- URL redirection tracing
- Phishing infrastructure analysis
- IOC extraction

## Report
- [Link the PDF](https://github.com/OsmanDhaqane/dfir-phishing-image-lure/blob/main/report/phishingcase1.pdf)


