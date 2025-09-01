<h1>🖥️ Keylogger Red-vs-Blue Team 🖥️ </h1>


<h2>Description</h2>
This Lab demonstrates a Python-based keylogger built with the pynput library as part of a cybersecurity lab exercise. The lab explores both the offensive perspective (how attackers capture keystrokes, compile tools into executables, and simulate exfiltration) and the defensive perspective (how blue teams detect, stop, and prevent such threats).
The keylogger logs keystrokes into a file, which defenders can identify by monitoring processes, file artifacts, and suspicious outbound traffic. To simulate real-world attacker techniques, the project also includes packaging the script into a standalone Windows executable (pylogger.exe) using PyInstaller. This demonstrates how compiled binaries make malware more stealthy, and how defenders can respond through process analysis, binary inspection, and endpoint monitoring.
The lab reinforces the importance of endpoint visibility, behavioral detection, and ethical cybersecurity practices while providing a practical red team vs. blue team training exercise.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python 3.13</b> 
- <b>pynput</b>
- <b>PyInstaller</b> 
- <b>Task Manager</b>

<h2>Environments Used </h2>

- <b>Windows 10/11 (vultr)</b> 
- <b>VS Code</b> 
- <b>Virtual Environment (venv)</b> 

<h2>Workflow:</h2>

<p align="center">
<b>Active Direcotry Windows server will be used for lab:<b/> <br/>
<img src="https://i.imgur.com/ePrPX0w.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Load Visual Studio Code and save file keylogger.py:<b/>  <br/>
<img src="https://i.imgur.com/jyD8Dxo.png" height="80%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Install pynput<b/>: <br/>
<img src="https://i.imgur.com/eXGMEH7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Complie code that will run when :  <br/>
<img src="https://i.imgur.com/0cKrMkA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deauthentication to Forces client reconnection Confirm handshake in Wireshark:  <br/>
<img src="https://i.imgur.com/YNtAQoF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Locate file and send to VM with ssh:  <br/>
<img src="https://i.imgur.com/PprrkzP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use aircrack-ng with dictionary wordlist successfully cracked - “test123!”:  <br/>
<img src="https://i.imgur.com/6pENfVx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
