# File-Integrity-Monitoring-System
A Python-based File Integrity Monitoring (FIM) system with advanced features such as real-time file change detection, automatic backup of modified files, email alerts, Excel reporting, password-protected GUI, dark mode, and folder/file exclusion support.
# File Integrity Monitoring System

A Python-based **File Integrity Monitoring (FIM) System** that helps protect data from unauthorized modifications.  
It provides real-time monitoring, automatic backup, email alerts, and a secure GUI.

---

## 🚀 Features
- Initial Full Scan (generate & store hash values)
- Re-scan & compare (detect file tampering)
- Real-Time Monitoring (Watchdog)
- Email Alerts (SMTP with Gmail)
- Automatic Backup of modified files
- Export reports to Excel
- Password-protected GUI with Dark Mode
- Exclude specific files/folders
- Cross-platform support (Windows tested)

---

## 🛠 Tools & Technologies
- **Language:** Python 3.x  
- **Libraries:** hashlib, smtplib, watchdog, tkinter, pandas, openpyxl  
- **Platform:** Windows 10  
- **IDE:** VS Code / PyCharm  

---

## 📂 Installation & Usage
1. Clone the repository:
   ```bash
   https://github.com/khurram1238/File-Integrity-Monitoring-System.git
   
   Install dependencies:

pip install -r requirements.txt


Configure email in config.ini:

[EMAIL]
Sender = your_email@gmail.com
AppPassword = your_app_password
Receiver = receiver_email@gmail.com


Run the program:

python main.py

📧 Email Alerts

The system sends an email alert whenever a file is modified, deleted, or created.

📊 Output

Excel report of all scans

Log file of detected changes

Backup folder with timestamped files

🔮 Future Enhancements

Linux/Mac support

Cloud storage integration

SIEM integration

Role-based access control

👨‍💻 Author

Khurram Shahzad

📩 Contact

For any queries or collaboration, feel free to reach out at:
📧 khurram132khan@gmail.com
   
   cd REPO

