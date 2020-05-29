This playbook is to add the service account "svc_1900" for BMC discovery access to linux servers for inventory purposes.
- Copies users.allow and sudoers files for backup purposes (requested by management). 
- Appends users.allow with the service account.
- Updates /etc/sudoers file with the commands the service account is allowed to run for inventory purposes.

Paths and account names have been changed to protect customer data.