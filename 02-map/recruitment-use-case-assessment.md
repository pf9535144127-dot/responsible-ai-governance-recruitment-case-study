# MAP – Recruitment AI Use-Case Assessment

## 1. Use-case overview

GlobalTech Services Ltd. (fictional) is considering a third-party AI recruitment tool. The tool reads candidate CVs, extracts qualifications and experience, compares information with job requirements and produces candidate rankings or recommendations for HR recruiters.

**Intended purpose:** Support initial recruitment screening and prioritisation.  
**Not intended purpose:** Make final hiring decisions or automatically reject candidates without appropriate human review.

## 2. Business context

The business objective is to reduce manual screening effort and support consistent evaluation. Efficiency is not, by itself, sufficient justification: the organisation must establish that the system is suitable, fair, explainable enough for the context and appropriately controlled.

## 3. Stakeholders and affected parties

- Job applicants and candidates whose opportunities may be affected.
- HR recruiters and hiring managers who use the rankings.
- HR leadership and the business owner.
- AI vendor and its subprocessors.
- Technical, security, privacy, legal and compliance teams.
- AI Governance Function and authorised approval body.

Candidates are directly affected even if they do not interact with the AI system.

## 4. Data and information flows

Potential data includes candidate names and contact details, CV content, employment history, education, qualifications, skills and application responses.

The assessment must document:
- Data sources and collection methods.
- Data fields used by the model and their relevance to job criteria.
- Data storage locations and access.
- Vendor and subprocessor processing.
- Retention, deletion and backup arrangements.
- Whether data is used for model training or other secondary purposes.
- International transfers, where relevant.

## 5. Potential impacts and harms

| Potential issue | Possible impact |
|---|---|
| Career-break penalty | Qualified candidates may be ranked lower without job-related justification |
| Educational institution preference | Candidates from other institutions may be disadvantaged |
| Limited explainability | Recruiters may be unable to understand or challenge rankings |
| Inaccurate extraction | Skills or experience may be misread or omitted |
| Automation bias | Recruiters may over-rely on rankings |
| Privacy misuse | Candidate information may be used beyond the recruitment purpose |
| Security failure | Candidate data may be accessed or disclosed without authorisation |

## 6. Context and assumptions requiring validation

The portfolio scenario assumes recruiters retain final decision authority. The actual workflow must be checked: if recruiters only review the top-ranked candidates, lower-ranked candidates may effectively be excluded from consideration.

The organisation must determine whether ranking thresholds, filters or workflow design create de facto automated rejection.

## 7. Initial internal impact classification

For this illustrative assessment, the use case is classified as **high impact** because AI rankings may materially influence access to employment opportunities.

This is an internal portfolio judgement. NIST AI RMF does not prescribe a universal high-risk tier. Applicable laws may separately classify certain employment AI systems and impose specific obligations.

## 8. MAP conclusion

Before procurement or deployment, GlobalTech should document the actual recruitment workflow, intended and prohibited uses, affected groups, data flows, decision points, vendor dependencies and foreseeable impacts. Unclear purpose, data use or human oversight must be resolved before approval.
