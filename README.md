![](https://raw.githubusercontent.com/CrowdStrike/falconpy/main/docs/asset/cs-logo.png)

[![HIPAA](https://app.soluble.cloud/api/v1/public/badges/c64fe6c3-808e-4f74-be42-50d1df312b61.svg)](https://app.soluble.cloud/repos/details/github.com/bvenkat-lw/cloud-aws)  [![IaC](https://app.soluble.cloud/api/v1/public/badges/a56af908-06de-4671-8f58-f3e785f0536b.svg)](https://app.soluble.cloud/repos/details/github.com/bvenkat-lw/cloud-aws)  [![CIS](https://app.soluble.cloud/api/v1/public/badges/2b7041d7-fc31-4b01-87db-e0743d64d67e.svg)](https://app.soluble.cloud/repos/details/github.com/bvenkat-lw/cloud-aws)  


## AWS Service Integrations
| Integration Name | Description |
|:-|:-|
| [AWS Control Tower with CrowdStrike Discover for Cloud and Containers](Control-Tower/README.md) | Configure AWS Control Tower to register new AWS accounts with CrowdStrike Discover for Cloud and Containers. |
| [AWS Control Tower with CrowdStrike Horizon](Control-Tower-For-Horizon/README.md) | Configure AWS Control Tower to register new AWS accounts with CrowdStrike Horizon. |
| [AWS Network Firewall with CrowdStrike Threat Intelligence](Network-Firewall/README.md) | Build capabilities such as automated blocking of malicious domains (via AWS Network Firewall) based on CrowdStrike detection alerts, or perform threat hunting derived from CrowdStrike domain-based Indicators of Activity (IOAs). |
| [AWS Private Link with CrowdStrike Sensor Proxy](aws-privatelink/README.md) | Utilize AWS PrivateLink to provide provide private connectivity between your CrowdStrike Falcon protected workloads and the CrowdStrike cloud. |
| [AWS Security Hub with CrowdStrike Event Streams API](Falcon-Integration-Gateway/README.md) | The Falcon Integration Gateway publishes detections identified by CrowdStrike Falcon for instances residing within Amazon Web Services (AWS) to AWS Security Hub. |

## CrowdStrike Sensor Automation
| Integration Name | Description |
|:-|:-|
| [AWS Autoscale Groups for Auto Register/Deregister](Agent-Install-Examples/Cloudformation/autoscale/README.md) | Utilize AWS Autoscale Groups to install the CrowdStrike Falcon Sensor during virtual machine initialization, and AWS Autoscale Lifecycle hooks to deregister the instance with CrowdStrike upon virtual machine termination. |
| [AWS Systems Manager Parameter Store with PowerShell Sensor Installation Script](Agent-Install-Examples/powershell) | Sample automation which leverages AWS Systems Manager Parameter Store to store CrowdStrike API credentials. These credentials are passed into a Microsoft PowerShell script to bootstrap the CrowdStrike Falcon Sensor for Windows during a Windows virtual machine's first boot process. |
| [AWS Systems Manager with Linux BASH Sensor Installation Script](Agent-Install-Examples/bash) | POSIX script that will install CrowdStrike sensor. The script is current tailored to the use within AWS Systems Manager, but can be used outside the Systems Manager. |
| [AWS Terraform Template for Sensor Installation](Agent-Install-Examples/Terraform-bootstrap-s3) | Sample AWS Terraform template that builds a test VPC, creates an Ubuntu-based web server, and automatically installs the CrowdStrike Falcon sensor into the virtual machine. |