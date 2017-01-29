![alt tag](http://www.telnetport25.com/wp-content/uploads/2012/03/NagiosLogo.png)


This playbook helps automatically install **Nagios Core** monitoring system

### Before you start
<img src="http://icons.veryicon.com/ico/System/100%20Flat/warning.ico" height="20px" width="20px">
Install package `libselinux-python`, for CentOS run
```
yum install libselinux-python
```

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
