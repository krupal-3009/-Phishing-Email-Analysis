# Phishing Email Analysis

## Objective
Analyze a suspicious email sample and identify phishing characteristics such as spoofed sender, suspicious links, grammatical errors, and social engineering tactics.

## Task Summary
I examined a phishing email that impersonated PayPal. The goal was to analyze the structure and content of the email and identify red flags that indicate it's a phishing attempt.

## Sample Overview
- **Subject:** Re: PayPal Security Alert: Latest Login from Tokyo, Japan
- **Sender Display Name:** secure@intl-limited.com  
- **Actual Sender:** `mailsecuredaccounts-lvp6dgrzqru@keysosens.com`
- **Target:** PayPal user credentials
- **Attachment Type:** Email screenshot ![](https://github.com/krupal-3009/-Phishing-Email-Analysis/blob/016c820fe9502cf127c0dd3205c3d691fac0a776/phishing-email-example.png)

## Key Phishing Indicators Identified
**_1.Fake Sender Address_**
- **Displayed as:** `secure@intl-limited.com`
- **Actual sender:** `mailsecuredaccounts-lvp6dgrzqru@keysosens.com`
- **Red flag:** The domain `keysosens.com` is unrelated to PayPal.

**_2.Suspicious Subject Line_**
- Combines multiple themes: security alert, location (Tokyo), and gaming reference.
- Contains strange phrasing like **"Latest Login added Informed"**.
- Includes `[FWD]`(Forwarded) and a fake reference number to mimic official alerts.

**_3.Grammar and Spelling Errors_**
- Phrases like **“at the movement”**, **“Verify And Secure”**, and **“Which is blocked successfully”** are unnatural or incorrect.
- Overuse of capitalization inappropriately.

**_4.Generic Greeting_**
- Uses **“Hi Dear Customer”** instead of the recipient's name.
- Real PayPal emails usually address users by their full name.

**_5.Urgent and Threatening Language_**
- Claims like **“Your PayPal account has been limited”** and **“Unauthorized login was found”** aim to cause panic.
- Pressures the user to act immediately.

**_6.Social Engineering Tactics_**
- **Fear-based manipulation:** Reference to a login from Tokyo, Japan.
- **Authority mimicry:** Imitates PayPal branding and tone.
- **False reassurance:** Says access was "blocked" to gain trust.

**_7.Malicious Call-To-Action (CTA)_**
- Prominent **“Verify Now”** button likely leads to a fake login page.
- Purpose: Harvest PayPal login credentials.

**_8.Visual & Branding Tricks_**
- Uses PayPal's logo and color scheme.
- Overall layout is low quality with awkward spacing and inconsistent formatting.

## Risk Level
- **Threat Type:** Credential Harvesting  
- **Risk:** High – Could lead to account compromise, identity theft, or financial loss.

## References

- [PayPal Phishing Guide](https://www.paypal.com/us/security/scams)
- [Google - Report phishing](https://support.google.com/mail/answer/8253?hl=en)
- [Phishing Red Flags Checklist – CISA](https://www.cisa.gov/sites/default/files/publications/Phishing%20Red%20Flags_508C.pdf)

