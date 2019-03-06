Role Name
=========

An Ansible role for generating selfsigned ssl certificate for a web site

Requirements
------------

N/A

Role Variables
--------------

Require: `site_name`, default to `example.com`
Optional:
- `cert_dir`: directory for certificates, default to `/etc/ssl/certs/`
- `prikey_dir`: directory for private key, default to `/etc/ssl/private/`
- `csr_dir`: directory for certificate signing request, default to `/etc/ssl/csr`

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: selfsigned-ssl, site_name: "example.com" }

License
-------

MIT

Author Information
------------------

github.com/nguyendv
