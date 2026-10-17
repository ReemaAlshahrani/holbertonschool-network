# Networking basics #0

This project serves as the fundamental introduction to computer networking.
It covers core concepts such as the OSI model, network types, MAC and IP addresses, TCP and UDP transport protocols, ports, and ping diagnostics.

## Project Contents (Files and Descriptions)

| File Name | File Type | Description, Questions & Answers |
| :--- | :--- | :--- |
| **`0-OSI_model`** | Multiple-choice (Text) | • **Q1:** What is the OSI model? <br> *(Answer: A conceptual model characterizing communication functions without regard to internal structure - Option `2`)*<br>• **Q2:** How is the OSI model organized? <br> *(Answer: From the lowest to the highest level - Option `2`)* |
| **`1-types_of_network`** | Multiple-choice (Text) | • **Q1:** What type of network is a local computer connected to? <br> *(Answer: LAN - Option `3`)*<br>• **Q2:** What network connects an office to another a few streets away? <br> *(Answer: WAN - Option `2`)*<br>• **Q3:** What network do you use when browsing Google from your smartphone (not on Wi-Fi)? <br> *(Answer: Internet - Option `1`)* |
| **`2-MAC_and_IP_address`** | Multiple-choice (Text) | • **Q1:** What is a MAC address? <br> *(Answer: The unique identifier of a network interface - Option `2`)*<br>• **Q2:** What is an IP address? <br> *(Answer: Is to devices what postal address is to houses - Option `1`)* |
| **`3-UDP_and_TCP`** | Multiple-choice (Text) | • **Q1:** TCP box statement? <br> *(Answer: Transfers data in a slow way but surely - Option `1`)*<br>• **Q2:** UDP box statement? <br> *(Answer: Transfers data in a fast way and might lose data along the process - Option `2`)*<br>• **Q3:** TCP worker statement? <br> *(Answer: Have you received boxes x, y, z? - Option `1`)* |
| **`4-TCP_and_UDP_ports`** | Bash Script | A script that displays listening TCP, UDP, and UNIX sockets along with their PID and program name using the `netstat -lp` command. |
| **`5-is_the_host_on_the_network`** | Bash Script | A script that checks for an IP address argument (displays usage if missing) and pings the target IP address 5 times using ICMP. |

