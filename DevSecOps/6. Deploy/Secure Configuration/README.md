# DevSec Hardening Framework (Security + DevOps)

https://dev-sec.io/

https://github.com/dev-sec

Running secure infrastructure is a difficult task. Although server hardening is a well-known topic with many guides out in the wild, it is still very cumbersome to apply and verify secure configuration. If you manage many server, they need to be configured properly and maintained, which is difficult and time-consuming to get right. To answer these needs for security, compliance, and maintainability, we decided to launch this project as a common ground for requirements and their fulfillment.

# Base-Secure

https://github.com/philcryer/base-secure

Base-secure uses Ansible to automate the hardening of the Linux OS, and its SSH configuration using code from the **DevSec Hardening Framework**, which maintains a set of open source templates originally developed at Deutsche Telekom. The goal of that project is to cover most of the required hardening checks based on multiple standards; including Ubuntu Security Features, NSA Guide to Secure Configuration, ArchLinux System Hardening and others. After that it does a full system upgrade, using the thorian93.ansible-role-upgrade Ansible playbook, which verifies the host is running the latest kernel and that all software is up to date. I highly recommend this be run against a fresh Linux host, then reboot, and use that as your new base for new servers; be it a virtual machine, an Amazon Machine Image (AMI), or bare metal.

# Hardening Script Tutorial

https://fak3r.com/2021/06/18/secure-linux-servers-by-default/

# The Essentials: Cybersecurity in an Enterprise

https://web.archive.org/web/20230327012734/https://bitvijays.github.io/LFF-ESS-P0A-CyberSecurityEnterprise.html

# Infrastructure PenTest Series: Part 6 - **Configuration Review**

https://web.archive.org/web/20230519133929/https://bitvijays.github.io/LFF-IPS-P6-ConfigurationReview.html