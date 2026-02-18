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

Demonstrates manual identity and group management using the Azure Portal to implement structured administrative access.

<p align="center"><strong>Figure 1: Senior Admins Group Creation</strong></p>

<p align="center">
  <img src="images/senior-admins.png" width="700" height="400">
</p>

## Creating the Junior Admins Group using Azure Powershell

Steps performed:

1. Navigated to Azure Powershell
2. Created a new Security Group named Junior Admins
3. Added user Isabel Garcia as a member

This demonstrates manual identity and group management using the Azure Portal to implement structured administrative access.

## Creating the Service Desk Group using Azure CLI

Steps performed:

1. Navigated to Azure CLI
2. Created a new Security Group named Service Desk
3. Added user Dylan Williams as a member


## Assigning the Virtual Machine Contributor Role to the Service Desk Group

Steps performed:

1. Navigated to Azure Portal
2. Opened Subscriptions and selected the appropriate subscription
3. Clicked on Access Control (IAM)
4. Selected Add role assignment
5. Chose the Virtual Machine Contributor role
6. Selected Service Desk group as the member
7. Reviewed and clicked Assign to complete the role assignment


## Why Assign Roles to Groups Instead of Individual Users?
- Improves scalability – Manage access for multiple users efficiently.
- Simplifies onboarding and offboarding – Roles automatically apply to new or departing users.
- Reduces administrative overhead – Less manual assignment and maintenance.
- Supports Zero Trust architecture – Access is granted based on roles, not individuals.
- Enhances auditability – Easier tracking and reporting of permissions.

## Reviewing role assignments to confirm proper access controls

Verified access controls by reviewing role assignments: Eneattah Ogebe holds the Virtual Machine Contributor role, and Oluwatobi Babalola has no assigned roles

## Security Concepts Highlighted

- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Subscription-level scope control
- Delegated administration
- Automation via PowerShell & Azure CLI
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

- In enterprise cloud environments, improper access control is a leading cause of security breaches. RBAC ensures:
- Controlled distribution of privileges
- Reduced attack surface
- Compliance with governance standards
- Prevention of privilege escalation
- Clear separation of duties
- This lab mirrors production-grade cloud security practices commonly used in corporate environments.

## Conclusion

This lab demonstrates the practical implementation of Azure RBAC across multiple management interfaces while enforcing structured identity governance. It emphasizes secure access delegation and cloud security best practices, providing relevant experience for roles such as:
- Cloud Security Engineer
- Azure Administrator
- IAM Analyst
- SOC Analyst
