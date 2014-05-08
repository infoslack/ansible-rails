# Simple Ansible

- Requires Ansible 1.6.1 or newer
- Expects Ubuntu 12.04 LTS (64 bit)

### Recipe for Ruby on Rails in production enviroment
-----------------------------------------------------

- This ROR stack can be on a single node or multiple nodes.
The inventory file `hosts` defines the nodes in wich the stacks
should be configured.

#### To use

- Copy the `hosts.example` file to `hosts` and edit the `hosts`
inventory file to include the names or URLs of the servers
you want to deploy.

Run the playbook:

      ansible-playbook -i hosts server.yml
