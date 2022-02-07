# ansible-tutorial

## Description

This repository is used for ansible tutorial based on [this youtube playlist](https://www.youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70)

## Steps to reproduce

1. Change managed resource IP in inventory file
2. Run bootstrap.yml

   ```
   ansible-playbook --ask-become-pass bootstrap.yml
   ```

3. Add remote_user in ansible.cfg
4. run site.yml
   ```
   ansible-playbook site.yml
   ```
   sudoer file and remote_user are used so that password is not needed when running playbook
