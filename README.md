[![Cogniteo](https://cogniteo.io/images/icononly_transparent_nobuffer.png)](https://cogniteo.io)

# [Awesome Platform Engineering](https://github.com/Cogniteo/awesome-platform-engineering)

Collection of information on Platform Engineering, Cloud Native Platform Mesh, and Internal Developer Platforms.

# Table of Contents
- [Platform Engineering](#platform-engineering)
- [Internal Developer Platform](#internal-developer-platform)
- [Internal Developer Portal](#internal-developer-portal)
- [Platform Mesh](#platform-mesh)
- [Kubernetes Operator Pattern](#kubernetes-operator-pattern)
- [Automation](#automation)

# Platform Engineering

## YouTube
- [HashiCorp: What is an Internal Developer Platform (IDP)?](https://youtu.be/2Nrlkn-km5A?si=jUuIg70NWKBVcKUf)
- [DevOps Toolkit: How To Create A Complete Internal Developer Platform (IDP)?](https://youtu.be/Rg98GoEHBd4?si=0rQ2hA411-EUdRNx)

# Internal Developer Platform

## Return of Investment (ROI)
- [Natan Yellin: Dollars and DevOps: The business case for Internal Developer Platforms](https://www.youtube.com/live/zKU5bdgJ0uE?si=zww_p4MgQH99RY3G)
- [Bartek Antoniak: The economics of internal developer platforms](https://www.engineeringprimer.com/p/the-economics-of-internal-developer)


## Reference Architecture

- [Pini Reznik: The Platform Reference](https://www.linkedin.com/posts/pinireznik_%F0%9D%97%A7%F0%9D%97%B5%F0%9D%97%B2-%F0%9D%97%A3%F0%9D%97%B9%F0%9D%97%AE%F0%9D%98%81%F0%9D%97%B3%F0%9D%97%BC%F0%9D%97%BF%F0%9D%97%BA-%F0%9D%97%A5%F0%9D%97%B2%F0%9D%97%B3%F0%9D%97%B2%F0%9D%97%BF%F0%9D%97%B2%F0%9D%97%BB%F0%9D%97%B0%F0%9D%97%B2-activity-7308078358460882946-Titz)
- [Apeiro by SAP](https://documentation.apeirora.eu)

## KPIs and Metrics
- [DevOps Research and Assessment (DORA)](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance)
- [Backstage](https://backstage.io/docs/next/overview/adopting)
- [Puppet](https://www.puppet.com/blog/platform-engineering-metrics)

# Internal Developer Portal

## Adoption

### Market Share
<img width="642" alt="Portals Market Share" src="https://github.com/user-attachments/assets/2d619c98-cbcc-44e8-86c5-d71f85bf9ae2" />

### Backstage Adoption
<img width="688" alt="Bacsktage Adoption" src="https://github.com/user-attachments/assets/30739587-7dc5-4a3f-8a9e-a3234d01ea73" />

Source: https://youtu.be/7PeEK83Eg1g?si=LYlwIFQILqWSRSHS

## Portals
- [Backstage](https://www.backstage.com)
- [Port](https://www.port.io)
- [Cortex](https://www.cortex.io)
- [Krateo](https://krateo.io)

# Kubernetes Operator Pattern

Introduction: https://kubernetes.io/docs/concepts/extend-kubernetes/operator

## Enterprises using Kubernetes Operators 
- [Mercedes: How to Migrate 700 Kubernetes Clusters to Cluster API with Zero Downtime](https://youtu.be/KzYV-fJ_wH0?si=dB2OymzyqxwUuau1)
  - ClusterAPI 
- [Michelin: Driving Innovation at Michelin: How We Scaled Cloud & On-Prem](https://youtu.be/l1JNAqAvpPw?si=MtOuJpS8qkhHO44o)
  - ClusterAPI + Crossplane
- [SAP: Kyma](https://kyma-project.io)
  - Kyma
- [SAP: Gardener](https://gardener.cloud)
  - Gardener
- [VMware: Cluster API Intro and Deep Dive](https://youtu.be/9H8flXm_lKk?si=tm-qwsqlBpk8sy14)
  - ClusterAPI

## Enterprises using Internal Developer Portals 
- [Airbnb, Booking.com, Toyota, Lego, Philips using Backstage](https://youtu.be/7PeEK83Eg1g?si=AhhSNqFIgv6Laba1)
  - Backstage

## Infrastructure Management Operators

| Vendor                     | Name                                        | Type        | GitHub                                                      | Notes                   |
|----------------------------|---------------------------------------------|-------------|-------------------------------------------------------------|-------------------------|
| Amazon                     | AWS Controllers for Kubernetes (ACK)        | Open Source | https://github.com/aws-controllers-k8s                      |                         |
| Microsoft                  | Azure Service Operator for Kubernetes (ASO) | Open Source | https://github.com/Azure/azure-service-operator             |                         |
| Google                     | GCP Config Connector                        | Open Source | https://github.com/GoogleCloudPlatform/k8s-config-connector |                         |
| Microsoft, Google, Amazon  | Kube Resource Orchestrator (kro)            | Open Source | https://github.com/kro-run/kro                              |                         |
| Microsoft, Alibaba         | openvela                                    | Open Source | https://github.com/open-vela                                |                         |
| Microsoft, IBM, VMWare     | ClusterAPI (CAPI)                           | Open Source | https://github.com/kubernetes-sigs/cluster-api              |                         |
| SAP                        | Gardener                                    | Open Source | https://github.com/gardener/gardener                        |                         |
| Upbound                    | Crossplane                                  | Open Source | https://github.com/crossplane/crossplane                    | Terraform dependency    |

## Control Planes & API Mesh

| Vendor                     | Name                                        | Type        | GitHub                                                      | Notes                   |
|----------------------------|---------------------------------------------|-------------|-------------------------------------------------------------|-------------------------|
| Kubermatic, RedHat, VMware | kcp                                         | Open Source | https://github.com/kcp-dev                                  | API Mesh + Multicluster |
| Clastix                    | Kamaji                                      | Open Source | https://github.com/clastix/kamaji                           | Control Plane Manager   |

## Why Terraform, Ansible, etc.. is bad?

### LinkedIn
- [Daniel Gugel: "DevOps Engineers: Bash, Python, Terraform, and Ansible are not automation tools."](https://www.linkedin.com/posts/dangugel_bash-python-ansible-activity-7310705736345387008-NvWV)

# Automation

## Maturity Levels

### History
![image](https://github.com/user-attachments/assets/73d91f25-06da-45e1-af27-2d684141bf2d)

### Available Models
![image](https://github.com/user-attachments/assets/1e4329d4-5adc-44c3-9e95-d26821c18997)

### RedHat Proposal
![image](https://github.com/user-attachments/assets/806b4064-d850-47eb-bc63-c025831f9f04)


## Patterns
- [Controller Pattern by SAP](https://documentation.apeirora.eu/next/digital-twins/controller#proportional-integral-derivative)
- [Controller Pattern by Google](https://kubernetes.io/docs/concepts/architecture/controller)
- [Kubernetes Operator Pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator)
- [PID: Proportional-Integral-Derivative](https://en.wikipedia.org/wiki/Proportional%E2%80%93integral%E2%80%93derivative_controller)



