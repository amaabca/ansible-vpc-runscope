Role Name
=========

Download and adds systemd configuration for [runscope-radar agent](https://www.runscope.com/docs/api-testing/agent)

Requirements
------------

No requirements.

Role Variables
--------------

* agent_url: download url of runscope-radar agent.
* runscope_api_host: runscope api host
* runscope_threads: runscope threads
* runscope_timeout: runscope timeout
* runscope_disconnect_timeout: runscope disconnect timeout
* runscope_cafile: runscope cafile
* runscope_agent_path: path where the agent will reside.
* agent_conf_file_path: path where the agent configuration file will reside.

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: amaabca.ansible-vpc-runscope }

License
-------

MIT

Author Information
------------------
https://github.com/amaabca/ansible-vpc-runscope
