# Configuring Email Security to Prevent Phishing Attacks

## Introduction
Phishing attacks significantly threaten organizations, leading to data breaches, credential theft, and financial losses. **Fabrikam Inc.** has experienced an increase in phishing emails.

## Solution Overview
To mitigate phishing risks,  I implemented the following security measures:

**Anti-Phishing & Anti-Spam Policies** – Configured policies in **Microsoft Defender for Office 365** to detect and block phishing attempts.

**Safe Links & Attachments** – Enabled real-time protection against malicious links and attachments.

**SPF, DKIM, and DMARC** – Implemented email authentication protocols to prevent domain spoofing.

**Zero-Hour Auto Purge (ZAP)** – Automatically removed phishing emails post-delivery.

**Threat Explorer** analyzes phishing attempts and improves detection mechanisms.

### Step 1: Is to Configure Anti-Phishing Policies in Defender for Office 365
To do that:
- I went to Microsoft Defender Portal: https://security.microsoft.com
- Sign in as a security administrator or Global administrator
- Navigate to **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Anti-Phishing**.
- Define the policy name. In this case, I used **Fabrikam Anti-Phishing Policy**
- I Add **protected users, domains, and mailbox intelligence**.
- Then, I Enable **impersonation protection**.
- I finally Reviewed the policy and then click on done to apply the policy

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

- I went to Microsoft Defender Portal: https://security.microsoft.com
- Sign in as a security administrator or Global administrator
- Navigate to **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Anti-Spam**.
- Then click on **+ Create** to create new policies

![image](https://github.com/user-attachments/assets/1598adf6-a698-4bbb-8d31-023e01a47904)

![image](https://github.com/user-attachments/assets/edd4df82-fc6a-4a0c-aede-0d6f714bd8bc)

![image](https://github.com/user-attachments/assets/4f76da16-85b4-41b3-9bc6-bba07d6e51e9)

- Here are Actions to be taken
![image](https://github.com/user-attachments/assets/ff542780-c211-4d6e-8e35-6a1a9ff55d4d)

![image](https://github.com/user-attachments/assets/eeb740a9-27f5-4c90-8806-3dc84e23de84)

- Here I review the Anti-Spam Policy before I click on create
![image](https://github.com/user-attachments/assets/8f1497f2-f280-433a-a9d4-1d4d1dc3552b)

- After reviewing the Anti-Spam Policy I click on Create to create the policy
![image](https://github.com/user-attachments/assets/7af5bfc3-a9c6-4660-89ef-b88e61b09109)


### **Step 3: Implementing Safe Links and Safe Attachments**  
1. **To enable Safe Attachments**:
- Navigate to **Threat Policies** > **Safe Attachments**.
- Create a new policy to **scan attachments for malware** and define the policy
- I configure options to **block or quarantine** suspicious files.
- Then I reviewed and Applied the policy.

<img width="954" alt="img16" src="https://github.com/user-attachments/assets/002628d4-eceb-4c43-90cc-bb1e5f1cbfd7" />

<img width="950" alt="img17" src="https://github.com/user-attachments/assets/fdf2cc95-a2b1-4b81-a393-2bcaaec050dd" />

<img width="943" alt="img18" src="https://github.com/user-attachments/assets/2417ac8f-0860-49d4-ba50-5bc57407b918" />

<img width="954" alt="img20" src="https://github.com/user-attachments/assets/69016b48-7fb9-406b-8ce3-62733165aba2" />


2. **Enable Safe Links**:
To do that:
- Navigate to **Threat Policies** > **Safe Links**.
- I click **Create policy** and define the policy.
- I Enable real-time scanning of **URL links in emails**.
- Then I reviewed and Applied the policy.

<img width="950" alt="img21" src="https://github.com/user-attachments/assets/af84e68a-4edf-46d0-a594-0c3f7dc9bd7e" />

<img width="944" alt="img22" src="https://github.com/user-attachments/assets/fb621abf-6814-4468-9378-f53fc41db1a6" />

<img width="948" alt="img23" src="https://github.com/user-attachments/assets/1de1b78e-60f9-429f-8fc2-367489619abb" />
<img width="948" alt="img24" src="https://github.com/user-attachments/assets/1981edfa-cd1e-45d4-adfd-7b8fe71ddf35" />
<img width="954" alt="img25" src="https://github.com/user-attachments/assets/124a43d3-d929-4ca1-92ac-0d81eaaa9bf6" />


### **Setting up SPF, DKIM, and DMARC for Email Authentication**  
1. **SPF**: The SPF record has already been done
2. Before I enabled the **DKIM** I sent an email from my domain to Gmail to see if it would pass **SPF** and **DKIM** using Mxtoolbox to verify and see if it passes **SPF** and **DKIM**.

**The Screenshots below only show that it passes only SPF**
<img width="939" alt="img11" src="https://github.com/user-attachments/assets/fd34363e-6587-4f36-ab90-5f5531c37a69" />
<img width="935" alt="img12" src="https://github.com/user-attachments/assets/49d2fdfd-e643-4d28-b0ce-9da28d98758b" />

<img width="918" alt="img10" src="https://github.com/user-attachments/assets/cfba1802-2aa3-4624-a2e5-e532b2b417a1" />

So after I published the **Cname** in my domain provider and then enabled **DKIM** it passed both **SPF** and **DKIM**

![image](https://github.com/user-attachments/assets/7765df93-9801-4bbc-a5a1-7c55c481364a)

![image](https://github.com/user-attachments/assets/f959fd2c-07c5-4b08-b731-e1d614806ff1)

![image](https://github.com/user-attachments/assets/e3e39316-78ac-4d5a-8f25-2732837bd325)


## **DMARC**

![image](https://github.com/user-attachments/assets/a1f9e92d-9a3c-4199-a908-79b440af414a)

## **Step 3: To Enable Zero-Hour Auto Purge (ZAP) in Microsoft 365 Defender**
- Sign in to the **Microsoft 365 Defender portal**. 
- Navigate to **Threat Policies**:
- Under **Email & collaboration,** I select **Policies & rules**.
- Then, I selected **Threat policies**. 
- Then to configure the Anti-malware Policies:
- Under **Policies**, I selected **Anti-malware**, Selected the **Default (Default)** policy, and Clicked **Edit protection settings**. 
- Then, I checked the box labeled **Enable zero-hour auto purge for malware (Recommended)**.
- And Click **Save**. 
![image](https://github.com/user-attachments/assets/100e5b74-cca6-4511-9500-51583503e233)

## **After all the configurations I test for Phishing emails using Threat Explorer**

To do that:
- I Access **Threat Explorer**
- I went to the Microsoft Defender portal: https://security.microsoft.com
- Navigate to **Email & collaboration** > **Explorer**
- I selected the **Phish View** in **Threat Explorer** to filter the email 
![image](https://github.com/user-attachments/assets/27529d36-626b-4aef-a8f9-3b6de426f767)

![image](https://github.com/user-attachments/assets/97d05a1a-5cd6-4638-b638-2a35bbe82807)
