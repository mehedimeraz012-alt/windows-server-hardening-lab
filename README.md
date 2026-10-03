# Windows Server Infrastructure & Defense Hardening Lab

A virtual lab covering Windows Server domain setup, remote access configuration, and basic security assessment.

## Overview
This lab builds a corporate-style Windows domain environment and then tests and hardens it using a Linux-based assessment machine.

## Lab Environment
| Machine | OS | Role |
|---------|----|------|
| DC01 | Windows Server 2019/2022 | Domain Controller (AD DS, DNS, DHCP) |
| Client01 | Windows 10/11 | Domain-joined client |
| Attacker | Kali Linux | Assessment machine |

(Replace with your actual setup.)

## Part 1: Infrastructure
- Active Directory Domain Services (AD DS) installation and domain creation
- OU structure for departments
- Group Policy Objects (GPOs) for access control automation
- Remote Desktop Services (RDS/RDP) configuration and securing

## Part 2: Security Assessment
- Network footprinting and scanning
- Basic vulnerability assessment
- Privilege escalation lab scenarios (in an isolated lab only)

## Part 3: Hardening
- Findings and the fixes applied (e.g. restricted RDP access, password policy via GPO, patching)

## Tools
- VMware Workstation
- Windows Server
- Kali Linux

## Disclaimer
All testing was performed in an isolated virtual lab for educational purposes only.

## Author
Mehedi Hasan Meraz
[GitHub](https://github.com/mehedimeraz) | mehedimeraz012@gmail.com
