# Getting Started with Windows Modernization

## Overview
This repository contains a suite of tools designed to modernize and maintain Windows environments efficiently.

## Prerequisites
- Windows 10 or Windows 11
- PowerShell 5.1 or PowerShell 7+
- Administrator privileges

## Directory Structure
- `/src`: Contains the core PowerShell automation scripts.
- `/docs`: Documentation and guides.

## Running the Scripts
Navigate to the `src` directory and run the main script:

```powershell
cd src
.\modernize.ps1
```

Use the `-DryRun` switch to preview changes without applying them:

```powershell
.\modernize.ps1 -DryRun
```
