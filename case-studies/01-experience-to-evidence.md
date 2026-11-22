# Lighting signal fault isolation — shipboard show control

**Evidence classification: AUTHOR-REPORTED EXPERIENCE + ORIGINAL DEMONSTRATION DESIGN. Not independently verified employer documentation.**

## Situation and scope
Reported situation: flicker and loss of control in a GrandMA3 onPC-based cruise theatre rig, with approximately 85 fixtures and eight universes reported. A data/cable path was suspected. The user's account reports that checking cables revealed a fault. The precise failure mechanism, test measurements and corrective work order are not independently verified.

## Method and technical decisions
Operator workflow: (1) record symptom and affected fixtures; (2) confirm show-safe state; (3) compare local console output to node status; (4) inspect authorized patch and data path; (5) test one segment at a time without bypassing safety; (6) document observed versus expected behavior; (7) retest during a safe maintenance window; (8) hand over unresolved faults.

## Functional architecture (illustrative)
```text
[Console / grandMA3 onPC] --> [Show network / node] --> [DMX output] --> [Fixture chain]
```

## Traceability and verification
Provide a redacted fault log, approved patch extract, timestamped before/after functional tests and employer-approved photos. Do not publish node addresses, ship network diagrams or personnel allegations.

| Verification item | Expected result | Current status |
|---|---|---|
| Reproducible procedure | Another technician can follow the steps | DOCUMENTED, NOT FIELD-TESTED |
| Source evidence | Authorized records with date and role | PENDING |
| Operational result | Observed recovery, acceptance or show readiness | AUTHOR-REPORTED / PENDING |
| Employer approval | Public redistribution permission | PENDING |

## Leadership and management transfer
The operational lesson is to make failure modes observable, separate evidence from assumptions, prioritize safe show continuity, define responsibility and preserve a clear handover. These are transferable to fleet-level standardization, but **do not establish prior fleet-management authority**.

## Privacy and professional boundaries
No private medical or trauma information, workplace allegations, personnel names, access credentials or confidential show files belong in this public-facing case study.
