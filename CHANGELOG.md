# Changelog

**English** | [العربية](CHANGELOG.ar.md)

All notable changes to this repository, newest first.

## 2026-11-27 overhaul

A full review of the project. Each item below was checked against the code and data in this repository.

### What was wrong

- The README said 3 VLANs; the network has 12 (3 per building, 4 buildings).
- It claimed OSPF, DHCP and SSH, which the network does not use (it uses RIP v2 and Telnet).
- It described the addressing as VLSM; the plan uses fixed-size /26 subnets (FLSM).
- The documentation was only a PDF.

### What was fixed

- Repository renamed to hnu-campus-network-packet-tracer.
- README corrected: 12 VLANs, RIP v2, Telnet, FLSM.

### What was removed

- The false OSPF, DHCP and SSH claims.
- The original documentation PDF (replaced by Markdown).

### What was added

- Structured folders: docs, images, packet-tracer.
- docs/network-documentation.md, converted from the PDF.
- English and Arabic README with a language switch.
- Social preview made from the topology image.

## Original version

Initial version (2026-02-22): Packet Tracer file, topology image and a README, uploaded as-is under an earlier repository name.
