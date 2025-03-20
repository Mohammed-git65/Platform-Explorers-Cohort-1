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
