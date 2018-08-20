subscription-manager
=============================

This will configure a Red Hat Enterprise Linux 6 or 7 subscription manager.


Requirements
------------
You will need to have an active Redhat subscription.  This role supports Redhat
Customer portal


Role Variables
--------------
rhn_username
rhn_password


Dependencies
------------
None


Example Playbook
----------------
    - hosts:
        - rhel-servers
      roles:
        - rh-subscription-manager



## Author Information

This role was created in 2018 by [Michael Ventarola]

