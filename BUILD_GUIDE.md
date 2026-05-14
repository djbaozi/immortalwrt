# ImmortalWrt Build Guide

## Overview
ImmortalWrt is an opensource OpenWrt variant optimized for mainland China users.

## System Requirements
- Linux system (Ubuntu 20.04 LTS recommended)
- At least 8GB RAM
- 20GB free disk space

## Build Instructions

1. Install Dependencies: sudo apt-get install -y build-essential
2. Clone: git clone https://github.com/djbaozi/immortalwrt.git
3. Update feeds: ./scripts/feeds update -a
4. Build: make -j4
