# Individual Assignment II: Oracle Pluggable Database (PDB) Administration
* **Course Title:** Database Programming (C11665-DPR400210)
* **University:** University of Lay Adventists of Kigali (UNILAK)
* **Student Name:** Mohamed Siddiq Yassein Ayad
* **Student ID / Registration No:** 31189/2025

---

## 1. Assignment Overview
The objective of this assignment is to develop practical database administration skills through hands-on implementation of Oracle Multitenant Architecture and Pluggable Database (PDB) management.

## 2. Oracle Environment
* **Oracle Database Version:** Oracle Database 21c Express Edition Release 21.0.0.0.0 - Production.
* **Operating System:** Microsoft Windows 10 Pro.
* **Tools Used:** SQL*Plus Client Command Line Interface (CLI) and Oracle Enterprise Manager (OEM).

## 3. Task Documentation
* **PDB & User Creation:** Created a personal pluggable database named `mo_pdb_31189_2025` and established a local user `mohamed_plsqlauca_31189_2025` with proper administrative privileges.
* **Temporary PDB Management:** Demonstrated creating and completely dropping a temporary PDB (`mo_to_delete_pdb_31189_2025`) using administrative commands.
* **OEM Access:** Successfully configured and accessed the Oracle Enterprise Manager dashboard via localhost to monitor database instances.

## 4. Challenges and Solutions
* **Issue 1 (ORA-12154):** Occurred when trying to connect using short service names before configuring local network files. Resolved by utilizing the explicit EZConnect syntax.
* **Issue 2 (ORA-01017 & ORA-65016):** Triggered by incorrect container context during user login and missing file conversion paths. Solved by adjusting `db_create_file_dest` and logging into the correct PDB using the full network link: `sqlplus mohamed_plsqlauca_31189_2025/Mohamed123@//localhost:1521/MO_PDB_31189_2025`.

## 5. Lessons Learned
* Mastered navigating between CDB$ROOT and Pluggable Databases.
* Acquired real-world troubleshooting skills for common Oracle network connectivity errors.

## 6. Integrity Statement
"I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged."
