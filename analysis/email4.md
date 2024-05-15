### Email_4 Analysis Report
This is the solution for the fourth email phishing analysis exercise. The email headers and content are analyzed to determine the authenticity of the email.

It includes the examination of email headers, content, and hyperlinks to identify any signs of phishing or suspicious activity.

#### Email Headers Analysis:

1. **Received: by 2002:a05:6a11:8598:b0:436:a25f:fe2**
   - **SMTP ID**: ci24csp543644pxc
   - **Timestamp**: Fri, 3 Mar 2023 03:44:03 -0800 (PST)

2. **X-Received: by 2002:a0d:dfd8:0:b0:538:7870:f2da**
   - **SMTP ID**: i207-20020a0ddfd8000000b005387870f2damr1233034ywe.1.1677843842978
   - **Timestamp**: Fri, 03 Mar 2023 03:44:02 -0800 (PST)

3. **ARC-Seal**:
   - **Domain**: google.com
   - **Signature**: v6L26mDP7HL7HgjNoFnZGfyLeuAPBYtfSO8rzQTBs85sEohMDMOr5uxRjf0ijWCnJjFBG2GS95+f4C/GKF/w1qGsD4f4nniYyhhhlgzFF7IhK1RsKhpWEfdL6I7NEJOttluHjcdWRhkDHHM/OrKiRhgyPScXMVxaxmu5t7IUs2tUikoD5Sw2s32XsPfBoBRo6zAQSbSvCcLBIuAGtzqQgHhUwqwfdDyYLZ0AttaXF2ZtgHt5AEmzfDxdwcRLAechyZ1pa7Bt0qU58m7YeAlUTEheplu1tTfv2AljPoQO1oH9TimEQVZsaVSwdo8uLCFCjzLZN+c8Bum2TDyF10Bc/Q==

4. **ARC-Message-Signature**:
   - **Domain**: google.com
   - **Signature**: jBalA2hiKO7nMaY/53PDvDZS5WV9VAdlRF5jNNancx9k+uELu9BLUv/bLLnzlLgC1kb722hxwOg4ZcUgL81FC2gPwwBfPNyW8lVBc3PDriIteTWxma4oUIV6nsLGB4FuzDVpIEeXUbdnX0VpLq8aBHvK+0gJ6pHG0hKdnlCkt8Lxs3I9xNDdti8iaya5V3OjTY7BKcB/+WKLSVqr+LeLdL5kRPZYDHWc20KmwkPrEAg+4xAJB4bqSnuo96Upo6V6nEHQgVYyEjMfaAmDlpoSt0EQnzl7XO81t8bu2shbonDK3WkRsyiCXISoiA74qmiZg4tKe0UrRCCIqBnmvUMQjg==

5. **ARC-Authentication-Results**:
   - **dkim**: pass
   - **spf**: pass (domain of babakingsouthmichael@gmail.com designates 209.85.220.41 as permitted sender)
   - **dmarc**: pass (p=NONE sp=QUARANTINE dis=NONE) header.from=gmail.com

6. **Return-Path**: <babakingsouthmichael@gmail.com>
   - **Received: from**: mail-sor-f41.google.com (209.85.220.41)
   - **SMTP ID**: q4-20020a0dec04000000b005384f5fda06sor1499668ywn.77.2023.03.03.03.44.02
   - **Timestamp**: Fri, 03 Mar 2023 03:44:02 -0800 (PST)

7. **DKIM-Signature**:
   - **Domain**: gmail.com
   - **Selector**: 20210112
   - **Timestamp**: 1677843842
   - **Signature**: alVDrquOs3714iWumyRf7tYU4Wifd9lb0FpHzwOHGkxoBS60qMKpq0seUv2ZdNfmdpHOohBCkSP0x+A0H8VkF3Ecy0BbPdWqUHolalq8N/sqaWLi4Gnb+4rnxjZ74xdXgSABVfIToW6GPd6Y0GV5gwHivazCLZO/s4Cci3t1rJN78xYMIbCpmeXGKb5IJBIxt38HZJXi0YVWqhI47rhSj4QD8VttGUuIjr0BNsHEAO8MHDlGM9BU8KuxvbGJw6Xvcy80jAQjc7TY5jHC4XMJEtvq+hd9O6l4gj627/i93wgaqiOosxn04S4Ytmeb6AjIbPW/15xvMch4lxK7Z4GBBQ==

