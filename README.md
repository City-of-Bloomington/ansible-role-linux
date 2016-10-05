City-of-Bloomington.linux
=========
Ansible role for common settings across linux servers


Dependencies
------------

- ontic.ntp - Configure the NTP service

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

    - hosts: all
      become: yes
      roles:
        - City-of-Bloomington.linux

Copying and License
-------
This material is copyright 2016 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GLP) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt

