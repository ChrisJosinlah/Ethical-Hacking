# Ethical Hacking Practice
<h1>Fake Bank - Application</h1>

<h2>Description</h2>
This "Offensive Security" project consists of using a command-line application called "GoBuster" to brute-force FakeBank's website to find hidden directories and pages. GoBuster takes a list of potential page or directory names and tries accessing a website with each of them; if the page exists, it tells us.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Virtual Machine</b> 
- <b>GoBuster command-line application</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Step 1) Opened a terminal
<br/>
A terminal, also known as the command-line, allows us to interact with a computer without using a graphical user interface. On the machine, I opened the terminal using the Terminal icon:  

https://user-images.githubusercontent.com/125272645/218560010-876d3d04-7e57-415a-a494-198f440219ae.mp4

"/>
<br />
<br />
Step 2) Found hidden website pages

Most companies will have an admin portal page, giving their staff access to basic admin controls for day-to-day operations. For a bank, an employee might need to transfer money to and from client accounts. Often these pages are not made private, allowing attackers to find hidden pages that show, or give access to, admin controls or sensitive data.

I typed the following command into the terminal to find potentially hidden pages on FakeBank's website using GoBuster (a command-line security application).:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
