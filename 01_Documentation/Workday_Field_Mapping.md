# Workday Concept Mapping (indicative)

> This is a learning-oriented mapping from the tracker's fields to commonly used Workday HCM concepts. It is **not** based on any employer's tenant configuration; names and processes differ by organisation. I have not used this project with a live Workday tenant.

| Tracker field | Typical Workday concept | Used for |
|---|---|---|
| Emp ID | Employee ID / Worker | Lookup key for all requests |
| Name | Legal / Preferred Name | Letters, tracker |
| Job Title | Business Title / Job Profile | Reference letter, salary certificate |
| Department | Supervisory Organization / Cost Centre | Letters |
| Grade | Job Level / Compensation Grade | Reference letter |
| Hire Date | Hire Date / Original Hire Date | Letters |
| End Date | Termination / End Employment Date | Reference letters for former employees |
| Status | Worker Status (Active / Terminated) | Eligibility checks |
| Coach ID | Custom assignment / Manager-type relationship | Coach changes |
| Annual Salary | Compensation (restricted security group) | Salary certificates only |
| VDU User? | Custom field / health & safety flag | Eyecare eligibility |

## How this maps to day-to-day work
- `Employees` mirrors a **worker report** exported for support use.
- Each tracker row corresponds to a **case/ticket** in the HR case-management tool.
- Data changes (coach assignment, etc.) are performed in the HR system; the tracker is the audit trail and SLA monitor.
