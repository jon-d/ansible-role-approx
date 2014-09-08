ansible-role-approx
===================

Ansible role for approx (deb packages proxy) installation and configuration

Configuration
-------------

A minimal configuration file is provided with the stable debian repositories
accessed via the http://http.debian.net/ mirror redirector.

Git submodules usage
--------------------

Install this role as a submodule :

    git submodule add https://github.com/jon-d/ansible-role-approx.git roles/approx
    git commit -a

Customisation :

    cd roles/approx
    $EDITOR files/approx.conf
    git add files/approx.conf
    git commit -m "change configuration"
    cd ../../
    git add roles/approx
    git commit -m "change approx configuration"

