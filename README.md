Role Name
=========

Creates a systemd service to run the Prometheus statsd-exporter as a Docker container.

Requirements
------------

Docker, docker-py, and  systemd

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

TODO: Add Docker deps

Example Playbook
----------------

    - name: Prometheus statsd-exporter
      hosts: monitor
      become: yes
      roles:
        - { role: lmickh.statsd-exporter }
      tags:
        - statsd-exporter

License
-------

MIT
