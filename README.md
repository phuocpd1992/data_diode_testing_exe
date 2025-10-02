# Data Diode Testing (Executable)

This repository contains a pre-built **executable (.exe)** for testing one-way data transfer through a **Data Diode**. It simulates Modbus TCP communication with configurable parameters.

## 🚀 How to Use
1. Download or Clone: git clone https://github.com/phuocpd1992/data_diode_testing_exe.git && cd data_diode_testing_exe  
2. Run the Executable: simply double-click the file or run it from the command line: data_diode_testing.exe

## ⚙️ Default Configuration
The executable uses the following default parameters:  
IP_HOST = "192.168.1.1"   # Modbus TCP server IP  
PORT = 502                # Modbus TCP port  
UNIT_ID = 1               # Modbus server Unit ID  
TOTAL_ELEMENTS = 1000     # Total number of elements to process  
MAX_REGISTER = 100        # Maximum registers per request  

## 📂 Repository Structure
data_diode_testing_exe/  
│-- data_diode_testing.exe   # Main executable  
│-- requirements.txt         # Dependencies (for reference only)  
│-- config.json              # Optional configuration  
│-- README.md                # Documentation  
│-- .gitignore               # Ignore build/cache files  

## 🛠️ Requirements
- Windows 10 or later  
- Network access to a Modbus TCP device (or simulator)
