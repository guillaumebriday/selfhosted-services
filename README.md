# Ansible role for my self hosted services with Docker and Traefik

This is an [Ansible](https://www.ansible.com) role to install self hosted services in [Docker](https://www.docker.com) containers with [Traefik](https://traefik.io).

## Requirements

+ Ansible >= 2.4.0.0

## Applications

This role is designed to install multiple services :

+ [Lobsters](https://github.com/lobsters/lobsters)
+ [Wekan](https://wekan.github.io/)
+ [Miniflux](https://github.com/miniflux/miniflux)
+ [Wallabag](https://wallabag.org/)

## Installing on production

Copy the hosts example file and change the values to your needs :

```bash
$ cp hosts.example hosts
```

Set your variables then run the playbook :

```bash
$ ansible-playbook -i hosts playbook.yml
```

## Contributing

Do not hesitate to contribute to the project by adapting or adding features ! Bug reports or pull requests are welcome.

## License

This project is released under the [MIT](http://opensource.org/licenses/MIT) license.
