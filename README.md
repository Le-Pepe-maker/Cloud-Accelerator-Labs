# My Lab Portfolio

This repository contains my lab work for Tasks 1 and 2, demonstrating Windows user management, NTFS permissions, and manual backup & recovery using File History.

---

## Task 1: User Management & Security Groups

**Description:**  

In this task, I created user accounts and security groups in a Windows environment to simulate professional business network management. The steps performed include:

1. **Created user accounts:**  
   - Users were created for different departments, including **Marketing** and **Finance**.  
   - Each user was given a unique username and password.

2. **Created security groups:**  
   - Two groups were set up: **Marketing Group** and **Finance Group**.  
   - Users were added to their respective groups to enforce access control.

3. **Applied NTFS permissions:**  
   - The folders for each department were restricted so that:  
     - **Marketing users** could only access the Marketing folder.  
     - **Finance users** could only access the Finance folder.  
   - Permissions were configured to prevent unauthorized access to other department folders.

4. **Tested user access:**  
   - Logged in as different users to ensure that access restrictions were correctly applied.  
   - Verified that users could access only their department folder and were denied access to other folders.

**Outcome:**  
- Successfully implemented user management and folder access restrictions using Windows administrative tools.  
- Demonstrated understanding of Active Directory concepts and NTFS permission settings.


---

## Task 2: Manual Backup & Recovery

**Description:**  

In this task, I performed a manual backup and recovery of files in a Windows environment using File History. The steps performed include:

1. **Prepared a test folder:**  
   - Created a folder `C:\Users\Lab\Critical Projects` with sample files.

2. **Backed up files:**  
   - Used File History to back up the Critical Projects folder to a shared folder (`Z:\VM_Backups`).

3. **Simulated accidental deletion:**  
   - Deleted files from the folder and emptied the Recycle Bin to simulate file loss.

4. **Restored files:**  
   - Used File History’s **Restore personal files** feature to recover deleted files to their original location.  
   - Verified that all files were restored correctly.

**Outcome:**  
- Successfully backed up, deleted, and restored files using File History.  
- Demonstrated understanding of Windows backup and recovery processes.



---

**Notes:**  
- Screenshots are stored in the `Task1Screenshots` and `Task2Screenshots` folders.  
- All tasks were performed in a VirtualBox Windows VM to ensure a safe and controlled environment.
