# College Network Scenario

A simulated network infrastructure project designed for a college, implemented using Cisco Packet Tracer. The objective of this project is to design and implement a scalable, secure, and optimized LAN (Local Area Network) that connects various departments of a college campus.

---

## 📌 Objectives

- Redesign the college network for improved performance and scalability.
- Enhance network flexibility, remote access, and security.
- Centralize services and optimize resource usage.
- Integrate wired and wireless networks using modern devices.

---

## 🛠️ Technologies & Tools

- **Cisco Packet Tracer**
- **Cisco Catalyst 6509 & 4500 Switches**
- **Cisco Unified Computing System (UCS)**
- **Cisco Mobility Services Engine (MSE)**
- **Cisco Aironet 1140 Access Points**
- **Routing Protocols (RIP)**
- **TFTP Server**
- **DHCP Configuration**
- **VLAN Segmentation**

---

## 🧠 Key Features

- **Network Segmentation:**  
  Departments have individual subnets using private IP blocks like `192.168.x.x`, `128.168.0.0`, and `10.0.0.0`.

- **Routing & Subnetting:**  
  RIP implemented between routers. Departments use /24 subnets.

- **DHCP Integration:**  
  Dynamic IP assignment using DHCP servers across departments (Admin, Chemical, Aero).

- **VLAN Configuration:**  
  VLANs implemented for IT, ECE, and Computer Departments (VLAN2, VLAN3, VLAN4).

- **TFTP Server:**  
  For file transfer and backup across the network.

- **CNMS Web Access:**  
  Testing webpage access (e.g., bahria.com) from different hosts.

---

## 🖧 Subnet Allocation

### IT Department – `192.168.1.0/24`
- HOD: `192.168.1.2`
- IT Labs: `192.168.1.3–1.6`
- Printer: `192.168.1.7`

### Computer Department – `192.168.2.0/24`
- HOD: `192.168.2.2`
- Labs: `192.168.2.3–2.6`
- Printer: `192.168.2.7`

### Administration – `192.168.3.0/24`
- DHCP Enabled
- Static IPs: `192.168.3.2–3.6`

### Server Room – `1.0.0.0/8`
- DNS: `1.0.0.2`, Web: `1.0.0.3`, TFTP: `1.0.0.4`

### ECE Department – `128.168.0.0/24`
- Hosts: `128.168.0.2–0.6`

### Principal Room – `192.168.4.0/24`
- PC: `192.168.4.2`, Laptop: `192.168.4.3`

### Chemical Department – `192.168.5.0/24`
- DHCP Enabled via Wireless Router

### Aero Department – `192.168.6.0/24`
- DHCP Enabled via Wireless Router

---

## 📶 Wireless Access

- Cisco Aironet 1140 APs for wireless coverage.
- Supports centralized control with full Layer 3 mobility.

---

## 🧪 Testing & Deliverables

- RIP routing verification between routers.
- VLAN communication between departments.
- DHCP request handling from multiple departments.
- Ping tests and website access confirmation.

---



