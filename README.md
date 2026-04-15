# Microsoft 365 Security & Identity Lab

## Overview
This project demonstrates the configuration of identity and access management controls within Microsoft Entra ID. It simulates real-world IT support and security scenarios, including user management, Conditional Access policy enforcement, and authentication monitoring.

## Lab Setup
- Created users:
  - helpdesk.user
  - finance.user
  - test.admin (Helpdesk Administrator)
- Created groups:
  - MFA-Test-Group
  - Finance-Group
- Assigned Azure AD Premium P1 licenses
- Configured role-based access control (RBAC)

## Implementation
- Configured Conditional Access policy to enforce MFA
- Applied policy to MFA-Test-Group
- Enabled MFA authentication
- Verified sign-in activity using Entra logs

## Scenarios

### Scenario 1: MFA Enforcement
User login required MFA and was successfully authenticated.

### Scenario 2: Role-Based Access Control (RBAC)
Standard user was denied access to the Microsoft 365 Admin Center due to insufficient permissions.

### Scenario 3: Failed MFA Authentication
User denied the MFA request, resulting in access being blocked despite correct credentials.

## Key Outcomes
- Enforced MFA using Conditional Access
- Demonstrated least privilege access control
- Analysed authentication events using Entra logs
- Simulated real-world IT support and security scenarios
