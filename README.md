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

![Screenshot (25)](https://github.com/user-attachments/assets/a3328193-9589-4ff9-8456-83491ef4038c)


**Kali Linux network setting**


![Screenshot (22)](https://github.com/user-attachments/assets/06ef4302-d709-42fe-bd4d-4b2ba8cf5a8d)

**Boot order settings**

![Screenshot (20)](https://github.com/user-attachments/assets/d62291e1-25d2-474f-8f93-7cac45815683)

**5.	Verifying connectivity via ping test**

**Configuring Kali Linux static ip address**

![eth0 configuration ip address](https://github.com/user-attachments/assets/925ac3b8-6c5d-4410-8e60-d0950d22941d)

**Confirming Kali Linux static ip address**

![Kali Linux ip address](https://github.com/user-attachments/assets/b2912054-b5e6-4ec3-926f-1d96559b0fbb)


**Windows 7 static ip address**

![Win 7 ip address](https://github.com/user-attachments/assets/fa3542eb-77dd-4414-9768-d0d33ff59a35)


**Pinging Kali Linux from Windows 7**

![Win 7 ping kali](https://github.com/user-attachments/assets/b39daf58-6f1f-4f3b-a679-842b090e72fc)

**Pinging windows 7 from Kali Linux**

![Kali Linux pinging Windows 7](https://github.com/user-attachments/assets/a6865397-31bd-4c34-b509-3955a23a90f6)

**Shared resources on windows 7 access from Kali Linux**

![shared folders on win 7](https://github.com/user-attachments/assets/6a382529-61e6-482b-9643-cc02ca2f279d)

**Services on windows 7 accessed from Kali Linux** 

![service enum of win 7](https://github.com/user-attachments/assets/d23c0da0-fd88-45a4-99c9-3717cefbe1a6)

**Folders shared on Kali Linux accessed from windows 7**
![window shared folders](https://github.com/user-attachments/assets/60bd9d81-524a-4c36-acc5-054952c390db)

**Services enumeration on Kali-Linux **

![service enum win 7](https://github.com/user-attachments/assets/7b85a86d-955f-4b09-9743-04f5b49add1a)
