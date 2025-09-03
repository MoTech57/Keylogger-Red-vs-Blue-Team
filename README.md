# 🖥️ Keylogger Red-vs-Blue Team Lab 🖥️  

## 📖 Description  
This lab demonstrates a **Python-based keylogger** using the **pynput** library as part of a red team vs. blue team cybersecurity exercise.  

- **Red Team (Attacker):** Creates and packages a keylogger into a Windows executable with **PyInstaller**, simulates delivery through social engineering, and demonstrates keystroke capture.  
- **Blue Team (Defender):** Detects suspicious processes, investigates keylogger activity, and mitigates the threat using **Windows Task Manager** and monitoring techniques.  

The project emphasizes adversarial thinking and defensive countermeasures, providing realistic training for both offensive and defensive security operations.  

---

## 🛠️ Languages and Utilities Used  

- Python 3.13  
- pynput  
- PyInstaller  
- Visual Studio Code  
- Windows Task Manager  

---

## 🖥️ Environments Used  

- Windows 10/11 (Vultr VM)  
- Active Directory Domain Controller (for authentication testing)  
- Virtual Environment (venv)  

---

## 🔄 Workflow  

### 🔴 Red Team  

**Windows Server (Active Directory) used for lab setup:**  
![AD Setup](https://i.imgur.com/ePrPX0w.png)  

**Creating `keylogger.py` in Visual Studio Code:**  
![Keylogger Code](https://i.imgur.com/z1ezUmI.png)  

**Installing pynput:**  
![pynput Install](https://i.imgur.com/eXGMEH7.png)  

**Running the keylogger:**  
![Execution](https://i.imgur.com/0cKrMkA.png)  

**Installing PyInstaller:**  
![PyInstaller](https://i.imgur.com/NU4WYst.png)  

**Compiling to executable:**  
![Compile EXE](https://i.imgur.com/NKSrqYi.png)  

**Delivering payload (email simulation):**  
![Payload](https://i.imgur.com/tyHbeEz.png)  
![Email Simulation](https://i.imgur.com/XKIvdpF.png)  

---

### 🔵 Blue Team  

**Victim enters sensitive info (e.g., banking):**  
![Victim Input](https://i.imgur.com/fZq1HF2.png)  

**Keylogger captures keystrokes:**  
![Captured Keys](https://i.imgur.com/pElNzdG.png)  

**Defender investigates using Task Manager and kills malicious process:**  
![Task Manager](https://i.imgur.com/CMObJRb.png)  
![Kill Task](https://i.imgur.com/UgL7NuF.png)  

---
