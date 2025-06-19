
# 🐍 Simple Honeypot Intrusion Detection System

This project demonstrates a basic honeypot system built using Python. It includes:

- `honeypot.py`: Listens on a specific port and logs incoming connection attempts.
- `attack.py`: Simulates attacks with spoofed IPs to test the honeypot.
- `analyze.py`: Analyzes the logs and generates insightful visualizations on attacker behavior.

## 📁 Project Structure

```bash
.
├── honeypot.py        # Lightweight TCP honeypot
├── attack.py          # Simulated attack script with spoofed IPs
├── analyze.py         # Log analyzer and visualizer
├── honeypot.log       # Log of honeypot connection attempts
├── spoofed_ips.log    # List of spoofed IPs from attacks
└── graphs/            # Directory for generated plots

#How to run it
python3 honeypot.py

#launch the attackk simulation
python3 attack.py

#analyzing logs
python3 analyze.py

📊 Features

    Simulates brute-force or scan-like activity

    Tracks and logs incoming IPs

    Separates spoofed IPs for red/blue team exercises

    Produces charts for attack timeline, distribution, and frequency

🔍 Sample Visualizations

    Time series of attacks

    Spoofed vs. Real IPs

    Targeted ports

    Thread usage simulation

📌 Use Cases

    Educational cybersecurity projects

    Basic network monitoring practice

    Red vs Blue team demonstrations

⚠️ Disclaimer

This project is for educational purposes only. Do not use it to attack systems you do not own or have permission to test.

📎 License

MIT License
