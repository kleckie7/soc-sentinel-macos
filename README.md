![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-native-black?style=flat&logo=apple&logoColor=white)
![Detects](https://img.shields.io/badge/Detects-BruteForce%20%26%20SQLi-red)
![License](https://img.shields.io/badge/License-MIT-green)

# SOC Sentinel – macOS-native Threat Detection Engine

Professional log-analysis tool that automatically detects brute-force & SQL injection attacks and generates **executive-ready dark-mode reports**.

Built 100% on macOS (Apple Silicon + Intel) using Python 3.13, pandas 2.2.3, and matplotlib 3.9.2.

### Demo
![Threat Report](reports/threat_report_demo.png)

### Run in 60 Seconds (macOS)

```bash
git clone https://github.com/kleckie7/soc-sentinel-macos.git
cd soc-sentinel-macos
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
chmod +x main.py
./main.py











