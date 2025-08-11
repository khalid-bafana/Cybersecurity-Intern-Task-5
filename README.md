Objective
The objective of this task is to capture and analyze live network traffic using Wireshark to identify different types of packets, protocols, and potential anomalies in the network.

Tools Used
Wireshark (Network packet analyzer)

Steps Performed
Installed Wireshark on the system.

Launched Wireshark and selected the active network interface (Wi-Fi in my case) for live traffic capture.

Started live capture to record packets flowing through the selected interface.

Allowed traffic to run for a few minutes by browsing websites and performing normal online activities.

Stopped the capture and saved the file in .pcapng format for documentation and future analysis.

Filtered packets using display filters such as:

http for HTTP traffic

tcp for TCP packets

icmp for ping requests/replies

Observed packet details like:

Source and Destination IP addresses

Protocols in use

Packet size and timing

Saved the captured file (Wireshark-Analyze-Network_traffic.pcapng) for submission.

Findings
Captured multiple TCP and UDP packets showing communication between the system and different servers.

Detected DNS queries and responses.

Observed ICMP packets used for network connectivity tests.

Recorded HTTP requests and responses for visited websites.

Conclusion
Wireshark allows in-depth monitoring and analysis of network traffic. This exercise provided hands-on experience in capturing and interpreting packets, which is crucial for network troubleshooting, performance monitoring, and detecting potential security threats.