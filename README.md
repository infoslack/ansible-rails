# Simple Ansible

- Requires Ansible 1.6.1 or newer
- Expects Ubuntu 14.04 LTS (64 bit)

## Info

- This ROR stack can be on a single node or multiple nodes.
The inventory file `hosts` defines the nodes in wich the stacks
should be configured.

## Setup and use

      $ git clone https://github.com/infoslack/simple-ansible.git
      $ cd simple-ansible
      $ cp hosts.example hosts

- Change the **app_name** variable located in `group_vars/all` to the name of your application.
- Edit `hosts` and include the name servers `123.456.789.10` or `example.org`.
- You can change the rules or the order of execution in `server.yml`

Run the playbook:

      $ ansible-playbook -i hosts server.yml

## Contributing

1. Fork it ( https://github.com/[my-github-username]/versioning/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

simple-ansible is released under the [MIT license](https://github.com/infoslack/simple-ansible/blob/master/LICENSE)
