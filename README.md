# ansible-centos
Ansible Playbook for centos server security hardening

This script configures SSH to be more secure (disabling root login, requiring key-based authentication, and allowing a custom SSH port to be set)

* security_sudoers_passwordless: [ ]
* security_sudoers_passworded: [ ]

A list of users who should be added to the sudoers file so they can run any command as root (via sudo) either without a password or requiring a password for each command, respectively.
