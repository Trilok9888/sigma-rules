# REVSOC Sigma Rules Repository

## Overview

This repository contains **7,700+ Sigma detection rules** that have been fully standardized into a consistent Standardised format for real-world Security Operations Center (SOC) usage.
s
The goal of this project is to transform raw and inconsistent Sigma rules into a **production-ready detection library** that can be directly used in SIEM platforms.

---

## Key Highlights

* 7700+ Sigma rules
* Fully standardized structure 
* Clean folder hierarchy (no nested rule.yml issues)
* Consistent metadata across all rules
* Author unified as **REVSOC**
* Enriched with contextual notes and detection clarity

---

## What Was Done

The original dataset was processed and improved with the following enhancements:

* Standardized Sigma field ordering
* Cleaned and deduplicated rules
* Fixed inconsistent formatting
* Added missing `logsource` definitions
* Filled missing references, tags, and false positives
* Removed redundant and broken structures

---

## Folder Structure

```
/<product_or_category>/<service_or_category>/<rule>.yml
```

Examples:

```
/windows/security/...
/aws/cloudtrail/...
/okta/...
/zeek_network_monitor/...
```

---

## Standard Enhancements

Each rule includes structured and consistent sections:

* Notes
* API parameters
* CLI examples
* SIEM usage examples
* Remediation guidance
* Security context

---

## Supported Platforms

These rules cover multiple environments:

* AWS (CloudTrail, CloudWatch)
* Windows Event Logs
* Linux Audit Logs
* Azure / Entra ID
* SaaS platforms (Okta, O365, etc.)
* Network telemetry (Zeek, firewalls, proxies)

---

## Use Cases

* SOC Detection Engineering
* Threat Hunting
* SIEM Content Development
* Detection Rule Benchmarking
* Security Research

---

## Why This Repository Matters

Most public Sigma repositories are:

* Inconsistent
* Noisy
* Hard to operationalize

This project focuses on:

* Practical usability
* Standardization
* Scalability for real SOC environments

---

## Author

All rules standardized and maintained by:

**REVSOC**

---

## Disclaimer

These rules are derived from publicly available Sigma content and have been standardized for consistency, usability, and operational efficiency.
