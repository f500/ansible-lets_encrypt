## lets_encrypt
Works as an addition to [geerlingguy's certbot](https://github.com/geerlingguy/ansible-role-certbot) role.

### Requirements
This role is tailored for Debian Wheezy / Jessie / Stretch and Nginx.
The role `geerlingguy.certbot` must be installed.

### Role Variables

    server_templates: []
    #- name: example_short_name
    #  http_conf: "http.conf.j2"
    #  https_conf: "https.conf.j2"
    #  index: app.php
    #  web_root: "/your/path/here"
    #  domains:
    #    - "example.com"

### Dependencies
- [geerlingguy's certbot](https://github.com/geerlingguy/ansible-role-certbot)
- Debian Wheezy, Jessie or Stretch
- Nginx

### License

Copyright (C) 2017 Future500 B.V.

[LGPL-3.0](https://github.com/f500/ansible-lets_encrypt/blob/master/COPYING.LESSER)

