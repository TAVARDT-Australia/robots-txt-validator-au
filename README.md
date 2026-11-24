# Robots.txt Validator

[![Robots.txt Validator](https://img.shields.io/badge/TAVARDT-Robots.txt-5b3cf5.svg)](https://tools.tavardt.com/au/robots-txt-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Australian web crawl governance tool inspecting robots.txt directives, preventing crawl budget exhaustion, and securing private routes.

Engineered and maintained by the web indexing and digital standards division at **TAVARDT**.

***

## Robots.txt Audit Capabilities

* **De-indexation Trap Defense**: Identifies hostile or accidental disallow commands targeting Australian web assets.
* **Crawler and AI Governance**: Configures access permissions for commercial search engines and generative bots.
* **Sitemap Pointer Verification**: Audits XML sitemap declarations for seamless indexer discovery.
* **Directive Hygiene**: Evaluates allow and disallow pattern accuracy and crawler delay limits.
* **Crawlability Benchmark Score**: 0 to 100 score detailing prioritized optimizations for search webmasters.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external packages.

```bash
git clone https://github.com/TAVARDT-Australia/robots-txt-validator-au.git
cd robots-txt-validator-au
python robots_validator.py https://example.com.au
```

To run in automated pipelines with JSON output:

```bash
python robots_validator.py https://example.com.au -json
```

***

## Online Validation Platform

To assess robots.txt files and verify crawler permissions across Australian properties:

* **Official Robots.txt Validator**
* **TAVARDT Portal**

***

## Australian Digital Infrastructure Advisory

For complex search crawler architecture and technical alignment with Australian Web Standards and Robots Exclusion Protocol, consult **TAVARDT**.

***

© 2026 TAVARDT. All rights reserved.
