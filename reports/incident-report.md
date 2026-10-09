# PhishTrace — Phishing Investigation Report

## 1. Executive Summary

**Incident reference:** PHISHTRACE-001
**Investigation status:** Not yet investigated
**Severity:** To be determined
**Investigator:** Khayalethu Welcome Myeni
**Date:** To be completed after testing

This report documents a controlled phishing-email investigation using email evidence, Windows endpoint telemetry and the Wazuh security monitoring platform.

The investigation will assess the suspicious email, examine available indicators, review relevant endpoint events and document whether supporting evidence of suspicious activity was observed.

No conclusion will be made until the evidence has been collected and reviewed.

## 2. Investigation Objectives

* Examine the email sender, subject, timestamps and available headers.
* Review SPF, DKIM and DMARC results where available.
* Inspect the URL and domain using safe analysis methods.
* Review relevant Windows endpoint events.
* Determine whether relevant events were collected by Wazuh.
* Create an evidence-based timeline and practical security recommendations.

## 3. Scope

**In scope:**

* A controlled test email sent between accounts owned by the investigator.
* Email headers and other available email evidence.
* The investigator's Windows test endpoint.
* Relevant Wazuh events and alerts available during testing.

**Out of scope:**

* Sending phishing emails to unsuspecting people.
* Collecting real passwords or other credentials.
* Executing malware or accessing systems without permission.

## 4. Tools Used

| Tool                             | Purpose                                           |
| -------------------------------- | ------------------------------------------------- |
| Gmail                            | Controlled test email and email-header collection |
| Windows 10 test VM               | Endpoint telemetry review                         |
| Wazuh                            | SIEM event and alert investigation                |
| Sysmon                           | Endpoint event collection, where configured       |
| Browser-based analysis resources | Safe URL and domain research                      |
| GitHub                           | Documentation and evidence organisation           |

Only tools actually used during the investigation will remain in the final list.

## 5. Evidence Collected

| Evidence ID | Description                      | Source             | Status  |
| ----------- | -------------------------------- | ------------------ | ------- |
| E-01        | Test email and available headers | Gmail              | Pending |
| E-02        | URL and domain analysis          | Analysis notes     | Pending |
| E-03        | Relevant Windows endpoint events | Windows test VM    | Pending |
| E-04        | Relevant Wazuh events or alerts  | Wazuh dashboard    | Pending |
| E-05        | Investigation timeline           | Collected evidence | Pending |

## 6. Investigation Method

1. Identify the controlled test email.
2. Collect and review the available email headers.
3. Examine the URL and domain without visiting unsafe destinations.
4. Review endpoint logs for relevant activity.
5. Search Wazuh for corresponding telemetry.
6. Correlate timestamps and evidence sources.
7. Document findings, limitations and recommendations.

## 7. Findings

**Email analysis:** Pending evidence collection.

**URL and domain analysis:** Pending evidence collection.

**Endpoint analysis:** Pending evidence collection.

**Wazuh analysis:** Pending evidence collection.

**Correlation of evidence:** Pending investigation.

## 8. Incident Timeline

| Timestamp and timezone | Event           | Evidence source | Interpretation  |
| ---------------------- | --------------- | --------------- | --------------- |
| To be completed        | To be completed | To be completed | To be completed |

All timestamps will be recorded with their timezone where known. Any uncertainty will be documented.

## 9. Detection Assessment

The investigation will determine which relevant activities were visible in the collected evidence and which were not observed.

A missing alert will not automatically be treated as proof that an activity did not occur. The available telemetry and monitoring limitations will be considered.

## 10. Limitations

* Wazuh does not automatically access Gmail message contents.
* Endpoint visibility depends on enabled logging, agent configuration and collected events.
* A controlled test may not reproduce every behaviour of a real phishing incident.
* Any external URL or domain reputation results may change over time.

Additional limitations will be recorded if identified.

## 11. Recommendations

Recommendations will be based on the investigation findings and may include improvements to email security, user awareness, endpoint logging, SIEM monitoring and incident response procedures.

Specific recommendations will be completed after the investigation.

## 12. Conclusion

**Final conclusion:** Pending investigation.

The final conclusion will summarise the evidence reviewed, explain what could and could not be established, and identify any further investigation required.

## 13. Evidence Handling and Privacy

Evidence will be limited to information needed for the investigation. Personal email addresses, tokens, credentials and unrelated personal information will be redacted from public screenshots and repository files.

No finding will be reported as confirmed without supporting evidence.
