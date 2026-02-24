###About This Project###
All code in this repository is written by me. During development I rely on the official Terraform AzureRM provider documentation for reference, available at:
https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs

The documentation is used only to understand resource definitions, arguments, and recommended usage patterns.
Anyone is free to use, study, or adapt the code in this repository. I hope it will be useful for others who are learning Azure, Terraform, or cloud architecture best practices.

This project is deployed to my private Azure subscription and is intended exclusively for educational and testing purposes.

###What an Azure Landing Zone Is###
An Azure Landing Zone is a Microsoft‑recommended architectural framework for building a secure, scalable, and well‑governed cloud environment. It is part of the Cloud Adoption Framework (CAF) and provides a comprehensive set of best practices covering:

management group hierarchy and subscription organization

governance, policy enforcement, and compliance

identity and access management

network topology (commonly Hub and Spoke)

security baselines and guardrails

monitoring, logging, and operational insights

automation and Infrastructure as Code

A full Azure Landing Zone is designed for enterprise‑scale environments, multi‑team operations, and long‑term governance across multiple subscriptions.

###What This Project Is###
This repository contains a simplified, educational implementation inspired by Azure Landing Zone best practices.
It is not a full enterprise deployment. Instead, it focuses on:

learning and applying the core principles of CAF

practicing Infrastructure as Code using Terraform

understanding governance, policy assignments, and RBAC

building a functional Hub and Spoke network architecture

enabling monitoring and diagnostic logging

structuring code in a modular, maintainable way

demonstrating cloud engineering skills in a portfolio‑ready format

The project is intentionally scoped to a single subscription and a single landing zone (dev) to keep it manageable for learning.

###Differences Between a Full Azure Landing Zone and This Project###
Area	Full Azure Landing Zone	                                                            This Project
Scope	Enterprise‑scale, multi‑subscription, multi‑team	                                Single subscription, educational scope
Governance	Full CAF policy sets, compliance frameworks, automation	                        Selected policies focused on learning best practices
Networking	Production‑grade Hub and Spoke with firewalls, gateways, private endpoints	    Simplified Hub and Spoke suitable for testing
Identity	Enterprise identity integration, PIM, conditional access	                    Basic RBAC and identity structure for learning
Security	Advanced controls, SOC integration, threat protection	                        Core security policies and logging
Automation	CI/CD pipelines, GitOps, drift detection	                                    GitHub Actions for validation and deployment
Operational Model	Multiple landing zones (dev, test, prod, shared services)	            One landing zone (dev) for demonstration
In summary:

Azure Landing Zone is a complete enterprise blueprint.

This project is a scaled‑down, best‑practice‑aligned implementation designed for learning and experimentation.
>>>>>>> b9a6fdb (Create README.md with project information and goals.)
