[![Cogniteo](https://cogniteo.io/images/icononly_transparent_nobuffer.png)](https://cogniteo.io)

# [Awesome Platform Engineering](https://github.com/Cogniteo/awesome-platform-engineering)

Collection of information on Platform Engineering and Internal Developer Platforms.

## Table of Contents
- [Platform Engineering](#platform-engineering)
- [Internal Developer Platform](#internal-developer-platform)
- [Internal Developer Portal](#internal-developer-portal)
- [Kubernetes Operator Pattern](#kubernetes-operator-pattern)

## Platform Engineering

### YouTube
- [HashiCorp: What is an Internal Developer Platform (IDP)?](https://youtu.be/2Nrlkn-km5A?si=jUuIg70NWKBVcKUf)
- [DevOps Toolkit: How To Create A Complete Internal Developer Platform (IDP)?](https://youtu.be/Rg98GoEHBd4?si=0rQ2hA411-EUdRNx)

## Reference Architecture

- [Pini Reznik: The Platform Reference](https://www.linkedin.com/posts/pinireznik_%F0%9D%97%A7%F0%9D%97%B5%F0%9D%97%B2-%F0%9D%97%A3%F0%9D%97%B9%F0%9D%97%AE%F0%9D%98%81%F0%9D%97%B3%F0%9D%97%BC%F0%9D%97%BF%F0%9D%97%BA-%F0%9D%97%A5%F0%9D%97%B2%F0%9D%97%B3%F0%9D%97%B2%F0%9D%97%BF%F0%9D%97%B2%F0%9D%97%BB%F0%9D%97%B0%F0%9D%97%B2-activity-7308078358460882946-Titz)

## KPIs and Metrics
- [DevOps Research and Assessment (DORA)](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance)
- [Backstage](https://backstage.io/docs/next/overview/adopting)
- [Puppet](https://www.puppet.com/blog/platform-engineering-metrics)

## Internal Developer Portal
- [Backstage](https://www.backstage.com)

## Kubernetes Operator Pattern

Introduction: https://kubernetes.io/docs/concepts/extend-kubernetes/operator

### Infrastructure Management

| Vendor                  | Name                                        | Type        | GitHub                                                      | Notes                |
|-------------------------|---------------------------------------------|-------------|-------------------------------------------------------------|----------------------|
| Amazon                  | AWS Controllers for Kubernetes (ACK)        | Open Source | https://github.com/aws-controllers-k8s                      |                      |
| Microsoft               | Azure Service Operator for Kubernetes (ASO) | Open Source | https://github.com/Azure/azure-service-operator             |                      |
| Google                  | GCP Config Connector                        | Open Source | https://github.com/GoogleCloudPlatform/k8s-config-connector |                      |
| Microsoft Google Amazon | Kube Resource Orchestrator (kro)            | Open Source | https://github.com/kro-run/kro                              |                      |
| Microsoft Alibaba       | openvela                                    | Open Source | https://github.com/open-vela                                |                      |
| Upbound                 | Crossplane                                  | Open Source | https://github.com/crossplane/crossplane                    | Terraform dependency |

### Why Terraform, Ansible, etc.. is bad?

#### LinkedIn

- [Daniel Gugel: "DevOps Engineers: Bash, Python, Terraform, and Ansible are not automation tools."](https://www.linkedin.com/posts/dangugel_bash-python-ansible-activity-7310705736345387008-NvWV)
