<!-- This file is automatically generated by "make update_todo" -->

### xsrv/xsrv

- #966 - WIP: add bash completion to the xsrv script - **`-`** `feature`
- #965 - libvirt: changing `currentMemory` in the VM XML definition does not change current RAM until VM reboot - **`-`** `bug,enhancement`
- #961 - WIP nfs-server role + ability to mount filesystems from the common role - **`1.11.0`** `feature`
- #959 - WIP: libvirt: remove libvirt_port_fowrads, define port forwards at the VM level in libvirt_vms - **`-`** `enhancement`
- #956 - WIP: monitoring_netdata: add an option to reboot automatically daily after kernel upgrades - **`1.11.0`** `easy,enhancement,feature,security`
- #953 - nextcloud: upgrade to v25.x - **`-`** `maintenance`
- #949 - loki role - **`-`** `feature`
- #943 - nextcloud: enable clean URLs by default - **`1.11.0`** `configuration,enhancement`
- #937 - DDoS mitigation mode? - **`-`** `question,security`
- #936 - jitsi: prosody: add mod-listusers? - **`-`** `easy,enhancement,question`
- #931 - jitsi: noise cancellation/suppression doesn't work - **`1.11.0`** `bug,upstream`
- #927 - jitsi: permanently disable RECENT_LIST_ENABLED - **`1.11.0`** `easy,enhancement,security,upstream`
- #925 - jitsi: setup TURN server for P2P one-to-one calls? - **`-`** `enhancement,question`
- #924 - init-vm: add ability to attach more network interfaces? - **`-`** `enhancement,question`
- #920 - xsrv: graphical user interface? - **`-`** `question`
- #915 - Snipe-IT role - **`2.0.0`** `feature`
- #912 - mount /tmp noexec? - **`-`** `question,security`
- #911 - test compatibility with librelogic.librelogic.gitlab/gitlab-runner? - **`2.0.0`** `documentation,easy,enhancement,feature`
- #910 - doc: document all options for init-vm/init-vm-template - **`2.0.0`** `documentation,easy,enhancement`
- #909 - doc: add more screencasts - **`2.0.0`** `documentation,easy,enhancement`
- #890 - apache: implement modpagespeed? - **`-`** `performance,question`
- #881 - Keycloak role? - **`-`** `feature,question`
- #870 - xsrv: allow using `xsrv show-defaults | grep some_search_term` to search/filter available configuration variables - **`2.0.0`** `enhancement`
- #868 - dovecot: document how to open a local copy of a maildir with a mail client - **`-`** `backups,documentation`
- #867 - dovecot: document/test LDAPS setup - **`-`** `documentation,enhancement,security`
- #863 - dovecot: setup netdata dovecot plugin? - **`-`** `monitoring,question`
- #862 - dovecot: enable other mail plugins? - **`-`** `question`
- #861 - dovecot: performance tweaks? - **`-`** `performance,question`
- #860 - dovecot: harden SSL configuration/ciphers? - **`-`** `question,security`
- #859 - dovecot: allow generating and using Let's Encrypt SSL/TLS certificates - **`2.0.0`** `enhancement,security`
- #858 - dovecot: setup dovecot-submissiond? - **`-`** `question`
- #857 - dovecot: setup server-side full text search? - **`-`** `question`
- #856 - dovecot: setup antispam? - **`-`** `question`
- #855 - dovecot: add autoconfig TXT record or A record + webserver vhost? - **`-`** `question,wontfix`
- #849 - autoreadme: allow adding all hosts as SFTP servers in GTK bookmarks? - **`-`** `enhancement,question`
- #848 - autoreadme: display more information? - **`-`** `enhancement,question`
- #847 - autoreadme: allow adding netdata badges automatically? - **`-`** `enhancement,question`
- #835 - monitoring_utils: lynis: suggestion[]=HOME-9306|Double check the ownership of home directories as some might be incorrect. - **`-`** `enhancement,question,security`
- #834 - monitoring_utils: lynis: suggestion[]=HOME-9304|Double check the permissions of home directories as some might be not strict enough. - **`-`** `enhancement,question,security`
- #833 - monitoring_utils: lynis: suggestion[]=FILE-7524|Consider restricting file permissions - **`-`** `easy,enhancement,question,security`
- #832 - monitoring_utils: lynis: suggestion[]=FINT-4350|Install a file integrity tool to monitor changes to critical and sensitive files - **`-`** `easy,enhancement,question,security`
- #831 - monitoring_utils: lynis: suggestion[]=TIME-3128|Check ntpq peers output for time source candidates - **`-`** `enhancement,question,security`
- #829 - monitoring_utils: lynis: suggestion[]=ACCT-9622|Enable process accounting - **`-`** `configuration,easy,enhancement,monitoring,question,security`
- #817 - monitoring_utils: lynis: suggestion[]=HTTP-6643|Install Apache modsecurity to guard webserver against web application attacks - **`-`** `enhancement,security`
- #816 - monitoring_utils: lynis: suggestion[]=FIRE-4513|Check iptables rules to see which rules are currently not used - **`-`** `enhancement,question,security`
- #811 - monitoring_utils: lynis: suggestion[]=FILE-6430|Consider disabling unused kernel modules - **`-`** `enhancement,question,security`
- #808 - monitoring_utils: lynis: suggestion[]=AUTH-9229|Check PAM configuration, add rounds if applicable and expire passwords to encrypt with new values - **`-`** `configuration,enhancement,security`
- #804 - homepage: improve layout - **`2.0.0`** `enhancement`
- #802 - apache: allow using LDAP for basic auth - **`-`** `enhancement`
- #798 - tt_rss: document LDAP over SSL/TLS + self-signed certificate setup - **`-`** `documentation,enhancement,security`
- #796 - shaarli: document LDAP over SSL/TLS + self-signed certificate setup - **`2.0.0`** `documentation,enhancement,security`
- #794 - openldap: self-service-password: allow trusting self-signed certificates - **`1.11.0`** `configuration,easy,enhancement,security`
- #789 - apache: allow configuration of arbitrary reverse proxies - **`1.11.0`** `easy,enhancement,feature`
- #782 - xsrv init-vm: don't require sudo to fix cloned disk image permissions - **`2.0.0`** `enhancement,question`
- #778 - systemd-nspawn/systemd-machined role? - **`-`** `feature,question`
- #771 - WIP: netdata: add netdata-apt module (monitor number of upgradeable packages) - **`1.11.0`** `difficult,feature,monitoring`
- #770 - graylog: document example extractors - **`-`** `documentation,enhancement,monitoring`
- #768 - add ldap-client role (LDAP PAM/SSH authentication)? - **`-`** `feature,question`
- #764 - rocketchat: lynis: warning[]=DBS-1820|MongoDB instance allows any user to access databases - **`2.0.0`** `enhancement,monitoring,question,security`
- #755 - [debops] Join forces? - **`2.0.0`** `documentation,enhancement`
- #752 - monitoring_utils: add duc disk usage analyzer? - **`-`** `feature,monitoring,question`
- #751 - monitoring_utils: add scripts to measure disk usage by type/extension/path? - **`-`** `easy,enhancement,monitoring,question`
- #750 - rocketchat: update to v4.5? - **`2.0.0`** `maintenance,wontfix`
- #734 - nextcloud: add whiteboard app? - **`-`** `enhancement,question`
- #733 - monitoring_netdata: allow whitelisting debsecan bugs - **`-`** `enhancement,monitoring,security`
- #732 - allow disabling web applications - **`-`** `configuration,easy,enhancement`
- #731 - doc: add a role template - **`-`** `documentation,enhancement`
- #728 - rss_bridge: allow configuration of whitelisted bridges - **`-`** `enhancement`
- #723 - Automate DNS scans with dnsspy.io? - **`-`** `feature,question,security`
- #722 - Allow hdparm/disk spindown time configuration? - **`-`** `feature,question`
- #721 - Browser synchronization service? - **`2.0.0`** `feature,question`
- #720 - podman role/replace docker with podman? - **`-`** `enhancement,feature,maintenance,question`
- #717 - transmission: configuration templating task always returns changed (cleartext/hashed password) - **`2.0.0`** `enhancement,maintenance,upstream`
- #715 - dnsmasq: DNS-over-HTTPS support? - **`-`** `configuration,enhancement,question,security`
- #714 - dnsmasq: DNS-based ad blocking/fitering? - **`-`** `feature,question`
- #686 - samba: announce shares over  MDNS - **`-`** `enhancement`
- #685 - apache: automate running SSLLabs scans against all virtualhosts - **`-`** `feature`
- #684 - alltube role? - **`-`** `feature,question`
- #675 - pgmetrics: write results to file on the controller - **`-`** `enhancement`
- #668 - apache: allow defining custom ErrorDocuments - **`-`** `enhancement`
- #648 - graylog: setup authentication fro mongodb - **`-`** `easy,enhancement,security`
- #642 - mumble: LDAP user backend? - **`-`** `question`
- #641 - common: implement manual reboot/shudown (utils-reboot/utils-shutdown ansible tags) - **`-`** `easy,enhancement,feature`
- #640 - common: apt: enable purging data/configuration files by default - **`-`** `configuration,enhancement`
- #639 - common: apt: enable autoremove by default - **`-`** `configuration,easy`
- #638 - common: apt: implement forced/manual apt upgrade (utils-apt-upgrade ansible tag) - **`-`** `easy,feature`
- #637 - firewalld: implement DNAT/SNAT - **`-`** `enhancement`
- #635 - firewalld: implement outbound traffic filtering - **`2.0.0`** `enhancement,security`
- #628 - limit fact gathering inside roles to ansible_local facts (speed up setup: tasks) - **`-`** `enhancement,performance`
- #627 - WIP add molecule tests - **`2.0.0`** `difficult,enhancement,maintenance,question,tools`
- #622 - tt_rss: log cron job errors to syslog instead of sending them by mail - **`-`** `configuration,easy,enhancement,monitoring`
- #616 - common: ssh: make SSH port configurable - **`-`** `enhancement`
- #614 - common: allow disabling ctrl+alt+del combination - **`-`** `enhancement,security`
- #613 - common - implement sysctl-34 - link protection settings - **`-`** `enhancement,security`
- #612 - xsrv: allow wildcards in host names for edit-host, edit-vault,check, deploy... - **`-`** `feature`
- #604 - use j2cli for init-playbook/init-host templating? - **`-`** `maintenance,question,tools`
- #598 - CI/CD: automate checks for newer upstream versions of software - **`-`** `enhancement,tools`
- #593 - tt_rss: role/permission setup tasks are not idempotent - **`-`** `enhancement`
- #589 - homepage: add buttons to download self-signed certificates - **`-`** `enhancement`
- #561 - homepage: add a "copy to clipboard" button next to input fields - **`-`** `enhancement`
- #546 - nextcloud: allow optional configuration of server-side encryption? - **`-`** `configuration,enhancement,question,security`
- #545 - doc: gitea: repo mirrorring is now possible without custom hooks - **`-`** `documentation`
- #543 - homepage: add (optional) links section with links to recommendend mobile/desktop software - **`-`** `easy,enhancement`
- #540 - tt-rss: add an option to silence feed update error reports mail - **`-`** `enhancement,monitoring`
- #535 - Add hardening measures from ANSSI guidelines - **`-`** `enhancement,security`
- #529 - proxmox backup server role? - **`-`** `backups,feature,question`
- #522 - openldap: performance optimizations? - **`-`** `enhancement,performance,question`
- #518 - Mumble web interface - **`2.0.0`** `feature`
- #517 - allow configuration of a custom MOTD? - **`-`** `feature,question`
- #514 - doc: gitea: mirroring method should not try to mirror internal/pull requests refs - **`-`** `documentation,enhancement`
- #513 - doc: screenshots slideshow on main page instead of thumbnails? - **`-`** `documentation,enhancement`
- #507 - all roles/apache: disable reverse proxy rules and redirect to maintenance page when target service is disabled in configuration - **`2.0.0`** `enhancement,monitoring`
- #506 - graylog: add TCP portchecks for mongodb/elasticsearch - **`-`** `enhancement,monitoring`
- #503 - graylog/rsyslog: authenticate clients using client certificates? - **`-`** `enhancement,monitoring,question,security`
- #500 - docker: drop all capabilities by default, manually whitelist capabilities per-service? - **`-`** `enhancement,question,security`
- #498 - firewall: add GeoIP-based blacklist/whitelist mechanism? - **`-`** `feature,question,security`
- #497 - nextcloud: allow enabling 2-factor authentication? - **`-`** `configuration,enhancement,question,security`
- #489 - doc: update screencast - **`2.0.0`** `documentation`
- #485 - monitoring: netdata: disable python.d/go.d/aclk self-monitoring charts - **`-`** `enhancement,maintenance,monitoring,performance`
- #481 - add netdata portchecks for ssh, apache, mumble, samba, openldap - **`-`** `enhancement,monitoring`
- #475 - ACME certificate authority role? - **`-`** `feature,question,security`
- #474 - Benchmark performance/load testing of web applications? - **`-`** `monitoring,performance,question`
- #473 - Docker daemon hardening/container scanner service? - **`-`** `question,security`
- #472 - Ansible AWX role? - **`-`** `feature,question`
- #470 - monitoring: lnav should not interpret ansible log messages with warn=True as warnings - **`2.0.0`** `enhancement,monitoring`
- #466 - netdata: graph lynis warnings/suggestions? - **`-`** `enhancement,monitoring,question,security`
- #465 - lynis: add detection of SUID files? - **`-`** `enhancement,monitoring,question,security,wontfix`
- #459 - add xsrv nmap subcommand (nmap scan all hosts or a specific host, output to html) - **`-`** `easy,feature`
- #457 - samba: setup dfs_samba4/acl_xattr VFS modules? - **`-`** `configuration,enhancement,question,wontfix`
- #454 - postgresql: add an option to enable pg_stat_statements view - **`1.11.0`** `enhancement,maintenance,monitoring,performance`
- #453 - postgresql: enable checksums? - **`-`** `configuration,question,wontfix`
- #451 - Document management system? - **`-`** `feature,question`
- #450 - netdata: setup ML-based anomaly detection? - **`-`** `configuration,enhancement,monitoring,question,wontfix`
- #448 - netdata: send notifications using signal-cli? - **`-`** `feature,monitoring,question`
- #447 - display local mailboxes through netdata static web server, raise alarm if there is unread mail - **`-`** `feature,monitoring`
- #445 - bookstack role? - **`2.0.0`** `feature,question`
- #441 - openldap: allow restricting application access to groups/setup MemberOf overlay - **`-`** `enhancement,security`
- #433 - docker: additional hardening/CIS guidelines - **`2.0.0`** `configuration,enhancement,security`
- #428 - gitea: document backup restoration procedure - **`-`** `backups,documentation`
- #427 - transmission: document restoring backups - **`-`** `backups,documentation`
- #426 - samba: add ability to delete a share by setting state: absent - **`-`** `enhancement`
- #425 - openldap: self-service-password/ldap-account-manager: checksum/signature download verification? - **`-`** `enhancement,security`
- #405 - xsrv: replace environment variable-based settings with options, arguments or configuration from file? - **`2.0.0`** `enhancement,maintenance`
- #402 - jellyfin: frequent [ERR] Error sending socket message from 0.0.0.0 to 239.255.255.250:1900 - **`-`** `configuration,documentation,enhancement,upstream`
- #393 - Samba: performance improvements (socket options)? - **`-`** `configuration,enhancement,performance,question,wontfix`
- #389 - WIP: add autoreadme role - **`1.11.0`** `difficult,enhancement,question`
- #384 - jellyfin: allow/document uploading files from nextcloud - **`-`** `documentation,enhancement`
- #379 - setup IPV6 support (sysctl, firewall, applications...)? - **`-`** `question`
- #378 - netdata: add a "proxied" mode (proxy behind apache/mod_proxy) ? - **`-`** `monitoring`
- #376 - netdata: enable samba monitoring when samba role is installed - **`-`** `enhancement,monitoring`
- #375 - rocketchat: set Offline_Message_Use_DeepLink to false - **`1.11.0`** `configuration,easy,enhancement,security,upstream,wontfix`
- #374 - makefile/readthedocs: include roles documentation in generated docs - **`-`** `documentation,enhancement`
- #366 - nextcloud: file locking sometimes causes synchronization errors (enable redis?) - **`1.11.0`** `configuration,performance,question`
- #364 - pulseaudio: document setting up streaming from pulseaudio server to android tablet/phone - **`-`** `documentation`
- #360 - netdata: add httpchecks on each apache virtualhost setup by other roles - **`-`** `enhancement,monitoring`
- #357 - mattermost role? - **`1.11.0`** `feature,question`
- #351 - nextcloud: enable pretty URLs - **`-`** `configuration,easy,enhancement`
- #348 - ldap-account-manager: Unable to set locale - **`-`** `bug`
- #344 - nextcloud: replace onlyoffice integration with collabora/nextcloud office? - **`-`** `feature`
- #341 - nextcloud: warning on settings/admin/overview: Some app directories are owned by a different user than the web server one - **`-`** `enhancement`
- #337 - nextcloud: maps: enable OSRM demo servers by default - **`-`** `easy,enhancement`
- #323 - prometheus role? - **`-`** `monitoring`
- #322 - Frontail role? - **`-`** `monitoring`
- #321 - ELK stack? - **`-`** `monitoring`
- #331 - apache: php-fpm: chroot php pools? - **`-`** `enhancement,security`
- #330 - netdata: monitor php-fpm - **`-`** `enhancement,monitoring`
- #328 - apache: mpm_event performance tuning? - **`-`** `enhancement,performance,question`
- #327 - nextcloud: verify gpg signatures - **`-`** `enhancement,security`
- #317 - monitoring_utils: lynis: suggestion[]=BOOT-5264|Consider hardening system services - **`2.0.0`** `enhancement,security`
- #310 - samba: ability to whitelist/blacklist files by extension - **`-`** `enhancement,security`
- #309 - apply postgresqltuner recommended settings? - **`-`** `enhancement,performance`
- #307 - apache: make certificate status endpoint enable/disable configurable - **`-`** `enhancement,monitoring`
- #290 - netdata: monitor number of upgradeable APT packages - **`2.0.0`** `feature,monitoring,security`
- #280 - Samba Directory Controller or other Identity Management solution? - **`-`** `feature,question`
- #277 - Samba: protect samba accounts from bruteforce attemps with fail2ban - **`-`** `enhancement,security`
- #276 - Samba: protect file shares from cryptolockers - **`-`** `enhancement,security`
- #275 - Samba: implement filesystem/size quotas - **`-`** `enhancement`
- #274 - Samba: advertise samba server over avahi/zeroconf? - **`-`** `configuration,enhancement`
- #272 - postgresql: hardening - **`-`** `enhancement,security`
- #271 - apache: enable mod-md status handler - **`-`** `enhancement,monitoring`
- #269 - netdata http check: support all httpcheck module options - **`-`** `enhancement,monitoring`
- #267 - apache: make disabled modules list configurable, disable more modules by default - **`-`** `enhancement,performance`
- #265 - apache: provide custom error pages - **`-`** `enhancement`
- #256 - CAS, SAML or Oauth Sigle Sign On (SSO)? - **`-`** `feature`
- #254 - apache: LDAP authentication for virtualhosts - **`-`** `enhancement,security`
- #253 - apache: allow setting up HTTP basic auth username/password for virtualhosts - **`-`** `enhancement,security`
- #237 - WIP: install and configure auditd (Linux Auditing Framework) - **`2.0.0`** `feature,monitoring,security`
- #231 - apache: letsencrypt/selfsigned: reach A+ grade on Mozilla Security Observatory - **`-`** `enhancement,security,tools`
- #230 - mysql: add a read-only user for backups - **`-`** `enhancement,security`
- #229 - apache: add a config variable to log times taken to serve requests - **`-`** `enhancement,monitoring,performance`
- #228 - apache: additional hardening measures - **`-`** `enhancement,security`
- #226 - mysql: update root password for *all* root accounts - **`-`** `enhancement,security`
- #222 - apache: add ability to specify a whitelist/blacklist of IP adresses per-virtualhost - **`-`** `feature,security`
- #221 - apache: add a simple public HTTP server/vhost option - **`2.0.0`** `enhancement`
- #219 - xsrv-homepage: main/aggregated RSS feed on the homepage - **`-`** `feature`
- #216 - xsrv: automatically generate README.md - **`2.0.0`** `enhancement`
- #212 - apache: PHP OPCache tuning? - **`-`** `performance,question`
- #208 - netdata: graph/alert on logwatch warnings - **`-`** `feature,monitoring,security`
- #205 - netdata: monitor debsums warnings/return status - **`2.0.0`** `easy,feature,monitoring,security`
- #200 - roles for other monitoring software? - **`-`** `feature,monitoring,question`
- #199 - netdata: graph number of machines on LAN? - **`-`** `feature,monitoring,security`
- #195 - monitoring: add apt-listchanges - **`-`** `enhancement,monitoring`
- #193 - netdata: graph tiger warnings - **`-`** `feature,monitoring,security`
- #192 - monitoring/apache: add goaccess, generate reports for each virtualhost - **`-`** `feature,monitoring`
- #191 - monitoring_utils: add inxi? - **`-`** `feature,monitoring,question`
- #189 - netdata: graph VULS reports - **`-`** `feature,monitoring,security`
- #187 - monitoring: setup PSAD (Port Scan Attack Detector) Edit - **`-`** `feature,security`
- #186 - netdata: many ERROR messages in logs - **`-`** `bug,monitoring,upstream`
- #184 - netdata: add Mozilla observatory module - **`-`** `feature,monitoring,security`
- #181 - netdata: monitor MySQL server - **`-`** `enhancement,monitoring`
- #180 - netdata: graph SCAP workbench warnings - **`-`** `feature,monitoring,security`
- #178 - netdata: graph/alert on deborphan matches - **`-`** `feature,monitoring`
- #176 - netdata: add Qualys SSL check module - **`-`** `feature,monitoring`
- #174 - netdata: allow setting a repetition period for alarms - **`-`** `enhancement`
- #172 - netdata: support long-term archiving - **`-`** `enhancement,monitoring`
- #171 - needrestart: add a config variable to automatically reboot when a kernel upgrade is pending - **`1.11.0`** `easy,enhancement,security`
- #170 - netdata: add support for postgresql monitoring - **`-`** `enhancement,monitoring`
- #167 - monitoring: add spectre-meltdown-checker - **`-`** `feature,monitoring,security`
- #165 - gitea: Enable search/indexing for repository/code/issues - **`1.11.0`** `documentation,easy,enhancement,performance`
- #164 - gitea: add CI/CD service - **`1.11.0`** `feature`
- #155 - nextcloud: add Fulltextsearch App + OCR - **`1.11.0`** `feature,question`
- #150 - nextcloud: add maintenance on/off switch - **`-`** `easy,enhancement`
- #149 - nextcloud: add bookmarks app? - **`-`** `enhancement,question`
- #148 - nextcloud: verify downloads with GPG signature - **`-`** `enhancement,security`
- #146 - nextcloud: add Collabora Online integration - **`-`** `feature`
- #144 - nextcloud: role is not idempotent - **`-`** `enhancement`
- #142 - nextcloud: add files automated tagging app? - **`-`** `enhancement,question`
- #141 - nextcloud: add fail2ban to documentation - **`-`** `documentation,security,tools`
- #138 - apache: rewrite all 500 502 503 errors to generic 50x.html error page - **`-`** `enhancement,security`
- #137 - apache: allow setting up HTTP Basic auth and autoindex for specific directories/URLs/virtualhosts - **`-`** `feature,security`
- #130 - tt-rss: role is not idempotent - **`-`** `enhancement`
- #127 - xsrv: add commands to check firewall/fail2ban status/active TCP/UDP connections - **`-`** `enhancement`
- #125 - common: enforce AppArmor on all services/executables - **`-`** `enhancement,security`
- #123 - common: allow management of /etc/hosts - **`-`** `feature`
- #122 - common: ssh/sftp: harden default SFTP umask - **`-`** `enhancement,security`
- #121 - common: disable sysctl configuration when running in a container? - **`-`** `enhancement,question,tools`
- #120 - common: firewalld: add a manual IP whitelist/blacklist mechanism - **`-`** `feature,security`
- #119 - monitoring_utils: lynis: suggestion[]=AUTH-9262|Install a PAM module for password strength testing like pam_cracklib or pam_passwdqc - **`-`** `configuration,enhancement,question,security`
- #118 - common: allow restricting use of 'su' to a list of approved users - **`-`** `enhancement,security`
- #117 - common: prevent forkbombs through ulimit/limits.conf - **`-`** `enhancement,security`
- #116 - common: add an option to disable known compilers? - **`-`** `enhancement,question,security`
- #115 - monitoring_utils: lynis: suggestion[]=ACCT-9628|Enable auditd to collect audit information - **`-`** `feature,security`
- #114 - common: ssh/sftp: check that SFTP users are chrooted - **`-`** `enhancement,security,tools`
- #113 - common: fail2ban: allow permaban when accessing specific/honeypot URLs - **`-`** `feature,security`
- #112 - common: firewalld: implement a TARPIT action? - **`-`** `enhancement,question,security`
- #111 - common: setup process accounting? - **`-`** `enhancement,question,security`
- #109 - common: check that locale generation works correctly - **`-`** `enhancement,tools`
- #108 - common: minimize write access to a list of files/directories? - **`-`** `enhancement,security`
- #105 - xsrv: add a global download cache dir variable? (instead of /root) - **`-`** `maintenance,question,tools`
- #103 - common: firewalld: allow limiting a rule to a single user (owner iptables module)? - **`-`** `enhancement,question,security`
- #101 - common: improve OS hardening/implement STIG/CIS - **`-`** `enhancement,security`
- #100 - common: configure timezone - **`-`** `enhancement`
- #98 - Maps and routing services - **`-`** `feature`
- #97 - openshift/openstack role? - **`-`** `question`
- #96 - grafana role? - **`-`** `feature,monitoring,question`
- #94 - Kubernetes role? - **`-`** `feature,question,wontfix`
- #93 - VNC/other remote desktop server role? - **`-`** `feature,question`
- #92 - Add {{ ansible_managed }} in templates - **`-`** `enhancement`
- #86 - Peertube role - **`-`** `feature`
- #78 - Adminer role - **`-`** `feature`
- #70 - common: ssh: allow setting up endlessh? - **`-`** `feature,question,security`
- #69 - IDS/IPS role? - **`-`** `feature,question,security`
- #66 - add show-tasks command - **`-`** `enhancement`
- #64 - RAID role - **`-`** `feature`
- #63 - pfSense role? - **`-`** `feature,question,wontfix`
- #61 - GDPR compliance? - **`-`** `feature,question`
- #59 - Collaborative pad - **`-`** `feature`
- #58 - HTTP downloader - **`-`** `feature`
- #57 - rundeck role? - **`-`** `feature,question`
- #55 - Guacamole remote control gateway role? - **`-`** `feature,question`
- #54 - bittorrent tracker role? - **`-`** `feature,question,wontfix`
- #53 - web analytics role? - **`-`** `feature,question`
- #52 - blogging engine/static site generator role? - **`-`** `feature`
- #51 - dokuwiki role? - **`2.0.0`** `feature,question`
- #49 - caching HTTP proxy/squid role? - **`-`** `feature,question`
- #46 - Printer sharing server? - **`-`** `feature,question`
- #45 - Video hosting/streaming platform - **`-`** `feature`
- #44 - jellyfin: document DLNA/UPnP usage - **`-`** `configuration,documentation,feature,question`
- #43 - OSM routing service role? - **`-`** `feature,question`
- #42 - OpenStreetMap/maps tileserver role? - **`-`** `feature,question`
- #41 - network scanner (SANE) server role? - **`-`** `feature,question`
- #40 - Search engine role? - **`-`** `feature`
- #39 - wallabag role? - **`-`** `feature`
- #37 - Replace `ntp` with `chrony`? - **`2.0.0`** `question`
- #35 - simple git server role? - **`-`** `feature,question,wontfix`
- #34 - CentOS compatibility? - **`-`** `feature,question,wontfix`
- #33 - Minecraft server role? - **`-`** `feature,question,wontfix`
- #31 - Add bash completion to xsrv script - **`-`** `enhancement`
- #30 - Gitlab role - **`-`** `feature`
- #26 - dynamic DNS updater role? - **`1.11.0`** `feature`
- #24 - DHCP/TFTP/PXE server role? - **`-`** `feature,question`
- #16 - Automated performance benchmarks - **`-`** `feature`
- #10 - xsrv init-vm: use cloud-init images? - **`-`** `feature,question`
- #9 - openvpn-server role? - **`-`** `feature,question,security`
- #5 - Matrix IM server role? - **`1.11.0`** `feature,question`
- #3 - Mail server role? - **`-`** `feature,question`
