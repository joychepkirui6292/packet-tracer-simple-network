# packet-tracer-simple-network[README.md](https://github.com/user-attachments/files/22257308/README.md)
# Packet Tracer - Simple Network

This project is based on the Cisco Networking Academy lab: *Create a Simple Network*.

## Objective

-   Build a simple network in Cisco Packet Tracer.
-   Configure end devices (PC and Laptop).
-   Verify connectivity and IP addressing.

## Network Topology

-   **PC** (wired connection via Ethernet)
-   **Laptop** (wireless connection with NIC replaced)
-   **Wireless Router**
-   **Cable Modem**
-   **Cloud (ISP)**

## IP Configuration Results

  Device   IPv4 Address    Subnet Mask     Default Gateway
  -------- --------------- --------------- -----------------
  PC       192.168.0.101   255.255.255.0   192.168.0.1
  Laptop   192.168.0.102   255.255.255.0   192.168.0.1

## Steps Taken

1.  Added network devices (PC, Laptop, Wireless Router, Cable Modem,
    Cloud).
2.  Connected devices using appropriate cables (Ethernet, Coaxial).
3.  Configured PC to obtain an IP address via DHCP.
4.  Replaced Laptop's wired NIC with a wireless NIC (WPC300N) and
    connected to the wireless network.
5.  Verified connectivity using:
    -   `ipconfig` to check IP addresses.
    -   `ping cisco.srv` for connectivity test.

## Files in this Repository

-   `Creating a Simple Network.html` -- original Cisco lab instructions.[Consultation Form (1).pdf](https://github.com/user-attachments/files/22583959/Consultation.Form.1.pdf)

-   `a Simple Network.pkt` -- Packet Tracer project file.
-   `README.md` -- documentation (this file).
