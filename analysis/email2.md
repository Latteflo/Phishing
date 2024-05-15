### Email_2 Analysis Report
This is the solution for the second email phishing analysis exercise. The email headers and content are analyzed to determine the authenticity of the email. 

It includes the examination of email headers, content, and hyperlinks to identify any signs of phishing or suspicious activity.

#### Email Headers:

Here is the detailed analysis of the email headers provided:

1. **Received: from MW6PR19MB6903.namprd19.prod.outlook.com**
   - **IP Address**: (::1)
   - **By**: MN0PR19MB6312.namprd19.prod.outlook.com with HTTPS
   - **Timestamp**: Wed, 14 Dec 2022 05:54:16 +0000

2. **Received: from DM6PR06CA0019.namprd06.prod.outlook.com**
   - **IP Address**: 2603:10b6:5:120::32
   - **By**: MW6PR19MB6903.namprd19.prod.outlook.com
   - **SMTP Server**: Microsoft SMTP Server (TLS1_2, TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384)
   - **Timestamp**: Wed, 14 Dec 2022 05:54:14 +0000

3. **Received: from DM6NAM11FT101.eop-nam11.prod.protection.outlook.com**
   - **IP Address**: 2603:10b6:5:120:cafe::90
   - **By**: DM6PR06CA0019.outlook.office365.com
   - **SMTP Server**: Microsoft SMTP Server (TLS1_2, TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) via Frontend Transport
   - **Timestamp**: Wed, 14 Dec 2022 05:54:14 +0000

4. **Authentication-Results**:
   - **SPF**: none (sender IP is 172.81.119.154)
   - **smtp.mailfrom**: midnightmagicevents.com
   - **dkim**: pass (signature was verified)
   - **header.d**: midnightmagicevents.com
   - **dmarc**: bestguesspass action=none
   - **header.from**: midnightmagicevents.com
   - **compauth**: pass reason=109

5. **Received-SPF**: None (protection.outlook.com: midnightmagicevents.com does not designate permitted sender hosts)
   - **Client-IP**: 172.81.119.154

6. **Received: from vps37336.servconfig.com**
   - **IP Address**: 172.81.119.154
   - **By**: DM6NAM11FT101.mail.protection.outlook.com (10.13.172.208)
   - **SMTP Server**: Microsoft SMTP Server (TLS1_2, TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) via Frontend Transport
   - **Timestamp**: Wed, 14 Dec 2022 05:54:14 +0000

7. **DKIM-Signature**:
   - **Version**: 1
   - **Algorithm**: rsa-sha256
   - **Domain**: midnightmagicevents.com
   - **Selector**: default
   - **Headers**: Message-ID:Date:Content-Transfer-Encoding:Content-Type:Subject:To:Reply-To:From:MIME-Version:Sender:Cc:Content-ID:Content-Description:Resent-Date:Resent-From:Resent-Sender:Resent-To:Resent-Cc:Resent-Message-ID:In-Reply-To:References:List-Id:List-Help:List-Unsubscribe:List-Subscribe:List-Post:List-Owner:List-Archive
   - **Signature**: pZXgHeI0zrP8/oOKSHD0XtASxp9wg9MHUySE1yHncLXBgr8KIR3gd2BIk8JTk4Mual+A9Pk3HAMyOOo/JqgOG6L3h...

#### Content of the Email:

The email appears to be a phishing attempt claiming to be from Trust Wallet. Below are the key elements of the email content:

- **From**: "noreply" <stainless@midnightmagicevents.com>
- **Reply-To**: stainless@midnightmagicevents.com
- **To**: phishing@pot
- **Subject**: Trust Wallet
- **Message-ID**: <5348421712496313174540@WIN-HM6FI4VOIEP>
- **Date**: Mon, 12 Dec 2022 09:56:36 +0100
- **Content-Type**: text/html; charset="windows-1252"
- **Content-Transfer-Encoding**: quoted-printable

#### Email Body Analysis:
- **Greeting**: "Dear Customer"
- **Main Content**: Notification that the recipient's Trust Wallet has not been verified and a warning that unverified accounts will be suspended due to recent updates of NFTs and Coins.
- **Action Required**: The recipient is instructed to verify their Trust Wallet on a provided link.
- **Hyperlink**: The provided link for verification points to `https://climovil.com/`, which is not related to Trust Wallet.

#### Key Indicators of Phishing:
- **Sender Email**: The sender email domain is `midnightmagicevents.com`, which is unrelated to Trust Wallet.
- **SPF Check**: The SPF check failed (none).
- **Suspicious Link**: The verification link points to an unrelated domain (`https://climovil.com/`).
- **Generic Greeting**: Use of "Dear Customer" instead of a personalized greeting.
- **Urgency and Threat**: The email creates a sense of urgency by threatening account suspension.

#### Summary:
This email is highly suspicious and likely a phishing attempt designed to steal sensitive information. It does not come from a verified Trust Wallet domain, and the verification link points to an unrelated website. The urgency and threat of account suspension are common tactics used by phishers to prompt recipients to take immediate action without verifying the legitimacy of the email.

