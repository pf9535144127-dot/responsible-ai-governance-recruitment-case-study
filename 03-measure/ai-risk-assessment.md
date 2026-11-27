# MEASURE – AI Risk Assessment

## 1. Assessment objective

Evaluate whether the recruitment AI system performs appropriately for its intended context and whether its risks are understood and controlled. Testing should be planned before deployment and repeated after material changes and during operation.

## 2. Assessment domains

| Domain | Example assessment questions | Evidence |
|---|---|---|
| Fairness | Are similarly qualified candidates treated consistently? Are outcomes materially different across relevant groups? | Disaggregated testing, methodology, limitations and remediation results |
| Accuracy | Does the system correctly extract and evaluate job-related qualifications? | Test datasets, error analysis and validation results |
| Explainability | Can recruiters understand the main factors behind a recommendation? | System documentation, explanations and user testing |
| Privacy | Is personal data used only for defined authorised purposes? | Data-flow map, privacy assessment, retention and vendor documentation |
| Security | Are data and systems protected against unauthorised access and misuse? | Security assessment, access reviews, encryption and vulnerability evidence |
| Human oversight | Can recruiters meaningfully review, challenge and override outputs? | Workflow design, training, override records and audit trails |
| Reliability | Does performance remain consistent in relevant operating conditions? | Monitoring results, robustness tests and incident records |

## 3. Illustrative fairness finding

An independent test report indicates that candidates with career breaks are consistently ranked lower despite comparable qualifications and relevant experience.

This is a significant fairness concern. The organisation should not assume the cause is limited to training data. Potential causes may include feature selection, labels, model design, proxies, objective functions, thresholds or workflow use.

Required response:
1. Investigate the root cause.
2. Determine whether the feature is job-related and justified.
3. Review data representativeness and quality.
4. Test relevant candidate groups and scenarios.
5. Require vendor remediation.
6. Retest using an appropriate methodology.
7. Document limitations and residual risk.

## 4. Evidence quality

Evidence should be relevant to GlobalTech's intended use, current model version, data population and operating context. Independent reports can support assurance but must be reviewed for scope, methodology, independence, date, sample size, limitations and applicability.

A vendor certificate or general accuracy claim is not proof that the recruitment use case is fair or safe.

## 5. Human oversight assessment

The presence of a recruiter in the workflow is not sufficient on its own. Assess whether the recruiter:
- Sees enough information to understand the recommendation.
- Has time, authority and training to challenge it.
- Can review candidates outside the top-ranked group.
- Can override the AI without penalty.
- Records reasons for overrides and escalates concerns.
- Avoids relying solely on AI ranking.

If only the top ten candidates are reviewed, qualified candidates ranked lower may never receive meaningful consideration.

## 6. Risk scoring note

Any numerical scale used by GlobalTech is an internal assessment method and must be defined, calibrated and consistently applied. NIST AI RMF does not prescribe a universal numerical score or risk matrix.

## 7. MEASURE conclusion

The identified fairness issue and incomplete privacy/security evidence mean that the system is not ready for production approval. Corrective action, validated testing and documented residual-risk review are required.
