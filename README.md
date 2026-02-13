# Oracle Pluggable Database Management – Assignment II

## Student Information
- Name: Leonce iradukunda
- Student ID: 28296
- Course: Database Development with PL/SQL (INSY 8311)
- teacher: Eric Maniraguha

---

##  Assignment Objective

This assignment demonstrates practical understanding of Oracle Multitenant Architecture through:

- Creation of a Pluggable Database (PDB)
- User creation and management inside a PDB
- Creation and deletion of a temporary PDB
- Usage of Oracle Enterprise Manager (OEM)
- Professional technical documentation

---

##  Oracle Environment

- Database Version: Oracle 21c Express Edition (21.3.0.0.0)
- Platform: Windows 64-bit
- Architecture: Multitenant (CDB + PDB)

Container Database (CDB):
- XE

Pluggable Databases (PDBs):
- XEPDB1
- LE_PDB_28296

---

#  Task 1 – Create a New Pluggable Database

PDB Name:
LE_PDB_28296

User Created Inside the PDB:
LEONCE_PLSQLAUCA_28296

Steps Performed:
- Connected as SYSDBA
- Created the PDB using correct naming convention
- Opened the PDB
- Created user inside the PDB
- Granted CONNECT and RESOURCE roles
- Set tablespace quota

Evidence:
Screenshots provided in the screenshots folder.

---

#  Task 2 – Create and Delete a Temporary PDB

Temporary PDB Name:
LE_TO_DELETE_PDB_28296

Steps Performed:
1. Created the temporary PDB
2. Verified existence using SHOW PDBS
3. Closed the PDB
4. Dropped the PDB including datafiles
5. Verified deletion

Evidence:
Screenshots included in screenshots folder.

---

#  Task 3 – Oracle Enterprise Manager (OEM)

OEM Accessed via:
https://localhost:5500/em

Verification:
- Oracle 21c XE dashboard accessible
- Performance Hub visible
- Database status confirmed operational

Evidence:
OEM dashboard screenshot included.

---

#  Challenges Encountered

- ORA-00922: Missing or invalid option due to password formatting.
- Tablespace USERS not existing in XE environment.
- Limited container switching in EM Express.

Solutions:
- Used double quotes for password containing special characters.
- Assigned quota on SYSTEM tablespace.
- Verified PDB and user configuration via SQL*Plus.

---

#  Integrity Statement

I confirm that this work was performed individually in accordance with academic integrity guidelines. All commands were executed and documented from my own Oracle environment.



