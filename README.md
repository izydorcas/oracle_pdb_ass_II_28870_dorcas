# oracle_pdb_ass_II_28870_dorcas
assignment II PL&amp;SQL

<img width="745" height="476" alt="image" src="https://github.com/user-attachments/assets/33e4c5ea-dae2-4037-9454-578ef0fe25d6" />


## Overview of tasks
In this assignment, I created a pluggable database (PDB) with a user inside it. I also created and deleted a temporary PDB, and used Oracle Enterprise Manager to see my database.

## Oracle Environment used
I used Oracle Database 21c Express Edition (XE) on a Windows laptop. I ran commands in SQL*Plus and used EM Express in the browser.

## Explanation of each task

## Task 1: Creating My PDB and User
I created the PDB `do_pdb_28870` from the seed and opened it. Then I went inside it and created the user `dorcas_plsqlauca_28870`.

## Task 2: Creating and Deleting a Temporary PDB
I created the PDB `do_to_delete_pdb_28870` and checked that it existed. Then I closed it, deleted it with its files, and checked that it was gone.


## Task 3: Oracle Enterprise Manager
I opened EM Express at https://localhost:5500/em and logged in as SYS. The dashboard shows my PDB is open and the temporary PDB is no longer there.

## Challenges faced (if any) and how they were solved)
I got error ORA-65005 because I forgot quotes around a file path, so I added them. I also got ORA-12154 when logging in because my password had `@`, so I used `/ as sysdba` instead.

<img width="604" height="443" alt="image" src="https://github.com/user-attachments/assets/cc94edc9-1b7f-472e-b8a8-0b217f894529" />


## Integrity Statement
I did all the tasks myself on my own laptop, and all screenshots are from my own work. I used oracle documentation to help me understand some concepts, errors, and commands.

## Submission Details
Repository Link: https://github.com/izydorcas/oracle_pdb_ass_II_28870_dorcas
PDB Name Created: do_pdb_28870
Issues Encountered: Yes

 
