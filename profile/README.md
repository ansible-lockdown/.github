# Welcome to Ansible Lockdown

![Org Stars](https://img.shields.io/github/stars/ansible-lockdown?label=Org%20Stars&style=social)
![Lockdown_followers](https://img.shields.io/github/followers/ansible-lockdown?style=social)
![Discord_active](https://img.shields.io/discord/925818806838919229?logo=discord)

|<div style="width:400px"></div>Part of the [Lockdown Suite] by|
| :---: |
|<a href="https://mindpointgroup.com#GH_LockdownReadMe" target="_blank"><img src="https://assets-global.website-files.com/601959b76833363126385b0d/60195aa15ed9274f67255f9b_MPG-logo-mono-blue.svg" width="200" height="75" alt="MindPoint Group"/></a>|

## Based upon the following products

| Remediation Roles | Audit Profiles |
|:----: | :----:|
|[<img src="images/ansible.png" width="150" height="77" alt="Ansible by RedHat" />](https://www.ansible.com)|[<img src="images/github-mark.png" width="150" height="150" alt="Github hosted goss" />](https://goss.rocks)|
|<h2>[Ansible]</h2>by RedHat <br>|<h2>[Goss]</h2>Go Server Spec<br>|

## What is it?

Based upon industry recognized benchmarks and best practices, using leading products to enable highly adjustable configurations to bring your systems/platforms into security compliance.

- Open Source (MIT licensed)
  - Community supported as standard
  - Enterprise support available
- Configuration-as-code
  - Assist in bringing your systems/platform into compliance through the use of [Ansible]
  - Audit your current system/platform using [Goss]
- Highly configurable to work with your systems

## Content

|CIS| DISA-STIG |
|:--|:--:|
|[<img src="https://opscompass.com/wp-content/uploads/center-for-internet-security-logo.png" width="200" height="75" alt="CIS" />](https://www.cisecurity.org)|[<img src="https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,w_1440,h_528/https://assets.ubuntu.com/v1/ef01809f-DISA-logo-transparent.png" width="100" height="100" alt="Disa STIG" />](https://public.cyber.mil/stigs/)|
|[CIS Repos](#cis)|[STIG Repos](#stig)|

---

## Looking for support?

- [Enterprise Support]
- [Documentation]

## Useful Links

- Ansible Lockdown
  - [Ansible Galaxy]
  - [Discord Community Discussions]
  - [Videos]
  - [Full Repository list]
  - [G2 reviews]
  - [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/AnsibleLockdown.svg?style=social&label=Follow%20%40AnsibleLockdown)](https://twitter.com/AnsibleLockdown)

- MindPoint Group and other services:

  - [MindPoint Group]
  - [![Linkedin Url](images/LinkedIn-Blue.png)](https://www.linkedin.com/company/mindpoint-group-llc/)
  - [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/MindPointGroup.svg?style=social&label=Follow%20%40MindPointGroup)](https://twitter.com/MindPointGroup)

## Repositories

### CIS

---

|Links|
|---|
|[CIS-Linux](#cis-linux)|
|[CIS-Windows](#cis-windows)|
|[CIS-Platform](#cis-platform)|
|[CIS-Applications](#cis-applications)|

---

#### CIS-Linux

---

|OS|Remediate|Audit|
|--|--|--|
|Amazon2|[Amazon2-CIS]|[Amazon2-CIS-Audit]|
|Amazon2023|[Amazon2023-CIS]|[Amazon2023-CIS-Audit]|
|DEBIAN11|[DEBIAN11-CIS]|[DEBIAN11-CIS-Audit]|
|DEBIAN12|![Static Badge][Subscribers]|![Static Badge][Subscribers]|
|RHEL7|[RHEL7-CIS]|[RHEL7-CIS-Audit]|
|RHEL8|[RHEL8-CIS]|[RHEL8-CIS-Audit]|
|RHEL9|[RHEL9-CIS]|[RHEL9-CIS-Audit]|
|UBUNTU18|[UBUNTU18-CIS]|[UBUNTU18-CIS-Audit]|
|UBUNTU20|[UBUNTU20-CIS]|[UBUNTU20-CIS-Audit]|
|UBUNTU22|[UBUNTU22-CIS]|[UBUNTU22-CIS-Audit]|
|UBUNTU24|![Static Badge][Subscribers]|![Static Badge][Subscribers]|

#### CIS-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-10|[Windows-10-CIS]|![Static Badge][Coming Soon]|
|Windows-11|[Windows-11-CIS]|![Static Badge][Coming Soon]|
|Windows-2016|[Windows-2016-CIS]|[Windows-2016-CIS-Audit]|
|Windows-2019|[Windows-2019-CIS]|[Windows-2019-CIS-Audit]|
|Windows-2022|[Windows-2022-CIS]|![Static Badge][Coming Soon]|

#### CIS-Platform

---

|OS|Remediate|Audit|
|--|--|--|
|[Cisco-IOS-L2S]|[Cisco-IOS-L2S]|N/A|
|[AWS-Foundations]|[AWS-Foundations]|N/A|
|[Azure-CIS]|[Azure-CIS]|N/A|

#### CIS-Applications

---

|Application|Remediate|Audit|
|--|--|--|
|Apache-2.4|[Apache-2.4-CIS]|N/A|
|Postgres-12|[Postgres-12-CIS]|N/A|
|Kubernetes1.6.1|[Kubernetes1.6.1-CIS]|N/A|

---

### STIG

---

|Links|
|---|
|[STIG-Linux](#stig-linux)|
|[STIG-Windows](#stig-windows)|
|[STIG-Applications](#stig-applications)|
|[STIG-Archived](#stig-archived)|

---

#### STIG-Linux

---

|OS|Remediate|Audit|
|--|--|--|
|RHEL7|[RHEL7-STIG]|[RHEL7-STIG-Audit]|
|RHEL8|[RHEL8-STIG]|[RHEL8-STIG-Audit]|
|RHEL9|[RHEL9-STIG]|[RHEL9-STIG-Audit]|
|UBUNTU18|[UBUNTU18-STIG]|[UBUNTU18-STIG-Audit]|
|UBUNTU20|[UBUNTU20-STIG]|![Static Badge][Coming Soon]|
|UBUNTU22|![Static Badge][Subscribers]|![Static Badge][Subscribers]|

#### STIG-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-10|[Windows-10-STIG]|N/A|
|Windows-2016|[Windows-2016-STIG]|N/A|
|Windows-2019|[Windows-2019-STIG]|N/A|
|Windows-2022|[Windows-2022-STIG]|N/A|

#### STIG-Applications

---

|Application|Remediate|Audit|
|--|--|--|
|Apache-2.4-STIG|[Apache-2.4-STIG]|N/A|
|Cisco-IOS-L2S|[Cisco-IOS-L2S-STIG]|N/A|
|Windows-Advanced-Firewall|[WinFWADV-STIG]|[WinFWADV-STIG-Audit]|
|KUBERNETES-STIG|[KUBERNETES-STIG]|N/A|

#### STIG-Archived

---

|OS|
|--|
|[RHEL5-STIG]|
|[RHEL6-STIG]|
|[Windows-2008R2-Member-Server-STIG]|
|[Windows-2012-Member-Server-STIG]|
|[Windows-2012-Domain-Controller-STIG]|

|Application|
|--|
|[Postgres-9-STIG]|

<!---
Following entries used for consistent links across the document
--->
[Ansible]: https://www.ansible.com
[Ansible Galaxy]: https://galaxy.ansible.com/MindPointGroup
<!---
[CIS - Centre for Internet Security]: https://www.cisecurity.org
[DISA STIG]: https://public.cyber.mil/stigs
--->
[G2 reviews]: https://www.g2.com/products/ansible-lockdown/reviews
[GOSS]: https://goss.rocks
[MindPoint Group]: https://mindpointgroup.com/cybersecurity-consulting/automate/baseline-modernization#GH_LockdownReadMe
[Discord Community Discussions]: https://www.lockdownenterprise.com/discord
[Enterprise Support]: https://lockdownenterprise.com
[Lockdown Suite]: https://lockdownenterprise.com#GH_LockdownReadMe
[Documentation]: https://ansible-lockdown.readthedocs.io/en/latest/
[Full Repository list]: https://github.com/orgs/ansible-lockdown/repositories
[Videos]: https://www.youtube.com/watch?v=8aCSHD_pYbY&list=PLKpw0im6um14iqGuIS896rUWMOycdDYrv
[In Development]: https://img.shields.io/badge/In%20Development-0000FF?logo=ansible&labelColor=0000FF
[Coming Soon]: https://img.shields.io/badge/Coming%20Soon-0000FF?logo=ansible&labelColor=0000FF
[Subscribers]: https://img.shields.io/badge/Subscribers%20Only-0000FF?logo=ansible&labelColor=0000FF

<!---
CIS Repo links
--->

[Amazon2-CIS]: https://github.com/ansible-lockdown/AMAZON2-CIS
[Amazon2-CIS-Audit]: https://github.com/ansible-lockdown/AMAZON2-CIS-Audit
[Amazon2023-CIS]: https://github.com/ansible-lockdown/AMAZON2023-CIS
[Amazon2023-CIS-Audit]: https://github.com/ansible-lockdown/AMAZON2023-CIS-Audit
[DEBIAN11-CIS]: https://github.com/ansible-lockdown/DEBIAN11-CIS
[DEBIAN11-CIS-Audit]: https://github.com/ansible-lockdown/DEBIAN11-CIS-Audit
[DEBIAN12-CIS]: https://github.com/ansible-lockdown/DEBIAN12-CIS
[DEBIAN12-CIS-Audit]: https://github.com/ansible-lockdown/DEBIAN12-CIS-Audit
[RHEL7-CIS]: https://github.com/ansible-lockdown/RHEL7-CIS
[RHEL7-CIS-Audit]: https://github.com/ansible-lockdown/RHEL7-CIS-Audit
[RHEL8-CIS]: https://github.com/ansible-lockdown/RHEL8-CIS
[RHEL8-CIS-Audit]: https://github.com/ansible-lockdown/RHEL8-CIS-Audit
[RHEL9-CIS]: https://github.com/ansible-lockdown/RHEL9-CIS
[RHEL9-CIS-Audit]: https://github.com/ansible-lockdown/RHEL9-CIS-Audit
[UBUNTU18-CIS]: https://github.com/ansible-lockdown/UBUNTU18-CIS
[UBUNTU18-CIS-Audit]: https://github.com/ansible-lockdown/UBUNTU18-CIS-Audit
[UBUNTU20-CIS]: https://github.com/ansible-lockdown/UBUNTU20-CIS
[UBUNTU20-CIS-Audit]: https://github.com/ansible-lockdown/UBUNTU20-CIS-Audit
[UBUNTU22-CIS]: https://github.com/ansible-lockdown/UBUNTU22-CIS
[UBUNTU22-CIS-Audit]: https://github.com/ansible-lockdown/UBUNTU22-CIS-Audit
[UBUNTU24-CIS]: https://github.com/ansible-lockdown/UBUNTU24-CIS
[UBUNTU24-CIS-Audit]: https://github.com/ansible-lockdown/UBUNTU24-CIS-Audit

[Windows-10-CIS]: https://github.com/ansible-lockdown/Windows-10-CIS
[Windows-10-CIS-Audit]: https://github.com/ansible-lockdown/Windows-10-CIS-Audit
[Windows-11-CIS]: https://github.com/ansible-lockdown/Windows-11-CIS
[Windows-11-CIS-Audit]: https://github.com/ansible-lockdown/Windows-11-CIS-Audit
[Windows-2016-CIS]: https://github.com/ansible-lockdown/Windows-2016-CIS
[Windows-2016-CIS-Audit]: https://github.com/ansible-lockdown/Windows-2016-CIS-Audit
[Windows-2019-CIS]: https://github.com/ansible-lockdown/Windows-2019-CIS
[Windows-2019-CIS-Audit]: https://github.com/ansible-lockdown/Windows-2019-CIS-Audit
[Windows-2022-CIS]: https://github.com/ansible-lockdown/Windows-2022-CIS
[Windows-2022-CIS-Audit]: https://github.com/ansible-lockdown/Windows-2022-CIS-Audit

[Cisco-IOS-L2S]: https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG
[AWS-Foundations]: https://github.com/ansible-lockdown/AWS-FOUNDATIONS-CIS
[Azure-CIS]: https://github.com/ansible-lockdown/AZURE-CIS

[Apache-2.4-CIS]: https://github.com/ansible-lockdown/APACHE-2.4-CIS
[Postgres-12-CIS]: https://github.com/ansible-lockdown/POSTGRES-12-CIS
[Kubernetes1.6.1-CIS]: https://github.com/ansible-lockdown/Kubernetes1.6.1-CIS
[KUBERNETES-STIG]: https://github.com/ansible-lockdown/KUBERNETES-STIG

<!---
STIG Repo links
--->

[RHEL7-STIG]: https://github.com/ansible-lockdown/RHEL7-STIG
[RHEL7-STIG-Audit]: https://github.com/ansible-lockdown/RHEL7-STIG-Audit
[RHEL8-STIG]: https://github.com/ansible-lockdown/RHEL8-STIG
[RHEL8-STIG-Audit]: https://github.com/ansible-lockdown/RHEL8-STIG-Audit
[RHEL9-STIG]: https://github.com/ansible-lockdown/RHEL9-STIG
[RHEL9-STIG-Audit]: https://github.com/ansible-lockdown/RHEL9-STIG-Audit
[UBUNTU18-STIG]: https://github.com/ansible-lockdown/UBUNTU18-STIG
[UBUNTU18-STIG-Audit]: https://github.com/ansible-lockdown/UBUNTU18-STIG-Audit
[UBUNTU20-STIG]: https://github.com/ansible-lockdown/UBUNTU20-STIG
[UBUNTU20-STIG-Audit]: https://github.com/ansible-lockdown/UBUNTU20-STIG-Audit
[UBUNTU22-STIG]: https://github.com/ansible-lockdown/UBUNTU22-STIG
[UBUNTU22-STIG-Audit]: https://github.com/ansible-lockdown/UBUNTU22-STIG-Audit

[Windows-10-STIG]: https://github.com/ansible-lockdown/Windows-10-STIG
[Windows-2016-STIG]: https://github.com/ansible-lockdown/Windows-2016-STIG
[Windows-2019-STIG]: https://github.com/ansible-lockdown/Windows-2019-STIG
[Windows-2022-STIG]: https://github.com/ansible-lockdown/Windows-2022-STIG

[Apache-2.4-STIG]: https://github.com/ansible-lockdown/APACHE-2.4-STIG
[Postgres-9-STIG]: https://github.com/ansible-lockdown/POSTGRES-9-STIG
[Cisco-IOS-L2S-STIG]: https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG
[WinFWADV-STIG]: https://github.com/ansible-lockdown/WinFWADV-STIG
[WinFWADV-STIG-Audit]: https://github.com/ansible-lockdown/WinFWADV-STIG-Audit

[RHEL5-STIG]: https://github.com/ansible-lockdown/RHEL5-STIG
[RHEL6-STIG]: https://github.com/ansible-lockdown/RHEL6-STIG
[Windows-2008R2-Member-Server-STIG]: https://github.com/ansible-lockdown/Windows-2008R2-Member-Server-STIG
[Windows-2012-Member-Server-STIG]: https://github.com/ansible-lockdown/Windows-2012-Member-Server-STIG
[Windows-2012-Domain-Controller-STIG]: https://github.com/ansible-lockdown/Windows-2012-Domain-Controller-STIG
