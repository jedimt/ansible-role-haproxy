Ansible Role: HAProxy
=========

Deploy HAProxy to a VM.

Requirements
------------

Existing Ubuntu VM.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    # ===========================================================================
    # Install HAProxy on a VM
    # ===========================================================================
    - name: Install HAProxy on VM
    hosts: haproxy

    roles:
        - ansible-role-haproxy

License
-------

MIT

Author Information
------------------

Aaron Patten
aaronpatten@gmail.com
