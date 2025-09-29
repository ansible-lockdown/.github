<div align="center">

<a href="https://lockdownenterprise.com#GH_LockdownReadMe"><img src="https://raw.githubusercontent.com/ansible-lockdown/.github/logo/images/Tyto-Athene-Logo-Full-Color.png" alt="Tyto Athene" width="250" height="100"></a>
# Ansible Lockdown

[![Org Stars](https://img.shields.io/github/stars/ansible-lockdown?label=Org%20Stars&style=social)](https://github.com/ansible-lockdown)
[![Followers](https://img.shields.io/github/followers/ansible-lockdown?style=social)](https://github.com/ansible-lockdown)
[![Discord](https://img.shields.io/discord/925818806838919229?logo=discord)](https://www.lockdownenterprise.com/discord)

**Baseline hardening at scale** — remediation roles (Ansible) + audit profiles (Goss), mapped to CIS & DISA STIG.

</div>

---

## What is Ansible Lockdown?
Ansible Lockdown is an **open-source security automation framework** purpose-built for baseline hardening.  
It codifies industry benchmarks like **CIS** and **DISA STIG** into two complementary components:  

- **Remediation Roles (Ansible)**  
  Apply hardening controls directly to Linux, Windows, network appliances, and applications.  
  Every control is implemented as **idempotent code**, making remediation repeatable, and version-controlled.  

- **Audit Profiles (Goss)**  
  Lightweight compliance checks that run at machine speed.  
  Validate drift, prove compliance for audits, and integrate directly with CI/CD pipelines.  

The result: a **configuration-as-code foundation for security baselines** that plugs into existing DevOps workflows and scales across heterogeneous environments.

---

## Why you need Ansible Lockdown
Security and compliance challenges scale with your infrastructure. Manual hardening and one-off scripts can’t keep up.  
Ansible Lockdown gives you a **battle-tested, automated, and auditable approach** that solves for both operational efficiency and regulatory requirements.

### Business Value
- **Cut costs**: Reduce time spent on manual compliance by 70–80%.  
- **Accelerate audits**: Pre-mapped controls to CIS and STIG benchmarks simplify evidence collection.  
- **De-risk operations**: Reduce misconfiguration risk and insider error across thousands of endpoints.  
- **Enterprise-ready**: Community-driven, open-source under MIT license, with optional **commercial support**.  

### Technical Advantages
- **Multi-platform coverage**: Linux distros (RHEL, Ubuntu, Debian, etc.), Windows Server/Workstation, apps, and cloud.  
- **Infrastructure-as-Code ready**: Run inside Ansible Tower/AWX, GitHub Actions, GitLab, Jenkins, Terraform, or any CI/CD stack.  
- **Full lifecycle**: Apply → Audit → Monitor drift → Re-apply.  
- **Highly tunable**: Variables and tags let you enable/disable controls granularly, so you only enforce what fits your environment.  
- **Pre-deployment security**: Integrate compliance scans into image pipelines (Packer, Docker, VM templates) before workloads even deploy.  

---

## Why Ansible Lockdown?
- **Open source (MIT)** with an active community; **enterprise support** available.  
- **Configuration-as-code:** remediate with [Ansible], audit with [GOSS].  
- Built for **heterogeneous fleets** — Linux, Windows, platforms, and applications.  
- Proven in production by enterprises, federal agencies, and critical infrastructure providers.  

> Looking for a specific OS or benchmark? Jump to the **[Repo Matrix](#repo-matrix)**.

---

## What’s inside
- **Remediation Roles** — Ansible roles that implement benchmark controls.  
- **Audit Profiles** — Goss profiles that verify configured state.  
- **Benchmarks** — CIS and DISA STIG coverage across OS, platforms, and apps.  
- **Archived** — prior versions maintained for reference.

---

## Feature Comparison

| Capability              | Ansible Lockdown                         | Manual Scripts / Ad-hoc   | Commercial Tools       |
|--------------------------|-------------------------------------------|---------------------------|------------------------|
| **Open Source (MIT)**    | ✅ Yes                                    | ❌ No                     | ❌ No                  |
| **Mapped to CIS & STIG** | ✅ Direct mappings included               | ❌ Manual mapping needed   | ⚠️ Partial (varies)    |
| **Remediation (Ansible)**| ✅ Idempotent roles at scale              | ⚠️ Inconsistent            | ✅ Often included       |
| **Audit (Goss)**         | ✅ Lightweight, fast, CI-friendly         | ❌ No standard method      | ⚠️ Varies              |
| **Multi-Platform**       | ✅ Linux, Windows, Apps, Cloud            | ❌ OS-specific hacks       | ⚠️ Limited support     |
| **Customizable**         | ✅ Variables, tags, modular controls      | ❌ Hardcoded               | ⚠️ Vendor limits       |
| **Cost**                 | ✅ Free (Enterprise support optional)     | ✅ Free but costly in time | 💲 High license fee    |

---

## Real-World Use Cases
- **CIS/STIG compliance at scale** for regulated industries (Federal, Finance, Healthcare).  
- **Golden image pipelines** (Packer, Docker, Azure, AWS AMIs) pre-hardened before deployment.  
- **CI/CD enforcement**: Break builds or flag drift automatically.  
- **Hybrid IT environments**: Consistent baselines across Windows & Linux fleets.  
- **Audit-ready evidence**: Reports mapped to benchmark control IDs.  

---
<br>
<br>
<br>
<br>
<br><br>
<br>
<br>
<br>
<br>
<br>

<br>

## Repo Matrix

| OS                  | Remediation Repo Link                      | Main CIS Release Badge                                                                                       | Devel CIS Release Badge                                                                                      |
|----------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| **Windows Server 2022** | [Windows-2022-CIS](https://github.com/ansible-lockdown/Windows-2022-CIS) | ![Main Release](https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/self_hosted/badges/Windows-2022-CIS/benchmark-version-main.json) | ![Devel Release](https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/self_hosted/badges/Windows-2022-CIS/benchmark-version-devel.json) |

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


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

|OS|Remediate|Audit||
|--|--|--|--|
|Amazon2|[Amazon2-CIS]|[Amazon2-CIS-Audit]||
|Amazon2023|[Amazon2023-CIS]|[Amazon2023-CIS-Audit]||
|DEBIAN11|[DEBIAN11-CIS]|[DEBIAN11-CIS-Audit]||
|DEBIAN12|[DEBIAN12-CIS]|[DEBIAN12-CIS-Audit]||
|RHEL8|[RHEL8-CIS]|[RHEL8-CIS-Audit]||
|RHEL9|[RHEL9-CIS]|[RHEL9-CIS-Audit]||
|RHEL10|[RHEL10-CIS]|[RHEL10-CIS-Audit]|**Unofficial**|
|SUSE15|[SUSE15-CIS]|[SUSE15-CIS-Audit]||
|UBUNTU18|[UBUNTU18-CIS]|[UBUNTU18-CIS-Audit]||
|UBUNTU20|[UBUNTU20-CIS]|[UBUNTU20-CIS-Audit]||
|UBUNTU22|[UBUNTU22-CIS]|[UBUNTU22-CIS-Audit]||
|UBUNTU24|[UBUNTU24-CIS]|[UBUNTU24-CIS-Audit]||

#### CIS-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-10|[Windows-10-CIS]|![Static Badge][Coming Soon]|
|Windows-11|[Windows-11-CIS]|![Static Badge][Coming Soon]|
|Windows-2016|[Windows-2016-CIS]|[Windows-2016-CIS-Audit]|
|Windows-2019|[Windows-2019-CIS]|[Windows-2019-CIS-Audit]|
|Windows-2022|[Windows-2022-CIS]|![Static Badge][Coming Soon]|
|Windows-2025|![Static Badge][Coming Soon]|![Static Badge][Coming Soon]|

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

### CIS-Archived

---

|OS|
|--|
|[RHEL7-CIS]|

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
|RHEL8|[RHEL8-STIG]|[RHEL8-STIG-Audit]|
|RHEL9|[RHEL9-STIG]|[RHEL9-STIG-Audit]|
|UBUNTU18|[UBUNTU18-STIG]|[UBUNTU18-STIG-Audit]|
|UBUNTU20|[UBUNTU20-STIG]|![Static Badge][Coming Soon]|
|UBUNTU22|[UBUNTU22-STIG]|[UBUNTU22-STIG-Audit]|

#### STIG-Windows

---

|OS|Remediate|Audit|
|--|--|--|
|Windows-10|[Windows-10-STIG]|N/A|
|Windows-11|[Windows-11-STIG]|N/A|
|Windows-2016|[Windows-2016-STIG]|N/A|
|Windows-2019|[Windows-2019-STIG]|N/A|
|Windows-2022|[Windows-2022-STIG]|N/A|
|Windows-2025|![Static Badge][Coming Soon]|N/A|

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
|[RHEL7-STIG]|
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
[RHEL10-CIS]: https://github.com/ansible-lockdown/RHEL10-CIS
[RHEL10-CIS-Audit]: https://github.com/ansible-lockdown/RHEL10-CIS-Audit
[SUSE15-CIS]: https://github.com/ansible-lockdown/SUSE15-CIS
[SUSE15-CIS-Audit]: https://github.com/ansible-lockdown/SUSE15-CIS-Audit
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
[Windows-2025-CIS]: https://github.com/ansible-lockdown/Windows-2025-CIS
[Windows-2025-CIS-Audit]: https://github.com/ansible-lockdown/Windows-2025-CIS-Audit

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
[Windows-11-STIG]: https://github.com/ansible-lockdown/Windows-11-STIG
[Windows-2016-STIG]: https://github.com/ansible-lockdown/Windows-2016-STIG
[Windows-2019-STIG]: https://github.com/ansible-lockdown/Windows-2019-STIG
[Windows-2022-STIG]: https://github.com/ansible-lockdown/Windows-2022-STIG
[Windows-2025-STIG]: https://github.com/ansible-lockdown/Windows-2025-STIG

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
