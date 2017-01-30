![alt tag](http://www.telnetport25.com/wp-content/uploads/2012/03/NagiosLogo.png)


This playbook helps automatically install **Nagios Core** monitoring system

### Apply playbook to Ansible
* Add hosts to `/etc/ansible/hosts` for example:
```
[nagios]
192.168.10.10
192.168.10.20
```

* Into the `/path/to/roles/tasks/` do:
```
ansible-playbook main.yuml
```
