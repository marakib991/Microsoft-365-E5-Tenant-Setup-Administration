# Microsoft 365 E5 Tenant Setup & Administration

This project documents the setup and configuration of a Microsoft 365 E5 tenant, showcasing skills in **identity management, security hardening, mailbox administration, SharePoint provisioning, and compliance enforcement**.  

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

#### Enabled **Multi-Factor Authentication (MFA)** and **SMS** Authentication: 

MFA was turned on for all users and switched to *enable (legacy mode)* from *Microsoft Managed*. Also, the *lockout threshold* was set to 10, and the **SMS** authentication method policy was enabled for users' sign-in.

  ---
<img width="1268" height="615" alt="Image" src="https://github.com/user-attachments/assets/6e001642-e8a1-4922-9188-46f1dc29fbba" />
<img width="1167" height="881" alt="Image" src="https://github.com/user-attachments/assets/eb1cc7d8-e3b8-4d80-bbcc-e1a9619f80b8" />
<img width="1372" height="765" alt="Image" src="https://github.com/user-attachments/assets/7226f6a6-94e8-4ae9-9d04-18e8f57d9364" />
<img width="1410" height="761" alt="Image" src="https://github.com/user-attachments/assets/08f344e3-caad-4b19-bb00-74c2190c750c" />
<img width="1554" height="661" alt="Image" src="https://github.com/user-attachments/assets/7dc9b381-f32e-431b-a0fc-632ab339880a" />
<img width="1554" height="783" alt="Image" src="https://github.com/user-attachments/assets/6001ac2a-ec14-4585-b07e-42c5b75ffcf5" />
<img width="1554" height="628" alt="Image" src="https://github.com/user-attachments/assets/ded2a74d-86ae-4160-a8bb-eb2e110324d3" />
<img width="1554" height="659" alt="Image" src="https://github.com/user-attachments/assets/86f5f686-8885-459f-a5d9-625db708c959" />
<img width="1554" height="647" alt="Image" src="https://github.com/user-attachments/assets/54121598-6e30-4da8-82b8-fbcbe7a39daf" />

---

#### Added aliases for *abc xyz* user:

---
<img width="1360" height="641" alt="Image" src="https://github.com/user-attachments/assets/4dc58bc8-f2bc-4abd-a60d-67ce615b4874" />
<img width="1360" height="632" alt="Image" src="https://github.com/user-attachments/assets/13254b40-eb9b-4d80-82d8-0e5ecbcc4c62" />
<img width="1360" height="616" alt="Image" src="https://github.com/user-attachments/assets/0a44a51e-ea0e-4608-869a-068d24d1b482" />

---

#### Added contracts information to user profiles (e.g., *Mohammad Abdur Rakib*).


---

### 2. Group Administration

#### Created an **IT group**:

Navigated through the **MS365 admin center** to *Active teams & groups* and created a new group with email `itsupport@mar101.onmicrosoft.com` and kept it *public*.

---
<img width="1554" height="823" alt="Image" src="https://github.com/user-attachments/assets/5c2f7ad3-addb-4913-9b2a-4ebc44ec677a" />
<img width="1224" height="667" alt="Image" src="https://github.com/user-attachments/assets/c396da4d-5b4a-4b3c-8828-38747e19a468" />
<img width="1368" height="745" alt="Image" src="https://github.com/user-attachments/assets/831eae46-b4f2-47b8-b10e-cd1e84cb9328" />
<img width="1262" height="744" alt="Image" src="https://github.com/user-attachments/assets/f002a055-af1c-4be6-aa22-c836bb42c438" />
<img width="1267" height="563" alt="Image" src="https://github.com/user-attachments/assets/98cf7d50-d279-4eca-9eb7-e632042ea79c" />
<img width="1554" height="1120" alt="Image" src="https://github.com/user-attachments/assets/21be4028-5ea5-451a-9160-b07672e29076" />
<img width="1320" height="585" alt="Image" src="https://github.com/user-attachments/assets/5b60d755-bd7c-4699-a323-97084123f791" />
<img width="1259" height="665" alt="Image" src="https://github.com/user-attachments/assets/503a4608-8af9-4769-813d-c3894297795f" />
<img width="1548" height="943" alt="Image" src="https://github.com/user-attachments/assets/84eb766a-57cc-4307-8d7f-a05c5f6c171f" />
<img width="1548" height="726" alt="Image" src="https://github.com/user-attachments/assets/536657dc-e438-4506-bb43-d0578468af9e" />

---
- Updated group email to `it@mar101.onmicrosoft.com`.
- Deleted and restored the default **All Company** group.

---
### 3. Mailbox Configuration
- Created a **shared mailbox** `itsupport@mar101.onmicrosoft.com`.
- Added members (`abc xyz`, `helpdesk`) to the shared mailbox.
- Configured **email forwarding** for `ceo@mar101.onmicrosoft.com`.
- Set **automatic replies** with different messages for internal vs. external personnel.
- Adjusted **Sent Items settings**:
  - Copy to mailbox
  - Copy on behalf
- Granted **Send on Behalf permissions** to admin users.

  ---

### 4. SharePoint Administration
- Created a **SharePoint site** named `itsupport`.
- Added members and configured permissions/restrictions.

  ---

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

