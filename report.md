# Phishing Email Investigation – Case 01

## Objective
The purpose of this project is to analyze a suspicious phishing email and identify indicators of compromise, suspicious sender details, email headers, attachments, and final investigation verdict.

## Email Overview
- Spoofed Organization:
- Sender Email Address:
- Subject Line:
- Attachment Name:
- Suspicious URL:
- Source IP:

## Suspicious Indicators
- The email attempts to impersonate a reputable organization.
- The sender email address does not match the legitimate company domain.
- The email contains suspicious sender/source details.
- The email includes an attachment/link that required further investigation.
- Header analysis showed technical indicators that needed verification.

## Header Analysis
- X-Originating-IP:
- Authentication-Results Mail Server:
- SPF Result:
- DKIM Result:
- DMARC Result:

## IOC Extraction
- Email Address:
- IP Address:
- Domain:
- URL:
- Attachment Name:

## Analysis Summary
During the investigation, the email was reviewed from both rendered view and raw source view. The rendered view showed what a normal user would see, while the raw source helped identify technical details such as sender information, headers, attachment type, and originating IP address.

The suspicious indicators suggest that the email was designed to trick the user by impersonating a trusted organization.

## Final Verdict
Verdict: Phishing Email

## Recommended Actions
1. Do not click any links or open suspicious attachments.
2. Report the email to the security team.
3. Block the sender email/domain.
4. Investigate the originating IP address.
5. Search for similar emails across other user mailboxes.
6. Educate users about phishing and Business Email Compromise attacks.

## Skills Demonstrated
- Phishing email analysis
- Email header analysis
- IOC extraction
- Raw email source investigation
- Basic threat intelligence analysis
- Incident reporting
