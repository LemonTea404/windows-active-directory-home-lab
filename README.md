# Active Directory Home Lab

## Project Overview

I built a virtual Windows domain environment to practice common entry-level IT support and Active Directory administration tasks. The lab includes a Windows Server domain controller and a domain-joined Windows client.

The project is to demonstrates user and computer administration, organizational units, Group Policy, password resets, account lockout troubleshooting, security groups, and shared-folder permissions.

## Lab Environment

* VirutalMachine
* Window 11 Pro
* Window Server 2022
* **Domain:** `corplab.local`
* **Domain Controller:** `DC01`
* **Client Computer:** `PC01`
* **Test User:** `CORPLAB\jotaro.kujo`
* **Security Group:** `GG_IT_Share_RW`
* **Network Share:** `\\DC01\IT-Share`

## Skills Demonstrated

* Installed and configured Active Directory Domain Services
* Created a new Windows domain
* Organized users and computers with organizational units
* Joined a Windows client to the domain
* Created and managed domain users
* Reset user passwords
* Configured an account-lockout policy using Group Policy
* Diagnosed and unlocked a locked domain account
* Created and managed an Active Directory security group
* Configured share and NTFS permissions
* Tested authorized access, denied access, and restored access
* Used PowerShell to verify domain and account status
