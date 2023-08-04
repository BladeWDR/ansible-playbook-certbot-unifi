#### Ansible playbook for getting certificates set up on a Unifi controller.

Using the [geerlingguy.certbot](https://github.com/geerlingguy/ansible-role-certbot) ansible role and [Steve Jenkin's](https://www.stevejenkins.com/blog/2016/06/use-existing-ssl-certificate-linux-unifi-controller/) Unifi SSL script.

Usage:

1. Run `ansible-galaxy install -r requirements.yml`
2. add variables specific to your installation.
3. run the playbook.
