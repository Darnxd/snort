# snort

# 🛡️ Snort IDS Setup Guide on Kali Linux

This repository contains concise instructions to install, configure, and test the Snort Intrusion Detection System (IDS) on Kali Linux.

## 📦 Prerequisites

- Kali Linux (updated)
- Administrative (sudo) privileges
- Internet connection

## 🔧 Installation & Configuration Steps

### Step 1: Install Snort

##bash
sudo apt-get install snort -y

Step 2: Verify Configuration Files

ls -al /etc/snort

Step 3: Run Snort with Configuration
sudo snort -c /etc/snort/snort.conf

Step 4: Test Interface and Configuration
sudo snort -T -i enpXsY -c /etc/snort/snort.conf

Step 5: Detection Rules

Create or verify rule sets in:
/etc/snort/rules/




