# Microsoft 365 E5 Tenant Setup & Administration

This project documents the setup and configuration of a Microsoft 365 E5 tenant, showcasing skills in **identity management, security hardening, mailbox administration, SharePoint provisioning, and compliance enforcement**.  
It serves as a portfolio project to demonstrate practical IT support and systems administration expertise.

---

## Overview
- Created and accessed a Microsoft 365 E5 admin account.
- Configured users, groups, mailboxes, and security policies.
- Implemented SharePoint & OneDrive governance with secure permissions.
- Applied security & compliance policies (MFA, DLP, Conditional Access).
- Applied compliance controls aligned with **Canada’s Personal Information Protection and Electronic Documents Act (PIPEDA)**.

---

## Steps & Configuration

### 1. Identity & User Management

#### Created new users and added multiple accounts:

From **active users**, new users were created and assigned a license for each user. Additionally, the **Helpdesk** user was given **helpdesk administrator role access**.

  ---
  <img width="1022" height="577" alt="Image" src="https://github.com/user-attachments/assets/31e03114-d8c1-4c4a-a89d-ede7c7e87427" />
  <img width="887" height="557" alt="Image" src="https://github.com/user-attachments/assets/f857bf9f-7faa-4351-8c67-97cc60aba88e" />
  <img width="971" height="580" alt="Image" src="https://github.com/user-attachments/assets/d548f565-743b-4ee3-ac3d-c0dc5a8f2084" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/7d4ec5ba-f527-4e5a-baae-c463476e0537" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/33ca350a-5753-4836-beb0-b35e58a4d3ce" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/c04d2f07-22dc-42f4-a39d-4cc9fb950653" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/a54f7b5b-9e3f-4ff3-a3fb-ccbed0d46875" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/d9f15d7c-034c-4fe3-985a-13d3d9b7cc40" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/95cebba1-5d99-4729-a186-fec285af092a" />
  <img width="1554" height="779" alt="Image" src="https://github.com/user-attachments/assets/725a83fe-ffff-424a-820d-0d9c059d9898" />
  <img width="938" height="579" alt="Image" src="https://github.com/user-attachments/assets/1ebc44c3-fe73-4e08-a233-0241a3e3781d" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/c8d5ae2f-9c8a-487b-a850-f1a43bacf038" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/f8286e57-4ac1-476e-80d5-5095d578e0a2" />
  <img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/bf889233-3224-4f78-b324-8ffae3e834ca" />
  <img width="1554" height="774" alt="Image" src="https://github.com/user-attachments/assets/3e670d7b-d134-4515-9bcd-bf37542d6f61" />

---

- Enabled **Multi-Factor Authentication (MFA)**, switching from *Disabled* to *Microsoft Managed*.
- Configured **SMS authentication** for all users.
- Added aliases for specific users (e.g., `abc xyz`).
- Added contracts information to user profiles (e.g., *Mohammad Abdur Rakib*).

### 2. Group Administration
- Created an **IT group** with email `itsupport@mar101.onmicrosoft.com`.
- Updated group email to `it@mar101.onmicrosoft.com`.
- Deleted and restored the default **All Company** group.

### 3. Mailbox Configuration
- Created a **shared mailbox** `itsupport@mar101.onmicrosoft.com`.
- Added members (`abc xyz`, `helpdesk`) to the shared mailbox.
- Configured **email forwarding** for `ceo@mar101.onmicrosoft.com`.
- Set **automatic replies** with different messages for internal vs. external personnel.
- Adjusted **Sent Items settings**:
  - Copy to mailbox
  - Copy on behalf
- Granted **Send on Behalf permissions** to admin users.

### 4. SharePoint Administration
- Created a **SharePoint site** named `itsupport`.
- Added members and configured permissions/restrictions.

### 5. Security & Compliance
- Created a **Data Loss Prevention (DLP) policy**:  
  - **Canada Personal Information Protection Act (PIPEDA)**  
  - Blocks sharing of sensitive data (e.g., SIN, credit card numbers) with external users.

---

## Skills Demonstrated
- Microsoft 365 E5 administration
- Identity and access management
- Multi-Factor Authentication (MFA) configuration
- Group and mailbox administration
- SharePoint site provisioning
- Compliance and DLP policy creation
- Troubleshooting and documentation best practices

---