8. **X-Google-DKIM-Signature**:
   - **Domain**: 1e100.net
   - **Selector**: 20210112
   - **Timestamp**: 1677843842
   - **Signature**: e6lzskKgQuxM2OBaXEbP5MuTBMCbBTw2LyG1dYtU1xqpRw7XBC/8R842upiobSUq4dIWZA+RCI5zyzZwKWTowvw74xeowvmbvaS90eGAHhPghWgE1PwiZO66Teub1h8Mxf8ADtoPm49UkSrpqjOe1RufXpt5gjNzbqb2JPccXSlTPmTosxxIBR39bwKLZRqzridnL0vkukkq/PpXGF1eVyvPipnM0IiXjQwEZMVAkrYtZFVuG+jdLTw4R5sy8cPrl0xP3HJmqejNN49bR1OT8wLReDhGTGsSq1z7wxFd6uXot2ud8jd5b00sDvxFMG1OM0SAgNP8A7pWd6cj6Safcw==

9. **X-Gm-Message-State**: AO0yUKXGiaWNPGyZuwglTAdOl89xUrlELrhLP9tZ27cySf4f8ry3PA5+Vd8xCAtlYGy46u2n+ek2gfmMmPd8LmrC59vBtn8=

10. **X-Google-Smtp-Source**: AK7set8CUI3Dn7ZGnXp2R4Hbq+3ErtnsdM0XzdDhIufcxLWPR9A81VAA0N2YKtIcGVxtdV0tqvKk/KYoFsFcrPlXw5o=

11. **MIME-Version**: 1.0

12. **Received: by 2002:a81:ae4a:0:b0:52e:b7cf:4cd1 with SMTP id g10-20020a81ae4a000000b0052eb7cf4cd1mr754691ywk.5.1677843842222**
    - **Timestamp**: Fri, 03 Mar 2023 03:44:02 -0800 (PST)

13. **Received: by 2002:a05:7000:b613:b0:480:c95c:35f6 with HTTP**
    - **Timestamp**: Fri, 3 Mar 2023 03:44:01 -0800 (PST)

#### Email Body:

- **Reply-To**: imorourafiatou0@gmail.com
- **From**: "Dr. Dan Miller" <babakingsouthmichael@gmail.com>
- **Date**: Fri, 3 Mar 2023 12:44:01 +0100
- **Subject**: Re: RELIEF / COMPENSATION FUND OF $1,500,000.00 USD
- **To**: undisclosed-recipients:;
- **Content-Type**: text/plain; charset="UTF-8"
- **Content-Transfer-Encoding**: quoted-printable
- **Bcc**: becode@phishing-me.be

---

### Email Content Analysis:

The email claims to be from "Dr. Dan Miller," a representative of the United Nations Special Representative for Disaster Risk Reduction (UNDRR), informing the recipient of a relief/compensation fund worth $1,500,000.00 USD.

**Key Points:**

1. **Sender Email**: babakingsouthmichael@gmail.com


2. **Reply-To Email**: imorourafiatou0@gmail.com

3. **Claim**: The recipient’s email address has been selected to receive a $1,500,000.00 USD humanitarian relief fund.

4. **Reason for Fund**: The fund is supposedly established to help support low and middle-income people in response to the humanitarian crisis.

5. **Contact Information for Fund**:
   - **Grant Manager**: Mr. Robert TAIWO
   - **Email Address**: mrroberttaiwo212@gmail.com
   - **Telephone**: (+229) 699 363 62

6. **Requested Information**:
   - Given Name
   - Residential/Office Address
   - Phone Number
   - Gender

7. **Urgency**: The email emphasizes the need for the recipient's urgent attention to enable effective monitoring of the transaction.

### Key Indicators of Phishing:

1. **Generic Greeting**: The email does not address the recipient by name, using a generic greeting instead.

2. **Sender and Reply-To Discrepancy**: The sender's email address (babakingsouthmichael@gmail.com) and the reply-to email address (imorourafiatou0@gmail.com) are different, which is unusual for legitimate correspondence.

3. **Unusual Email Domain**: The email domain used for the sender (gmail.com) is a free email service, which is uncommon for official United Nations communications.

4. **Contact Information**: The provided contact email (mrroberttaiwo212@gmail.com) and phone number are not linked to any official United Nations or IMF domain.

5. **Urgency and Threats**: The email creates a sense of urgency, which is a common tactic used in phishing to prompt hasty action without careful consideration.

6. **Request for Personal Information**: The email requests sensitive personal information, which is a red flag for phishing attempts aiming to collect data for fraudulent purposes.

7. **Lack of Professional Formatting**: The email lacks the professional formatting and language typically seen in official communications from large organizations like the United Nations or IMF.

### Summary:

This email is a classic example of a phishing attempt. It uses the pretext of a large financial award to lure recipients into providing personal information. The email's claims are not supported by any verifiable facts, and the contact details provided are not associated with any legitimate organization. 