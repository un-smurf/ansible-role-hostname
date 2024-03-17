# Ansible Role: Hostname

[![ansible-lint](https://github.com/un-smurf/ansible-role-hostname/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/un-smurf/ansible-role-hostname/actions/workflows/ansible-lint.yml)
![GitHub release (latest by date)](https://img.shields.io/github/v/tag/un-smurf/ansible-role-hostname?color=yellow)
[![License: MIT](https://img.shields.io/badge/License-MIT-blueviolet.svg)](https://opensource.org/licenses/MIT)

Set the Hostname

## Requirements

No special requirements 

## Dependencies

None.

## Example Playbook

    - hosts: servers
	
	vars_files:
    - vars/main.yml
	
      roles:
        - un-smurf.hostname


Inside `vars/main.yml`:


	hostname_hostname: "server1.example.com"


## License

MIT

## Author Information

This role was created in 2024 by un-smurf.
