# Azure Arc Setup Guide

## Overview
At Graph Ascent, we bridge the gap between traditional data centers and modern cloud governance. We use **Azure Arc** to project your on-premise servers into the Azure Resource Manager.

This enables:
- **Unified Fleet Management**: View all servers in one dashboard.
- **Update Manager**: Automated patching across on-prem and cloud.
- **Log Analytics**: Centralized monitoring.

## Usage
Use the `src/onboard-arc.ps1` script to connect a server.

```powershell
.\src\onboard-arc.ps1 -SubscriptionId "YOUR-SUB-ID" -ResourceGroup "GraphAscent-RG" -TenantId "YOUR-TENANT-ID"
```

## Prerequisites
- A valid Azure Subscription.
- Internet connectivity (HTTPS 443) to Azure endpoints.
