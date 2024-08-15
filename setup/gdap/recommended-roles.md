# Recommended Roles

As CIPP is an application that touches many parts of M365 selecting the roles might be difficult. The following roles are recommended for CIPP, but you may experiment with less permissive groups at your own risk.

{% hint style="warning" %}
Please note that any relationship that contains the `Global Administrator`/`Company Administrator` role will NOT be eligible for auto extend.
{% endhint %}

The table below outlines the recommended roles for use in CIPP, describing what each role enables. Click on the Role Name to navigate to Microsoft's [Azure AD built-in roles](https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#cloud-app-security-administrator) page for detailed information about each specific role.

<table><thead><tr><th width="282">Role Name</th><th>What it allows for</th></tr></thead><tbody><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#application-administrator"><strong>Application Administrator</strong></a></td><td>Can create and manage all applications, service principals, app registration, enterprise apps, consent requests. Cannot manage directory roles, security groups.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#user-administrator"><strong>User Administrator</strong></a></td><td>Manages all aspects of users, groups, registration, and resets passwords for limited admins. Cannot manage security-related policies or other configuration objects.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#intune-administrator"><strong>Intune Administrator</strong></a></td><td>Manages all aspects of Intune, including all related resources, policies, configurations, and tasks.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#exchange-administrator"><strong>Exchange Administrator</strong></a></td><td>Manages all aspects of Exchange Online, including mailboxes, permissions, connectivity, and related settings. Limited access to related Exchange settings in Azure AD.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#security-administrator"><strong>Security Administrator</strong></a></td><td>Can read security information and reports, and manages security-related features, including identity protection, security policies, device management, and threat management in Azure AD and Office 365.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#cloud-app-security-administrator"><strong>Cloud App Security Administrator</strong></a></td><td>Manages all aspects of the Defender for Cloud App Security in Azure AD, including policies, alerts, and related configurations.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#cloud-device-administrator"><strong>Cloud Device Administrator</strong></a></td><td>Enables, disables, deletes devices in Azure AD, reads Windows 10 BitLocker keys. Does not grant permissions to manage other properties on the device.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#teams-administrator"><strong>Teams Administrator</strong></a></td><td>Manages all aspects of Microsoft Teams, including telephony, messaging, meetings, teams, Microsoft 365 groups, support tickets, and service health.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#sharepoint-administrator"><strong>SharePoint Administrator</strong></a></td><td>Manages all aspects of SharePoint Online, Microsoft 365 groups, support tickets, service health. Scoped permissions for Microsoft Intune, SharePoint, and OneDrive resources.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#privileged-authentication-administrator"><strong>Privileged Authentication Administrator</strong></a></td><td>Sets/resets authentication methods for all users (admin or non-admin), deletes/restores any users. Manages support tickets in Azure and Microsoft 365. Restrictions on managing per-user MFA in legacy MFA portal.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#authentication-policy-administrator"><strong>Authentication Policy Administrator</strong></a></td><td>Configures authentication methods policy, MFA settings, manages Password Protection settings, creates/manages verifiable credentials, Azure support tickets. Restrictions on updating sensitive properties, deleting/restoring users, legacy MFA settings.</td></tr><tr><td><a href="https://learn.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#privileged-role-administrator"><strong>Privileged Role Administrator</strong></a></td><td>Manages role assignments in Azure AD, Azure AD Privileged Identity Management, creates/manages groups, manages all aspects of Privileged Identity Management, administrative units. Allows managing assignments for all Azure AD roles including Global Administrator.</td></tr></tbody></table>