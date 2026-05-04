# Digital parking permit system
This project similates a parking permit system for a university
Tools used:
Google Docs
Google sheets
Diagram.net
GitHub
Files:
final_report.pdf
workflow diagram
test cases
Workflow:
Vehicle registration -> Permit Request -> Zone check -> Permit approval -> Parking verification

## Requests:

### Functional requirements :

1. Users can register vehicles in the system.
2. Users can request a parking permit.
3. The system shows available parking zones.
4. Security staff can verify permits and record violations.

### Non-functional requirements:
1. System must respond within 2 seconds
2. System must be secure, user authentication is required

### Defect analysis

| Item    | Answer |
| -------- | ------- |
| Defect category | Functional defect   |
| Severity | High     |
| Priority    | High    |
| Possible root cause    | Incorrect date validation logic    |
| Regression test    | Check valid permits are not marked
expired    |

