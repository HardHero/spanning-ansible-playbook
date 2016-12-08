Spanning-Apache
=========

This sets up apache with a simple http virtual host

Requirements
------------

Ubuntu 14.04

Variables
--------------

spanning_host_root: the vhost root
starter_name: the owner

Dependencies
------------

geerlingguy.apache

Example Playbook
----------------

To run:
1. Update the `hosts` file with 2 other servers
2. Run the following:
        ansible-playbook tasks/main.yml -i hosts
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
