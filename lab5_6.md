
# Experiment 7 & 8: Managing Directory Permissions and Changing Default Umask

## Objective
Learn to create directories, set permissions using symbolic and octal methods, and change the default `umask` value.

## Steps

### *1. Create the `/home/consultants` Directory*
Use the `mkdir` command to create the directory:
```bash
sudo mkdir /home/consultants
```

### *2. Add Write Permission to the `consultants` Group*
Use the symbolic method to grant write permission to the `consultants` group:
```bash
sudo chmod g+w /home/consultants
```

### *3. Forbid Others from Accessing the Directory*
Use the octal method to revoke all permissions for others:
```bash
sudo chmod o=--- /home/consultants
```

### *4. Change the Default `umask` for the `operator1` User*
Switch to the `operator1` user:
```bash
sudo su - operator1
```
Edit the `.bashrc` file to modify the `umask` value:
```bash
nano ~/.bashrc
```
Add the following line at the end of the file:
```bash
umask 007
```

### *5. Verify the Umask Change*
Reload the `.bashrc` file to apply the changes:
```bash
source ~/.bashrc
```
Check the `umask` value:
```bash
umask
```

## Conclusion
Successfully created the `/home/consultants` directory, modified permissions using both symbolic and octal methods, and changed the default `umask` for the `operator1` user.

## Screenshots
![Screenshot 2025-03-19 134014](https://github.com/user-attachments/assets/12250ab8-1aa3-4b10-bc9f-af2dc30425dd)

![Screenshot 2025-03-19 134027](https://github.com/user-attachments/assets/1ba3a1ce-fc78-4dfc-851f-b10e39b8e3ad)
