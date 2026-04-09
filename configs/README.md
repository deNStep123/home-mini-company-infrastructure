## Configuration Files

This directory contains the baseline configuration for the Linux server used in the Education Project.

The configuration is organized by system layer:

### Network Configuration
- `netplan.yaml` — Defines bridged and internal network interfaces

### Security Configuration
- `sshd_config` — Hardened SSH configuration (key-based authentication only)
- `ufw.rules` — Firewall ruleset (importable via iptables-restore)
- `ufw-summary.txt` — Human-readable documentation of firewall rules

These files represent the intended target state of the system and are used to reproduce the server configuration consistently.
