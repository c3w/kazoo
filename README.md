Kazoo
=====

Kazoo Ansible role for Kazoo

Requirements
------------

None

Role Variables
--------------

User Variables
- erlang_cookie - The Erlang cookie used by all Kazoo components
- couch_user - The CouchDB username
- couch_password - The CouchDB password

Dependencies
------------

Roles
- kazoo-ansible.haproxy

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kazoo-ansible.kazoo, erlang_cookie: cookie, couch_user: user, couch_password: password }

License
-------

MIT

