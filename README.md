# Active Directory Homelab

This is an Active Directory homelab built with VirtualBox, Windows Server 2022, and Windows 10.

## What I built

- A Windows Server 2022 domain controller (DC01)
- Active Directory Domain Services (AD DS)
- DNS configured on the server
- Multiple domain users
- A Windows 10 workstation joined to the domain

## Lab setup

- Domain: MyCompany.local  
- Domain Controller: DC01  
- Server IP: 192.168.1.10  

Users created:
- jsmith
- mgarcia
- dlee
- sjohnson

## What I learned

- How Active Directory stores and manages users
- How DNS is required for domain communication
- How to join a client machine to a domain
- How authentication works between a workstation and a domain controller

## Screenshots

### Server configuration
This shows the domain controller setup, including the domain and IP.

![Domain Controller](screenshots/domain-controller-config.png)

---

### Active Directory users
These are the users created in Active Directory.

![Users](screenshots/active-directory-users.png)

---

### Domain Joined
This confirms the client machine is joined to the domain.

![AD DS](screenshots/domain-joined.png)

---

## Logged in as a domain user
This shows a successful login using a domain account (MYCOMPANY\jsmith).

![Domain User Login](screenshots/domain-user-login.png)

---

## Next steps

- Resetting passwords and locking accounts
- Creating groups and assigning permissions
- Setting up shared folders
