<h1 align="center">Apricot Queries</h1>



## Overview

This repository contains a collection of JSON files with helpful queries for getting started and exploring Zeek, Suricata, and Snort data within the Zui app. These queries are designed to facilitate the analysis of network traffic and security events, helping users to quickly derive insights from their data.

## Features

- **Predefined Queries**: A set of queries tailored for Zeek, Suricata, and Snort data.
- **Easy Import**: Simple steps to import queries into Zui.
- **Organized Folder Structure**: Queries are organized into a folder named `Apricot` for easy access.

## Getting Started

To import these queries into Zui, follow these steps:

1. **Download the Repo**
    - Clone the repository to your local system using the following command:
      ```bash
      git clone https://github.com/yourusername/apricot-queries.git
      ```
    - Alternatively, you can download the ZIP file from the repository's main page and extract it.

2. **Open Zui**
    - Launch the Zui app on your system.

3. **Import Queries**
    - In Zui, click the **+** menu in the upper-left corner of the app window.
    - Select **Import Queries...** from the dropdown menu.
    - Navigate to the location where you downloaded the repo and select the JSON files using the file picker utility.

4. **Access the Queries**
    - Once imported, the loaded queries will appear in the "QUERIES" tab of Zui's left sidebar.
    - They will be organized into a new folder named `Apricot`.

## Usage

- **Zeek Queries**: Utilize the Zeek-specific queries to analyze network connections, HTTP traffic, DNS queries, SSL/TLS handshakes, file transfers, and more. Example queries include:
  - Top talkers in the network.
  - HTTP request and response analysis.
  - DNS query distribution.
  - SSL certificate analysis.

- **Suricata Queries**: Leverage Suricata queries for detailed insights into IDS/IPS alerts, network protocol anomalies, threat detection, and performance metrics. Example queries include:
  - High-priority IDS alerts.
  - Protocol distribution analysis.
  - Suspicious activity detection.
  - Network flow analysis.

- **Snort Queries**: Explore Snort data with queries designed to uncover intrusion attempts, suspicious activities, security events, and network behavior patterns. Example queries include:
  - Top intrusion detection alerts.
  - Anomalous traffic patterns.
  - Source and destination IP analysis.
  - Malware detection alerts.

- **Additional Network Analysis Queries**: The repository also includes general network analysis queries that are not specific to any single tool. These can be used to gain a broader understanding of network behavior and security posture. Example queries include:
  - Bandwidth usage over time.
  - Unusual port activity.
  - Top communication pairs.
  - Network latency analysis.
  - Geolocation of IP addresses.

## Contributing

We welcome contributions from the community to enhance and expand the query library. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and ensure they are well-documented.
4. Submit a pull request with a detailed description of your changes.

## Support

If you encounter any issues or have questions, please open an issue on the repository or contact us at okwaratoto11@gmail.com.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the developers of Zeek, Suricata, Snort, and Zui for their incredible tools and contributions to the cybersecurity community.

---

