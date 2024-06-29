# Android-Frida-Scripts
Custom or Modified Frida scripts

# Frida Scripts: Custom or Modified

## Overview

This repository contains custom or modified Frida scripts designed for various purposes, including dynamic instrumentation and analysis of applications. Frida is a powerful framework for dynamic instrumentation of apps in real-time, providing deep insights into their behavior and allowing for runtime manipulation.

## Contents

- **Script 1**: Single Script for Root and SSL Pinning bypass.
- **Script 2**: Single Script for Root AES key and IV at runtime.

Each script is tailored to specific use cases, enhancing the flexibility and functionality of Frida for different applications and environments.

## Usage

frida -U -f <you-app-package-name> -l <path-to-frida-script-file>
eg: frida -U -f com.example.targetapp -l //file.js

### Requirements

- [Frida](https://frida.re/): Install Frida on your system.

### Running Scripts

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/frida-scripts.git
   cd frida-scripts

2. Run a script:
   frida -U -f com.example.targetapp -l script.js

   

