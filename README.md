# Active Directory & Help Desk Administration Lab

## Project Overview

This project is a hands-on IT administration lab built using Windows Server 2022 and Oracle VirtualBox. The purpose is to practice common IT support and system administration tasks in a simulated company environment.

## Lab Environment

- Virtualization: Oracle VirtualBox
- Operating System: Windows Server 2022 Standard Evaluation
- Directory Service: Active Directory Domain Services (AD DS)
- Domain: corp.local
- Server Name: IT-SERVER01
- Tools: PowerShell, Active Directory

## Tasks Completed

1. ### Windows Server Configuration

   - Created a Windows Server 2022 virtual machine.
   - Configured network connectivity.
   - Verified connectivity using the `ping` command.

2. ### Active Directory Setup

   - Installed Active Directory Domain Services.
   - Promoted the server to a Domain Controller.
   - Created the `corp.local` domain.

3. ### Organizational Unit Management

   - Created an Employees Organizational Unit.
   - Verified the OU using PowerShell.
  
4. ### Employee Account Management

   - Created a test employee account for John Smith.
   - Enabled the account.
   - Configured a password reset.
   - Required a password change at the next login.
   - Queried account properties to verify configuration.
  
## PowerShell Skills Practiced

- `Get-ADDomain`
- `New-ADOrganizationalUnit`
- `New-ADUser`
- `Get-ADUser`
- `Set-ADUser`
- `Set-ADAccountPassword`

## Future Exercises

- Unlock locked employee accounts.
- Create and manage security groups.
- Disable employee accounts.
- Configure shared folders and permissions.
- Join a Windows client computer to the domain.
- Troubleshoot DNS and network connectivity.

## Project Goal

Develop practical skills in windows administration, Active Directory, PowerShell, and troubleshooting to prepare for entry-level IT Support and Help Desk Position.
