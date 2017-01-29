![alt tag](http://www.telnetport25.com/wp-content/uploads/2012/03/NagiosLogo.png)


This playbook helps automatically install **Nagios Core** monitoring system

### Before you start
![](https://img.clipartfox.com/c762c6ab68fd80920b2be82288cc7e05_warning-clip-art-clipart-warning_900-800.png =18x)
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
