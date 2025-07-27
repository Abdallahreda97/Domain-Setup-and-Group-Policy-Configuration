# Active Directory Lab - Domain Setup and Group Policy Configuration

This project demonstrates the setup of an Active Directory domain environment and implementation of multiple Group Policy configurations using Windows Server and a Windows 10 client, all hosted on VirtualBox.

Here You Can Find The Exam:
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%20-%20Active%20Directory%20%2B%20Group%20Policy.png

## 🛠️ Lab Environment

- **Domain Name:** exam.local  
- **Domain Controller (PDC):**
  - Hostname: `PDC`
  - IP Address: `192.168.1.2`
- **Client Machine:**
  - Hostname: `HRPC01`
  - IP Address: `192.168.1.40`

## 🧩 Configurations Performed

1. Created Organizational Units for:
   - HR
   - Sales
   - IT

2. Created users:
   - **HR:** Mohamed Zohdy, Salma Mohamed
   - **Sales:** Maha Ahmed, Alaa Kamal
   - **IT:** Moataz Yusuf, Ahmed Nabil

3. Created security groups for each department and assigned users.

4. Joined the Windows 10 machine to the domain.

5. Added the IT group as a local administrator on the client.

6. Applied Group Policies to HR OU:
   - Show only Fonts in Control Panel
   - Remove “Properties” from This PC context menu
   - Disable Command Prompt
   - Block external storage for all HR users except Mohamed Zohdy
   - Create desktop shortcut to `hrapp.exam.local`

7. Configured domain-wide password policy:
   - Min. length: 6 characters
   - Enforce complexity
   - Password change every 60 days
   - Remember last 3 passwords
   - Lock account for 30 minutes after 5 failed attempts

## 📸 Screenshots

https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%201.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%202.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%203.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%204.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%205.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%206.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%207.png
https://github.com/Abdallahreda97/Domain-Setup-and-Group-Policy-Configuration/blob/main/Screenshots/Exam%20LAB%208.png

## 💻 Virtualization

Both Windows Server and Windows 10 were installed on VirtualBox.

## 📂 Folder Structure

Refer to this repo's structure for clear understanding of steps and verification screenshots.

---

**Author:** Abdallah Elmohr  
**Project Date:** July 2025

