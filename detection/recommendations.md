# Security Recommendations

## Purpose

These recommendations describe practical actions an organisation can take to reduce phishing risk. They will be reviewed against the evidence collected during the PhishTrace investigation.

## Recommended Actions

### 1. Email Security

* Configure SPF, DKIM and DMARC for organisational email domains.
* Review email filtering rules and suspicious-message reporting procedures.
* Train employees to recognise unexpected attachments, suspicious links and requests for sensitive information.

### 2. User Awareness

* Encourage employees to report suspicious emails to the security team.
* Provide a clear process for reporting suspected phishing.
* Avoid clicking unexpected links or entering credentials on unverified websites.

### 3. Endpoint Monitoring

* Ensure endpoint security logging is enabled where appropriate.
* Collect relevant Windows security and Sysmon events.
* Confirm that the Wazuh agent is connected and collecting the intended logs.

### 4. Security Monitoring

* Review relevant Wazuh events and alerts during an investigation.
* Investigate suspicious activity using timestamps and supporting evidence.
* Create or tune detection rules only when the required telemetry is available and the rule can be tested safely.

### 5. Incident Response

* Record evidence sources, timestamps and investigation actions.
* Preserve original evidence and document any limitations.
* Escalate confirmed malicious activity according to the organisation's incident response procedure.

## Evidence-Based Improvements

After the investigation, recommendations will be prioritised according to the findings. Recommendations that have not been validated against the lab evidence will be identified as general security improvements.

## Safety

All testing for this portfolio project will use accounts and systems controlled by the investigator. No real credentials will be collected, and no unsuspecting recipients will be targeted.
