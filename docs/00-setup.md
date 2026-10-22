# Module 0 — Environment Setup

## Tools
| Tool | Purpose |
|---|---|
| Splunk Enterprise | Log search and analytics platform |
| Git + GitHub | Version control and portfolio |
| VS Code | Writing documentation and configs |

## Lesson learned: virtualization
My first plan was to run Splunk in Docker, but Docker Desktop requires CPU virtualization (Intel VT-x)
enabled in the BIOS. Without it, the error is `Virtual Machine Platform not enabled / No virtualization available`.
How to check: Task Manager → Performance → CPU → "Virtualization".
Workaround: install Splunk Enterprise natively on Windows (.msi).

## Result
- Splunk Enterprise **10.6.1.1** installed from the official `.msi` (digital signature verified: Splunk LLC)
- `Splunkd` service running with automatic startup
- Web UI: http://localhost:8000

## Lesson learned: credentials
Passwords never go into chats, screenshots or repositories. This repo's `.gitignore` blocks credential files.
