## **Setting Up Email Encryption for Sensitive Communication**
The law firm will implement Microsoft Purview Message Encryption (OME) in Exchange Online to protect sensitive legal documents in email communication. This setup ensures that any email containing legal documents is encrypted when sent externally, complying with data protection and confidentiality requirements.

## **Step 1: Is Understanding Microsoft Purview Message Encryption**

Microsoft Purview Message Encryption is an online service that's built on Azure Rights Management (Azure RMS) which is part of Microsoft Purview Information Protection. This service includes encryption, identity, and authorization policies to help secure your email.

## **Here are the Key Features of Microsoft Purview Message Encryption**
- Enforces encryption based on predefined rules
- Works seamlessly with Microsoft Outlook and Outlook Web Access
- Protects sensitive information by encrypting email content
- Allows external recipients to securely read encrypted emails


## **Step 2: Is to Configure Mail Flow Rules to Automatically Encrypt Emails for the law firm**
To ensure emails containing sensitive legal documents are encrypted, the law firm will create mail flow rules in Exchange Online. These rules will detect specific keywords or attachments and apply encryption automatically

**To Configure Mail Flow Rules Here are the Steps to Take**

1. Access the Exchange Admin Center (EAC)

- Sign in to the Microsoft 365 Admin Center → Open the Exchange Admin Center.
  <img width="705" alt="img1" src="https://github.com/user-attachments/assets/3e19380b-ac16-4832-ad97-c535218c0891" />


2. Create a New Mail Flow Rule

- Navigate to Mail Flow → Rules → Click + Add a Rule → Select Create a New Rule.
![image](https://github.com/user-attachments/assets/b7436432-4fc2-4ae7-869d-14b9de9d3d4a)

![image](https://github.com/user-attachments/assets/25113b1e-4b6d-4116-82c6-10b5c454d359)

![image](https://github.com/user-attachments/assets/239b288f-b22e-44aa-81e6-ec4f461a33f9)


3. Define the Conditions for Encryption

- Name the rule: "Encrypt Emails with Sensitive Legal Documents"

Apply the rule if:

![image](https://github.com/user-attachments/assets/20064c99-5921-44de-be5e-45ba5884fd6d)

The subject or body contains specific words: keywords like "Confidential"

![image](https://github.com/user-attachments/assets/d0e5263c-7fd1-4bb8-be57-01887c44b300)

To Apply the Encryption Action
Under Do the following, I choose:
- Modify the message security
- Apply Office 365 Message Encryption and Rights Protection
- And then select Encrypt.

![image](https://github.com/user-attachments/assets/485b1222-8cca-4fa7-8585-554b9c704535)

![image](https://github.com/user-attachments/assets/ec789fe1-a85b-4a11-89b8-c3f9d54f6f59)


Save and Activate the Rule

Click Save and test the rule to verify functionality.

