# Assignment 2 – Dual-Layer Protocol Visualizer

Extends Assignment 1 while keeping the left Activity panel unchanged.

## Added
- Application Layer / Transport Layer toggle
- Synchronized Application + TCP traces
- TCP 3-way handshake: SYN, SYN-ACK, ACK
- Seq/Ack/Flags/Window/direction/timing
- Application data carried over TCP
- TCP FIN/ACK teardown
- Browsing, Mail/SMTP and Streaming/HTTP flows
- Replay, Previous, Next and Auto/Pause

## Run
python -m pip install -r requirements.txt
python app.py

Open http://127.0.0.1:8000
