# Exchange Online Anti-Phishing Protection

## Introduction
Phishing attacks are a significant threat to organizations, leading to data breaches, credential theft, and financial losses. **Fabrikam Inc.** has experienced an increase in phishing emails.

## Solution Overview
To mitigate phishing risks,  I implemented the following security measures:

**Anti-Phishing & Anti-Spam Policies** – Configured policies in **Microsoft Defender for Office 365** to detect and block phishing attempts.

**Safe Links & Attachments** – Enabled real-time protection against malicious links and attachments.

**SPF, DKIM, and DMARC** – Implemented email authentication protocols to prevent domain spoofing.

**Zero-Hour Auto Purge (ZAP)** – Automatically removed phishing emails post-delivery.

**Threat Explorer** analyzes phishing attempts and improves detection mechanisms.

### Step 1: Is to Configure Anti-Phishing Policies in Defender for Office 365
- Go to Microsoft Defender Portal: https://security.microsoft.com
- Sign in as a security administrator or Global administrator
- Navigate to Email & Collaboration > Policies & Rules > Threat Policies > Anti-Phishing.
- Review existing policies and determine gaps.
- Then click on + Create to create new policies

![image](https://github.com/user-attachments/assets/9e99add5-9958-4ab4-ae48-4b1dc9b6cd26)

![image](https://github.com/user-attachments/assets/aa8d97a0-6952-4f06-9e8c-4acf2b3971ca)

![image](https://github.com/user-attachments/assets/0dc84cbf-9b50-4c5e-83a3-67b221a60a92)

![image](https://github.com/user-attachments/assets/2ba2e8d5-68ee-4359-91d4-92683bd144aa)

![image](https://github.com/user-attachments/assets/40cbcd27-b1e8-411e-b1e1-11fc83ca3556)

- Here I added the domain
  ![image](https://github.com/user-attachments/assets/f887b9fe-ecc9-4948-ac45-3699c75ddb08)

  ![image](https://github.com/user-attachments/assets/9db96315-06ac-4a2a-8991-4a85618191c6)

![image](https://github.com/user-attachments/assets/d26edde4-27de-499f-b00c-c4bb70d27dee)

- Here I review the Anti-Phishing policy before submitting
  ![image](https://github.com/user-attachments/assets/bd22d541-394d-4830-beb7-10a5eea1f73b)

### Step 2: I created an Anti-Spam policy

- Go to Microsoft Defender Portal: https://security.microsoft.com
- Sign in as a security administrator or Global administrator
- Navigate to Email & Collaboration > Policies & Rules > Threat Policies > Anti-Spam.
- Then click on + Create to create new policies

![image](https://github.com/user-attachments/assets/1598adf6-a698-4bbb-8d31-023e01a47904)

![image](https://github.com/user-attachments/assets/edd4df82-fc6a-4a0c-aede-0d6f714bd8bc)

![image](https://github.com/user-attachments/assets/4f76da16-85b4-41b3-9bc6-bba07d6e51e9)

- Here Action to be taken
![image](https://github.com/user-attachments/assets/ff542780-c211-4d6e-8e35-6a1a9ff55d4d)

![image](https://github.com/user-attachments/assets/eeb740a9-27f5-4c90-8806-3dc84e23de84)

- Here I review the Anti-Spam Policy before I click on create
![image](https://github.com/user-attachments/assets/8f1497f2-f280-433a-a9d4-1d4d1dc3552b)

- After reviewing the Anti-Spam Policy I click on Create to create the policy
![image](https://github.com/user-attachments/assets/7af5bfc3-a9c6-4660-89ef-b88e61b09109)
