
# Microsoft Entra ID — Authentication Methods Security

## 1. Project Overview

This case study documents my experience working with Microsoft Entra ID authentication policies during my IT Support / Cybersecurity internship at a Managed Service Provider (MSP).

The objective was to review authentication methods and address security baseline findings involving SMS and voice-call authentication.

## 2. Security Concern

SMS and voice-call authentication can be vulnerable to:

- SIM-swapping attacks
- Social engineering
- Phishing
- Interception of authentication codes

Organizations may reduce these risks by adopting stronger authentication methods, such as Microsoft Authenticator or FIDO2 security keys.

## 3. Tools Used

- Microsoft Entra Admin Center
- Microsoft Entra ID
- Syncro XMM
- Authentication Methods Policy

## 4. Remediation Procedure

1. Sign in to the Microsoft Entra Admin Center.
2. Navigate to Entra ID.
3. Select Authentication methods.
4. Open the Policies section.
5. Select SMS and review its configuration.
6. Disable SMS authentication where authorized.
7. Select Voice call and review its configuration.
8. Disable voice-call authentication where authorized.
9. Save the changes.

## 5. Verification

Verification should include:

- Confirming the intended authentication methods are disabled.
- Checking that approved authentication methods remain available.
- Reviewing the security baseline finding after reassessment.
- Confirming users retain an approved sign-in method.

## 6. Skills Demonstrated

- Identity and Access Management (IAM)
- Microsoft Entra ID administration
- Authentication policy configuration
- Security baseline remediation
- Security troubleshooting

## 7. Lessons Learned

This task helped me understand how authentication methods affect organizational security.

I gained practical experience navigating Microsoft Entra ID and reviewing authentication policies as part of a security remediation workflow.

## 8. Documentation and Evidence

Screenshots from a personal lab environment will be added to demonstrate the configuration and verification process.

No confidential client information or production screenshots are included.

