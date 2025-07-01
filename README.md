# Cybersecurity Internship - Task 5

## 📁 Task Name:
**Capture and Analyze Network Traffic Using Wireshark**

## 🎯 Objective:
Use Wireshark to capture live packet data and analyze the top 5 protocols used in the traffic.

## 📄 File Analyzed:
`interntask5.pcapng`

## 🛠 Tools Used:
- Wireshark

## 🔍 Top 5 Protocols Identified:
1. **HTTP** – Handles web browsing traffic (likely to/from websites).
2. **TCP** – Underlying reliable protocol for most communications.
3. **DNS** – Resolves domain names to IP addresses.
4. **TLS** – Secures HTTP traffic (HTTPS).
5. **UDP** – Connectionless protocol used for fast transmission (e.g., video, DNS).

## 📝 Summary:
This task involved capturing and analyzing network packets. The capture file showed a combination of encrypted and unencrypted traffic. DNS and TCP were heavily used for name resolution and connection handling, while TLS secured the content. HTTP traffic was still visible, likely from non-secure sources.

## 📌 Learning Outcomes:
- Understood how to use Wireshark to capture real-time traffic.
- Learned to identify and filter key protocols.
- Gained insight into encrypted vs unencrypted communication.

---


Top 5 Protocols Identified:
1. HTTP - 34% of traffic (Web browsing and content transfer)
2. TCP - 30% of traffic (Reliable connection-oriented traffic)
3. DNS - 15% of traffic (Domain name resolution)
4. TLS - 12% of traffic (Encrypted HTTPS communication)
5. UDP - 9% of traffic (Unreliable, fast transport like video/audio)

Summary:
- The capture shows common internet usage with a high volume of web and DNS traffic.
- TCP and UDP traffic indicates standard transport protocols in use.
- TLS presence confirms encrypted data exchange, such as HTTPS websites.
