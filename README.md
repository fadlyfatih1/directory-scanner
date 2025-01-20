# 📂 Directory Scanner

A simple Python script to scan directories on a target website and identify accessible paths. This script is useful for testing purposes, such as checking for publicly accessible directories on a web server.

---

## 🚀 Features

- Scans directories listed in a text file.
- Supports HTTP URLs
- Lightweight and easy to use.

---

## 🛠️ How to Use

### Prerequisites
- Python 3.x
- `requests` library (install with `pip install requests`)

---

### 📝 Setup

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-repo/directory-scanner.git
   cd directory-scanner
   ```
   
2. Install the required dependencies:
    ```bash
    pip install requests
    ```

## Usage 🚀

1. Prepare a txt file with potential directory names:
    ```bash
    admin
    login
    dashboard
    images
    server-status
    ```

2. Run the script:
    ```bash
    python directories.py
    ```

3. Example input, the target is my own local server:
    ```bash
    [*] Enter Target URL: 127.0.0.1
    [*] Enter Name Of The File Containing Directories: common.txt
    ```
    
## Notes 📝
- Always ensure you have proper authorization to scan a website.
- Unauthorized scanning may violate laws and terms of service.
