# ansible-sudo-user
Simple role to create and configure an unprivileged user to allow sudo access

Requirements
------------

* Desired unprivileged user name
* The crypted password you want to set for the user
* The desired public key you want to set for the user

Role Variables
--------------

*unprivileged_user* - Username of the unprivileged user to allow sudo execution to
*unprivileged_user_publickey* - Public key to store for the sudo user
*unprivileged_user_password* - Encrypted sudo user's password to set. See docs for details: https://docs.ansible.com/ansible/latest/reference_appendices/faq.html#how-do-i-generate-encrypted-passwords-for-the-user-module

License
-------

Public domain.

Author Information
------------------

Björn Fischer - @BjoernCFischer