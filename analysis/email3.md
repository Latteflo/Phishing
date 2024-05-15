### Email_3 Analysis Report
This is the solution for the third email phishing analysis exercise. The email headers and content are analyzed to determine the authenticity of the email. 

It includes the examination of email headers, content, and hyperlinks to identify any signs of phishing or suspicious activity.


#### Email3 Headers Analysis:

1. **Received: from AS4PR10MB5151.EURPRD10.PROD.OUTLOOK.COM**
   - **IP Address**: 2603:10a6:20b:4c2::5
   - **By**: AS2PR10MB6869.EURPRD10.PROD.OUTLOOK.COM
   - **Protocol**: HTTPS
   - **Timestamp**: Sun, 26 Mar 2023 10:31:57 +0000

2. **Received: from BN9PR03CA0884.namprd03.prod.outlook.com**
   - **IP Address**: 2603:10b6:408:13c::19
   - **By**: AS4PR10MB5151.EURPRD10.PROD.OUTLOOK.COM
   - **SMTP Server**: Microsoft SMTP Server (TLS1_2, TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384)
   - **Timestamp**: Sun, 26 Mar 2023 10:31:56 +0000

3. **Received: from BN8NAM12FT109.eop-nam12.prod.protection.outlook.com**
   - **IP Address**: 2603:10b6:408:13c::4
   - **By**: BN9PR03CA0884.outlook.office365.com
   - **SMTP Server**: Microsoft SMTP Server (TLS1_2, TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) via Frontend Transport
   - **Timestamp**: Sun, 26 Mar 2023 10:31:56 +0000

4. **Authentication-Results**:
   - **SPF**: none (sender IP is 80.78.255.128)
   - **smtp.mailfrom**: 80-78-255-128.cloudvps.regruhosting.ru
   - **dkim**: none (message not signed)
   - **header.d**: none
   - **dmarc**: none action=none
   - **header.from**: 80-78-255-128.cloudvps.regruhosting.ru
   - **compauth**: pass reason=105

5. **Received-SPF**: None (protection.outlook.com: 80-78-255-128.cloudvps.regruhosting.ru does not designate permitted sender hosts)
   - **Client-IP**: 80.78.255.128

6. **Received: from 80-78-255-128.cloudvps.regruhosting.ru**
   - **IP Address**: 80.78.255.128
   - **By**: BN8NAM12FT109.mail.protection.outlook.com (10.13.182.106)
   - **SMTP Server**: Microsoft SMTP Server
   - **Timestamp**: Sun, 26 Mar 2023 10:31:55 +0000

7. **Message-ID**: <83652665.822718944.263455149669@80-78-255-128.cloudvps.regruhosting.ru>

#### Content of the Email:

The email appears to be a phishing attempt claiming to be from Tinder. Below are the key elements of the email content:

- **From**: Tinder <gq@80-78-255-128.cloudvps.regruhosting.ru>
- **To**: "Ludo" <becode@phishing-me.be>
- **Subject**: It's a Match!
- **Message-ID**: <83652665.822718944.263455149669@80-78-255-128.cloudvps.regruhosting.ru>
- **Date**: Sun, 26 Mar 2023 13:31:56 +0000
- **Content-Type**: text/html; charset=UTF-8

#### Email Body Analysis:
- **Greeting**: "It's a Match!"
- **Main Content**: Notification of a match on Tinder, encouraging the recipient to click on a provided link to see the match.
- **Action Required**: The recipient is instructed to click a link ("FIND OUT WHO") to discover their match.
- **Hyperlink**: The provided link points to `http://blog.tulingxueyuan.cn/contradictedqm.php?utm_campaign=tpdjuresn`, which is not related to Tinder.

#### Key Indicators of Phishing:
- **Sender Email**: The sender email domain is `80-78-255-128.cloudvps.regruhosting.ru`, which is unrelated to Tinder.
- **SPF Check**: The SPF check failed (none).
- **Suspicious Link**: The verification link points to an unrelated website (`http://blog.tulingxueyuan.cn/`).
- **Generic Content**: The email uses a generic match notification format that is common in phishing attempts.

#### Summary:
This email is highly suspicious and likely a phishing attempt designed to steal sensitive information. It does not come from a verified Tinder domain, and the link provided points to an unrelated and suspicious website.

