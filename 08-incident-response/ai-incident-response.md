# AI Incident Response and Escalation Procedure

**Scenario:** A vendor is found to have used candidate CVs to train its own AI model without authorisation.

## 1. Objective

Provide a coordinated response to suspected AI-related incidents, including unauthorised data processing, privacy or security breaches, biased outcomes, unsafe model behaviour and unauthorised model changes.

## 2. Initial response

1. Activate the organisation's incident response process.
2. Restrict or stop the suspected unauthorised processing where appropriate.
3. Preserve relevant evidence, logs, contracts, communications and model/version information.
4. Notify the relevant internal incident, privacy, security, legal and vendor-management owners.
5. Record the time, detection source, systems, data and initial actions.

## 3. Investigation and impact assessment

Establish:
- What data was involved and whose data it was.
- What the vendor did, why and for how long.
- Whether data was disclosed, transferred, copied or used for training.
- Whether subprocessors or further systems were involved.
- Whether model artifacts, embeddings, logs or backups may contain or derive from the data.
- Whether individuals, customers or business operations are affected.
- Whether the event is a personal data breach or another form of unauthorised processing under applicable law.

Do not assume every contractual violation is automatically a legally reportable personal data breach. Legal and Privacy should assess the facts and notification duties.

## 4. Containment and remediation

- Stop or restrict unauthorised processing.
- Require the vendor to preserve evidence and cooperate.
- Determine whether deletion, isolation, model retraining or other remediation is technically and legally appropriate.
- Review access credentials, integrations and data flows.
- Consider suspending the vendor or affected AI functionality.
- Assess whether the AI system's outputs may have been affected.

## 5. Notification and communication

Legal and Privacy determine whether regulatory, individual, customer or other notifications are required, by whom and within what timeframe. Communications must be accurate, approved and supported by the investigation.

## 6. Vendor and governance decision

Review contractual remedies, audit rights, suspension and termination options. Reassess vendor risk and whether the AI system can continue to be used.

## 7. Closure and lessons learned

Document root cause, impact, decisions, notifications, remediation, evidence and lessons learned. Update the risk register, vendor assessment, controls and training.

## 8. Roles

| Function | Response responsibility |
|---|---|
| Incident lead | Coordinate response and maintain incident record |
| Information Security | Investigate technical access and security issues |
| Privacy / Legal | Assess privacy obligations and notification requirements |
| Vendor Management / Procurement | Enforce contractual cooperation and remedies |
| HR Business Owner | Assess recruitment impact and candidate workflow |
| AI Governance | Coordinate AI risk reassessment and governance escalation |
| Authorised management | Decide on significant residual risk and business continuation |

## 9. Recovery and reactivation

Reactivation requires evidence that the issue is contained, corrective actions are effective, affected data and model implications are understood, legal/privacy/security reviews are complete, residual risk is assessed and authorised approval is obtained.
