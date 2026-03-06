# Hey there! 👋

I am a DevOps Engineer and Security enthusiast focused on the convergence of resilient infrastructure and offensive security. My background in Ethical Hacking allows me to architect systems that are not only scalable but inherently secure by design.

### 🎯 Core Focus
* **🛡️ Infrastructure Security:** Hardening CI/CD pipelines and Kubernetes environments against modern threats.
* **🏗️ Automation:** Developing high-performance internal tooling and operators using Go.
* **🌐 Open Source:** Active contributor to the community, focusing on security tools and infrastructure reliability.

---

## 🚀 Open Source Contributions
*A curated log of my merged pull requests, focusing on Kubernetes ecosystem improvements, Helm chart configurations, and monitoring reliability.*

### 🌟 Featured Problem Solving

**1. Eliminating Alert Fatigue in Kubernetes HPAs**
> **Project:** `kubernetes-monitoring/kubernetes-mixin` | **Link:** [#1194](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1194)
> * **The Fix:** Updated the PromQL expression to append a `min != max` check, explicitly filtering out fixed-scale HPAs so the alert only fires for dynamic HPAs genuinely starving for resources.

**2. Securing RabbitMQ Operator Deployments**
> **Project:** `bitnami/charts` | **Link:** [#19568](https://github.com/bitnami/charts/pull/19568)
> * **The Fix:** Updated the container security context for the pods to align with recommended PodSecurity policies, ensuring a secure deployment for Kubernetes v1.26 environments.

**3. Enabling Custom Plugin Webservers for Mattermost**
> **Project:** `mattermost/mattermost-helm` | **Link:** [#396](https://github.com/mattermost/mattermost-helm/pull/396)
> * **The Fix:** Added an `extraPorts` key to the `values.yaml` file, allowing users to dynamically define and expose additional ports for the backend service.

### 📚 Complete Log

| Date | Repository | PR Link | Impact / TL;DR | Tech Stack |
| :--- | :--- | :--- | :--- | :--- |
| **Mar 2026** | `kubernetes-mixin` | [#1194](https://github.com/kubernetes-monitoring/kubernetes-mixin/pull/1194) | Fixed `KubeHpaMaxedOut` PromQL false positive for fixed-scale HPAs. | PromQL, Prometheus |
| **Sep 2023** | `bitnami/charts` | [#19568](https://github.com/bitnami/charts/pull/19568) | Resolved Kubernetes v1.26 PodSecurity violations in RabbitMQ. | Helm, Kubernetes |
| **Jun 2023** | `mattermost-helm` | [#396](https://github.com/mattermost/mattermost-helm/pull/396) | Added `extraPorts` in values.yaml to support external plugin webservers. | Helm, Kubernetes |

---

## 📫 Let's Connect

I advocate for shifting security left. Let's connect on [LinkedIn](https://www.linkedin.com/in/divyamazad/) to discuss secure architecture and reliability engineering.

<br>

<a href="https://www.buymeacoffee.com/nihaldivyam"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Support My Open Source Work" width="180"/></a>
