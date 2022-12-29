## Playbook Overview
This playbook creates a new user called newuser on the target systems, and adds them to the sudo group. The password for the user is encrypted using the SHA-512 algorithm and stored in the playbook.

To use this playbook, you will need to replace the hash in the password with the actual encrypted hash of the password that you want to use. You can generate the encrypted hash using the openssl or python command-line utilities.

For example, to generate the encrypted hash using openssl, you can use the following command:

```
openssl passwd -6 -salt salt password
```
This command generates an encrypted hash of the password password using the salt salt and the SHA-512 algorithm. You can then copy the generated hash and use it in the playbook.


