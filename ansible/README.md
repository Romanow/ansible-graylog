# MongoDB / ElasticSearch / Graylog playbook configuration

1. Add vault password to `.vault_pass`.
2. Run command:
```bash
ansible-playbook -i inventories/static.yml --vault-password-file=.vault_pass logging.yml
```