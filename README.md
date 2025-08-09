# Enterprise-PKI-Authentication-
Enterprise PKI and Certificate based authentication with Windows server active directory certificate services. 

Project Overview
This project implements an Enterprise Public Key Infrastructure (PKI) using Active Directory Certificate Services (ADCS) on Windows Server 2016. The PKI enables secure authentication, encryption, and digital signing within the domain by issuing certificates to users, computers, and services.

Features
- Enterprise Root Certification Authority deployment.

- Certificate templates for users, computers, and services.

- Auto-enrollment of certificates via Group Policy.

- Integration with Active Directory for authentication.

- Support for secure email, VPN, Wi-Fi, and SSL/TLS.

System Requirements
- Windows Server 2016 with ADCS role installed.

- Active Directory domain environment.

- Proper DNS configuration.

Setup Instructions
1. Install and configure the ADCS role as an Enterprise Root CA.

2. Create and configure certificate templates.

3. Configure Group Policy for certificate auto-enrollment.

4. Deploy certificates to clients and services.

5. Manage certificate revocation lists (CRL) and CA lifecycle.

Testing
- Verify certificate issuance and auto-enrollment.

- Test certificate-based authentication on client machines.

- Confirm secure communication (e.g., SSL VPN, Wi-Fi authentication).

Notes
- Protect the CA private key securely.

- Regularly publish and monitor CRLs.

- Plan CA backup and disaster recovery.

