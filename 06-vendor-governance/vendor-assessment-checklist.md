# Third-Party AI Vendor Assessment Checklist

**Use case:** Recruitment screening and candidate ranking  
**Vendor classification:** High impact for this illustrative internal assessment  
**Assessment status:** Conditional / not approved for production

## 1. Due diligence checklist

| Area | Evidence to request | Current scenario finding |
|---|---|---|
| Purpose and functionality | Intended purpose, system description, workflow and prohibited uses | Further detail required |
| Transparency | Explanation of ranking factors, limitations and system behaviour | Vendor protects proprietary details; sufficient evidence still required |
| Fairness | Independent bias testing relevant to recruitment context | Career-break ranking disparity identified |
| Accuracy and reliability | Validation results, error analysis and limitations | Further validation required |
| Human oversight | Recruiter review, override and escalation design | Must be demonstrated |
| Privacy | Data-flow map, purposes, lawful basis where applicable, retention and deletion | Secondary use unclear; five-year retention needs justification |
| Security | Access reviews, encryption, vulnerability assessments and incident controls | Evidence incomplete; certificate alone is insufficient |
| Model updates | Change notification, versioning, testing and rollback | Must be contractually and operationally defined |
| Subprocessors | List, locations, purposes and approval/change process | Must be documented |
| Contract | Processing instructions, confidentiality, security, audit, breach and exit clauses | Restrictions on independent reuse inadequate |

## 2. Vendor transparency and intellectual property

A vendor may protect source code and trade secrets. Source-code disclosure is not automatically required in every procurement. However, the vendor must provide enough information and evidence for GlobalTech to evaluate the system's functionality, limitations, testing, fairness, security and suitability.

Independent reports must be reviewed for scope, methodology, date, model version, independence and relevance to GlobalTech's intended use.

## 3. Data and contract safeguards

The agreement should define:
- Permitted processing purposes and documented instructions.
- No unauthorised reuse or disclosure of candidate data.
- Restrictions on use of candidate data for vendor model training or other independent purposes, subject to documented legal/privacy review and authorisation.
- Confidentiality and security obligations.
- Subprocessor requirements.
- Data location and transfer arrangements.
- Retention, return and deletion.
- Incident notification and cooperation.
- Audit and compliance evidence.
- Assistance with data subject requests where applicable.
- Exit and transition requirements.

## 4. Illustrative scoring

Scale: 1 = Strong controls; 2 = Minor gaps; 3 = Moderate gaps; 4 = Significant gaps; 5 = Critical gap.

| Assessment area | Preliminary score | Reason |
|---|---:|---|
| Transparency and explainability | 4 | Sufficient evidence and explanations require validation |
| Fairness and accuracy | 4 | Career-break disparity identified |
| Data privacy | 5 | Secondary use unclear, retention not justified and contract lacks explicit restriction |
| Information security | 4 – provisional | Evidence of vulnerability testing, access reviews and encryption incomplete |
| Human oversight | Pending | Workflow and meaningful review not yet validated |
| Contractual controls | 5 | Independent data reuse restrictions inadequate |

These are illustrative judgements based on the scenario, not independently verified vendor ratings. A critical gap must not be hidden by averaging scores.

## 5. Vendor decision

**Decision:** Conditional – not approved for production deployment.

Reassessment is required after remediation, supporting evidence, privacy/security/legal review and documented residual-risk assessment. Approval must follow the organisation's delegated authority.

## 6. Ongoing oversight

Review vendor performance, incidents, contractual compliance, subprocessor changes, model updates, fairness evidence and security assurance throughout the relationship.
