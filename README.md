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

Step 1) Opened a terminal
<br/>
A terminal, also known as the command-line, allows us to interact with a computer without using a graphical user interface. On the machine, I opened the terminal using the Terminal icon:  

https://user-images.githubusercontent.com/125272645/218560010-876d3d04-7e57-415a-a494-198f440219ae.mp4

<br />Step 2) Found hidden website pages
Most companies will have an admin portal page, giving their staff access to basic admin controls for day-to-day operations. For a bank, an employee might need to transfer money to and from client accounts. Often these pages are not made private, allowing attackers to find hidden pages that show, or give access to, admin controls or sensitive data.

I typed the following command into the terminal to find potentially hidden pages on FakeBank's website using GoBuster (a command-line security application).:

<br/>
<img src="https://user-images.githubusercontent.com/125272645/218570689-209aff77-5291-402a-8bb0-d04c9f04c3c7.png"/>

In the command above, -u is used to state the website we're scanning, -w takes a list of words to iterate through to find hidden pages.
<br />

As you can see, GoBuster scans the website with each word in the list, finding pages that exist on the site. GoBuster shows us the pages it found in the list of page/directory names (indicated by Status: 200).
<br />

<img src="https://user-images.githubusercontent.com/125272645/218573103-3aa275b0-6e6e-4b9a-9f8b-147c18c5c6e6.png"/>
<br />
Step 3) Hack the bank

I found a secret bank transfer page that allows one to transfer money between accounts at the bank (/bank-transfer). 

I then typed the hidden page into the FakeBank website on the machine.  <br/>

https://user-images.githubusercontent.com/125272645/218575129-177ff228-adf1-45a7-8144-884e40cbe2ea.mp4


This page allows an attacker to steal money from any bank account, which is a critical risk for the bank. As an ethical hacker, I would (with permission) find vulnerabilities in their application and report them to the bank to fix before a hacker exploits them.
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
