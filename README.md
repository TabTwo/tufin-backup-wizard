# Tufin Backup Wizard
Tufin backup wizard is a solution that eases the difficulties an automated backup can create. It helps you to configure and realize the backup you desired, no matter if you are using SecureTrack or SecureChange / SecureApp.

# Prerequisites
A Tufin installation containing TufinOS with TOS (Tufin Orchestration Suite) installed is required. For remote backups make sure that the user has the required permissions to store data on a remote server.

# Quickstart
Simply download the latet copy of the backup wizard and place it on your Tufin Servers:
1. Download the latest copy
2. Place it in the following directory on your Tufin Server: **/usr/local/bin/**
3. Make sure to set the correct owner of the script: **chown root:root /usr/local/bin/backup-wizard.sh**
4. Also make sure to set the correct permissions: **chmod 750 /usr/local/bin/backup-wizard.sh**
5. **Finally:** Run the wizard and follow the instructions: **/usr/local/bin/backup-wizard.sh**

# Supported versions
The script has been verified to work with TufinOS 2.13 / 2.14 and TOS R16-4 up to R17-1.
