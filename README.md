# Host a Website on Azure Windows Server using IIS and PowerShell

## Project Overview

This project demonstrates how to deploy a Windows Server virtual machine in Microsoft Azure and host a static HTML website using Internet Information Services (IIS) configured with PowerShell.

The project is designed for beginners learning Azure Administration and Windows Server.

---

## Technologies Used

- Microsoft Azure
- Windows Server 2025
- IIS (Internet Information Services)
- PowerShell
- HTML

---

## Architecture

(Add architecture diagram here later.)

---

## Project Steps

1. Create Resource Group
2. Deploy Windows Server VM
3. Configure Networking
4. Connect using RDP
5. Install IIS using PowerShell
6. Create HTML Website
7. Test using localhost
8. Test using Public IP

---

## PowerShell Commands

See:

Commands/powershell-commands.md

---

## Screenshots


<img width="1536" height="1024" alt="ChatGPT Image Jul 4, 2026, 01_43_50 PM" src="https://github.com/user-attachments/assets/6ccaf1b2-19f1-452b-a989-e4e857e2a202" />

---

## Result

The website was successfully hosted and accessed using the Azure VM Public IP.

---
| Error                | Solution                                       |
| -------------------- | ---------------------------------------------- |
| IIS page not loading | Check HTTP port (80) in NSG                    |
| RDP not connecting   | Verify port 3389 is allowed                    |
| HTML not displaying  | Ensure `index.html` is in `C:\inetpub\wwwroot` |
| IIS service stopped  | Run `Start-Service W3SVC`                      |

## Learning Outcomes

After completing this project you will understand:

- Azure Virtual Machines
- Resource Groups
- Virtual Networks
- Network Security Groups
- Windows Server
- IIS
- PowerShell
- Static Website Hosting

---

## Author

Shabin Shareefa

Cloud With Shabin
