# Using nginx playbook with roles

This playbook consists of two roles: `nginx-install` and `nginx-virthosts`.

## Role nginx-install

This role is used for installing nginx with own config file, which placed in template `nginx.conf.j2`. This role I'll be use when I need to install and configure nginx with some common parameters.

## Role nginx-virthosts

This role is used for adding and configuring nginx virtual hosts with own config files, which placed in template `virt_hosts.conf.j2`. This role I'll be use when I need to configure new virtual hosts to installed nginx.

## Playbook

For using this playbook you have to define all variables in `nginx.yml` file.
