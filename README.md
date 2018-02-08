Sample ansible playbook that launches heat orchestration templates
=========

This playbook allows you to choose either a standalone or cluster VE launch.

Source your OpenStack RC file before running the playbook.

Set -e deployment to 'standalone' or 'cluster'
Set -e status to 'absent' to delete the instance.


Usage
------------
`cd f5-hot-ansible`
`ansible-playbook main.yaml -e standalone`


Requirements
------------
- /etc/ansible/hosts should exist
- tested with default ansible configs
- openstackrc file must include password value
- corresponding environment file(s) must exist

Role Variables
--------------


Dependencies
------------

shade 1.8 or higher
heat-client 1.4 or higher (otherwise, there is an error with client manager)

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
