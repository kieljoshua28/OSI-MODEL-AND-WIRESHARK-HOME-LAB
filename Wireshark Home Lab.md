Wireshark Home Lab

1. Open the Wireshark Application

<img width="1427" height="323" alt="Screenshot 2026-07-23 135340" src="https://github.com/user-attachments/assets/154763a4-a7c0-44e9-9568-e04b12f61fec" />

<br>

2. Click the "Wi - Fi" in the list

<img width="1437" height="381" alt="Screenshot 2026-07-23 135553" src="https://github.com/user-attachments/assets/e4403414-42f5-4a3d-b52c-840a76124d7d" />

<br>

3.Open commmand prompt and ping google.com (for this example) to know if it's reachable, and yes it send back.

<img width="732" height="253" alt="Screenshot 2026-07-23 140142" src="https://github.com/user-attachments/assets/63d827a7-e7a5-4c12-a82b-d5e507acd21b" />

<br>

4. Here, is identifying the parts of the OSI model we can see in wireshark

<img width="1917" height="930" alt="Screenshot 2026-07-23 140648" src="https://github.com/user-attachments/assets/1b7d7b35-d6ea-4ab3-820d-d5d5ff55c907" />

I click Frame 226 and this is what I got:
- "Frame 226: Packet, 74 bytes on wire (592 bits), 74 bytes captured (592 bits) on interface \Device\NPF_{9D4E7238-2DB4-43D9-89F9-F784D4E756D2}, id 0". displayed here is how many bytes captured, which interface it came form, what time it captured (when opening the dropdown in frame 226).
  
-The "Ethernet II, Src: AzureWaveTec_57:9c:8d (e8:fb:1c:57:9c:8d), Dst: DLinkInterna_e3:0c:49 (e0:1c:fc:e3:0c:49)" lands on the layer 2 of the OSI model which is the data link. It shows the "Ethernet" which is the standard protocol that operates at Layer 2 on wired/Wi-Fi networks. Also, we can see the MAC address here (e8:fb:1c:57:9c:8d and e0:1c:fc:e3:0c:49).

- The "Internet Protocol Version 4, Src: 192.168.0.187, Dst: 142.251.220.142" line is on layer 3, the network layer because it describes the internet protocol and literally there is 2 ip address here, the Src (source) and the Dst (destination) ip address. Also, in other scans, we can see the Domain Name System (DNS) of that frame.

The end for this example. Imma provide another example for layer 4 - 7.






