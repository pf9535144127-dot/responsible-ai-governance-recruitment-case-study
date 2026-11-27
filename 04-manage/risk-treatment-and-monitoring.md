# MANAGE – Risk Treatment and Monitoring Plan

## 1. Objective

Prioritise and respond to identified AI risks, assign owners, select treatment actions, monitor effectiveness and make authorised decisions about deployment, restriction, suspension or retirement.

## 2. Risk treatment options

- **Mitigate:** Implement controls to reduce likelihood or impact.
- **Avoid:** Do not proceed with a use case or feature where risk is unacceptable or prohibited.
- **Transfer/share:** Allocate certain responsibilities contractually or through insurance where appropriate. This does not eliminate the organisation's own accountability.
- **Accept:** Formally accept residual risk only where permitted, justified and approved by the authorised decision-maker.

## 3. Treatment plan

| Risk | Treatment action | Accountable owner / support | Evidence for closure |
|---|---|---|---|
| Career-break bias | Root-cause analysis, remediation and fairness retesting | Vendor / technical owner; HR and AI Governance review | Validated test results and documented residual risk |
| Education proxy bias | Assess relevance of features and test outcomes | Vendor / technical owner; HR review | Feature assessment and test evidence |
| Unauthorised data reuse | Clarify processing, restrict secondary use and amend contract | Procurement / Legal / Privacy | Executed contractual safeguards and vendor evidence |
| Excessive retention | Justify retention and implement deletion schedule | HR / Privacy / Vendor | Approved schedule and deletion evidence |
| Security assurance gaps | Obtain and review technical security evidence | Information Security / Vendor | Security assessment and remediation evidence |
| Weak human oversight | Redesign workflow, train recruiters and monitor overrides | HR Business Owner | Approved workflow, training and monitoring records |
| Unassessed model updates | Introduce change notification and pre-release assessment | System Owner / AI Governance | Change record, impact assessment and approval |

## 4. Deployment gate

Production deployment remains on hold until:
- Material fairness issues are remediated and retested.
- Privacy and security reviews are complete.
- Vendor contractual safeguards are adequate.
- Human oversight is demonstrated in the real workflow.
- Residual risks and limitations are documented.
- Required specialist reviews are complete.
- The authorised approval body has made the decision.

## 5. Residual risk and approval

Risk cannot always be eliminated. Residual risk must be assessed after controls are implemented, considering severity, likelihood, affected people, applicable law, organisational risk appetite and control effectiveness.

The AI Governance Function may assess and recommend. The business owner owns the business use case. Significant residual-risk acceptance must be made by the authorised decision-maker under the organisation's governance structure.

## 6. Ongoing monitoring

| Monitoring area | Example indicator | Review owner |
|---|---|---|
| Fairness | Ranking and selection outcomes across relevant groups | HR / AI Governance |
| Accuracy | Extraction and recommendation error rates | Technical owner |
| Human oversight | Review coverage, overrides and escalations | HR |
| Privacy | Access, retention, deletion and data-use exceptions | Privacy |
| Security | Vulnerabilities, access reviews and incidents | Information Security |
| Vendor | Contract compliance, model changes and assurance updates | Vendor Management |
| Reliability | Performance drift, availability and failures | Technical owner |

Thresholds must be defined for the actual system and context; this portfolio does not invent numerical performance limits.

## 7. Suspension and reactivation

If significant bias, privacy misuse, security incidents or unsafe behaviour is detected, GlobalTech should restrict or suspend the affected functionality as appropriate, preserve evidence, investigate and assess impacts.

Reactivation requires corrective actions, evidence that controls are effective, updated residual-risk assessment, specialist review and authorised approval. Enhanced monitoring and a rollback plan should be in place after reactivation.

## 8. MANAGE conclusion

The organisation must treat AI risk management as an ongoing lifecycle activity rather than a one-time approval exercise.
