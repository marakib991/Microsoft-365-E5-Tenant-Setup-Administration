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

#### Added aliases for `abc xyz` user:

<img width="1360" height="641" alt="Image" src="https://github.com/user-attachments/assets/4dc58bc8-f2bc-4abd-a60d-67ce615b4874" />
<img width="1360" height="632" alt="Image" src="https://github.com/user-attachments/assets/13254b40-eb9b-4d80-82d8-0e5ecbcc4c62" />
<img width="1360" height="616" alt="Image" src="https://github.com/user-attachments/assets/0a44a51e-ea0e-4608-869a-068d24d1b482" />

---

#### Added contracts information to user profiles named `Mohammad Abdur Rakib`:

<img width="1194" height="524" alt="Image" src="https://github.com/user-attachments/assets/eca89669-ff2b-4f06-8ef9-9498790205b4" />
<img width="1360" height="720" alt="Image" src="https://github.com/user-attachments/assets/df59f877-bd09-4887-8921-4f30bae685eb" />
<img width="1289" height="516" alt="Image" src="https://github.com/user-attachments/assets/fbf70dd6-b794-40cc-8536-376d5330766d" />
<img width="1356" height="527" alt="Image" src="https://github.com/user-attachments/assets/e45cb8f5-812f-4cc8-a43d-e49aaa504d3d" />

---

### 2. Group Administration

#### Created an **IT group**:

Navigated through the **MS365 admin center** to *Active teams & groups* and created a new group with email `itsupport@mar101.onmicrosoft.com` and kept it *public*.

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

#### Updated group email to `it@mar101.onmicrosoft.com`:

<img width="1288" height="701" alt="Image" src="https://github.com/user-attachments/assets/2c5137e6-be6b-4f9b-a6d3-e7bd2169ac63" />
<img width="1283" height="362" alt="Image" src="https://github.com/user-attachments/assets/af69446a-db4b-46d1-ae69-b2f52469c8e4" />
<img width="1064" height="455" alt="Image" src="https://github.com/user-attachments/assets/ac16fc9f-3e1d-48aa-910e-e872fd6119b4" />
<img width="1229" height="568" alt="Image" src="https://github.com/user-attachments/assets/b2b90fc1-7a93-4691-b5ef-c323c20f631f" />

---

#### Deleted and restored the default **All Company** group:

<img width="1221" height="743" alt="Image" src="https://github.com/user-attachments/assets/157b9a81-04ec-48ed-a714-a13f4801c851" />
<img width="1066" height="722" alt="Image" src="https://github.com/user-attachments/assets/7b140c15-12f2-4686-b86e-d8cef764c2ea" />
<img width="1140" height="577" alt="Image" src="https://github.com/user-attachments/assets/164bafb7-a31a-49b2-b487-b4706b57e1dd" />
<img width="1360" height="686" alt="Image" src="https://github.com/user-attachments/assets/5e9f1296-151a-40a7-9804-72209c323c0c" />
<img width="1360" height="588" alt="Image" src="https://github.com/user-attachments/assets/e5cb6bcd-c4f7-467c-b12e-677d482ff259" />
<img width="1229" height="606" alt="Image" src="https://github.com/user-attachments/assets/517536c6-4f3c-4276-8f7d-fb4e4ff647c7" />
<img width="1252" height="527" alt="Image" src="https://github.com/user-attachments/assets/bb9a42f9-d952-420b-88a7-bc017af6f5a7" />
<img width="1360" height="733" alt="Image" src="https://github.com/user-attachments/assets/1b6de0c7-506b-48cf-80cc-5f2fc3d33f45" />

---

### 3. Mailbox Configuration

#### Created a **shared mailbox**:

As `itsupport@mar101.onmicrosoft.com` email has already been used for the `IT group` as an alias email, deleted the alias and created a **shared mailbox** with `itsupport@mar101.onmicrosoft.com` email address.

