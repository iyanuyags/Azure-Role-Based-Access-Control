# Azure Role-Based Access Control Implementation Lab

## Project Overview

This project demonstrates the implementation of **Role-Based Access Control (RBAC)** in Microsoft Azure.  

The lab showcases how to:

- Create Microsoft Entra ID (Azure AD) security groups
- Assign users to groups
- Implement role-based permissions at subscription scope
- Enforce the Principle of Least Privilege
- Manage identities using Portal, PowerShell, and CLI

All resources were deployed in the **West US** region.


## Lab Objectives

- Create Senior Admins group and add Joseph Price using the Azure Portal
- Create Junior Admins group and add Isabel Garcia using the PowerShell 
- Create Service Desk group and add Dylan Williams using the Azure CLI
- Assign Virtual Machine Contributor role to the Service Desk group  
- Test the implemented access control


## Technologies & Services Used

- Microsoft Entra ID (Azure AD)
- Azure Role-Based Access Control (RBAC)
- Azure Portal
- Azure PowerShell
- Azure CLI
- Subscription-level role assignments



# Implementation Walkthrough

## Creating the Senior Admins Group using Azure Portal

Steps performed:

1. Navigated to Microsoft Entra ID
2. Created a new Security Group named Senior Admins
3. Added user Joseph Price as a member

This demonstrates GUI-based identity administration.

Senior Admins Group Creation



![Senior Admins Group](images/senior-admins.png)


## Creating the Senior Admins Group using Azure Portal

## Why Assign Roles to Groups Instead of Users?
- Improves scalability
- Simplifies onboarding/offboarding
- Reduces administrative overhead
- Supports Zero Trust architecture
- Enhances auditability


## Security Concepts Demonstrated

- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Subscription-level scope control
- Delegated administration
- Automation using PowerShell & CLI
- Principle of Least Privilege
- Access governance best practices


## Skills Demonstrated
- Azure identity governance
- RBAC configuration and enforcement
- Cloud access control implementation
- PowerShell automation
- Azure CLI administration
- Secure delegation of privileges


## Real-World Enterprise Relevance
In enterprise cloud environments, improper access control is a leading cause of breaches.
RBAC ensures:
- Controlled privilege distribution
- Reduced attack surface
- Compliance with governance standards
- Prevention of privilege escalation
- Clear separation of duties
- This lab reflects production-grade cloud security practices used in corporate environments.


## Conclusion
This lab demonstrates practical implementation of Azure RBAC using multiple management interfaces while enforcing structured identity governance.
It highlights secure access delegation and cloud security best practices relevant to:
- Cloud Security Engineer
- Azure Administrator
- IAM Analyst
- SOC Analyst

