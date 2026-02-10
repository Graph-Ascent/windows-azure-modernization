# Server Baselines & Standardization

## Philosophy: Cattle, Not Pets
We treat servers like cattle, not pets. Every server in your environment—whether it's a domain controller or a file server—must stay in its desired state automatically. No manual tweaking.

## Standardized Operations
Our `src/enforce-baselines.ps1` script ensures adherence to **NIST/CIS** standards.

### Key Checks
- **Windows Update**: Must be running and managed by Arc/Update Manager.
- **Defender**: Real-time monitoring enabled.
- **Remote Management**: WinRM enabled/hardened.

## Usage
Run this script on a schedule (e.g., via Task Scheduler or Azure Automation).

```powershell
.\src\enforce-baselines.ps1
```