<img width="1360" height="657" alt="Image" src="https://github.com/user-attachments/assets/8bbdcd13-9472-424d-994f-cb35402dd44a" />
<img width="1275" height="513" alt="Image" src="https://github.com/user-attachments/assets/9a89bb70-a0ea-45c4-a345-f2c72777c5fc" />
<img width="1198" height="496" alt="Image" src="https://github.com/user-attachments/assets/e135f314-d684-46db-a37e-51ea3ba1b96d" />
<img width="1284" height="608" alt="Image" src="https://github.com/user-attachments/assets/930d9121-6288-4b3b-8c37-89078c3cf182" />
<img width="1360" height="597" alt="Image" src="https://github.com/user-attachments/assets/ccd5b2fe-19b5-45f4-92fb-dc0c5d16613c" />
<img width="1315" height="575" alt="Image" src="https://github.com/user-attachments/assets/2133fbc0-2246-4e16-ac63-94b7eab38fa1" />
<img width="1303" height="488" alt="Image" src="https://github.com/user-attachments/assets/1dcb5c03-f03b-4bd1-ab77-8a0b81991abe" />
<img width="1299" height="506" alt="Image" src="https://github.com/user-attachments/assets/82c2d0e4-15cd-4860-a7c8-ed36331830a7" />

---

#### Added members (`abc xyz`, `helpdesk`) to the shared mailbox:

<img width="1293" height="498" alt="Image" src="https://github.com/user-attachments/assets/25053e68-9fb9-45e5-adee-a0f33c773d7f" />
<img width="1253" height="426" alt="Image" src="https://github.com/user-attachments/assets/47f58a62-5c2b-48a1-9860-9d47d605500a" />
<img width="1303" height="760" alt="Image" src="https://github.com/user-attachments/assets/5b97baf9-0ec3-40b0-8e53-712332ec2f16" />
<img width="1228" height="546" alt="Image" src="https://github.com/user-attachments/assets/819f249e-a38e-4eb1-bcc8-e3632c30efb6" />

---

#### Configured **email forwarding** for `ceo@mar101.onmicrosoft.com`:

<img width="1034" height="620" alt="Image" src="https://github.com/user-attachments/assets/a7575e65-0afd-4bf3-9c7a-4fa50d61c0bb" />
<img width="1360" height="685" alt="Image" src="https://github.com/user-attachments/assets/55c23e3c-0044-4f3e-9570-06f9f1060fec" />
<img width="1289" height="560" alt="Image" src="https://github.com/user-attachments/assets/50b00382-6aaa-452b-bc91-61dcb61e38f4" />
<img width="1099" height="596" alt="Image" src="https://github.com/user-attachments/assets/8913c565-f736-4340-afea-86646bc77115" />

---

#### Set **automatic replies** with different messages for internal vs. external personnel:

<img width="1186" height="646" alt="Image" src="https://github.com/user-attachments/assets/415a5d50-6d57-4867-835f-965f8ace3ec2" />
<img width="1248" height="710" alt="Image" src="https://github.com/user-attachments/assets/6f522842-4c5b-43bc-9e23-d1eb8e75b578" />
<img width="1208" height="638" alt="Image" src="https://github.com/user-attachments/assets/970e1a13-e113-4e3a-bbb1-556fd91e610f" />

---

#### Adjusted **Sent Items settings**:
  - Copy to mailbox was enabled
  - Copy on behalf was enabled

<img width="1002" height="560" alt="Image" src="https://github.com/user-attachments/assets/f90bc191-5ea3-4700-9d9a-8a28c1b0e0da" />
<img width="1103" height="510" alt="Image" src="https://github.com/user-attachments/assets/fea1c5c1-075b-45da-80d5-e2d3daea9cca" />
<img width="814" height="484" alt="Image" src="https://github.com/user-attachments/assets/895c66e1-64af-44cc-8825-c2178c79b2db" />

---

#### Granted **send on behalf permissions** to admin users:

<img width="1220" height="581" alt="Image" src="https://github.com/user-attachments/assets/4b078ef8-b882-4127-aab4-24c6b6c4f4ce" />
<img width="948" height="517" alt="Image" src="https://github.com/user-attachments/assets/b4edcf86-15c4-41d4-963e-661bc8bece8b" />
<img width="929" height="548" alt="Image" src="https://github.com/user-attachments/assets/6c740107-ec21-419a-9737-35837f145caf" />

  ---

### 4. SharePoint Administration

