<h1>The Dangers Of Social Engineering</h1>

 ### [YouTube Demonstration]()

<h2>Description</h2>
For this project, I chose to research social engineering and the tools employed to carry out these attacks.For this instance, I chose the Social Engineering Toolkit (SET for short).Social engineering attacks constituted over 70% of all attacks in 2020.This emphasizes the importance of education on the subject.I will be demonstrating the sending of a phishing link to a victim containing a credential harvester using SET.
<br />


<h2>Utilities Used</h2>

- <b>Social Engineering Toolkit(SET)</b> 
- <b>VirtualBox</b>
- <b>Hyperlinks</b>

<h2>Environments Used </h2>

- <b>Kali(Attacker)</b> 
- <b>Windows 10(Victim)</b>

<h2>Project Walkthrough</h2>
First, after choosing SET, i researched how to download and configure it on my attacker kali VM. Then i researched the tool itself and its capabilities and chose credential harvester as the method i will be demonstarting.
<br />
<br />



Launch the utility: <br/>
![1 jpg](https://user-images.githubusercontent.com/125488657/223505584-b28bdf9e-7e76-4d45-8736-a048ffaa6818.png)

<br />
<br />
After launching SET and selecting options 1, 2, and 3 in that order, select option 1 for site templates. These are pre-constructed website templates that are available for use. If you wish to clone a particular website, select option 2 for site cloning and insert the URL you would like to clone.
<br />
<br />

Paste in local address: <br/>
![2 jpg](https://user-images.githubusercontent.com/125488657/223531234-495be71b-7827-4340-90dd-78ebeeee4cb5.png)

<br />
<br />
Once you have entered the IP address of the machine you wish to receive the credentials for, your harvester is now configured. Now we must find a way to connect with the victim. It could be in an email, an image, or a text message. For this demonstration, we will be simulating attacking someone we are familiar with.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
