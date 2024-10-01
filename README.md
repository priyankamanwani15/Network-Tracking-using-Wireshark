# Network-Tracking-using-Wireshark
# Network Tracking using Wireshark, Google Maps, and Python

## Overview

This project aims to track and visualize network traffic using Wireshark for packet analysis, Google Maps for geographical representation, and Python for data processing and visualization. It enables users to understand network behavior, detect anomalies, and analyze network traffic patterns.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Technologies Used

- **Wireshark**: A network protocol analyzer for capturing and inspecting packets.
- **Google Maps API**: For geographical visualization of network traffic.
- **Python**: Programming language for data processing.
- **Libraries**:
  - `scapy`: For packet manipulation.
  - `pandas`: For data analysis.
  - `folium`: For creating interactive maps.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/network-tracking.git
   cd network-tracking
pip install scapy pandas folium

python network_tracking.py --file path/to/your/file.pcap --api_key YOUR_GOOGLE_MAPS_API_KEY
Features
Capture and analyze network packets using Wireshark.
Visualize network traffic on an interactive Google Map.
Identify the geographical location of network sources and destinations.
Filter and process captured data using Python.
