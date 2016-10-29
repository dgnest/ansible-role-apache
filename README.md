# Ansible Role Apache

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-apache.svg)](https://travis-ci.org/dgnest/ansible-role-apache)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-apache.svg)](https://github.com/dgnest/ansible-role-apache/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


This Ansible Role infuses antigravity, you are warned

Install it with the following command:

```bash
$ ansible-galaxy install dgnest.apache

```
Requirements
------------

None



## Role Variables

Here is the list of all variables and their default values:

```yaml
    ---
    # defaults file for dgnest.apache
    apache_domain: ''

    apache_venv_port: 80
    apache_venv_server_admin: ''
    apache_venv_server_name: ''
    apache_venv_server_alias: ''

    apache_venv_documentroot: ''

    apache_env:
      APPLICATION_ENV: local

    apache_modules:
      - rewrite

```


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
    - hosts: servers
      roles:
        - dgnest.apache
```


## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]

---

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
[link-contributors]: contributors
[link-company]: https://github.com/dgnest