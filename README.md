# Graph Ascent: Windows Server Modernization

> **Legacy Power | Modern Agility**
> *Hybrid Infrastructure, Optimized*

Windows Server isn't legacy—it's foundational. But managing it manually is a relic of the past. Whether your workloads sit on-premises or are Azure-hosted, at **Graph Ascent**, I automate Windows Server 2022/2025 management to ensure your core infrastructure is as agile as the cloud.

I bridge the gap between traditional data centers and modern cloud governance. By using **Azure Arc**, I project your on-prem servers into the Azure Resource Manager, allowing for unified policy, security, and update management across your entire fleet.

---

## Core Capabilities

### 🛡️ Policy & Cleanup
Decades of "Group Policy drift" can leave environments unstable and insecure. I perform deep AD cleanups and modernize legacy GPOs.

- **GPO Migration**: Shifting from legacy ADMX to Intune/Settings Catalog.
- **Structure Optimization**: Automated OU structure restructuring.
- **Security hardening**: Applying Server Baselines (NIST/CIS).

### ☁️ Hybrid Cloud Integration
Bring cloud intelligence to your local hardware without the cost of a full migration.

- **Azure Arc**: Unified Fleet Management (`Set-AzArcServer -Status "Projecting"`).
- **Update Manager**: Automated Patching and compliance reporting.
- **Log Analytics**: Centralized Monitoring and insights.

### ⚙️ Standardized Server Operations
I treat your servers like cattle, not pets. Through PowerShell DSC and Azure Policy, I ensure every server in your environment—whether it's a domain controller or a file server—stays in its desired state. 

- **No more manual updates.**
- **No more undocumented registry "fixes".**
- **Just a rock-solid foundation for your business applications.**

---

## Source Code & Usage

See the `src/` directory for the modernization toolchain.

### Quick Start
```powershell
# Project a server to Azure Arc and apply baselines
.\src\modernize.ps1 -ProjectToAzure -ApplyBaselines
```

---

**Modernize My Fleet**
© Graph Ascent. All rights reserved.  
*Automation Architect: ktzr*
