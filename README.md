# Linux-Permissions
This project demonstrates the management and auditing of file and directory permissions in a Linux environment. The goal was to identify files with misconfigured permissions, adjust them according to security best practices, and restrict unauthorized access to sensitive directories.
## Screenshots

### Checking file and directory details
![screenshots/cd ls -l.png](https://github.com/Dai05/Linux-Permissions/blob/822c832fb58f48c01b95754fbc1adf57030c77c2/screenshots/cd%20ls%20-l.png)

This screenshot shows the use of the `ls -l` command inside the *projects* directory.  
It lists the existing file and directory permissions, which were later analyzed to detect insecure configurations.

### 2. Restricting group permissions on project_m.txt
![screenshots/Chmod g.png](https://github.com/Dai05/Linux-Permissions/blob/main/screenshots/Chmod%20g.png?raw=true)

Here the command `chmod g-r project_m.txt` was used to remove **read access** from the group for `project_m.txt`.  
This ensures that the file cannot be read by group members, reducing the risk of unauthorized access.
