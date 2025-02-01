# SOC Home Lab

## Overview
This project is a fully functional **Security Operations Center (SOC) Home Lab**, designed for cybersecurity professionals, students, and researchers to practice and improve their security skills. The lab consists of various tools and platforms to simulate real-world attack and defense scenarios.

## Components
The SOC Home Lab is composed of the following components:

### **Security Monitoring & SIEM**
- **[Wazuh](https://wazuh.com/)** - Open-source security monitoring and SIEM solution.
- **[Security Onion](https://securityonion.net/)** - A free and open platform for threat hunting, network security monitoring, and log management.

### **Threat Intelligence & Incident Response**
- **[TheHive](https://thehive-project.org/)** - Open-source security incident response platform.
- **[Cortex](https://thehive-project.org/)** - Analyzes observables using multiple analyzers to enrich investigations.

### **Adversary Simulation & Exploitation**
- **[Caldera](https://github.com/mitre/caldera)** - Automated adversary emulation system developed by MITRE.
- **[Metasploit](https://www.metasploit.com/)** - A powerful penetration testing framework.

### **Vulnerability Assessment**
- **[Nessus](https://www.tenable.com/products/nessus)** - A widely used vulnerability scanner.

### **Web Application Security Testing**
- **[Damn Vulnerable Web Application (DVWA)](http://www.dvwa.co.uk/)** - A PHP/MySQL web application for security testing.
- **[bWAPP](http://www.itsecgames.com/)** - A buggy web application for practicing security testing.
- **[WebGoat](https://github.com/WebGoat/WebGoat)** - A deliberately insecure web application for learning about web security.

### **Containerized Environment**
- **[Docker](https://www.docker.com/)** - Containerization platform for hosting various security tools.
- **[Portainer](https://www.portainer.io/)** - A web-based container management interface.

### **Operating Systems**
- **Windows Server** - A virtualized Windows Server for domain control and security policy implementation.
- **Windows Clients** - Windows 10 and Windows 11 virtual machines for endpoint security testing.
- **Ubuntu** - Linux-based virtual machines for testing and security operations.

### **Network Security**
- **[pfSense](https://www.pfsense.org/)** - Open-source firewall and router solution.

## Usage
- **Threat Detection**: Use Wazuh and Security Onion to monitor logs and detect threats.
- **Incident Response**: Investigate and respond to security incidents using TheHive and Cortex.
- **Penetration Testing**: Use Metasploit, Nessus, and Caldera to simulate attacks.
- **Web Security Testing**: Practice exploiting web applications using DVWA, bWAPP, and WebGoat.
- **Network Security**: Implement firewall rules and segmentation using pfSense.

## Future Enhancements
- Integration of **ELK Stack** for centralized log management.
- Adding **Suricata or Zeek** for enhanced network intrusion detection.
- Automating threat intelligence with **MISP**.
- Implementing **SOAR (Security Orchestration, Automation, and Response)** capabilities.

## Contributing
Contributions are welcome! Feel free to submit issues, suggest improvements, or fork the project to enhance the SOC Home Lab.

## License
This project is licensed under the MIT License. See `LICENSE` for details.
