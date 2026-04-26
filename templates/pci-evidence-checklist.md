# PCI DSS Evidence Checklist

## Purpose

Use this checklist to collect, review, and document audit-ready evidence for PCI DSS control validation. For each item, confirm the evidence is complete, current, tied to the assessment scope, and traceable to the related ticket, screenshot, or repository record.

## Acceptable Evidence Standard

Evidence is acceptable when it is sufficient to support the control objective and includes:

- PCI DSS control reference: PCI DSS requirement or internal control ID being tested.
- Scope: in-scope systems, processes, users, vendors, or sample population covered.
- Period: assessment period or sample date range covered by the evidence.
- Source: authoritative report, screenshot, ticket, repository record, approval, system export, or compliance attestation.
- Traceability: direct links or filenames connecting the evidence to tickets, PRs, screenshots, logs, and supporting records.
- Integrity: generated or captured date is visible where practical, and the evidence has not been manually altered.
- Ownership: evidence owner, reviewer name, and review date are identifiable.
- Exceptions: gaps, exclusions, or compensating controls are documented with owner, due date, and follow-up action.

Screenshots should show the system name, relevant setting or record, user or object reviewed where applicable, and capture date where practical.

Review outcome must be one of: `Pass`, `Fail`, or `Needs Follow-up`.

## Access Control

| PCI DSS control reference | Evidence item | Acceptable evidence requirements | Review focus | Review outcome | Notes |
| --- | --- | --- | --- | --- | --- |
|  | User access list for CDE systems | Current export or report showing users, roles, systems, and date generated | Active users are authorized, role-appropriate, and tied to business need |  |  |
|  | Privileged access review | Review record showing admin accounts, approver, review date, and disposition | Admin accounts are approved, limited, and reviewed periodically |  |  |
|  | Joiner, mover, leaver samples | Sample tickets or approvals showing request, approval, completion date, and affected access | Access changes are completed timely and supported by tickets or approvals |  |  |
|  | MFA configuration evidence | Screenshot, policy export, or configuration report showing MFA scope and enforcement status | MFA is enforced for administrative and remote access |  |  |
|  | Password and authentication settings | Screenshot or configuration export showing relevant authentication settings and date captured | Settings align with PCI DSS requirements and internal policy |  |  |

## Logging and Monitoring

| PCI DSS control reference | Evidence item | Acceptable evidence requirements | Review focus | Review outcome | Notes |
| --- | --- | --- | --- | --- | --- |
|  | Audit log configuration | Screenshot or configuration export showing enabled log sources, event types, and systems covered | Critical systems generate logs for user, admin, and security events |  |  |
|  | Log retention evidence | Policy, storage configuration, or report showing retention period and protection settings | Logs are retained for the required period and protected from alteration |  |  |
|  | Daily log review or alert review samples | Sample review records showing date, reviewer, alerts reviewed, and escalation outcome | Reviews are performed, documented, and escalated when needed |  |  |
|  | SIEM or monitoring rule inventory | Rule export or inventory showing covered systems, rule purpose, and enabled status | Rules cover in-scope systems and key PCI-relevant events |  |  |
|  | Incident escalation records | Incident tickets showing alert source, triage actions, owner, closure date, and resolution | Alerts and incidents show timely triage, ownership, and closure |  |  |

## Vulnerability Management

| PCI DSS control reference | Evidence item | Acceptable evidence requirements | Review focus | Review outcome | Notes |
| --- | --- | --- | --- | --- | --- |
|  | Internal vulnerability scan results | Scan report showing scan date, assets covered, findings, severity, and remediation status | Scans cover in-scope assets and findings are tracked to resolution |  |  |
|  | External ASV scan attestations | Quarterly ASV attestations or reports showing scan result, scope, and date | Passing scans are available for each required quarter |  |  |
|  | Remediation tickets | Tickets showing finding, risk rating, owner, due date, remediation action, and closure evidence | High-risk findings are remediated within policy timelines |  |  |
|  | Patch management reports | Patch report or change records showing evaluation, approval, deployment date, and affected assets | Security patches are evaluated, approved, and deployed timely |  |  |
|  | Penetration test report and retest evidence | Final report and retest records showing scope, findings, remediation, and validation results | Scope includes CDE and segmentation controls where applicable |  |  |

## Change Management

| PCI DSS control reference | Evidence item | Acceptable evidence requirements | Review focus | Review outcome | Notes |
| --- | --- | --- | --- | --- | --- |
|  | Change tickets for sampled production changes | Tickets showing request, risk, approval, testing, implementation date, and rollback plan | Changes include approval, testing, implementation, and rollback details |  |  |
|  | Emergency change records | Emergency tickets showing justification, implementation details, approval, and post-implementation review | Emergency changes are documented and reviewed after implementation |  |  |
|  | Secure development evidence | Pull request, code review, security test, and release approval records for sampled changes | Code review, security testing, and approval are completed before release |  |  |
|  | Configuration baseline changes | Baseline change record showing authorization, affected standard, implementation, and validation | Changes to security baselines are authorized and traceable |  |  |
|  | Deployment logs | Deployment record showing date, approver, environment, version, and linked change ticket | Deployment activity matches approved change records |  |  |

## Third-Party Service Providers

| PCI DSS control reference | Evidence item | Acceptable evidence requirements | Review focus | Review outcome | Notes |
| --- | --- | --- | --- | --- | --- |
|  | Service provider inventory | Inventory showing provider name, service, PCI impact, owner, and review date | Providers with PCI impact are identified and assigned owners |  |  |
|  | Responsibility matrix | Current matrix showing PCI responsibilities assigned to the organization and provider | PCI control responsibilities are documented and current |  |  |
|  | Current AOC or compliance report | AOC, ROC summary, or compliance report showing provider name, scope, status, and period covered | Provider compliance evidence covers the assessment period |  |  |
|  | Contract or security addendum | Executed contract, addendum, or excerpt showing PCI, breach notification, and data protection terms | PCI, breach notification, and data protection obligations are included |  |  |
|  | Provider access review | Review record showing third-party accounts, business need, approver, date, and removals | Third-party access is approved, limited, monitored, and removed when no longer needed |  |  |

## Supporting Links

| Field | Details |
| --- | --- |
| Ticket links |  |
| Pull request links |  |
| Screenshot links |  |
| Log links or locations |  |
| Supporting record links |  |
| Evidence repository location |  |

## Evidence Review Notes

| Field | Details |
| --- | --- |
| Assessment period |  |
| In-scope systems or processes |  |
| Sample population and selection method |  |
| Open evidence gaps |  |
| Exceptions or compensating controls |  |

## Review Outcome

Select one final outcome after evidence review:

- [ ] Pass: Evidence is complete, current, scoped, and supports the control objective.
- [ ] Fail: Evidence does not support the control objective or a control gap is confirmed.
- [ ] Needs Follow-up: Evidence is incomplete, unclear, outdated, or requires additional validation.

| Field | Details |
| --- | --- |
| Outcome rationale |  |
| Follow-up actions |  |
| Follow-up owner |  |
| Due date |  |

## Reviewer Sign-Off

| Field | Details |
| --- | --- |
| Reviewer name |  |
| Review date |  |
| Final disposition |  |
