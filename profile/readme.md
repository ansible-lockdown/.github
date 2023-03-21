<centre>

# Welcome to Ansible Lockdown

|<div style="width:400px"></div>Part of the lockdown suite by|
| :---: |
|<a href="[MPG_lockdown]" target="_blank"><img src="https://assets-global.website-files.com/601959b76833363126385b0d/60195aa15ed9274f67255f9b_MPG-logo-mono-blue.svg" width="200" height="75" alt="MindPoint Group"/></a>|

### Based upon the following products

|<div style="width:290px"></div>| |
:----: | :----:
|[<img src="https://ansible.com/hubfs/Images/Red-Hat-Ansible_OG_1200x630.png" width="150" height="77" alt="Ansible by RedHat" />](https://www.ansible.com)|[<img src="images/github-mark.png" width="150" height="150" alt="Github hosted goss" />](http://goss.rocks)|
|<h2>[Ansible]</h2>by RedHat <br>|<h2>[Goss]</h2>Go Server Spec<br>|

## What is it?

Based upon industry recognized benchmarks and best practices, Using leading products to enable highly adjustable configurations to bring your systems/platforms into security compliance.

- Open Source (MIT licensed)
  - Community supported as standard
  - Enterprise support available
- Configuration-as-code
  - Assist in bringing your systems/platform into compliance through the use of [Ansible]
  - Audit your current system/platform using [Goss]
- Highly configurable to work with your systems

## Looking for support?

- [Enterprise Support]("[LockdownEnterprise]")
- [Documentation]("[ReadtheDocs]")

|||
|--|--|
|<img src="https://www.cisecurity.org/-/media/project/cisecurity/cisecurity/data/media/img/cis-logo.png?h=86&iar=0&w=300&rev=cab111cd442d438e9a25aad90b81bcfe&hash=864E27F8A942D9677949C871231E0E2F" alt="CIS" />|<img src="https://www.eiutah.com/wp-content/uploads/2015/10/DISA-1024x1024.png" width="100" height="100" alt="Disa STIG" />|
|[CIS Repos](#cis)|[STIG Repos](#stig)|

---

## Useful Links

- Ansible Lockdown
  - [Ansible Galaxy]
  - [Community]("[Discord]") using discord
  - [Full Repository list]("[RepositoryList]")
  - [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/AnsibleLockdown.svg?style=social&label=Follow%20%40AnsibleLockdown)](https://twitter.com/AnsibleLockdown)

- MindPoint Group and other services: [MindPoint Group]("[MindPointGroup]")

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
|RHEL7|[RHEL7-CIS]|[RHEL7-CIS-Audit]|
|RHEL8|[RHEL8-CIS]|[RHEL8-CIS-Audit]|
|RHEL9|[RHEL9-CIS]|[RHEL9-CIS-Audit]|
|UBUNTU18|[UBUNTU18-CIS]|[UBUNTU18-CIS-Audit]|
|UBUNTU20|[UBUNTU20-CIS]|[UBUNTU20-CIS-Audit]|
|UBUNTU22|[UBUNTU22-CIS]|[UBUNTU22-CIS-Audit]|

#### CIS-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-2016|[Windows-2016-CIS]|[Windows-2016-CIS-Audit]|
|Windows-2019|[Windows-2019-CIS]|[Windows-2019-CIS-Audit]|
|Windows-2022|[Windows-2022-CIS]|[Windows-2022-CIS-Audit]|

#### CIS-Platform

---

|OS|Remediate|Audit|
|--|--|--|
|[Cisco-IOS-L2S]|[Cisco-IOS-L2S]|False|
|[AWS-Foundations]|[AWS-Foundations]|False|
|[Azure-CIS]|[Azure-CIS]|False|

#### CIS-Applications

---

|Application|Remediate|Audit|
|--|--|--|
|Apache-2.4-CIS|[Apache-2.4-CIS]|False|
|Postgres-9-CIS|[Postgres-12-CIS]|False|
|Kubernetes1.6.1-CIS|[Kubernetes1.6.1-CIS]|False|

---
---

### STIG

---

|Links|
|---|
|[STIG-Linux](#stig-linux)|
|[STIG-Windows](#stig-windows)|
|[STIG-Applications](#stig-applications)|[STIG](#stig-application)|
|[STIG-Archived](#stig-archived)|

---

#### STIG-Linux

---

|OS|Remediate|Audit|
|--|--|--|
|RHEL7|[RHEL7-STIG]|[RHEL7-STIG-Audit]|
|RHEL8|[RHEL8-STIG]|[RHEL8-STIG-Audit]|
|UBUNTU18|[UBUNTU18-STIG]|False|
|UBUNTU20|[UBUNTU20-STIG]|False|

#### STIG-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-10|[Windows-10-STIG]|False|
|Windows-2016|[Windows-2016-STIG]|False|
|Windows-2019|[Windows-2019-STIG]|False|
|Windows-2022|[Windows-2022-STIG]|False|

#### STIG-Applications

---

|Application|Remediate|Audit|
|--|--|--|
|Apache-2.4-STIG|[Apache-2.4-STIG]|False|
|Postgres-9-STIG|[Postgres-9-STIG]|False|
|Cisco-IOS-L2S|[Cisco-IOS-L2S-STIG]|False|
|Windows-Advanced-Firewall|[WinFWADV-STIG]|False|

#### STIG-Archived

---

|OS|
|--|
|[RHEL5-STIG]|
|[RHEL6-STIG]|
|[Windows-2008R2-Member-Server-STIG]|
|[Windows-2012-Member-Server-STIG]|
|[Windows-2012-Domain-Controller-STIG]|

</centre>

<!---
Following entries used for consistent links across the document
--->
[Ansible]: https://www.ansible.com
[Ansible Galaxy]: https://galaxy.ansible.com/search?deprecated=false&keywords=mindpointgroup&order_by=-relevance&page=1
[CIS - Centre for Internet Security]: https://www.cisecurity.org
[DISA STIG]: https://public.cyber.mil/stigs
[G2_reviews]: https://www.g2.com/products/ansible-lockdown/reviews
[GOSS]: https://goss.rocks
[MindPoint Group]: https://mindpointgroup.com
[MPG_lockdown]: https://www.mindpointgroup.com/cybersecurity-consulting/automate/baseline-modernization#LockdownReadMe
[Discord]: https://discord.io/ansible-lockdown
[LockdownEnterprise]: https://lockdownenterprise.com
[Linkedin]: https://www.linkedin.com/signup/cold-join?session_redirect=https%3A%2F%2Fwww%2Elinkedin%2Ecom%2Fcompany%2Fmindpoint-group-llc&trk=organization_guest_nav-header-join
[ReadTheDocs]: https://ansible-lockdown.readthedocs.io/en/latest/
[Repository List]: https://github.com/orgs/ansible-lockdown/repositories

<!---
CIS Repo links
--->

[Amazon2-CIS]: https://github.com/ansible-lockdown/AMAZON2-CIS
[Amazon2-CIS-Audit]: https://github.com/ansible-lockdown/AMAZON2-CIS-Audit
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
[UBUNTU22-CIS]: https://github.com/ansible-lockdown/UBUNTU20-CIS
[UBUNTU22-CIS-Audit]: https://github.com/ansible-lockdown/UBUNTU20-CIS-Audit

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

<!---
STIG Repo links
--->

[RHEL7-STIG]: https://github.com/ansible-lockdown/RHEL7-STIG
[RHEL7-STIG-Audit]: https://github.com/ansible-lockdown/RHEL7-STIG-Audit
[RHEL8-STIG]: https://github.com/ansible-lockdown/RHEL8-STIG
[RHEL8-STIG-Audit]: https://github.com/ansible-lockdown/RHEL8-STIG-Audit
[UBUNTU18-STIG]: https://github.com/ansible-lockdown/UBUNTU18-STIG
[UBUNTU18-STIG-Audit]: https://github.com/ansible-lockdown/UBUNTU18-STIG-Audit
[UBUNTU20-STIG]: https://github.com/ansible-lockdown/UBUNTU18-STIG

[Windows-10-STIG]: https://github.com/ansible-lockdown/Windows-10-STIG
[Windows-2016-STIG]: https://github.com/ansible-lockdown/Windows-2016-STIG
[Windows-2019-STIG]: https://github.com/ansible-lockdown/Windows-2019-STIG
[Windows-2022-STIG]: https://github.com/ansible-lockdown/Windows-2022-STIG

[Apache-2.4-STIG]: https://github.com/ansible-lockdown/APACHE-2.4-STIG
[Postgres-9-STIG]: https://github.com/ansible-lockdown/POSTGRES-9-STIG
[Cisco-IOS-L2S-STIG]: https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG
[WinFWADV-STIG]: https://github.com/ansible-lockdown/WinFWADV-STIG

[RHEL5-STIG]: https://github.com/ansible-lockdown/RHEL5-STIG
[RHEL6-STIG]: https://github.com/ansible-lockdown/RHEL6-STIG
[Windows-2008R2-Member-Server-STIG]: https://github.com/ansible-lockdown/Windows-2008R2-Member-Server-STIG
[Windows-2012-Member-Server-STIG]: https://github.com/ansible-lockdown/Windows-2012-Member-Server-STIG
[Windows-2012-Domain-Controller-STIG]: https://github.com/ansible-lockdown/Windows-2012-Domain-Controller-STIG
