# docker-mysql-to-pg-migrator-ansible
A kubernetes-compliant playbook (and role) for execution
of the migrator container. This is used to migrate MySQL data
into a PostgreSQL database where the namespace is expected to
contain a 'database' secret.

## Preparation
You'll need a Python environment where you need to install the project
requirements (for Python and Ansible): -

    $ conda activate docker-mysql-to-pg-migrator-ansible
    $ pip install -r requirements.txt

---
