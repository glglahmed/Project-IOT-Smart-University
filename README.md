### IoTSecLab - Securing Smart Devices in Campus Network

#### Project Overview
This project, developed for CET262 - Network Operation and Management (Spring 2025) at Elsewedy University of Technology, focuses on designing a secure network integrating IoT devices to create a smart campus environment. It connects multiple campus networks, IoT servers, and devices, enabling internal and external communication via the internet. The system includes services like mail, FTP, and smart IoT controls for devices such as sprinklers, RFID door access, cameras, lights, and smoke detectors.

#### Key Features
- **Network Design**: Interconnected campuses with routers, switches, and wireless routers using RIP for dynamic routing.
- **IoT Integration**: IoT servers manage devices like sprinklers, RFID readers, cameras, and environmental controls, accessible via PCs or mobile devices.
- **Security Measures**:
  - **ACL**: Standard Access Control List on Router3 (FastEthernet 0/1) permits specific IP addresses (192.168.0.102–119) and denies 193.2.2.2.
  - **Port Security**: Cisco Switch2 (FastEthernet 0/4) restricts access to a single MAC address (0040.0B45.E0CB) with shutdown on violation.
  - **MAC Filtering**: Wireless router blocks a specific MAC address (00:05:5E:AE:B6:A0).
- **Services**: Mail, FTP, and DNS servers configured for campus-wide access.
- **Simulation**: Built and tested using Cisco Packet Tracer.

#### Motivation
The project aims to enhance campus efficiency through smart IoT systems, such as automated attendance tracking, inspired by the need for time-saving and innovative university operations.

#### Objectives
- Design a secure, scalable network for PCs, servers, and IoT devices.
- Enable inter-campus communication and internet connectivity.
- Implement smart IoT services for campus management.

#### Limitations
- Limited to basic IoT functionalities; advanced features like IP phones or smart parking systems were not implemented.
- IoT server and device security requires further enhancement.
- Simulator-based; real-world deployment untested.

#### Future Plans
- Expand IoT device integration for additional smart services (e.g., teacher rooms, meeting rooms).
- Enhance security protocols for IoT devices and servers.
- Conduct further research to identify and address specific campus needs.

#### Contributors
- Omar Ahmed (230105097)
- Moayad Ayman (230105619)
- Bavly Wagyh (230103983)
- Galal Ahmed (230103349)
- Noreen Kamal (230104820)

#### Supervisors
- Dr. Hesham Sakr
- Eng. Suleiman Haitham
- Eng. Merna Ayman

#### Tools
- Cisco Packet Tracer
- AutoCAD (for background design)

#### How to Run
1. Open the project in Cisco Packet Tracer.
2. Configure devices as per the documentation (IP assignments, ACLs, port security, etc.).
3. Test IoT device connectivity via IoT Monitor on PCs using provided credentials (e.g., Server: 191.2.2.16, Username: moayad, Password: 1234).

For detailed configurations and screenshots, refer to the [Project Report](Project_IOT_Report.pdf).
