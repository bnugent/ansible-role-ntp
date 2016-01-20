Role Name
=========

This role installs and configures NTP client and server on Ubuntu.


Role Variables
--------------

* `ntp_client_pkg_name` - Name of the NTP client package
* `ntp_client_pkg_state` - NTP client package state
* `ntp_client_config_servers` - List of NTP servers
* `ntp_client_service_name` - NTP client service name
* `ntp_client_service_enabled` - Enable or disable NTP client service on boot
* `ntp_client_service_state` - NTP client service state

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - ntp

License
-------

MIT

Author Information
------------------

Role created by Ben Nugent.
