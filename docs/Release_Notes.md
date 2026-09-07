---
layout: default
title: Release Notes
nav_order: 3
---
# SQL Server 2022 Developer Edition on Windows Server 2022 Datacenter - Release Notes

# Version SQL2022DEV-2026Q4

## Key Changes and Updates

### 1. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 25 (KB5081477)**: The version is 16.0.4255.1.

### 2. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to include the latest June 2026 security patches (KB5094128).

### 3. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**:
  - CVE-2026-42904, CVE-2026-44815, CVE-2026-45602, CVE-2026-45657, CVE-2026-47291: Mitigated via latest OS security patches (KB5094128).
  - General vulnerabilities addressed through standard OS patching.

# Version SQL2022DEV-2026Q3

## Key Changes and Updates

### 1. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 25 (KB5081477)**: The version is 16.0.4255.1.

### 2. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to v20260515, including the latest security patches.

### 3. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**:
  - CVE-2026-40402: Mitigated via latest OS security patches (KB5087545).
  - General vulnerabilities addressed through standard OS patching.


# Version SQL2022DEV-2026H2

## Key Changes and Updates

### 1. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 24 (KB5080999)**: The version is 16.0.4245.2.

### 2. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to v20260429, including the latest security patches.

### 3. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**: 
  - CVE-2026-33824: Mitigated via latest OS security patches.
  - General vulnerabilities addressed through standard OS patching.

# Version SQL2022DEV-2026Q1

## Key Changes and Updates

### 1. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 23 (KB5078297)**: Ensures the system includes the latest fixes and improvements from Microsoft. The version is `16.0.4236.2`.

### 2. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to `v20260114`, including the latest security patches and updates from Microsoft.

### 3. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**: The following CVEs have been addressed and fixed via standard OS patching:
  - CVE-2024-55414 (Motorola SM56 Driver Vulnerability)
  - CVE-2025-6965 (SQLite Memory Corruption in winsqlite3.dll)

# Version SQL2022DEV-2025Q4

## Key Changes and Updates

### 1. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 22 (KB5068450)**: Ensures the system includes the latest fixes and improvements from Microsoft. The version is `16.0.4225.2`.

### 2. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to `v20251112`, including the latest security patches and updates from Microsoft.

### 3. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**: The following CVEs have been addressed and fixed:
  - CVE-2016-9535
  - CVE-2020-17042
  - CVE-2024-21416
  - CVE-2024-3596
  - CVE-2024-38063
  - CVE-2024-38074
  - CVE-2024-38076
  - CVE-2024-38077
  - CVE-2024-38124
  - CVE-2024-38140
  - CVE-2024-38199
  - CVE-2024-38240
  - CVE-2024-43455
  - CVE-2024-43639
  - CVE-2024-49112
  - CVE-2025-21298
  - CVE-2025-21307
  - CVE-2025-47981
  - CVE-2025-49708
  - CVE-2025-50171
  - CVE-2025-53766
  - CVE-2025-55234
  - CVE-2025-59287

---
# Version 2024H2
## Key Changes and Updates

### 1. SQL Server Management Studio (SSMS)
- **Updated Version**: SSMS has been upgraded from version 19.3 to 20.1

### 2. Security Enhancements
- **sa_user Removal**: The `sa_user` is now deleted from OS.
- **sysadmin Account**: The sysadmin account is now set to `BUILTIN/Administrators` to align sa_user removal.

### 3. SQL Cumulative Update
- **Deployment of SQL Cumulative Update 13**: Ensures the system includes the latest fixes and improvements.

### 4. Windows OS Security Update
- **Vulnerability Fix**: The Windows OS has been updated to address and fix the vulnerability identified as CVE-2024-30080, ensuring a more secure operating environment.

---
These updates significantly enhance the security, stability, and performance of SQL Server 2022 Developer Edition on Windows Server 2022 Datacenter. For more details, please contact our [support team](https://gcp.gclouds.co.uk/support.html)