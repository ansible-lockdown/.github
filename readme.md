# Welcome to ansible lockdown

## Brought to you by

<center>
<img src="images/mindpoint_logo.png" width="75" height="75" alt="MindPointGroup"/>

[MindPointGroup]

</center>

|Based upon the following products||
|--|--|
|[<img src="https://www.ansible.com/hubfs/Logo-Red_Hat-Ansible-A-Reverse-SVG.svg" width="150" height="150" alt="Ansible by RedHat" />](https://www.ansible.com)|[<img src="images/github-mark.png" width="75" height="75" alt="Github hosted goss" />](http://goss.rocks)|
|<h2>[Ansible]</h2>by RedHat <br>|<h2>[Goss]</h2>Go Server Spec<br>|

## What is it?

Based upon industry recognised benchmarks, Using leading products to enable highly adjustable configurations to bring your systems/platforms into security complaince.

|||
|--|--|
|[<img src="https://www.cisecurity.org/-/media/project/cisecurity/cisecurity/data/media/img/cis-logo.png?h=86&iar=0&w=300&rev=cab111cd442d438e9a25aad90b81bcfe&hash=864E27F8A942D9677949C871231E0E2F" alt="CIS" />](https://www.cisecurity.org/cis-benchmarks)|[<img src="https://www.eiutah.com/wp-content/uploads/2015/10/DISA-1024x1024.png" width="100" height="100" alt="Disa STIG" />](https://public.cyber.mil/stigs/)|
|[CIS - Centre for Internet Security]|[DISA STIG]|
|[Linux](#CIS-Linux)|[STIG](#Linux)|
|[Windows](#CIS-Windows)|[STIG](#Linux)|
|[Platform](#CIS-Platform)|[STIG](#Linux)|
|[Applications](#CIS-Applications)|[STIG](#Linux)|

- Assist in bringing your systems/platform into compliance through the use of [Ansible]
- Audit your current system/platform using [Goss]

## Repositories

### CIS

#### CIS-Linux

|OS|Remediate|Audit|
|--|--|--|
|Amazon2-CIS|[Amazon2-CIS]|[Amazon2-CIS-Audit]|
|RHEL7-CIS|[RHEL7-CIS]|[RHEL7-CIS-Audit]|
|RHEL8-CIS|[RHEL8-CIS]|[RHEL8-CIS-Audit]|
|RHEL9-CIS|[RHEL9-CIS]|[RHEL9-CIS-Audit]|
|UBUNTU18-CIS|[UBUNTU18-CIS]|[UBUNTU18-CIS-Audit]|
|UBUNTU20-CIS|[UBUNTU20-CIS]|[UBUNTU20-CIS-Audit]|
|UBUNTU22-CIS|[UBUNTU22-CIS]|[UBUNTU22-CIS-Audit]|

#### CIS-Windows

|OS|Remediate|Audit|
|--|--|--|
|Windows-2016-CIS|[Windows-2016-CIS]|[Windows-2016-CIS-Audit]|
|Windows-2019-CIS|[Windows-2019-CIS]|[Windows-2019-CIS-Audit]|
|Windows-2022-CIS|[Windows-2022-CIS]|[Windows-2022-CIS-Audit]|

#### CIS-Cloud

|OS|Remediate|Audit|
|--|--|--|
|[Cisco-IOS-L2S]|[Cisco-IOS-L2S]|False|
|[AWS-Foundations]|[AWS-Foundations]|False|
|[Azure-CIS]|[Azure-CIS]|False|

#### CIS-Applications

|Application|Remediate|Audit|
|--|--|--|
|Apache-2.4-CIS|[Apache-2.4-CIS]|False|
|Postgres-12-CIS|[Postgres-12-CIS]|False|
|Kubernetes1.6.1-CIS|[Kubernetes1.6.1-CIS]|False|

<!---
Following entries used for consistent links across the document
--->
[ansible]: https://www.ansible.com
[CIS - Centre for Internet Security]: https://www.cisecurity.org
[DISA STIG]: https://public.cyber.mil/stigs
[GOSS]: https://goss.rocks
[MindPointGroup]: https://mindpointgroup.com

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
