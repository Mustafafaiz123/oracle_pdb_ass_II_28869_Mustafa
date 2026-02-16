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

# Assignment Submission Checklist
✅ Repository Name: My repository is named exactly oracle_pdb_ass_II_28869_Mustafa.

✅ Public Access: I have verified that my GitHub repository is set to PUBLIC.

✅ Screenshots Folder: I created a folder named screenshots/ and uploaded all required evidence.

✅ Task 1 Evidence: I included a screenshot showing the successful creation of MU_pdb_28869 and its status as READ WRITE.

✅ Task 2 Evidence: I included a screenshot of the creation and successful dropping of the temporary PDB MU_to_delete_pdb_28869.

✅ Task 3 Evidence (OEM): I included the screenshot of the Oracle Enterprise Manager Dashboard showing my environment and the list of Containers.

✅ Challenges Documented: I have explained the solutions for the File Path (SMARTDEVICE) and OEM Login (SYSDBA) issues in the README.

✅ Integrity Statement: I have included the mandatory statement confirming this is my individual work.
