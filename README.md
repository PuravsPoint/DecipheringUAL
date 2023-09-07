# DecipheringUAL

This repo aims to help you decipher the UAL from a Digital Forensics & Incident Response (DFIR) perspective. The UAL is the Microsoft 365 Unified Audit Log.

I use the decipher term here purposely because Microsoft have a lot of GUID's and ID's in the Audit log entries and there are helpful ways available to resolve these into more meaningful entities. Additionally, it isn't always clear which fields are important to look at so I'll provide some insight here.

Below is a break down of the pages within this repo:

[01-Access](01-Access.md) - This page walks through setting up initial access to the UAL using Purview Audit.

[02-New-RoleGroup](02-New-RoleGroup.md) - This page breaks down the auditing of New-RoleGroup operation event including key fields of note and how to decipher them.

[03-Add-RoleGroupMember](03-Add-RoleGroupMember.md) - This page will help you investigate the audit event for the Add-RoleGroupMember operation from a DFIR perspective.

[04-Get-RoleGroup](04-Get-RoleGroup.md) - This page will help you investigate the audit event for the Get-RoleGroup operation from a DFIR perspective.

[05-Get-RoleGroupMember](05-Get-RoleGroupMember.md) - This page will help you investigate the audit event for the Get-RoleGroupMember operation from a DFIR perspective.

[06-Update-RoleGroupMember](06-Update-RoleGroupMember.md) - This page will help you investigate the audit event for the Update-RoleGroupMember operation from a DFIR perspective.

[07-Set-TeamsProtectionPolicy] - This upcoming page will help you investigate the audit event for the Set-TeamsProtectionPolicy operation from a DFIR perspective.

<br>
<h3>Notable features:</h3>

[Issue 88 of Rod Trent's Microsoft Defender Weekly Wrap](https://microsoftdefender.substack.com/i/135906120/defender-things)
