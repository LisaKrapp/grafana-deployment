Install-grafana
=========

This role installes and configures grafana on the host.

Role Variables
--------------

grafana-theme: theme of the UI (dark, light or system)

Example Playbook
----------------

    - hosts: servers
      roles:
         - install-grafana
