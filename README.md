# Hey there! I'm Divyam 👋

I build systems that are meant to be broken and then I make sure they can't be.

By day, I am a **DevOps Engineer**; by nature, I am a **Penetration Tester**. My journey began in **Ethical Hacking**, which fundamentally changed how I view infrastructure. I don't just architect for scalability; I architect to survive an adversary.

### 🛠️ Tech Stack & Arsenal
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=Helm&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### 🎯 Core Focus
* **🛡️ Infrastructure as Code (Security):** Hardening CI/CD pipelines and Kubernetes clusters before the first line of app code is even deployed.
* **🏗️ Engineering Automation:** Writing high-performance internal tools and Kubernetes Operators in **Go** to replace manual toil with reliable code.
* **🌐 Community First:** I believe the best way to secure the web is through Open Source. I'm an active contributor focused on infrastructure reliability and cloud-native security.

---

## 🚀 Open Source Impact
*Break it, report it, fix it — the loop that keeps cloud-native infra honest.*

### 🌟 Featured Problem Solving

**1. Eliminating Alert Fatigue in Kubernetes HPAs**
> **Project:** `kubernetes-monitoring/kubernetes-mixin`
> * **Found:** [#1193](https://github.com/kubernetes-monitoring/kubernetes-mixin/issues/1193) — `KubeHpaMaxedOut` fires false positives on fixed-scale HPAs (`minReplicas == maxReplicas`).
> * **Fixed:** [#1194](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1194) — updated the PromQL to exclude them. Engineers now only get paged when resources are genuinely starving.

**2. Securing RabbitMQ Operator Deployments**
> **Project:** `bitnami/charts`
> * **Found:** [#19394](https://github.com/bitnami/charts/issues/19394) — the RabbitMQ-Operator chart violated PodSecurity standards on K8s v1.26+.
> * **Fixed:** [#19568](https://github.com/bitnami/charts/pull/19568) — hardened container security contexts so the chart deploys cleanly under strict PodSecurity policies.

**3. Enabling Custom Plugin Webservers for Mattermost**
> **Project:** `mattermost/mattermost-helm` | **PR:** [#396](https://github.com/mattermost/mattermost-helm/pull/396)
> * **The Fix:** Engineered dynamic `extraPorts` support in Helm, letting plugins with standalone webservers integrate cleanly with Mattermost.

### 🐛 Bugs Found & Issues Raised

| Date | Repository | Issue | Status | TL;DR |
| :--- | :--- | :--- | :--- | :--- |
| Aug 2026 | `netbirdio/kubernetes-operator` | [#397](https://github.com/netbirdio/kubernetes-operator/issues/397) | 🟢 Open | `netbird-kubeapi-proxy` image is hardcoded with no override, stuck a release behind. |
| Mar 2026 | `kubernetes-mixin` | [#1193](https://github.com/kubernetes-monitoring/kubernetes-mixin/issues/1193) | ✅ Fixed — [PR #1194](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1194) | `KubeHpaMaxedOut` false positive on fixed-scale HPAs. |
| Jan 2026 | `mattermost-operator` | [#447](https://github.com/mattermost/mattermost-operator/issues/447) | 🟢 Open | Operator defaults to multiple replicas, breaking core messaging for non-Enterprise users. |
| Jun 2025 | `brancz/kubernetes-grafana` | [#139](https://github.com/brancz/kubernetes-grafana/issues/139) | 🟢 Open | Bundled Grafana version stuck behind upstream — requested bump to 12.0.0. |
| Dec 2023 | `vmware-tanzu/helm-charts` | [#533](https://github.com/vmware-tanzu/helm-charts/issues/533) | 🟢 Open | Velero backups go `PartiallyFailed` — fails to get the VolumeSnapshot. |
| Sep 2023 | `bitnami/charts` | [#19394](https://github.com/bitnami/charts/issues/19394) | ✅ Fixed — [PR #19568](https://github.com/bitnami/charts/pull/19568) | RabbitMQ-Operator chart violates PodSecurity policy. |
| May 2023 | `zalando/postgres-operator` | [#2337](https://github.com/zalando/postgres-operator/issues/2337) | 🟢 Open | Logical backups use `pg_dump` instead of `pg_dumpall`. |
| Apr 2023 | `zalando/postgres-operator` | [#2288](https://github.com/zalando/postgres-operator/issues/2288) | 🟢 Open | Postgres pod comes back as secondary after a Kubernetes cluster upgrade. |
| Jul 2021 | `hashicorp/terraform-provider-aws` | [#20161](https://github.com/hashicorp/terraform-provider-aws/issues/20161) | ✅ Closed | Canary docs wrong for `s3://` script-location URIs. |

### ✅ Pull Requests Merged

| Date | Repository | PR | Impact | Tech Stack |
| :--- | :--- | :--- | :--- | :--- |
| Mar 2026 | `kubernetes-mixin` | [#1194](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1194) | Fixed `KubeHpaMaxedOut` PromQL false positive. | PromQL, Prometheus |
| Sep 2023 | `bitnami/charts` | [#19568](https://github.com/bitnami/charts/pull/19568) | Patched PodSecurity violations for RabbitMQ. | Helm, Kubernetes |
| Jun 2023 | `mattermost-helm` | [#396](https://github.com/mattermost/mattermost-helm/pull/396) | Added `extraPorts` support for backend plugins. | Helm, Kubernetes |

---

## 📫 Let's Connect

I'm always up for a deep dive into secure architecture, reliability engineering, or shifting security left.

[LinkedIn](https://www.linkedin.com/in/divyamazad/) • [Support My Work](https://www.buymeacoffee.com/nihaldivyam)
