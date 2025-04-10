# 🏨 Hotel Network Management System - Cisco Packet Tracer Simulation

This project simulates a **Hotel Network Management System** using Cisco Packet Tracer, incorporating advanced networking concepts and IoT automation. The hotel spans **6 floors**, each representing a distinct department with independent local area networks (LANs), automated door control, and fire suppression systems.

---

## 📁 Project Structure

### 🏢 Floors & Departments
- **1st Floor:** Reception
- **2nd Floor:** Store & Logistics
- **3rd Floor:** Food & Beverages
- **4th Floor:** Human Resources
- **5th Floor:** Management
- **6th Floor:** IT Department

---

## 🌐 Web & DNS Configuration

The hotel features internal web services and a DNS server for domain resolution:
- `hotel.com` – Main hotel website (guest services)
- `course.com` – Employee training portal
- `nsuece.com` – Backend/technical operations
- **DNS Server** – Resolves internal domain names

---

## 🔧 What’s Implemented

| Feature | Description |
|--------|-------------|
| **LAN Segmentation** | Each floor is a separate LAN using switches |
| **IP Addressing** | Unique subnets per department |
| **Router Configuration** | Central router connects all floors; supports inter-VLAN routing |
| **DNS & Web Servers** | Internal domains with HTTP access from devices |
| **Switching** | Layer 2 switching for intra-floor traffic |
| **DHCP** | Auto IP allocation via DHCP server or router |
| **VLANs** | (Optional) Could be added for enhanced floor-level isolation |
| **IoT Automation** | Door automation and fire suppression systems on each floor |

---

## 📊 Network Flow Summary

- **Intra-Floor Communication:** Direct via switch
- **Inter-Floor Communication:** Routed via central router
- **Web Access:** Resolved using DNS, served via internal web servers
- **IoT Triggers:** Based on conditions (motion detection, fire sensors)

---

## 🧠 Concepts Demonstrated

- LAN, IP Subnetting
- Switching & VLANs
- Static/Dynamic Routing (RIP/OSPF optional)
- DHCP, DNS, HTTP
- IoT Automation in Networking

---

## ▶️ How to Use

1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Power on all devices if not already on.
3. Test web access by visiting `hotel.com`, `course.com`, or `nsuece.com` from a browser.
4. Observe IP assignment using DHCP.
5. Trigger IoT devices (doors/fire sensors) to test automation scripts.

---

## 👥 Team Members

- 👤 Prapti Dethe (23102A0038)
- 👤 Mubina (23102A0039)
- 👤 Ayush Manore (23102A0040)
- 👤 Harshal Patil (23102A0041)
- 👤 Aashna Gaikwad (23102A0042)

---

## 📜 License

This project is part of our CN Mini Project submission and is for educational use only.

---

## 📬 Contact

If you have questions, feel free to reach out via GitHub or open an issue!

