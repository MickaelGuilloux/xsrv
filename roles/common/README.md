common
=============

This role will install/configure a basic Debian-based server. 

- hostname
- sysctl/kernel settings: networking, swap/memory management, security
- APT package management, automatic daily security updates
- NTP date/time synchronization
- SSH server configuration/hardening
- firewall (`firehol`) and IPS (`fail2ban`)
- user accounts, resources, PAM restrictions
- (optional) creation of a user account for remote backups
- `sftponly` group: chrooted, SFTP-only accounts
- outgoing mail (through a SMTP relay)
- basic command-line utilities/diagnostic tools
- streamlining/Removal of unwanted packages

All configuration tasks are optional.

Requirements
------------

- Ansible 2.8 or higher on the controller
- basic Debian GNU/Linux 9/10 installation on host
- ansible inventory hostname resolves to the host (using DNS, /etc/hosts...)
- SSH server reachable from the controller
- user account on the host, for which you know the password, member of the `sudo` group
- the controller SSH key is authorized on this user account (`ssh-copy-id user@host`)


Configuration variables
-----------------------

See [defaults/main.yml](defaults/main.yml)


Usage
------------

 - SSH access: `ssh user@example.org`
 - SFTP access: `sftp://user@example.org` (clients: [Thunar](http://docs.xfce.org/xfce/thunar/start), [Nautilus](https://wiki.gnome.org/action/show/Apps/Nautilus), [Dolphin](https://www.kde.org/applications/system/dolphin/)), `sftp`, `rsync`, `scp`, Windows: [WinSCP](https://winscp.net/eng/index.php), PuTTY...)
- Force a power off: `ssh user@my.example.org sudo poweroff`
- Force an immediate reboot: `ssh user@my.example.org sudo reboot`
- Force purge of unused configuration files: `ssh user@my.example.org sudo aptitude -y purge ~c`
- Force rotation of system logs: `ssh user@my.example.org sudo logrotate -f /etc/logrotate.conf`
- If running in a KVM virtual machine in libvirt/virt-manager, to share a directory from the hypervisor to the VM: access VM settings in `virt-manager`. Click `Add hardware > Filesystem`, Set Mode: `Mapped`, Source path: `/path/to/the/directory/to/share` (on the hypervisor), Target path: `/exampleshareddirectory` (in the VM), then inside the VM run `sudo apt install 9mount, mount -t 9p /exampleshareddirectory /mnt/example`.
- Force upgrade of all packages `ssh user@my.example.org 'sudo apt update; sudo apt safe-upgrade'`
- Backups: nothing to backup. See the [backup](https://gitlab.com/nodiscc/ansible-xsrv-backup) role.


License
-------

[GNU GPLv3](LICENSE)

References
-----------------

- https://stdout.root.sx/links/?searchtags=debian
- https://stdout.root.sx/links/?searchtags=ssh
- https://stdout.root.sx/links/?searchtags=security
- https://stdout.root.sx/links/?searchtags=network
- https://stdout.root.sx/links/?searchtags=linux
- https://stdout.root.sx/links/?searchtags=admin