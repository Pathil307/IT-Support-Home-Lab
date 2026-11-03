# IT -Support- Home -Lab

A hands-on IT Support and Networking home lab documenting practical experience with Windows Server, Windows 11, Active Directory, DNS, network configuration, user administration and troubleshooting.

## Overview

This repository documents my hands-on learning journey through an IT Support home lab built using Oracle VirtualBox.

The lab provides a virtual environment where I practise Windows Server administration, Active Directory management, basic networking and troubleshooting.

My goal is to develop practical technical skills relevant to entry-level IT Support / ICT Support roles while building a foundation for a future career in Network Engineering.

## Technologies & Tools

- Windows Server
- Windows 11
- Oracle VirtualBox
- Active Directory Domain Services (AD DS)
- Domain Name System (DNS)
- IPv4 Networking
- Windows Command Prompt (CMD)
- File and Folder Permissions

## Lab Environment

The home lab was created using Oracle VirtualBox and consists of two virtual machines.

| Component | Configuration |
|---|---|
| Virtualisation Platform | Oracle VirtualBox |
| Server | Windows Server |
| Client | Windows 11 |
| Active Directory Domain | `LAB.local` |
| Server IP Address | `192.168.56.101` |
| Client IP Address | `192.168.56.102` |
| Network Configuration | Host-only and NAT adapters |

### Network Setup

- Configured a Host-only network to enable communication between the virtual machines.
- Configured a NAT adapter to provide internet connectivity.
- Configured IPv4 addressing for the server and client.
- Configured DNS for the Active Directory environment.
- Used Windows 11 as a client machine for testing network and domain connectivity.

## Projects & Practical Exercises

### 1. Windows Server & Active Directory

Installed and configured Windows Server in Oracle VirtualBox to create a virtual Active Directory environment.

**Practical tasks completed:**

- Installed Windows Server in a virtual machine.
- Configured Windows Server as a Domain Controller.
- Installed Active Directory Domain Services (AD DS).
- Created the `LAB.local` domain.
- Created Organizational Units (OUs).
- Created and managed user accounts.
- Created security groups.
- Organised directory objects within the appropriate OUs.

**Key Learning:**

Gained an understanding of how Active Directory provides centralised management of users, groups and other directory objects within a Windows domain environment.

### 2. User & Group Management

Practised managing user accounts and security groups within Active Directory.

**Tasks completed:**

- Created an Accounts Organizational Unit to organise user accounts.
- Created a Groups Organizational Unit to organise groups.
- Created user accounts within the appropriate OU.
- Created security groups.
- Practised adding users to security groups.
- Explored how OUs help administrators organise and manage directory objects.

**Key Learning:**

Organizational Units provide a structured way to organise users, computers and groups within an Active Directory domain. Security groups help administrators manage access to shared resources and permissions.

### 3. Shared Folders & Permissions

Configured departmental shared folders within the Windows Server lab to practise file sharing and access management.

**Example departments:**

- HR
- Finance

**Practical tasks:**

- Created departmental folders.
- Explored Windows file and folder permissions.
- Practised controlling access to shared resources.
- Learned how permissions can be used to restrict or grant access to departmental information.

**Key Learning:**

Shared folders allow users to access common resources over a network. Appropriate permissions help ensure that users can only access information they are authorised to use.

### 4. Windows 11 Client Configuration

Created and configured a Windows 11 virtual machine in Oracle VirtualBox to practise client-side networking and domain connectivity.

**Practical tasks:**

- Created a Windows 11 virtual machine.
- Configured network adapters in VirtualBox.
- Configured IPv4 network settings.
- Established network communication between the Windows 11 client and Windows Server.
- Successfully connected the Windows 11 client machine to the Active Directory domain.
- Tested connectivity between virtual machines.

**Key Learning:**

Understanding how client machines communicate with servers is essential in a Windows domain environment. This exercise provided practical exposure to client-server networking and domain connectivity.

### 5. Networking & Hands-on Troubleshooting

Performed practical networking configuration and troubleshooting exercises using Windows Server and Windows 11 virtual machines.

**Troubleshooting exercises included:**

**DNS Resolution Issues**

- Investigated DNS configuration and name resolution.
- Used `nslookup` to test DNS queries.
- Explored how DNS affects communication between devices and domain services.

