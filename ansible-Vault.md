Ansible Vault
-----------------------------------------------------------------------
 Ansible Vault is feature of ansible that allows you to keep sensitive data such 
 as passwords or keys in encrypted files, rather than as plaintext in playbooks or roles.

ansible-vault
create: to create ansible vault file in the encrypted format
view: to view data of encrypted file
edit: to edit encrypted file
encrypt:  to encrypt, an unencrypted file
decrypt: to ddecrypt an encrypted file

   **--ask-vault-pass**: to provide password while  running playbook
   **--vault-password-file**: to pass a vault password through a file.
