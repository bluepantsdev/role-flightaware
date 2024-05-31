FlightAware Ansible Role
=========

Installs FlightAware's PiAware software on a Raspberry Pi.

Requirements
------------

This role is intended to be run on a Raspberry Pi running Raspbian. It has been tested on a Raspberry Pi 3B+ running Raspbian Buster.

Role Variables
--------------

The following variables can be set to customize the installation:

flightaware_enabled: true|false|skipp

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: flightaware
      roles:
         - { role: bluepants.flightaware }

License
-------

BSD

Author Information
------------------

See [bluepants.dev](https://bluepants.dev/)
