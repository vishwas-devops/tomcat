Ansible Role for Tomcat
=========

The Apache Tomcat® software is an open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies. The Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket specifications are developed under the Java Community Process.

Requirements
------------

The requirment for jetty is:-
1. Debian and RedHat or CentOS Machine.
2. Openjdk or oracle java installed in it.
3. Python should be installed in target machine.

Role Variables
--------------

The role variable are stored in [vars](https://github.com/abhishek-ansible/tomcat/tree/master/vars) You don't have any need to pass extra vars

Dependencies
------------

There are no any futher dependency rather than [java](https://github.com/abhishek-ansible/java). You have to specify variables in [vars](https://github.com/abhishek-ansible/tomcat/tree/master/vars).

Example Playbook
----------------

The main playbook file looks like

    - hosts: tomcat
      user: root
      roles:
        - tomcat

License
-------

BSD

.
