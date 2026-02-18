<div align="center>
<p align="center">
  <img src="https://raw.githubusercontent.com/S4M73l09/S4M73l09/refs/heads/main/assets/Agujeronegro.webp" alt="banner" width="100%"/>
</p>

<h1 align="center">Hello, Im Samuel, nice to meet you!!
  <img src="https://raw.githubusercontent.com/S4M73l09/S4M73l09/refs/heads/main/assets/Saludo.gif" width="28" height= "28" alt="wave"/>
  </h1>

<p align="center">
  <a href="https://www.malt.es/profile/samueljesuscarcarenaz"><img alt="Hire me on Malt" src="https://img.shields.io/badge/Hire%20me%20on-Malt-red"></a>
  <a href="https://s4m73109.github.io/Cloud-infra-portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/View%20Portfolio-Online-blue"></a>
  <a href="https://github.com/S4M73109?tab=repositories"><img alt="Repos" src="https://img.shields.io/badge/Repos-Explore-lightgrey"></a>
   <a href="https://www.linkedin.com/in/samuelillobaby/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Contact me-blue"><a/>
</p>
<p align="right" style="margin:0; padding:0;">
  <a href="https://github.com/S4M73109/S4M73109/blob/main/README.md">
    <img src="https://img.shields.io/badge/ES-1f6feb?style=flat" height="18" alt="Español" />
  </a>
</p>
</div>


#### Azure DevOps. IaC (Terraform + Ansible), CI/CD (GitHub Actions), pipelines,  Docker & Observability (Prometheus/Grafana).  


<details open>
  <summary><b>🖥️ Multimedia server project (finished)</b></summary>
  <br/>
  <b>Multimedia project where Jellyfin is used to create a home Netflix, using CI/CD.</b>
  <br/><br/>

  <a href="https://github.com/S4M73109/ProyectoServer">
    <img src="https://img.shields.io/badge/Repo-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-1A1918?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Observability-Prometheus%2FGrafana-orange?style=for-the-badge" />
</details>

<details>
  <summary><b>🧩 Scripts Windows Core (Finished)</b></summary>
  <br/>
  <b>Quick automation for setting up domains/roles on Windows Server Core.</b>
  <br/><br/>

  <a href="https://github.com/S4M73109/scripts-guia-windows">
    <img src="https://img.shields.io/badge/Repo-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows_Server_Core-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
</details>

<details>
  <summary><b>☁️ GCloud-Scripts (Finished)</b></summary>
  <br/>
  <b>PowerShell + Bash to prepare necessary resources for Terraform on Google Cloud.</b>
  <br/><br/>

  <a href="https://github.com/S4M73109/Gcloud-Script">
    <img src="https://img.shields.io/badge/Repo-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
</details>

---


## 🧪 Infrastructure Lab
**More complex projects** that use separate Bootstrap governance for separated, reproducible infrastructures.

- **GCS-Bootstrap---Live** (✅ Completed) — Google Cloud bootstrap to prepare the deployment foundation and workflows.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/GCS-Bootstrap---Live)
  <details>
    <summary><b>Show features</b></summary>

    - Clear separation between **bootstrap** and **live infra**
    - CI/CD with **GitHub Actions** using **OIDC / Workload Identity Federation (WIF)**
    - Foundation resources prepared for the platform (remote state / roles / policies depending on the design)
    - Workflows tailored to safely deploy and use the bootstrap layer
  </details>

- **GCS-Infra-Live** (✅ Completed) — Real infrastructure deployed from the Bootstrap layer, with environments and branch promotion.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/GCS-Infra-Live)
  <details>
    <summary><b>Show features</b></summary>

    - Branch-based flow: **testing → promotion** (controlled rollout)
    - GitHub Actions pipelines per environment (plan/apply)
    - **Ansible** integration for post-configuration when needed
    - Best-practices oriented structure: environment layout + reproducible changes
  </details>

- **AZ-Bootstrap** (✅ Completed) — Azure bootstrap (simulated) following best practices and a reusable foundation.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/AZ-Bootstrap)
  <details>
    <summary><b>Show features</b></summary>

    - Bootstrap foundation ready to extend into **live infra**
    - GitHub Actions CI/CD + auth (depending on the scenario: OIDC / Service Principal)
    - Modular structure designed for future deployments
  </details>

- **AZ-InfraLive** (🚧 In progress) — Environment split (staging/prod) with pipelines and progressive hardening.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73l09/AZ-InfraLive)
  <details>
    <summary><b>Show features</b></summary>

    - Environment separation: **staging/prod**
    - CI/CD workflows per environment (plan/apply)
    - Progressive hardening + observability in phases
  </details>

> **Access hardening:** GCP **OS Login** · Azure **SP/Entra ID** · access policies managed with **Terraform**.



<h2>🧰 Stack</h2>

<details open>
  <summary><b>☁️ Cloud</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
</details>

<details open>
  <summary><b>🏗️ IaC & Automation</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-1A1918?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white" />
</details>

<details>
  <summary><b>🔁 CI/CD</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Git- F05032?style=for-the-badge&logo=git&logoColor=white" />
</details>

<details>
  <summary><b>🐳 Containers</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure_Container_Registry_(ACR)-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure_Container_Instances_(ACI)-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
</details>

<details>
  <summary><b>📈 Observability</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
</details>

<details>
  <summary><b>🔐 Identity & Security (DevOps)</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Azure_AD-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/OIDC-000000?style=for-the-badge&logo=openid&logoColor=white" />
</details>

<details>
  <summary><b>🖥️ OS & Tools</b></summary>
  <br/>
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/WSL-0A0A0A?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <br/><br/>
  <sub>GCP: OS Login • Azure: SP/Entra ID • Access policies manage for Terraform.</sub>
</details>



### Contact
- Reach me on **Malt** (above) or on **[LinkedIn](https://www.linkedin.com/in/samuellilobaby/)**  
