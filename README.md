# Microsoft Entra ID & Privileged Identity Management (PIM) Lab Walkthrough

This repository contains a complete, step-by-step visual documentation and lab guide for performing identity governance, user management, authentication setups, enterprise application management, and Privileged Identity Management (PIM) tasks within the Microsoft Entra admin center.

---

## 📋 Table of Contents
1. [User Overview & Profile Management](#1-user-overview--profile-management)
2. [Authentication & Multi-Factor Authentication (MFA) Setup](#2-authentication--multi-factor-authentication-mfa-setup)
3. [Tenant Overview & App Management](#3-tenant-overview--app-management)
4. [Privileged Identity Management (PIM) Role Assignment](#4-privileged-identity-management-pim-role-assignment)

---

## 1. User Overview & Profile Management
Administrators can oversee user directories, inspect active accounts, and manage identities across the tenant.

* **User Profile - Chris Green:** Viewing details for user **Chris Green** (`ChrisG@wwlx313810.onmicrosoft.com`), verifying basic account information, user principal name, Object ID, and account status[cite: 10].
  
  ![Chris Green Profile](1.jpg)

---

## 2. Authentication & Multi-Factor Authentication (MFA) Setup
Users enrolling in multi-factor authentication setup their security info using the Microsoft Authenticator application.

* **QR Code Registration:** Scanning the generated QR code using the Microsoft Authenticator app to link the user account[cite: 1].
  
  ![Scan QR Code](3.jpg)

* **Authenticator Confirmation:** Verifying successful registration of the Microsoft Authenticator app as the default sign-in method[cite: 2].
  
  ![Authenticator Added](4.jpg)

---

## 3. Tenant Overview & App Management
Administrators manage organization-wide tenant status, application catalogs, and single sign-on (SSO) configurations.

* **Microsoft Entra Admin Center Dashboard:** Overview of tenant status, user risk metrics, and quick shortcuts for administrative tasks[cite: 3].
  
  ![Entra Dashboard](5.jpg)

* **Enterprise Applications Listing:** Inspecting integrated tenant applications, application IDs, homepage URLs, and activation statuses[cite: 4].
  
  ![Enterprise Applications](6.jpg)

* **App Gallery Navigation:** Browsing cloud platforms such as AWS, Google Cloud Platform, and Oracle from the Microsoft Entra App Gallery[cite: 5].
  
  ![App Gallery](7.jpg)

---

## 4. Privileged Identity Management (PIM) Role Assignment
Administrators assign and govern privileged directory roles using just-in-time and role duration controls.

* **Selecting Member for Assignment:** Searching and selecting **Chris Green** (`ChrisG@wwlx313810.onmicrosoft.com`) as the target user during role assignment[cite: 9, 11].
  
  ![Selecting Member](11.jpg)

* **Role & Scope Configuration:** Assigning the **Application Administrator** role under the Directory scope[cite: 6].
  
  ![Role Assignment Details](8.png)

* **Setting Assignment Properties:** Configuring the assignment type as **Active**, setting the duration boundaries, and entering the mandatory business justification (*"Required for managing app permissions and SSO configurations"*)[cite: 7].
  
  ![Assignment Settings](9.png)

* **Roles & Administrators Directory:** Reviewing administrative role definitions, permissions, and built-in directory assignments[cite: 8].
  
  ![Roles and Administrators](10.jpg)

---

## 📁 Repository Structure
```text
├── README.md
└── Screenshots/
    ├── 1.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    ├── 6.jpg
    ├── 7.jpg
    ├── 8.png
    ├── 9.png
    ├── 10.jpg
    └── 11.jpg
