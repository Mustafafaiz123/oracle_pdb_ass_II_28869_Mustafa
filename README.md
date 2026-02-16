# oracle_pdb_ass_II_28869_Mustafa
**Create a New Pluggable Database**

## 1. Overview
This repository contains the documentation and evidence for Individual Assignment II, focused on managing Oracle Pluggable Databases (PDBs) and configuring Oracle Enterprise Manager (OEM).

![WhatsApp Image 2026-02-16 at 9 11 51 AM](https://github.com/user-attachments/assets/b713b261-ca0e-4c72-a19f-617d0d4e65be)

**2.Open the PDB and Verify State:**
<img width="926" height="398" alt="image" src="https://github.com/user-attachments/assets/795baba5-4a33-4c7a-96b9-24d77101791e" />

**Grant Permissions to the User:**
![WhatsApp Image 2026-02-16 at 9 17 00 AM](https://github.com/user-attachments/assets/2c78714f-81e5-4b9d-a857-e19a598736c2)

# Task 2: Create and Delete a Temporary PDB
<img width="916" height="554" alt="image" src="https://github.com/user-attachments/assets/cf37170e-bb7e-4245-95b8-b5b884013bff" />

**Verify and then Delete:**
<img width="936" height="948" alt="image" src="https://github.com/user-attachments/assets/d1bd4938-45fa-414c-9a16-c343590aa407" />

# Task 3: Oracle Enterprise Manager (OEM)
<img width="1860" height="952" alt="image" src="https://github.com/user-attachments/assets/5309bc52-a635-45eb-a126-f76859c0665f" />

## Challenges Faced and Solutions
- **File Path Mismatch (ORA-65005):** The initial script failed because the file path didn't match the local system. I solved this by identifying the correct path (`C:\APP\SMARTDEVICE\...`) provided in the error message.
- **Login Issues:** Encountered "Invalid Database Credentials" in OEM. Solved by ensuring the login was executed with the **SYSDBA** role.
