![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-native-black?style=flat&logo=apple&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Docker-lightgrey)
![Detects](https://img.shields.io/badge/Detects-BruteForce%20%26%20SQLi-red)
![License](https://img.shields.io/badge/License-MIT-green)

# SOC Sentinel – macOS-native Threat Detection Engine

Automated Apache/web log analyzer that:
- Parses logs in real time
- Detects brute-force attacks & SQL injection attempts
- Generates dark-mode visual reports automatically

Built 100 % on macOS (Apple Silicon + Intel ready) with Python + pandas + matplotlib.

### Demo
![Threat Report](reports/threat_report_demo.png)

### Quick Start – Run in < 2 Minutes

Follow these steps on macOS (tested on Apple Silicon & Intel, Python 3.13):

```bash
# 1. Clone the repo
git clone https://github.com/kleckie7/soc-sentinel-macos.git
cd soc-sentinel-macos

# 2. Set up virtual environment
python3 -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the tool (generates & opens the report automatically)
chmod +x main.py        # Only needed once
./main.py

### Quick run
```bash
./main.py