**No Internet Access**

- Investigated network adapter configurations.
- Checked IP configuration and network connectivity.
- Used `ping` to test connectivity.

**IP Address Conflicts**

- Investigated IP addressing problems.
- Examined IPv4 configurations using `ipconfig`.
- Explored how duplicate IP addresses can affect network communication.

**Network Connectivity**

- Tested communication between virtual machines.
- Used command-line tools to identify connectivity issues.
- Practised identifying possible causes of network communication failures.

**Key Learning:**

These exercises helped me develop a structured approach to troubleshooting by investigating network configurations, testing connectivity and identifying possible causes of common networking problems.

### 6. Windows Networking Commands

Practised using Windows Command Prompt (CMD) to inspect network configurations, test connectivity and troubleshoot common networking issues.

| Command | Purpose |
|---|---|
| `ipconfig` | Displays IP configuration information. |
| `ipconfig /all` | Displays detailed network configuration, including DNS and DHCP information. |
| `ipconfig /release` | Releases a DHCP-assigned IP address. |
| `ipconfig /renew` | Requests a new DHCP-assigned IP address. |
| `ipconfig /flushdns` | Clears the local DNS resolver cache. |
| `ping` | Tests connectivity between devices. |
| `nslookup` | Queries DNS to investigate name resolution. |

**Key Learning:**

These commands helped me understand how to inspect network settings, test connectivity, investigate DNS problems and troubleshoot common Windows networking issues.

## Troubleshooting Scenarios & Learning Notes

### 1. Active Directory: User Accounts and Password Resets

Explored an IT Support scenario involving a user who has forgotten their password.

**The documented support procedure includes:**

1. Verify the user's identity according to organisational security procedures.
2. Locate the user's existing account in Active Directory.
3. Reset the existing user's password.
4. Configure the account to require a password change at the next login, where appropriate.
5. Provide temporary credentials securely.

**Important distinction:**

- **New employee or student:** Create a new user account.
- **Existing employee or student who forgot their password:** Reset their existing account's password.

**Key Learning:**

An Organizational Unit helps administrators organise user accounts, while password resets are performed through Active Directory user administration. Understanding the difference between creating a new account and resetting an existing account is important when handling common IT Support requests.

### 2. Troubleshooting: Alternative Input Methods

While working in Active Directory Users and Computers, I needed to access the right-click context menu without a physical mouse.

**Problem:** No physical mouse was available.

**Investigation:** Identified that the laptop touchpad was still functional.

**Solution:** Used a two-finger tap on the touchpad to perform a right-click.

**Result:** Successfully accessed the context menu and continued with administrative tasks.

**Key Learning:**

IT Support troubleshooting also involves identifying alternative methods of completing tasks when particular hardware or resources are unavailable. This experience reinforced the importance of adaptability and problem-solving when working with limited resources.

## Skills Developed

Through this home lab, I have developed practical knowledge and experience in the following areas:

### Windows Administration

- Windows Server administration.
- Windows 11 configuration.
- Active Directory Domain Services.
- User and group management.
- Organizational Unit management.

### Networking

- IPv4 configuration.
- DNS fundamentals.
- Basic network connectivity troubleshooting.
- Client-server communication.
- Windows networking commands.

### IT Support

- Basic hardware and software troubleshooting.
- Identifying and investigating technical issues.
- File and folder permissions.
- Problem-solving.
- Technical documentation.

### Virtualisation

- Creating and configuring virtual machines.
- Working with Oracle VirtualBox.
- Configuring virtual network adapters.

## Future Improvements

I plan to continue expanding my home lab by exploring:

- DHCP configuration and management.
- Group Policy Objects (GPO).
- Advanced Active Directory administration.
- PowerShell fundamentals.
- Additional DNS troubleshooting scenarios.
- More Windows 11 support scenarios.
- Helpdesk and IT Support simulations.
- Additional networking configuration and troubleshooting exercises.

## Career Development

This project forms part of my practical learning portfolio as I prepare for entry-level IT Support / ICT Support opportunities.

My long-term career goal is to progress into Network Engineering by continuously developing my knowledge of Windows administration, networking and IT infrastructure.
