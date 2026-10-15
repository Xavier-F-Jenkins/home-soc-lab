# Home SOC Lab

This is my self-hosted cybersecurity lab which I have designed to help me gain
practical expereience in Linux administration, networking & network security,
logging, security monitoring, and incident detection.

## Project Overview

This project involves building a small Security Operations Centre (SOC)
enviornment using an old desktop I had lying around with open source software to
teach myself cyber security fundamentals with little to no budget.

## Hardware

The lab runs on my 2012 Dell Inspiron 660 Desktop.

| Hardware | Specs |
|----------|-------|
|Computer | Dell Inspiron 660 |
| CPU | Intel Core i5-2320 |
| Cores | 4 |
| RAM | 8GB DDR3 |
| Storage | 2TB HDD |

## Software

The lab is managed by Proxmox which currently runs two Debian Linux containers.

## Project Goals & Progress

- [x] Install and configure Proxmox VE
- [x] Deploy Debian Linux containers
- [x] Configure container networking
- [x] Implement centralized logging using rsyslog
- [x] Verify remote auth log collection
- [ ] Configure SSH auth monitoring
- [ ] Implement security detection rules
- [ ] Develop automated security alerts
- [ ] Build a security monitoring dashboard

## Stretch Goals 

- [ ] Buy an additional 8GB of RAM
- [ ] Buy a SSD to replace the HDD
- [ ] Install & run Wazuh

## Doccumentation

I will write detailed technical doccumentation about specific parts of this lab
in the 'docs/' directory of this repo.

## Project status

In active development since 13 October 2026

