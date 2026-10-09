# Investigation Methodology

PhishTrace follows a structured SOC Level 1 phishing investigation workflow.

## Investigation Steps

1. Identify and record the suspicious email.
2. Preserve relevant email evidence.
3. Examine sender details and email headers.
4. Review SPF, DKIM, and DMARC results when available.
5. Inspect the test URL and domain safely.
6. Check available Windows, Sysmon, and Wazuh telemetry.
7. Build an evidence-based timeline.
8. Assess detection coverage and limitations.
9. Document findings and defensive recommendations.

## Evidence Handling

Record the source and timestamp of each observation. Keep private originals separate from sanitized evidence intended for public sharing.

## Reporting Principle

Conclusions must be supported by observed evidence. Missing telemetry or alerts must be documented honestly.
