
# Microsoft 365 — Group Privacy Security Remediation

## 1. Project Overview

This case study documents my hands-on experience reviewing and modifying Microsoft 365 group privacy settings during my IT Support / Cybersecurity internship at a Managed Service Provider (MSP).

The objective was to address security baseline findings involving Microsoft 365 groups configured as Public instead of Private.

## 2. Security Concern

Public Microsoft 365 groups allow users within an organization to join without group-owner approval, potentially providing broader access to shared resources than intended.

This can create security concerns involving:

- Unauthorized access to internal collaboration resources
- Excessive access permissions
- Unintended information exposure
- Failure to follow least-privilege principles

Private groups require membership approval or an authorized administrator to add members.

## 3. Tools Used

- Microsoft 365 Admin Center
- Microsoft Entra ID
- Microsoft 365 Groups
- Syncro XMM

## 4. Remediation Procedure

1. Sign in to the Microsoft 365 Admin Center.
2. Navigate to Teams & groups.
3. Select Active teams & groups.
4. Locate the affected Microsoft 365 group.
5. Open the group's settings.
6. Select the Privacy setting.
7. Change the group from Public to Private.
8. Save the configuration changes.

## 5. Verification

Recommended verification steps:

1. Reopen the group's settings.
2. Confirm that Privacy is set to Private.
3. Review group membership and access permissions.
4. Confirm that the configuration meets the organization's security requirements.
5. Recheck the original security baseline finding.

## 6. Skills Demonstrated

- Microsoft 365 administration
- Security misconfiguration remediation
- Identity and Access Management (IAM)
- Group access management
- Least-privilege security principles
- Security baseline assessments

## 7. Lessons Learned

This task helped me understand how Microsoft 365 group privacy settings affect access to organizational collaboration resources.

I gained hands-on experience navigating Microsoft 365 administrative settings and applying configuration changes to address security findings.

I also learned the importance of verifying security settings after making administrative changes.

## 8. Documentation and Evidence

Future updates will include recreated configuration screenshots from a personal Microsoft 365 lab environment.

No confidential client information, credentials, or production screenshots are included.

