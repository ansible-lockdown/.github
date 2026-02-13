<div align="center">

<a href="https://lockdownenterprise.com#GH_LockdownReadMe"><img src="https://raw.githubusercontent.com/ansible-lockdown/.github/logo/images/Tyto-Athene-Logo-Full-Color.png" alt="Tyto Athene" width="250" height="100"></a>
# Ansible Lockdown

[![Org Stars](https://img.shields.io/github/stars/ansible-lockdown?label=Org%20Stars&style=social)](https://github.com/ansible-lockdown)
[![Followers](https://img.shields.io/github/followers/ansible-lockdown?style=social)](https://github.com/ansible-lockdown)
[![Discord](https://img.shields.io/discord/925818806838919229?logo=discord)](https://www.lockdownenterprise.com/discord)

**Baseline hardening at scale** — remediation roles (Ansible) + audit profiles (Goss), mapped to CIS & DISA STIG.

---

## 💡 Looking for Support?

[![Enterprise Support](https://img.shields.io/badge/Enterprise_Support-LockdownEnterprise.com-1E90FF?style=flat-square&logo=google-chrome&logoColor=white)](https://lockdownenterprise.com)
[![Docs](https://img.shields.io/badge/Docs-ReadTheDocs-1E90FF?style=flat-square&logo=readthedocs&logoColor=white)](https://ansible-lockdown.readthedocs.io/en/latest/)
[![Discord](https://img.shields.io/discord/925818806838919229?style=flat-square&logo=discord&logoColor=white&label=Community%20Chat)](https://www.lockdownenterprise.com/discord)



## 🔗 Useful Links

**Ansible Lockdown**

[![Galaxy](https://img.shields.io/badge/Ansible-Galaxy-EE0000?style=flat-square&logo=ansible)](https://galaxy.ansible.com/MindPointGroup)
[![YouTube](https://img.shields.io/badge/Videos-YouTube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=8aCSHD_pYbY&list=PLKpw0im6um14iqGuIS896rUWMOycdDYrv)
[![GitHub](https://img.shields.io/badge/Full%20Repo%20List-GitHub-181717?style=flat-square&logo=github)](https://github.com/orgs/ansible-lockdown/repositories)
[![G2](https://img.shields.io/badge/Reviews-G2-FF6B00?style=flat-square&logo=g2)](https://www.g2.com/products/ansible-lockdown/reviews)
[![Twitter](https://img.shields.io/twitter/follow/AnsibleLockdown?style=social)](https://twitter.com/AnsibleLockdown)

---

## 🤝 Company & Partners

<table>
<tr>
<td align="center" width="50%">

<strong>Tyto Athene</strong><br>

<a href="https://tytoathene.com">
  <img src="https://img.shields.io/badge/Website-Tyto_Athene-1E90FF?style=flat-square&logo=google-chrome&logoColor=white" />
</a>
<a href="https://www.linkedin.com/company/tyto-athene/">
  <img src="https://img.shields.io/badge/LinkedIn-Tyto_Athene-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/TytoAthene">
  <img src="https://img.shields.io/twitter/follow/TytoAthene?style=social" />
</a>
<a href="https://www.facebook.com/TytoAthene">
  <img src="https://img.shields.io/badge/Facebook-Tyto_Athene-1877F2?style=flat-square&logo=facebook&logoColor=white" />
</a>

</td>
<td align="center" width="50%">

<strong>MindPoint Group</strong><br>

<a href="https://www.mindpointgroup.com">
  <img src="https://img.shields.io/badge/Website-MindPoint_Group-1E90FF?style=flat-square&logo=google-chrome&logoColor=white" />
</a>
<a href="https://www.linkedin.com/company/mindpoint-group-llc">
  <img src="https://img.shields.io/badge/LinkedIn-MindPoint_Group-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/MindPointGroup">
  <img src="https://img.shields.io/twitter/follow/MindPointGroup?style=social" />
</a>

</td>
</tr>
</table>
</div>

---

## What is Ansible Lockdown?
Ansible Lockdown (Lockdown Compliance within Lockdown Suite) is an **open-source security automation framework** purpose-built for compliance hardening. It codifies industry benchmarks like **CIS** and **DISA STIG** for both remediation and auditing.

- **Remediation Roles (Ansible)**
  Apply hardening controls directly to Linux, Windows, network appliances, and applications.
  Every control is implemented as **idempotent code**, making remediation repeatable, and version-controlled.

- **Audit Profiles (Goss)**
  Lightweight compliance checks that run at machine speed.
  Validates compliance state, exports compliance state in multiple formats, and integrates easily directly into CI/CD pipelines.

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

---

## Community vs Private Repositories

### Release Strategy

We follow a **staged release model** to ensure the highest quality baselines reach the community:

1. **Subscriber (Private) Release** - Completed benchmark updates are released to our private repositories first
2. **Subscriber Validation** - Subscribers use the updates in their production environments and report any issues they encounter
3. **Bug Fixing** - We work with subscribers to resolve any issues discovered during real-world usage
4. **Community Release** - After 90 days as Subscriber release the benchmark updates are released to the community (Public). Leading to 90 days of real world use by subscribers before being publicly available.

**Why This Approach?**
- Ensures community repositories contain production-ready, battle-tested code
- Reduces breaking changes for users relying on stable releases
- Allows us to iterate quickly on new features without disrupting community workflows
- Provides value to subscribers who support our development efforts

### Private Repository Access

**What You Get:**
- Early access to new benchmark versions
- Cutting-edge security controls before public release
- Direct influence on development through early feedback
- Support for critical issues during testing phase
- Access to experimental features and controls

**Subscription Required:**
To access private repositories, you must be an active subscriber. Visit https://www.lockdownenterprise.com/ to learn more about subscriber benefits and pricing.

### Understanding Benchmark Versions

#### Private Benchmark Version Badge
The **Private Benchmark Version** badge shows the benchmark version currently under development or in testing within the private repository. This version may include:
- Newly released CIS/STIG benchmark updates
- Experimental security controls
- Performance improvements
- Bug fixes not yet validated for community release

#### Main vs Devel Badges
- **Benchmark Version (main)** - Stable, production-ready version in the main branch
- **Benchmark Version (devel)** - Active development version with new features and updates
- **Lockdown Release** - Latest tagged release available for download

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

# Available Baselines by OS, Platform, or Application

## How to Use This Documentation

All remediation and audit content is maintained in dedicated repositories.
Each benchmark is presented below with:

- **Remediation Repos** → Contain Ansible automation for enforcing CIS/STIG controls.
- **Audit Repos** → Contain Goss/inspec-driven audit profiles for compliance validation.
- **Private Repos** → Internal branches/repositories for testing, staging, and pre-release.
- **Badges** → Show current benchmark version, development branch status, and Lockdown release.

### Understanding the Badges

Each baseline displays status badges showing:
- **Benchmark Version (main)**: The CIS/STIG benchmark version implemented in the main branch
- **Benchmark Version (devel)**: The benchmark version actively released to the community.
- **Private Version (latest)**: The benchmark version in active development to be released.
- **Lockdown Release**: The latest stable release version (click to view release notes)
- **Repo Status**: Availability status for audit repositories

### Getting Started

1. **Choose Your Platform**: Expand the selection for your operating system or platform
2. **Pick a Baseline**: Choose either CIS (Center for Internet Security) or STIG (Security Technical Implementation Guide)
3. **Access the Repository**: Click the repository link to view documentation and code
4. **Check Compatibility**: Review the benchmark version badges to ensure compatibility with your environment

### CIS vs STIG

- **CIS Benchmarks**: Industry consensus-based security configuration guidelines
- **STIG Baselines**: Department of Defense security requirements for government systems



## 🐧 Linux

### Red Hat Enterprise Linux

<details>
<summary><b>RHEL 10</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL10-CIS">RHEL10-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL10-CIS">Private-RHEL10-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL10-CIS-Audit">RHEL10-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL10-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL10-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL10-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL10-STIG">RHEL10-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL10-STIG">Private-RHEL10-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL10-STIG-Audit">RHEL10-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL10-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL10-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL10-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL10-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>RHEL 9</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL9-CIS">RHEL9-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL9-CIS">Private-RHEL9-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL9-CIS-Audit">RHEL9-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL9-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL9-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL9-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL9-STIG">RHEL9-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL9-STIG">Private-RHEL9-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL9-STIG-Audit">RHEL9-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL9-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL9-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL9-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL9-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>RHEL 8</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL8-CIS">RHEL8-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL8-CIS">Private-RHEL8-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL8-CIS-Audit">RHEL8-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL8-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL8-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL8-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL8-STIG">RHEL8-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL8-STIG">Private-RHEL8-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL8-STIG-Audit">RHEL8-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL8-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL8-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL8-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL8-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>RHEL 7</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL7-CIS">RHEL7-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL7-CIS">Private-RHEL7-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL7-CIS-Audit">RHEL7-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL7-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL7-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL7-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL7-STIG">RHEL7-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL7-STIG">Private-RHEL7-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL7-STIG-Audit">RHEL7-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL7-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL7-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL7-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL7-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>RHEL 6</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL6-CIS">RHEL6-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL6-CIS">Private-RHEL6-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL6-CIS-Audit">RHEL6-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL6-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL6-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL6-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL6-STIG">RHEL6-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL6-STIG">Private-RHEL6-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL6-STIG-Audit">RHEL6-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL6-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL6-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL6-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL6-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>RHEL 5</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL5-CIS">RHEL5-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL5-CIS">Private-RHEL5-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL5-CIS-Audit">RHEL5-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL5-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL5-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL5-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/RHEL5-STIG">RHEL5-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-RHEL5-STIG">Private-RHEL5-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/RHEL5-STIG-Audit">RHEL5-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/RHEL5-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/RHEL5-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-RHEL5-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/RHEL5-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Ubuntu Linux

<details>
<summary><b>Ubuntu 24</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU24-CIS">UBUNTU24-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU24-CIS">Private-UBUNTU24-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU24-CIS-Audit">UBUNTU24-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU24-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU24-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU24-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU24-STIG">UBUNTU24-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU24-STIG">Private-UBUNTU24-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU24-STIG-Audit">UBUNTU24-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU24-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU24-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU24-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU24-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Ubuntu 22</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU22-CIS">UBUNTU22-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU22-CIS">Private-UBUNTU22-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU22-CIS-Audit">UBUNTU22-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU22-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU22-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU22-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU22-STIG">UBUNTU22-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU22-STIG">Private-UBUNTU22-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU22-STIG-Audit">UBUNTU22-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU22-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU22-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU22-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU22-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Ubuntu 18</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU18-CIS">UBUNTU18-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU18-CIS">Private-UBUNTU18-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU18-CIS-Audit">UBUNTU18-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU18-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU18-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU18-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU18-STIG">UBUNTU18-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-UBUNTU18-STIG">Private-UBUNTU18-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/UBUNTU18-STIG-Audit">UBUNTU18-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/UBUNTU18-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/UBUNTU18-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-UBUNTU18-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/UBUNTU18-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Debian Linux

<details>
<summary><b>Debian 12</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN12-CIS">DEBIAN12-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-DEBIAN12-CIS">Private-DEBIAN12-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN12-CIS-Audit">DEBIAN12-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/DEBIAN12-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-DEBIAN12-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/DEBIAN12-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN12-STIG">DEBIAN12-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-DEBIAN12-STIG">Private-DEBIAN12-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN12-STIG-Audit">DEBIAN12-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/DEBIAN12-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN12-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-DEBIAN12-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/DEBIAN12-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Debian 11</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN11-CIS">DEBIAN11-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-DEBIAN11-CIS">Private-DEBIAN11-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN11-CIS-Audit">DEBIAN11-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/DEBIAN11-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-DEBIAN11-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/DEBIAN11-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN11-STIG">DEBIAN11-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-DEBIAN11-STIG">Private-DEBIAN11-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/DEBIAN11-STIG-Audit">DEBIAN11-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/DEBIAN11-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/DEBIAN11-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-DEBIAN11-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/DEBIAN11-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Amazon Linux

<details>
<summary><b>Amazon Linux 2023</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2023-CIS">AMAZON2023-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AMAZON2023-CIS">Private-AMAZON2023-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2023-CIS-Audit">AMAZON2023-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AMAZON2023-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AMAZON2023-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AMAZON2023-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2023-STIG">AMAZON2023-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AMAZON2023-STIG">Private-AMAZON2023-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2023-STIG-Audit">AMAZON2023-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AMAZON2023-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2023-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AMAZON2023-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AMAZON2023-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Amazon Linux 2</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2-CIS">AMAZON2-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AMAZON2-CIS">Private-AMAZON2-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2-CIS-Audit">AMAZON2-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AMAZON2-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AMAZON2-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AMAZON2-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2-STIG">AMAZON2-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AMAZON2-STIG">Private-AMAZON2-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/AMAZON2-STIG-Audit">AMAZON2-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AMAZON2-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AMAZON2-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AMAZON2-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AMAZON2-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### SUSE Linux

<details>
<summary><b>SUSE 15</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/SUSE15-CIS">SUSE15-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-SUSE15-CIS">Private-SUSE15-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/SUSE15-CIS-Audit">SUSE15-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/SUSE15-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-SUSE15-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/SUSE15-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/SUSE15-STIG">SUSE15-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-SUSE15-STIG">Private-SUSE15-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/SUSE15-STIG-Audit">SUSE15-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/SUSE15-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/SUSE15-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-SUSE15-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/SUSE15-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>


## 🪟 Windows

### Windows Server Editions

<details>
<summary><b>Windows Server 2025</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2025-CIS">Windows-2025-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2025-CIS">Private-Windows-2025-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2025-CIS-Audit">Windows-2025-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2025-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2025-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2025-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2025-STIG">Windows-2025-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2025-STIG">Private-Windows-2025-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2025-STIG-Audit">Windows-2025-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2025-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2025-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2025-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2025-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows Server 2022</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2022-CIS">Windows-2022-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2022-CIS">Private-Windows-2022-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2022-CIS-Audit">Windows-2022-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2022-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2022-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2022-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2022-STIG">Windows-2022-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2022-STIG">Private-Windows-2022-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2022-STIG-Audit">Windows-2022-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2022-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2022-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2022-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2022-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows Server 2019</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2019-CIS">Windows-2019-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2019-CIS">Private-Windows-2019-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2019-CIS-Audit">Windows-2019-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2019-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2019-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2019-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2019-STIG">Windows-2019-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2019-STIG">Private-Windows-2019-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2019-STIG-Audit">Windows-2019-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2019-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2019-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2019-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2019-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows Server 2016</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2016-CIS">Windows-2016-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2016-CIS">Private-Windows-2016-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2016-CIS-Audit">Windows-2016-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2016-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2016-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2016-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2016-STIG">Windows-2016-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2016-STIG">Private-Windows-2016-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2016-STIG-Audit">Windows-2016-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2016-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2016-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2016-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2016-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Windows Server (Legacy STIGs)

<details>
<summary><b>Windows Server 2008 R2 Member Server</b></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2008R2-Member-Server-STIG">Windows-2008R2-Member-Server-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2008R2-Member-Server-STIG">Private-Windows-2008R2-Member-Server-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2008R2-Member-Server-STIG-Audit">Windows-2008R2-Member-Server-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2008R2-Member-Server-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2008R2-Member-Server-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2008R2-Member-Server-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2008R2-Member-Server-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2008R2-Member-Server-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2008R2-Member-Server-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows Server 2012 Member Server</b></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2012-Member-Server-STIG">Windows-2012-Member-Server-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2012-Member-Server-STIG">Private-Windows-2012-Member-Server-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2012-Member-Server-STIG-Audit">Windows-2012-Member-Server-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Member-Server-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Member-Server-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2012-Member-Server-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Member-Server-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2012-Member-Server-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2012-Member-Server-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows Server 2012 Domain Controller</b></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-2012-Domain-Controller-STIG">Windows-2012-Domain-Controller-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-2012-Domain-Controller-STIG">Private-Windows-2012-Domain-Controller-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-2012-Domain-Controller-STIG-Audit">Windows-2012-Domain-Controller-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Domain-Controller-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Domain-Controller-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-2012-Domain-Controller-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-2012-Domain-Controller-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-2012-Domain-Controller-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-2012-Domain-Controller-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Windows Desktop Editions

<details>
<summary><b>Windows 11 Enterprise</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-11-CIS">Windows-11-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-11-CIS">Private-Windows-11-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-11-CIS-Audit">Windows-11-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-11-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-11-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-11-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-11-STIG">Windows-11-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-11-STIG">Private-Windows-11-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-11-STIG-Audit">Windows-11-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-11-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-11-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-11-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-11-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Windows 10 Enterprise</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-10-CIS">Windows-10-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-10-CIS">Private-Windows-10-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-10-CIS-Audit">Windows-10-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-10-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-10-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-10-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Windows-10-STIG">Windows-10-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Windows-10-STIG">Private-Windows-10-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/Windows-10-STIG-Audit">Windows-10-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Windows-10-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Windows-10-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Windows-10-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Windows-10-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

### Windows Add-on STIGs

<details>
<summary><b>Windows Advanced Firewall</b></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/WinFWADV-STIG">WinFWADV-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-WinFWADV-STIG">Private-WinFWADV-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/WinFWADV-STIG-Audit">WinFWADV-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/WinFWADV-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/WinFWADV-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/WinFWADV-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/WinFWADV-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-WinFWADV-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/WinFWADV-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

## 🌐 Network Devices

### Cisco

<details>
<summary><b>Cisco IOS Router</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-CIS">CISCO-IOS-RTR-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-CISCO-IOS-RTR-CIS">Private-CISCO-IOS-RTR-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-CIS-Audit">CISCO-IOS-RTR-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-CISCO-IOS-RTR-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/CISCO-IOS-RTR-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-STIG">CISCO-IOS-RTR-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-CISCO-IOS-RTR-STIG">Private-CISCO-IOS-RTR-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-STIG-Audit">CISCO-IOS-RTR-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/CISCO-IOS-RTR-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-RTR-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-CISCO-IOS-RTR-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/CISCO-IOS-RTR-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Cisco IOS Layer 2 Switch</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-CIS">CISCO-IOS-L2S-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-CISCO-IOS-L2S-CIS">Private-CISCO-IOS-L2S-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-CIS-Audit">CISCO-IOS-L2S-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-CIS/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-CISCO-IOS-L2S-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/CISCO-IOS-L2S-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG">CISCO-IOS-L2S-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-CISCO-IOS-L2S-STIG">Private-CISCO-IOS-L2S-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG-Audit">CISCO-IOS-L2S-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/CISCO-IOS-L2S-STIG/releases/latest">
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/CISCO-IOS-L2S-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-CISCO-IOS-L2S-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/CISCO-IOS-L2S-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

## ☁️ Cloud Platforms

<details>
<summary><b>AWS Foundations</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-CIS">AWS-FOUNDATIONS-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AWS-FOUNDATIONS-CIS">Private-AWS-FOUNDATIONS-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-CIS-Audit">AWS-FOUNDATIONS-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AWS-FOUNDATIONS-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AWS-FOUNDATIONS-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-STIG">AWS-FOUNDATIONS-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AWS-FOUNDATIONS-STIG">Private-AWS-FOUNDATIONS-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-STIG-Audit">AWS-FOUNDATIONS-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AWS-FOUNDATIONS-STIG/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AWS-FOUNDATIONS-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AWS-FOUNDATIONS-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AWS-FOUNDATIONS-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Microsoft Azure</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AZURE-CIS">AZURE-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AZURE-CIS">Private-AZURE-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/AZURE-CIS-Audit">AZURE-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AZURE-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AZURE-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AZURE-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/AZURE-STIG">AZURE-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-AZURE-STIG">Private-AZURE-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/AZURE-STIG-Audit">AZURE-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/AZURE-STIG/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/AZURE-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-AZURE-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/AZURE-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

## 📦 Applications

<details>
<summary><b>Apache 2.4</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/APACHE-2.4-CIS">APACHE-2.4-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-APACHE-2.4-CIS">Private-APACHE-2.4-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/APACHE-2.4-CIS-Audit">APACHE-2.4-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/APACHE-2.4-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-APACHE-2.4-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/APACHE-2.4-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>

  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/APACHE-2.4-STIG">APACHE-2.4-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-APACHE-2.4-STIG">Private-APACHE-2.4-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/APACHE-2.4-STIG-Audit">APACHE-2.4-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/APACHE-2.4-STIG/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/APACHE-2.4-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-APACHE-2.4-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/APACHE-2.4-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

## 🗄️ Databases

<details>
<summary><b>PostgreSQL 12</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/POSTGRES-12-CIS">POSTGRES-12-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-POSTGRES-12-CIS">Private-POSTGRES-12-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/POSTGRES-12-CIS-Audit">POSTGRES-12-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-12-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-12-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/POSTGRES-12-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-12-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-POSTGRES-12-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/POSTGRES-12-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>PostgreSQL 9</b> <img src="https://img.shields.io/badge/ARCHIVED-black?style=flat-square&logo=github" height="20" style="vertical-align:middle; margin-left:5px;"></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/POSTGRES-9-STIG">POSTGRES-9-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-POSTGRES-9-STIG">Private-POSTGRES-9-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/POSTGRES-9-STIG-Audit">POSTGRES-9-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-9-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-9-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/POSTGRES-9-STIG/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/POSTGRES-9-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-POSTGRES-9-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/POSTGRES-9-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>
</details>

## ⚙️ Kubernetes

<details>
<summary><b>Kubernetes 1.6.1</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/Kubernetes1.6.1-CIS">KUBERNETES1.6.1-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Kubernetes1.6.1-CIS">Private-Kubernetes1.6.1-CIS</a></td>
    <td><a href="https://github.com/ansible-lockdown/Kubernetes1.6.1-CIS-Audit">KUBERNETES1.6.1-CIS-Audit</a></td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Kubernetes1.6.1-CIS/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Kubernetes1.6.1-CIS/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/Kubernetes1.6.1-CIS/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Kubernetes1.6.1-CIS/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Kubernetes1.6.1-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/Kubernetes1.6.1-CIS-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>

</details>

<details>
<summary><b>Kubernetes (Generic CIS)</b></summary>

<table>
  <!-- **********************************  CIS LINKS  ********************************** -->
  <tr>
    <td>N/A</td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-Kubernetes-CIS">Private-KUBERNETES-CIS</a></td>
    <td>N/A</td>
  </tr>
  <!-- **********************************  CIS BADGES  ********************************* -->
  <tr>
    <td>N/A</td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-Kubernetes-CIS/benchmark-version.json&style=flat-square" height="20"></td>
    <td>N/A</td>
  </tr>
</table>

</details>

<details>
<summary><b>Kubernetes STIG</b></summary>

<table>
  <!-- **********************************  STIG LINKS  ********************************* -->
  <tr>
    <td><a href="https://github.com/ansible-lockdown/KUBERNETES-STIG">KUBERNETES-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/github_windows_IaC/tree/self_hosted/badges/Private-KUBERNETES-STIG">Private-KUBERNETES-STIG</a></td>
    <td><a href="https://github.com/ansible-lockdown/KUBERNETES-STIG-Audit">KUBERNETES-STIG-Audit</a></td>
  </tr>
  <!-- **********************************  STIG BADGES  ******************************** -->
  <tr>
    <td>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/KUBERNETES-STIG/benchmark-version-main.json&style=flat-square" height="20"><br>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/KUBERNETES-STIG/benchmark-version-devel.json&style=flat-square" height="20"><br>
      <a href="https://github.com/ansible-lockdown/KUBERNETES-STIG/releases/latest">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/KUBERNETES-STIG/lockdown-release.json&style=flat-square" height="20">
      </a>
    </td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/Private-KUBERNETES-STIG/benchmark-version.json&style=flat-square" height="20"></td>
    <td><img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ansible-lockdown/github_windows_IaC/refs/heads/self_hosted/badges/audit/KUBERNETES-STIG-Audit-Badge.json&style=flat-square" height="20"></td>
  </tr>
</table>
</details>
