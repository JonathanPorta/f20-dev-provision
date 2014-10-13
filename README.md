## Fedora 20 Provisioning via Ansible

An Ansible playbook for provisioning a Vagrant box.

This was written to be used as the provisioning playbook for [f20-dev-vagrant](https://github.com/JonathanPorta/f20-dev-vagrant).

Things this playbook does for you:

1. Ensure that your user account exists.
2. Ensure that your public key is in `authorized_keys`.
3. Ensure that your user is in the `wheel` group.
4. Ensure that members of the `wheel` group can use `sudo` without a password.
5. Ensure that the Vagrant public key is not in `authorized_keys`.
6. Ensure that the system is up-to-date.
7. Ensure that some basic build/development tools are installed.
