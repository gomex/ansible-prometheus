Role Name
=========

Install and config Prometheus, Alermanager and Grafana.

Requirements
------------

 - Docker

Role Variables
--------------

 - monitor_targets
 - alertmanager_api_url
 - 

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    -  hosts: prometheus
       become: yes
       vars:
         monitor_targets:
           - name: hostname
             env: production
             location: SAO
             role: kafka

License
-------

GPL

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
