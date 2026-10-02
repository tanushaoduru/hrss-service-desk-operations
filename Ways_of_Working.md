# Ways of Working - offshore shared-services model (India delivery, Ireland client)

> Illustrative model for this portfolio. Real teams' structures differ; confirm with your Team Lead.

## 1. Time-zone overlap (calculated)
India Standard Time is UTC+5:30 all year. Ireland is UTC+0 (winter, GMT) and UTC+1 (summer, IST - Irish Standard Time).

| India shift | Ireland - winter (GMT) | Ireland - summer (IST) |
|---|---|---|
| 13:30 - 22:30 IST | 08:00 - 17:00 | 09:00 - 18:00 |
| 14:00 - 23:00 IST | 08:30 - 17:30 | 09:30 - 18:30 |

**Implication:** the India team's shift covers the Irish working day. Requests received overnight in Ireland are picked up at the start of shift; urgent queries from Ireland can be answered within the same day.

## 2. RACI (who does what)
| Activity | HRSS Associate | Team Lead / QC | Client HR (Ireland) | DPO / Privacy |
|---|---|---|---|---|
| Log & process routine requests | **R** | A | I | - |
| Four-eyes quality check | C | **R/A** | - | - |
| Policy/eligibility exception | C | R | **A** | - |
| Suspected data incident | **R (report)** | R | I | **A** |
| SLA reporting | C | **R/A** | I | - |
| Process change / new SOP | C | R | **A** | C |

R = Responsible, A = Accountable, C = Consulted, I = Informed.

## 3. Escalation matrix
| Trigger | Escalate to | When |
|---|---|---|
| Request at risk of missing SLA (<50% time left, work not started) | Team Lead | Same shift |
| Data conflict between systems/records | Team Lead -> Client HR | Same day |
| Eligibility exception or unusual request | Team Lead -> Client HR | Before acting |
| Wrong recipient / lost or misdirected data | Team Lead + DPO/Privacy | **Immediately** |
| Employee complaint or sensitive circumstance | Team Lead | Same day |

## 4. Shift handover procedure
1. Update every request in `Request_Tracker` before end of shift.
2. Complete a row in `Handover_Log`: open items, at-risk IDs, priority actions, comms pending, escalations.
3. Receiving agent acknowledges (Yes) at start of shift.
4. Anything due within one working day is flagged (see live counter on the log).

## 5. KPI definitions
| KPI | Definition |
|---|---|
| SLA compliance % | Met / (Met + Breached + Overdue) |
| Turnaround | Working days from receipt to closure |
| First-time-right % | Quality checks passed / checks performed |
| Backlog ageing | Open requests by working days open |
| Escalations | Items needing Team Lead / DPO involvement |
