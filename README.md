# AzurePIM
Full documentation and testing report for Microsoft Entra PIM (Privileged Identity Management) implementation, covering Just-In-Time access, role management, privileged access groups, approvals, audit logging, and break-glass accounts.
# Azure Privileged Identity Management (PIM) Implementation

This repository contains comprehensive documentation of the implementation and testing of Microsoft Entra Privileged Identity Management (PIM). The project aims to enhance the security posture of Azure environments by enabling Just-In-Time (JIT) access, approval workflows, privileged access groups, access reviews, auditing, and emergency break-glass accounts.

## Overview

Microsoft Entra PIM allows organizations to manage, control, and monitor access to important resources within Azure. It enforces the principle of least privilege by enabling time-bound role activation and requiring approval for privileged roles.

All steps in this project have been configured and tested using a real Azure Active Directory tenant.

## Contents

| File Name                             | Description                                             |
|--------------------------------------|---------------------------------------------------------|
| 01_Introduction.docx                 | Project overview, goals, and scope                      |
| 02_Prerequisites.docx                | License, tenant setup, and account configuration        |
| 03_JIT_Activation.docx               | Just-In-Time activation setup and test                  |
| 04_Entra_Roles_PIM.docx              | Managing Microsoft Entra roles with PIM                 |
| 05_Resource_Roles_PIM.docx           | Configuring Azure resource roles in PIM                 |
| 06_Privileged_Groups.docx            | Setup of Privileged Access Groups                       |
| 07_Approval_Process.docx             | Implementing request and approval workflow              |
| 08_Audit_History.docx                | Viewing and analyzing PIM audit logs                    |
| 09_Breakglass_Accounts.docx          | Creating and testing break-glass accounts               |
| 10_Eligible_Active_Roles.docx        | Understanding eligible vs active roles                  |
| 11_Time_Limits_Access_Review.docx    | Configuring role time limits and access reviews         |
| 12_Final_Summary.docx                | Summary and conclusions of the implementation           |

## Accounts Used

The following accounts were configured for testing and implementation:

| Account Email                               | Purpose                    |
|--------------------------------------------|----------------------------|
| GunishBakshi@Bakshi2004.onmicrosoft.com     | Global Admin               |
| admin@Bakshi2004.onmicrosoft.com            | Role Admin                 |
| reviewer@Bakshi2004.onmicrosoft.com         | PIM Request Reviewer       |
| breakglass@Bakshi2004.onmicrosoft.com       | Emergency Break-Glass Use |

## How to Use

1. Clone or download the repository.
2. Open the Word documents in order to follow the step-by-step implementation.
3. Each document includes placeholders for screenshots which can be replaced with your own if replicating.

## License

This project is provided under the MIT License. You are free to reuse and modify the documentation.

## Author

Gunish Bakshi  
gunishbakshi@gmail.com