#### Created a **SharePoint site** named `itsupport2`:

Created a new **SharePoint site** with the **IT Helpdesk** template and added users.

<img width="919" height="522" alt="Image" src="https://github.com/user-attachments/assets/6b672543-1db1-4db0-b6c2-1b7abb967d9d" />
<img width="945" height="495" alt="Image" src="https://github.com/user-attachments/assets/7c0af2ce-c057-4e3a-a585-babf809a1112" />
<img width="1352" height="685" alt="Image" src="https://github.com/user-attachments/assets/05978e3e-5d75-4a80-b270-4a91d31bbd45" />
<img width="1333" height="753" alt="Image" src="https://github.com/user-attachments/assets/8008de05-c851-4480-89e7-dbf4b1f7304c" />
<img width="1321" height="762" alt="Image" src="https://github.com/user-attachments/assets/0448e63c-2331-4f1e-8f40-877a5348a4c3" />
<img width="1298" height="771" alt="Image" src="https://github.com/user-attachments/assets/47a3d706-37df-4869-876a-139dacb39d69" />
<img width="1252" height="758" alt="Image" src="https://github.com/user-attachments/assets/0e895aed-ef6f-4264-8bcc-04882917efdc" />
<img width="1274" height="762" alt="Image" src="https://github.com/user-attachments/assets/9e172c71-86e0-44cc-b468-01c27c42f3f5" />
<img width="1360" height="750" alt="Image" src="https://github.com/user-attachments/assets/bbc96c70-06b8-41a7-9248-89cab48209b2" />

---

#### Reviewed the initial user permissions:

<img width="1302" height="565" alt="Image" src="https://github.com/user-attachments/assets/b5fe7d03-5868-49d4-a3e0-d0c20305664a" />
<img width="957" height="656" alt="Image" src="https://github.com/user-attachments/assets/83513e6f-85c6-40a7-9f0b-502cfe7bcfda" />
<img width="1134" height="567" alt="Image" src="https://github.com/user-attachments/assets/29cabc19-2521-45e4-b172-a7c32a855ffd" />

  ---
  
#### Changed the initial site sharing settings from the **SharePoint site** page:

<img width="1298" height="446" alt="Image" src="https://github.com/user-attachments/assets/fa6773d1-4aa8-4507-b284-a7286c00728f" />
<img width="689" height="544" alt="Image" src="https://github.com/user-attachments/assets/e4194250-f1fd-4301-97d0-152abc2a2d34" />
<img width="954" height="752" alt="Image" src="https://github.com/user-attachments/assets/954bcbd5-7110-4438-b9ce-d1b77205b7b1" />

---

#### Configure **SharePoint site** and **OneDrive** policy:

Navigated through the **SharePoint admin center** to change the advanced **SharePoint site** and **OneDrive** sharing policy, so that only people from the organization can share the data from **OneDrive**. Also, modified the guest access policy and verification code reauthentication policy.

<img width="915" height="641" alt="Image" src="https://github.com/user-attachments/assets/e44ba7f2-4deb-43a0-8283-30af72ca1ac9" />
<img width="927" height="553" alt="Image" src="https://github.com/user-attachments/assets/84ee922e-2c8f-483f-bbac-b67b095d2cce" />
<img width="1210" height="668" alt="Image" src="https://github.com/user-attachments/assets/8c996b03-3b5e-4e38-9ce4-0e66cb518dd2" />
<img width="1128" height="682" alt="Image" src="https://github.com/user-attachments/assets/985d50c9-8c2e-4668-837d-64201e10ba04" />
<img width="1066" height="610" alt="Image" src="https://github.com/user-attachments/assets/22c1d7b2-2fc7-43c1-8839-48c55e9cc092" />
<img width="1113" height="550" alt="Image" src="https://github.com/user-attachments/assets/c67d21a3-2411-45cf-89e1-35004d196837" />
<img width="1157" height="745" alt="Image" src="https://github.com/user-attachments/assets/965d025c-0079-4a18-b52e-f9fb64b11ff4" />
<img width="977" height="669" alt="Image" src="https://github.com/user-attachments/assets/7f94655d-3192-4442-bf42-420930743089" />

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

