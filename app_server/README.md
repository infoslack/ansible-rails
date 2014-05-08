## App Server

- Requires Ansible 1.6.1 or newer
- Expects Ubuntu 12.04 LTS

To use, copy the `hosts.example` file to `hosts` and edit the `hosts`
inventory file to include the names or URLs of the servers you want to deploy.

Run the playbook:

        ansible-playbook -i hosts server.yml