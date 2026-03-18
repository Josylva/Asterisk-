# Asterisk-
This is a hands-on implementation of a Private Branch Exchange (PBX) system using Asterisk, covering SIP configuration, dial plans, call routing, and VoIP troubleshooting.
# Asterisk 16 PBX Setup

## Overview
This project documents the setup of a Private Branch Exchange (PBX) system using **Asterisk 16** on Ubuntu.  
It includes installation steps, SIP extensions, trunk configuration, dialplan examples, and security hardening.  
The goal is to demonstrate practical VoIP and telephony skills by building a working PBX from source.

## Objective
- Build and configure Asterisk 16 from source
- Set up SIP extensions and trunks
- Implement dialplan logic for internal calls, voicemail, music on hold, and call parking
- Secure the PBX with firewall rules and Fail2Ban

## Prerequisites
- **OS**: Ubuntu 18.04 LTS (tested)
- **Dependencies**:
  ```bash
  sudo apt-get update
  sudo apt-get install bison wget openssl libssl-dev \
    libasound2-dev libc6-dev libxml2-dev libsqlite3-dev \
    libnewt-dev libncurses5-dev zlib1g-dev gcc g++ make perl \
    uuid-dev git subversion unixodbc-dev unixodbc-bin unixodbc \
    autoconf libedit-dev
