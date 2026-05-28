# Windows Fundamentals Part 1 - TryHackMe

**Date:** 5/28/2026  
**Path:** Cybersecurity 101  

---

## Executive Summary
This room provided a foundational walkthrough of the Microsoft Windows operating system environment. It covered core Graphical User Interface (GUI) navigation, fundamental system administration utilities, and the underlying file system structure that dictates security and access control.

---

## Key Core Concepts Covered

### 1. File Systems & Storage (NTFS)
* **NTFS (New Technology File System):** Beyond simply storing files and folders on the hard drive, NTFS introduces robust, advanced features. Most notably, it handles **file permissions** (Access Control Lists) to restrict or allow user access to specific data.
* **System Directories:** The core operating system files are structurally isolated. Windows stores its critical system files inside the `System32` folder. 
* **Environment Variables:** The system utilizes `%windir%` as a shortcut variable to dynamically point to the main Windows installation directory (typically `C:\Windows`).

### 2. Remote Management & GUI Customization
* **Remote Desktop Protocol (RDP):** Practiced accessing a remote Windows environment directly through the terminal to simulate real-world administrative workflows.
* **Interface Flexibility:** Explored the structural components of the Windows GUI, including the ability to fully customize the Taskbar configuration to optimize workspace efficiency.

### 3. System Security & Privilege Management
* **User Account Control (UAC):** Operating continuously as a full local Administrator poses a severe security risk. To mitigate this, Windows implements UAC. Even if an account has administrative privileges, UAC acts as a defensive barrier by explicitly warning the user and demanding confirmation before executing high-impact system changes.

### 4. System Monitoring
* **Task Manager:** Serves as a vital built-in utility for real-time visibility into the OS. It monitors active processes, application performance statuses, resource consumption (CPU, Memory, Disk, Network), and overall system health.

