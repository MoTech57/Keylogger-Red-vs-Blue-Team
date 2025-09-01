<h1>🖥️ Keylogger Red-vs-Blue Team 🖥️</h1>

<h2>Description</h2>
This lab demonstrates a Python-based keylogger built with the <b>pynput</b> library as part of a cybersecurity exercise. The lab explores both the offensive perspective (how attackers capture keystrokes, compile tools into executables, and simulate exfiltration) and the defensive perspective (how blue teams detect, stop, and prevent such threats).  

The keylogger logs keystrokes into a file, which defenders can identify by monitoring processes, file artifacts, and suspicious outbound traffic. To simulate real-world attacker techniques, the project also includes packaging the script into a standalone Windows executable (<b>pylogger.exe</b>) using <b>PyInstaller</b>. This demonstrates how compiled binaries make malware more stealthy, and how defenders can respond through process analysis, binary inspection, and endpoint monitoring.  

The lab reinforces the importance of endpoint visibility, behavioral detection, and ethical cybersecurity practices while providing a practical red team vs. blue team training exercise.  
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python 3.13</b>  
- <b>pynput</b>  
- <b>PyInstaller</b>  
- <b>Task Manager</b>  

<h2>Environments Used</h2>

- <b>Windows 10/11 (Vultr VM)</b>  
- <b>Visual Studio Code</b>  
- <b>Virtual Environment (venv)</b>  

<h2>Red Team🟥</h2>

<p align="center">

<b>Active Directory Windows Server will be used for the lab:</b><br/>  
<img src="https://i.imgur.com/ePrPX0w.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Create keylogger.py in Visual Studio Code:</b><br/>  
<img src="https://i.imgur.com/z1ezUmI.png" height="80%" width="80%" alt="Keylogger Code in VSCode"/>  
<br /><br />

<b>Install pynput:</b><br/>  
<img src="https://i.imgur.com/eXGMEH7.png" height="80%" width="80%" alt="Installing pynput"/>  
<br /><br />

<b>Build the Keylogger:</b><br/>  
<img src="https://i.imgur.com/0cKrMkA.png" height="80%" width="80%" alt="Keylogger Execution"/>  
<br /><br />

<b>Install PyInstaller:</b><br/>  
<img src="https://i.imgur.com/NU4WYst.png" height="80%" width="80%" alt="Installing PyInstaller"/>  
<br /><br />

<b>Compile keylogger.py into an .exe:</b><br/>  
<img src="https://i.imgur.com/NKSrqYi.png" height="80%" width="80%" alt="Compiling to EXE with PyInstaller"/>  
<br /><br />

<b>Locate the file and simulate targeting a victim via email:</b><br/>  
<img src="https://i.imgur.com/tyHbeEz.png" height="80%" width="80%" alt="Generated Executable File"/>  
<img src="https://i.imgur.com/XKIvdpF.png" height="40%" width="80%" alt="Email Simulation"/>  
<br /><br />

<h2>Blue Team🟦</h2>

<p align="center">

<b>Victims Enters Bamk Information:</b><br/>  
<img src="https://i.imgur.com/fZq1HF2.png" height="100%" width="100%" alt="Active Directory Setup"/>  
<br /><br />

<b>Keylogger captures key strokes:</b><br/>  
<img src="https://i.imgur.com/pElNzdG.png" height="80%" width="80%" alt="Keylogger Code in VSCode"/>  
<br /><br />

<b>Cybersecurity professional will load Task Manger and kill tasks:</b><br/>  
<img src="https://i.imgur.com/CMObJRb.png" height="80%" width="80%" alt="Installing pynput"/>  
<img src="https://i.imgur.com/UgL7NuF.png" height="80%" width="80%" alt="Installing pynput"/>  

<br /><br />

</p>
