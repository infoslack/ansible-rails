# Simple Ansible

- Requires Ansible 1.6.1 or newer
- Expects Ubuntu 12.04 LTS (64 bit)

## To use

- This ROR stack can be on a single node or multiple nodes.
The inventory file `hosts` defines the nodes in wich the stacks
should be configured.
- Copy the `hosts.example` file to `hosts` and edit the `hosts`
inventory file to include the names or URLs of the servers
you want to deploy.

Run the playbook:

      ansible-playbook -i hosts server.yml

## To setup your project

- Change the **app_name** variable located in `group_vars/all` to the name
of your application.

TODO:Write more instructions!

## Contributing

1. Fork it ( https://github.com/[my-github-username]/versioning/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

simple-ansible is released under the [MIT license](https://github.com/infoslack/simple-ansible/blob/master/LICENSE)
