<div align="center>
<p align="center">
  <img src="https://raw.githubusercontent.com/S4M73l09/S4M73l09/refs/heads/main/assets/Agujeronegro.webp" alt="banner" width="100%"/>
</p>


<h1 align="center">Hola, soy Samuel, encantado!!
  <img src="https://raw.githubusercontent.com/S4M73l09/S4M73l09/refs/heads/main/assets/Saludo.gif" width="28" height= "28" alt="wave"/>
  </h1>
  


<p align="center">
  <a href="https://www.malt.es/profile/samueljesuscarrera"><img alt="Contrátame en Malt" src="https://img.shields.io/badge/Contr%C3%A1tame%20en-Malt-red"></a>
  <a href="https://s4m73l09.github.io/Cloud-infra-portfolio/?lang=es"><img alt="Portfolio" src="https://img.shields.io/badge/Ver%20Portfolio-Online-green"></a>
  <a href="https://github.com/S4M73l09?tab=repositories"><img alt="Repos" src="https://img.shields.io/badge/Repos-Explorar-lightgrey"></a>
  <a href="https://www.linkedin.com/in/samuelillobaby/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Contactame-blue"><a/>
</p>
<p align="right" style="margin:0; padding:0;">
  <a href="https://github.com/S4M73109/S4M73109/blob/main/README_EN.md">
    <img src="https://img.shields.io/badge/EN-1f6feb?style=flat" height="18" alt="English" />
  </a>
</p>
</div>


DevOps en Azure. IaC (Terraform+Ansible), CI/CD (GitHub Actions), uso de pipelines, contenedores y observabilidad (Prometheus/Grafana).  

<h2>🚀 Proyectos destacados</h2>

<details open>
  <summary><b>🖥️ Proyecto multimedia Server (Terminado)</b></summary>
  <br/>
  <b>Proyecto multimedia donde se usa Jellyfin para crear un Netflix casero, utilizando CI/CD.</b>
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
  <summary><b>🧩 Scripts de Windows Core (Terminado)</b></summary>
  <br/>
  <b>Automatización rápida para montar dominio/roles en Windows Server Core.</b>
  <br/><br/>

  <a href="https://github.com/S4M73109/scripts-guia-windows">
    <img src="https://img.shields.io/badge/Repo-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows_Server_Core-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
</details>

<details>
  <summary><b>☁️ GCloud-Scripts (Terminado)</b></summary>
  <br/>
  <b>PowerShell + Bash para preparar recursos necesarios para Terraform en Google Cloud.</b>
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



## 🧪 Laboratorio de infraestructura
**Proyectos mas complejos** que utilizan la gobernanza separada de Bootstrap para Infraestructuras separadas y reproducibles.

- **GCS-Bootstrap---Live** (✅ Terminado) — Bootstrap en Google Cloud para preparar la base del despliegue y los workflows.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/GCS-Bootstrap---Live)
  <details>
    <summary><b>Ver funciones</b></summary>

    - Separación clara entre **bootstrap** e **infra live**
    - CI/CD con **GitHub Actions** usando **OIDC / Workload Identity Federation (WIF)**
    - Preparación de recursos base (estado remoto/roles/políticas según diseño del proyecto)
    - Workflows adaptados para uso y despliegue del bootstrap
  </details>

- **GCS-Infra-Live** (✅ Terminado) — Infra real desplegada a partir del Bootstrap, separando entornos y promoción por ramas.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/GCS-Infra-Live)
  <details>
    <summary><b>Ver funciones</b></summary>

    - Despliegue por ramas: **pruebas → promoción** (flujo controlado)
    - CI/CD con GitHub Actions (plan/apply por entorno)
    - Integración con **Ansible** para post-config cuando aplica
    - Enfoque en buenas prácticas: estructura por entornos + cambios reproducibles
  </details>

- **AZ-Bootstrap** (✅ Terminado) — Bootstrap en Azure siguiendo buenas prácticas y base reutilizable.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/S4M73109/AZ-Bootstrap)
  <details>
    <summary><b>Ver funciones</b></summary>

    - Base “bootstrap” preparada para extender a **infra live**
    - CI/CD con GitHub Actions + autenticación (según escenario: OIDC/SP)
    - Estructura modular orientada a despliegues futuros
  </details>

- **AZ-InfraLive** (🚧 En curso) — Infra por staging/prod con pipelines y hardening progresivo.  
  [![Repo](https://img.shields.io/badge/Repo-181717?style=flat&logo=github&logoColor=white)](PON_AQUI_EL_LINK)
  <details>
    <summary><b>Ver funciones</b></summary>

    - Separación de entornos: **staging/prod**
    - 
    - 
  </details>

> **Access hardening:** GCP **OS Login** · Azure **SP/Entra ID** · políticas de acceso gestionadas con **Terraform**.



  
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
  <sub>GCP: OS Login • Azure: SP/Entra ID • Access policies administrado por Terraform.</sub>
</details>


### Contacto
- Escríbeme por **Malt** (arriba) o por [**LinkedIn**](https://www.linkedin.com/in/samuelillobaby/)
