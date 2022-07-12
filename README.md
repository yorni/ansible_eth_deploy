# Ansible playbook which deploy eth node

---

You need to setup hosts file ./production - replace PROD_HOST with your server ip or domain name.

---

`ansible-playbook -i production site.yml --limit geth_servers`
