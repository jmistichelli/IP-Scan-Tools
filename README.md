# IP-Scan-Tools
This tool discovers active/allocated IP addresses on a subnet.

*** scan_network.py ***

This tool uses a simple ping sweep to find IP addresses. There are no extra dependencies beyond ping3 or using OS ping.

Usage examples:
python3 scan_network.py 192.168.1.0/24
python3 scan_network.py 192.168.1.0/24 --resolve
python3 scan_network.py 10.0.0.0/24 --workers 200

