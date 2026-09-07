# Phishing Email Analysis

## Overview
An investigation into a suspicious/phishing email, demonstrating email header analysis, indicator of compromise (IOC) extraction, and incident write-up practices used in a SOC.

## Methodology
1. **Header Analysis** — reviewed sender address, Return-Path, SPF/DKIM/DMARC results, and Received headers to trace the email's origin
2. **Content Analysis** — examined links, attachments, and social engineering tactics used in the email body
3. **IOC Extraction** — pulled out suspicious URLs, IP addresses, and file hashes
4. **Verdict** — determined whether the email was malicious, and classified the type of attack (e.g. credential phishing, malware delivery)

## Indicators of Compromise (IOCs)
*(List the URLs, IPs, or hashes you found here)*

## Sample Incident Write-up
*(Write this as if you were logging it as a SOC ticket — what happened, what you found, what action you'd recommend, e.g. "block sender domain", "notify affected users")*

## Skills Demonstrated
- Email header and metadata analysis
- IOC identification
- Incident documentation
