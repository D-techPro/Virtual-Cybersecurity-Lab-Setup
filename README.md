# Virtual Cybersecurity Lab-Setup

**1.	Introduction**\
Ethical hacking requires a safe and isolated environment to practice and test vulnerabilities without risking real systems. A virtual lab provides this isolation, allowing users to sharpen their skills and learn from mistakes without causing harm.

**2.	Essential Components** 
To set up a virtual cybersecurity lab, I made use of three main components:  
•	Virtualization Software (VirtualBox): This software allows a single physical computer (host) to run multiple virtual machines (VMs). Each VM acts as a separate computer with its own operating system. In this project I used two virtual machines with Kali Linux and windows 7 as the operating systems.
•	Attacking Machine (VM): This VM is used to perform penetration testing and vulnerability assessments. Kali Linux OS is used as it come pre-installed with a wide array of cybersecurity tools
•	Target Machine (VM): This VM is the system that will be attacked and analyzed. I made use of windows 7 OS for this project.

**3.	Installation Process**
**Install VirtualBox**
I downloaded and install VirtualBox from its official website. I ensured I also download and install the VirtualBox Extension Pack.

**Install Attacking Machine** (Kali Linux) 
I downloaded the VirtualBox image for Kali Linux OS iso file. uploaded the downloaded iso file into logical optical anchor of the storage section in the virtual machine.


![Screenshot (21)](https://github.com/user-attachments/assets/0f080f99-e209-4b7a-ae91-edf9eeb62768)


**Install Target Machine** (Windows 7 OS) 
I downloaded windows 7 OS iso file as a vulnerable VM attached the iso file to the logical optical CD of the storage section of the virtual machine.

![Screenshot (24)](https://github.com/user-attachments/assets/15f65ed6-be76-44e6-b68f-c831af36519c)


**4.	Network Configuration (Internal Network)** 

To isolate my lab from the public internet and allow VMs to communicate with each other, internal Network was used. This setup ensures that my hacking activities remain within the virtual lab and do not affect my host machine or external networks. Similar to Host-Only, but VMs can only communicate with other VMs on the same internal network, not with the host machine. This offers even greater isolation.

**Windows 7 network settings**
