# Detection Coverage

## Purpose

This document explains which parts of the phishing investigation can be observed using the available evidence and security tools.

## Detection Coverage Matrix

| Investigation activity       | Evidence source                   | Expected observation                                           | Status  |
| ---------------------------- | --------------------------------- | -------------------------------------------------------------- | ------- |
| Review suspicious email      | Gmail message and email headers   | Sender details, subject, timestamps and authentication results | Pending |
| Inspect email authentication | Email headers                     | SPF, DKIM and DMARC results, when available                    | Pending |
| Examine suspicious URL       | URL and domain analysis           | URL structure, domain details and reputation findings          | Pending |
| Review endpoint activity     | Windows 10 endpoint logs          | Relevant process, network or security events, if recorded      | Pending |
| Review SIEM telemetry        | Wazuh dashboard and alerts        | Events or alerts relevant to the investigation, if collected   | Pending |
| Build incident timeline      | Email, endpoint and SIEM evidence | Events arranged in chronological order                         | Pending |

## Important Limitations

* Wazuh does not automatically read the contents of a Gmail mailbox.
* Email evidence must be collected and analysed separately unless an appropriate integration is configured.
* Wazuh can only show endpoint events that its agent and configured log sources collect.
* An event appearing in Wazuh does not automatically mean that phishing was detected.
* No detection will be claimed without supporting evidence.

## Status Definitions

* **Pending:** Investigation has not yet verified the evidence.
* **Confirmed:** Supporting evidence has been collected and reviewed.
* **Not observed:** The activity was not found in the available evidence.
* **Not tested:** The relevant test has not been performed.

## Conclusion

Detection coverage will be updated after the controlled email investigation and Wazuh telemetry review. Findings will distinguish confirmed observations from limitations and untested areas.
