Oracle Pluggable Database (PDB) Assignment II 

 Task 1 :Created a new Pluggable Database named BE_PDB_28806.
 Task 2 :Managed and verified PDB deletion or state procedures.
 Task 3 :Accessed Oracle Enterprise Manager (OEM) Express and verified the PDB environment dashboard.
Task 4: Compiled documentation and published this report on GitHub.

 Oracle Environment Used 
Database Edition:

 Oracle Database Express Edition (XE) 21c
 Platform:  Windows Subsystem for Linux / Windows x86_64
Container Architecture : 

  CDB (Container Database) with PDB architecture

 Explanation of Each Task 

 PDB Creation : Executed the SQL command to create a secure pluggable database (BE_PDB_28806) with default parameters and storage options.
 PDB State Management:

 Verified database connectivity and status using administrative credentials (SYS/SYSTEM) via SQL*Plus and OEM.

 OEM Verification :

 Logged into Oracle Enterprise Manager Express on port 5500 to inspect the container health and tablespace storage allocation.

 Challenges Faced 


Container Context:

 Navigated from the root CDB container directly into the custom PDB container (XE / BE_PDB_28806) to properly display the active tablespaces and metrics for verification.

 Integrity Statement 


I confirm that this assignment is my own work and was completed in accordance with the course guidelines and academic integrity policies.

 Required Submission Details Block

 Repository Link: https://github.com/benie1234/oracle_pdb_ass_II_28806_benie
* PDB Name Created: BE_PDB_28806
* Issues Encountered: Yes
