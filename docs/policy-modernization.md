# Policy Modernization & Cleanup

## The Problem: Group Policy Drift
Decades of "Group Policy drift" can leave environments unstable and insecure. Old settings pile up (e.g., "Enable SMB1", loose RDP settings), creating vulnerabilities.

## The Solution
We perform deep cleans and modernize legacy GPOs by migrating them to **Intune** or the **Settings Catalog**.

## Tools
Run `src/optimize-policy.ps1` to scan for common drift indicators.

```powershell
# Analyze only
.\src\optimize-policy.ps1 -AnalyzeOnly

# Apply fixes (requires testing!)
.\src\optimize-policy.ps1 -Fix
```

## Migration Strategy
1. **Identify**: Use the script to find legacy registry hacks.
2. **Export**: Map these to Intune Configuration Profiles.
3. **Delete**: Remove the local GPO links.
