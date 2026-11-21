# Enterprise Security Hardening & Controls Assurance Lab

Local KVM lab simulating enterprise Windows/RHEL hardening, vulnerability management, and SIEM control validation.

## Lab Environment
- **Hypervisor:** QEMU/KVM (`virt-manager`) on Fedora Linux
- **Network:** Isolated virtual subnet (`lab-isolated`)
- **Targets:** Windows Server (AD DS / GPO / AD CS), Windows 11 Enterprise Client, RHEL Host
- **Monitoring & Scanning:** Wazuh SIEM + Sysmon, Greenbone/OpenVAS

## Repository Structure
- `rhel-hardening/` — OpenSCAP HTML reports, `autotailor` exception profiles, and generated Ansible playbooks
- `windows-baselines/` — Microsoft Security Compliance Toolkit exports and Policy Analyzer drift diffs
- `vulnerability-scans/` — Before/after Greenbone/OpenVAS scan summaries
- `writeups/` — Control validation notes and SIEM alert screenshots
