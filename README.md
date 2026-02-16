# Oracle Pluggable Database Management Assignment II
**Student Name:** Mustafa
**Student ID:** 28869

## 1. Overview
This repository contains the documentation and evidence for Individual Assignment II, focused on managing Oracle Pluggable Databases (PDBs) and configuring Oracle Enterprise Manager (OEM).

## 2. Oracle Environment
- **Database Version:** Oracle Database 21c Express Edition
- **Operating System:** Microsoft Windows x86 64-bit

## 3. Task Execution
### Task 1: Create a Permanent PDB
- Created a PDB named `MU_pdb_28869`.
- Created an administrative user `Mustafa_plsqlauca_28869` with DBA privileges.

### Task 2: Temporary PDB Management
- Created a temporary PDB named `MU_to_delete_pdb_28869`.
- Verified the creation, then successfully closed and dropped it including all datafiles.

### Task 3: Oracle Enterprise Manager (OEM)
- Successfully accessed the OEM Database Express dashboard.
- Confirmed that the dashboard reflects the created PDBs and system resources.

## 4. Challenges Faced & Solutions
- **File Name Pattern Error (ORA-65005):** The initial creation command failed due to an incorrect file path. I identified the correct local path (`C:\APP\SMARTDEVICE\...`) from the error log and updated the `FILE_NAME_CONVERT` parameter.
- **OEM Login Issues:** Encountered an "Invalid Database Credentials" error. This was solved by ensuring the login was performed using the `SYSDBA` role.
