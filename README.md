# cybersecurity-journey
My 8-week cybersecurity learning journey and TryHackMe write-ups.

## About Me
I am a Computer Education and Instructional Technology student at Boğaziçi University. This repository documents my transition into cybersecurity, focusing on Linux administration, network security, and Python scripting.

---

## Lab Setup & Fundamentals
**Date:** July 22, 2026

### Objective
Set up the foundational virtual environment and establish a secure connection to the TryHackMe network.

### Tasks Completed
* **Virtual Machine Setup:** Successfully imported and configured Kali Linux on Oracle VM VirtualBox.
* **Network Connection:** Downloaded the TryHackMe `.ovpn` configuration file and established a secure VPN tunnel.
* **Verification:** Verified the connection using the `sudo openvpn` command and confirmed the `Initialization Sequence Completed` message.

### Challenges & Troubleshooting
* **Linux Case Sensitivity:** While navigating directories in the terminal, I received a `No such file or directory` error when typing `cd downloads`. I quickly realized Linux is case-sensitive and corrected the command to `cd Downloads`. This was a great hands-on reminder of Linux fundamentals!

---

## Cybersecurity Fundamentals & OS Concepts
**Date:** July 25, 2026

### Objective
Understand the core domains of cybersecurity, explore career paths, and grasp the foundational architecture of operating systems.

### Tasks Completed
*   **TryHackMe Modules Completed:** Achieved 100% completion in the freely available rooms on TryHackMe. Key areas covered include:
    *   **Cyber Security Intro:** Explored offensive and defensive security methodologies, alongside potential career paths.
    *   **Computer & OS Architecture:** Examined core hardware components ("Inside a Computer System"), the invisible manager functions ("Operating Systems: Introduction"), and workspace configurations ("Windows Basics").
*   **Independent Research:** Navigated around TryHackMe's Premium limitations by conducting comprehensive independent research to complete the remaining module topics. Successfully studied the following core concepts on my own:
    *   **Virtualisation & Lab Setup:** The mechanics of virtualization and virtual machine deployments.
    *   **Linux CLI Basics:** Core terminal commands and file system navigation.
    *   **Client-Server Basics:** Network communication principles between systems.
    *   **OS Security:** Fundamental defense mechanisms in modern operating systems.

### Key Takeaways
*   Understanding the separation between Kernel Space and User Space is critical when analyzing a system's vulnerability.
*   Learned the importance of User Management features; an attacker's primary goal during exploitation is often to bypass these to steal a highly privileged credential.
