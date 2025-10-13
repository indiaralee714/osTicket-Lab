# osTicket Lab – Azure Deployment

This repository documents a **personal lab I completed using Microsoft Azure**, demonstrating the installation, configuration, and testing of **osTicket**, a popular open-source support ticket system. The lab includes setup of the web server, PHP, MySQL database, and user management.

---

## Table of Contents

1. [Lab Overview](#lab-overview)
2. [Environment Setup](#environment-setup)
3. [Installing osTicket](#installing-osticket)
4. [Post-Installation Configuration](#post-installation-configuration)
5. [Users, Roles, and Departments](#users-roles-and-departments)
6. [Testing the Ticket System](#testing-the-ticket-system)
7. [Screenshots](#screenshots)

---

## Lab Overview

**Objective:** Deploy and configure osTicket on Azure to simulate a support ticketing environment.  

**Tools Used:**
- Microsoft Azure (VMs, Networking)
- Windows Server / Linux Server (depending on deployment)
- IIS / Apache Web Server
- PHP
- MySQL / MariaDB
- osTicket Web Application
- HeidiSQL / phpMyAdmin (for database management)
- RDP / SSH for remote access

**Key Outcomes:**
- Successfully installed osTicket on Azure VM
- Configured web server, PHP, and database
- Created users, roles, and departments
- Verified ticket creation and resolution workflows

---

## Environment Setup

<details>
<summary>View Environment Details</summary>

- Azure VM with Windows Server
- Public IP configured
- Network Security Group rules allowing HTTP/HTTPS
- RDP access enabled
- Database server installed (MySQL/MariaDB)

</details>

---

## Installing osTicket

<details>
<summary>View Installation Steps</summary>

1. Download osTicket from the official website.
2. Upload osTicket files to the web server (IIS/Apache).
3. Configure PHP settings (e.g., `file_uploads`, `memory_limit`).
4. Create MySQL database for osTicket using HeidiSQL.
5. Set permissions for the web server to access osTicket files.

**Example:**

<img src="https://i.imgur.com/your-example-image.png" alt="osTicket Installation" style="max-width:100%; height:auto; display:block; margin:auto;" />

</details>

---

## Post-Installation Configuration

<details>
<summary>View Post-Installation Steps</summary>

- Complete the web-based setup by navigating to the Azure VM's public IP.
- Enter database credentials and administrator account info.
- Remove the `setup/` folder for security.
- Verify that the admin dashboard is accessible.

<img src="https://i.imgur.com/your-dashboard-image.png" alt="osTicket Admin Dashboard" style="max-width:100%; height:auto; display:block; margin:auto;" />

</details>

---

## Users, Roles, and Departments

<details>
<summary>View User & Role Configuration</summary>

- Created multiple user accounts (staff & admin)
- Defined roles and permissions
- Configured departments to organize tickets

<img src="https://i.imgur.com/your-users-image.png" alt="Users and Roles" style="max-width:100%; height:auto; display:block; margin:auto;" />

</details>

---

## Testing the Ticket System

<details>
<summary>View Ticket Testing Steps</summary>

- Submitted test tickets via the customer portal
- Verified tickets appear in the admin dashboard
- Tested ticket assignment to specific departments
- Confirmed email notifications work (if configured)

<img src="https://i.imgur.com/your-ticket-test-image.png" alt="Ticket Testing" style="max-width:100%; height:auto; display:block; margin:auto;" />

</details>

---

## Screenshots

<details>
<summary>View All Lab Screenshots</summary>

![Installation Screenshot](https://i.imgur.com/your-example-image.png)  
![Admin Dashboard](https://i.imgur.com/your-dashboard-image.png)  
![Users & Roles](https://i.imgur.com/your-users-image.png)  
![Ticket Testing](https://i.imgur.com/your-ticket-test-image.png)  

</details>

---

