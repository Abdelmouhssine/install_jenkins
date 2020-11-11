<h2>Installation of Jenkins via Ansible On Centos7</h2>
=========================================================

This role is used to install jenkins, the an open source automation server which enables developers around the world to reliably build, test, and deploy their software.<br>
This YAML script is installed via ansible and tested on Centos7 machines.

<h2>Requirements</h2>
-------------------

There is no really requirement needed for install Jenkins, just run the playbook and everything will be installed correctly. <br>
Ansible Version should be >= 2.7


<h2>Example Playbook</h2>
---------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      become: yes
	  become_method: sudo
	  gather_facts: false

      roles:
         - install_jenkins

<h2>License</h2>
------------------

BSD <br>
GPL3

<h2>Author Information</h2>
------------------

Author : HOUARI ABDELMOUHSSINE <br>
EMAIL : houariabdelmouhssine@gmail.com<br>
LINKEDIN: www.linkedin.com/in/abdelmouhssine-houari<br>
FACEBOOK : https://www.facebook.com/Houari.Mouhssine/