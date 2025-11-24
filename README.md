 Real-Time Networking & Protocol Analysis Project

This project demonstrates how I deployed and tested a QUIC (HTTP/3) server on Kali Linux using Caddy, and analyzed QUIC packets in Wireshark to understand how it improves latency and solves TCP limitations such as Head-of-Line (HOL) Blocking & Slow Handshakes.

📌 Project Goals

✔ Understand how QUIC works internally
✔ Deploy HTTP/3 server using Caddy on Kali Linux
✔ Test QUIC using curl --http3
✔ Capture & analyze QUIC packets in Wireshark
✔ Compare TCP vs QUIC behavior
✔ Prepare resume/interview-level explanation of QUIC

🧠 What is QUIC? (Quick Intro)
Feature	TCP	QUIC (HTTP/3)
Handshake	3-way	0-RTT / 1-RTT
Transport Layer	TCP	UDP
Encryption	External TLS	Built-in TLS 1.3
Multiplexing	Head-of-line blocking	No blocking
Mobile network support	Breaks connection	Seamless

QUIC runs over UDP but provides reliability, encryption, and streams like TCP —
which is why Google, YouTube, Zoom, WhatsApp & Instagram use it today.
