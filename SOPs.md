# Standard Operating Procedures - HR Support Services (HRSS)

> Portfolio SOPs written for a synthetic desk. SLAs, limits and values are illustrative (see `Lists` sheet in the tracker). Replace with your organisation's real policy before use.

## 0. Common intake & closure (applies to every request)
1. **Log** the request in `Request_Tracker`: Req ID, type, Employee ID, date received, assignee, **purpose of data access**.
2. **Verify identity/authority**: requester is the employee (or an authorised HR/line contact). Never release personal data to third parties without documented authority.
3. **Check eligibility** using the rules in the relevant section below.
4. **Execute** and keep the Workday/case reference in `Notes`.
5. **Quality check (four-eyes on sensitive items)**: name, dates, job title, salary and addressee verified against the source record.
6. **Close**: enter Date Closed, send confirmation to the requester, then confirm the SLA Result column.
7. **Escalate** to the Team Lead if: due date is at risk (<50% of SLA left and work not started), data conflicts exist, or the request is unusual.

---

## 1. Employment Reference Letters
| | |
|---|---|
| **Trigger** | Current or former employee requests a reference letter. |
| **SLA** | 2 working days |
| **Inputs** | Employee ID, full name, job title, department, grade, hire date, end date (former staff). |
| **Eligibility** | Request comes from the employee. Former employees must have an end date on record. |
| **Tracker tool** | `Letter_Generator` (status cell must read *Ready*). |

**Steps**
1. Enter Employee ID in `Letter_Generator`; confirm status = Ready.
2. Cross-check generated dates and title against the HR system.
3. Copy into the approved letterhead template; save as PDF.
4. Issue to the employee (or the address they authorised). Record in tracker; close.

**Controls:** facts only (dates, role) - no performance opinions unless authorised by policy; unique reference number; purpose logged.
**Common errors:** wrong end date, wrong job title at leaving, sending to an unverified email.

---

## 2. Salary Certificates
| | |
|---|---|
| **Trigger** | Current employee needs proof of salary (mortgage, visa, rental, etc.). |
| **SLA** | 1 working day |
| **Eligibility** | Employee is **active**; purpose stated. |
| **Tracker tool** | `Letter_Generator` (shows NOT ELIGIBLE for non-active staff). |

**Steps**
1. Record the stated purpose; enter ID, purpose and issuer.
2. Verify salary against the HR system (gross annual, correct currency).
3. Generate, review, export to PDF, send only to the employee.
4. Log and close.

**Controls:** salary is special-handling data - release only to the employee; purpose-limited wording on the certificate; second check on amount.

---

## 3. Coach Changes
| | |
|---|---|
| **Trigger** | Employee or manager requests a different coach. |
| **SLA** | 3 working days |
| **Eligibility** | New coach is active, is not the employee, is not already the coach, and is under the capacity limit (15). |
| **Tracker tool** | `Coach_Changes` (Validation column must read OK). |

**Steps**
1. Log in `Coach_Changes`; confirm Validation = OK.
2. Obtain confirmation from the new coach (and approval per policy).
3. Update the coach assignment in the HR system.
4. Notify employee, old coach and new coach. Close.

**Controls:** keep the reason for change need-to-know; update effective date correctly; confirm the old coach is informed.

---

## 4. Bike to Work Scheme
| | |
|---|---|
| **Trigger** | Employee applies to use the scheme. |
| **SLA** | 4 working days |
| **Eligibility** | Active; item cost within cap (Lists); no prior claim within the gap period. |
| **Tracker tool** | `Bike_to_Work` (Eligibility must read Eligible). |

**Steps**
1. Log application; enter item type, cost and previous claim date (if any).
2. If *Not eligible*, reply with the specific reason and next steps.
3. If eligible, issue the certificate/approval per the scheme provider process; record status.
4. Track completion and any payroll deduction handover. Close.

**Controls:** cap and gap come from `Lists` - verify against the current scheme rules before relying on them; retain evidence for audit.

---

## 5. Eyecare / VDU Vouchers
| | |
|---|---|
| **Trigger** | VDU user requests an eye test voucher. |
| **SLA** | 2 working days |
| **Eligibility** | Active; registered VDU/display-screen user; no voucher within the gap period (24 months). |
| **Tracker tool** | `Eyecare_VDU` (Eligibility = Eligible; expiry auto-calculated). |

**Steps**
1. Log request; confirm VDU flag and last voucher date.
2. If eligible, issue the voucher code and send with expiry date.
3. Record code and status. Close.

**Controls:** health-related data minimised - record only entitlement, never results; compliance with health & safety obligations; unique voucher codes.

---

## 6. Personal Milestones (Perx vouchers, flowers, baby gifts)
| | |
|---|---|
| **Trigger** | HR/manager/employee notifies a milestone (baby, wedding, bereavement, long service, illness). |
| **SLA** | 3 working days |
| **Tracker tool** | `Milestones` (event drives gift type and value). |

**Steps**
1. Log event and date; gift and value auto-populate.
2. Verify delivery details **with the employee or manager** - do not assume.
3. Add a personal, appropriate message (tone check for sensitive events).
4. Place the order/issue the voucher; record dispatch date. Close.

**Controls:** sensitive life events are need-to-know; confirm consent/awareness where appropriate; accurate spelling of names; timely delivery.

---

## 7. Ad-hoc / process-transition requests
Log as *Ad-hoc / Other*. Document the steps taken so the task can become a new SOP. Raise unclear ownership with the Team Lead before acting.
