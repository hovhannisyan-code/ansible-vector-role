Vector
=========

An Ansible role that installs and configures Vector, a high-performance observability data pipeline.


Role Variables
--------------

vector_version_rpm: The version of Vector to install via RPM (default: "0.21.1")
vector_version_deb: The version of Vector to install via DEB (default: "0.32.1")
vector_config_dir: The directory where Vector configuration files will be stored (default: "{{ ansible_user_dir }}/vector_config")


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Gor Hovhannisyan
