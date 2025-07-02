# Task- 5

Objective: Capture live network packets and identify basic protocols and traffic types.


Tools: Wireshark (free).


Deliverables:  A packet capture (.pcap) file and a short report of protocols identified.

# Wireshark Network Analysis

This project demonstrates the use of Wireshark to capture and analyze network traffic. The process includes installing Wireshark, capturing live traffic, filtering packets, and analyzing protocols.

**Steps Followed**

1. **Install Wireshark**
   - Downloaded and installed the latest version from [https://www.wireshark.org](https://www.wireshark.org).
   - ![image](https://github.com/user-attachments/assets/ea8bfabe-ed5a-41b7-b95d-b88e9191d809)


2. **Start Capture**
   - Captured packets on the active network interface (e.g., Wi-Fi).
   - ![image](https://github.com/user-attachments/assets/1fe121a9-b6f5-4ea3-aa9f-9380efcd2298)


3. **Generate Network Traffic**
   - Opened a few websites and pinged public servers (`ping google.com`) to create traffic.
   - ![image](https://github.com/user-attachments/assets/b2a65474-dded-43d3-853b-87c75dc79135)


4. **Stop Capture**
   - Capture was stopped after approximately 1 minute and analysed traffic with the help of expert analyze option.
   - ![image](https://github.com/user-attachments/assets/f4c5f44d-22c9-4caa-bac1-1563a1fb83fe)

  
5. **Filter Packets**
   - Used the display filters in Wireshark to view specific protocols:
     - `http`
     - ![image](https://github.com/user-attachments/assets/7ad7791c-1dd2-45bb-995b-51aca260d017)

     - `dns`
     - ![image](https://github.com/user-attachments/assets/e2024b6b-5ad3-430c-b611-1afcf4232b6e)
     - ![image](https://github.com/user-attachments/assets/fc42e9be-a95a-4cbe-9f94-cf2de2418c34)


     - `tcp`
     - ![image](https://github.com/user-attachments/assets/5683189a-23a8-484a-b8be-7787a2c06835)


6. **Identified Protocols**
   - Protocols captured include:
     - DNS (Domain Name System)
     - HTTP (HyperText Transfer Protocol)
     - TCP (Transmission Control Protocol)

7. **Export Capture**
   - The capture file was exported in `.pcap` format.

8. **Summary of Findings**
   - DNS: Resolved multiple domain names such as `google.com`, `youtube.com`.
   - HTTP: GET requests for web pages were visible with response status codes.
   - TCP: Multiple TCP handshakes were observed indicating new connections.
