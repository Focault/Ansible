# Ansible Configuration

To set up the configuration, run the following commands:

```bash
ansible-playbook -i hosts main.yml -K
```

To check the syntax of the playbook, run the following command:

```bash
ansible-playbook -i hosts main.yml --syntax-check
```