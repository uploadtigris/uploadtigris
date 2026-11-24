# Hi, I'm Tigris 🐯

IT support at Amazon · building toward DevOps and cloud security · Austin, TX

[LinkedIn](https://www.linkedin.com/in/tigrismendez) · [Portfolio](https://uploadtigris.github.io)

## About me

I'm an IT Support Associate at Amazon, where I troubleshoot VPN, DNS, and domain problems for 5,000+ users. I'm moving into DevOps by building the things I'd run in production: a segmented network, a self-hosted SIEM, and automation I can rebuild from a repo.

At home I run a pfSense firewall, a managed PoE switch, a multi-SSID access point, and a Pi-hole, segmented into five VLANs with least-privilege firewall rules. The homelab is where I practice Linux, containers, monitoring, and infrastructure as code.

**Currently:** getting fluent in Bash and Linux, then Git and GitHub Actions, then Terraform on AWS.

## Featured projects

| Project | What it shows | Status |
|---|---|---|
| [wazuh-siem-homelab](https://github.com/uploadtigris/wazuh-siem-homelab) | Self-hosted Wazuh SIEM deployed with Docker Compose. First build ran file integrity monitoring and CIS checks (about 100 failed checks per Ubuntu host). Rebuilding on a dedicated laptop to collect pfSense firewall logs and Pi-hole DNS queries | 🔧 Rebuild in progress |
| [network-segmentation-ids](https://github.com/uploadtigris/network-segmentation-ids) | Five VLANs (Mgmt, Trusted, IoT, Guest, Servers), least-privilege pfSense rules, DNS forced through Pi-hole, 10 of 10 validation tests passed | ✅ Phase 1 complete |
| [linux-automation](https://github.com/uploadtigris/linux-automation) | Bash and Python scripts for Linux administration | 🔧 Ongoing |
| [sysadmin_handbook](https://github.com/uploadtigris/sysadmin_handbook) | Real troubleshooting write-ups (DNS, TCP/IP, Windows, Linux) in STAR format, with commands | 📓 Ongoing |

## Skills

| Area | Tools |
|---|---|
| Linux and scripting | Linux, Bash, Python |
| Containers | Docker, Docker Compose |
| Networking | pfSense, Pi-hole, VLANs, Tailscale, nmap |
| Security and monitoring | Wazuh, CIS Benchmarks, MITRE ATT&CK |
| Cloud and IaC | AWS (learning), Terraform (learning), GitHub Actions (learning) |

**Certifications:** CompTIA Security+ · AWS Certified AI Practitioner · UT Austin Elements of Computing Certificate

## What I'm building next

- Terraform AWS environment (VPC, compute, load balancer) deployed through GitHub Actions with security scans on every push
- A k3s cluster in my homelab with Prometheus and Grafana monitoring
- A one-command rebuild of the Wazuh stack from this repo

## Also

I like hardware too: [hydroponics_sensing](https://github.com/uploadtigris/hydroponics_sensing) revives a Gardyn garden with my own Raspberry Pi Pico W sensors (I2C, MQTT).
