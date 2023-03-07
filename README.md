<h1>The Dangers Of Social Engineering</h1>

 ### [YouTube Demonstration]()

<h2>Description</h2>
Social engineering is a major issue in the cyber world. It is the manipulation and 
tricking of individuals into performing certain actions like divulging confidential 
information. Cybercriminals use social engineering in their attacks more than 90% of 
the time through various methods such as phishing and smishing. Over 70% of all 
companies worldwide were also victims of these attacks in 2020, making education 
and training on the topic ever more important.  As It is difficult for the average 
person to identify a spoofed email or website.
<br />
<br />
<br />
I used a lot of concepts and tools on this project, such as social engineering and 
phishing, website spoofing, HTTP server hosting, the Social Engineering Toolkit 
(SET), and virtual machines as a sandbox environment to test these tools. I had one 
victim machine and one attacker machine. When researching social engineering, I 
first looked up popular engineering tools that social engineers use and came across 
SET. After selecting SET, I researched how to get it on my Kali machine and get it 
all configured. After I set up my victim machine, I installed SET and began 
testing.

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



<b>Launch the utility:</b> <br/>
![1 jpg](https://user-images.githubusercontent.com/125488657/223505584-b28bdf9e-7e76-4d45-8736-a048ffaa6818.png)

<br />
<br />
After launching SET and selecting options 1, 2, and 3 in that order, select option 1 for site templates. These are pre-constructed website templates that are available for use. If you wish to clone a particular website, select option 2 for site cloning and insert the URL you would like to clone.
<br />
<br />

<b>Paste in local address:</b> <br/>
![2 jpg](https://user-images.githubusercontent.com/125488657/223531234-495be71b-7827-4340-90dd-78ebeeee4cb5.png)

<br />
<br />
Once you have entered the IP address of the machine you wish to receive the credentials for, your harvester is now configured. Now we must find a way to connect with the victim. It could be in an email, an image, or a text message. For this demonstration, we will be simulating attacking someone we are familiar with.
<br />
<br />

<b>Listening for Credentials:</b> <br />
![3 jpg](https://user-images.githubusercontent.com/125488657/223535692-d6ab01ca-8a6d-4cb7-b9e6-9321ca759902.png)
<br />
<br />
Now that the listener is set up and awaiting credentials, we will now conceal the link in an email to a friend, informing them to view the post on Twitter. Once the victim clicks on the link, they will be directed to a replica of the genuine website's login page. After they entered the credentials, they were sent to my attack machine's terminal. Below is the email with the hidden link ready to send.
<br />
<br />
![4 jpg](https://user-images.githubusercontent.com/125488657/223542611-62b10b8d-c78f-448f-83b8-0d7e07142b89.png)
<br />
<br />
<b>Victim receives phishing link email:</b> <br />
![5 jpg](https://user-images.githubusercontent.com/125488657/223543041-9f8b9d8a-b5d3-4107-b41d-6057ab2cadac.png)
<br />
<br />
<br />
<b>Victim inputs credentials:</b> <br />
![7 jpg](https://user-images.githubusercontent.com/125488657/223543710-c5f6913a-d36b-4970-9b92-ca67c7eeb21f.png)
<br />
<br />
<br />
<br />
<b>Attacker receives credentials. Attack successful:</b>
![8 jpg](https://user-images.githubusercontent.com/125488657/223544448-4dd8d76c-d169-4049-a541-aa094aa14a03.png)

<h2>The Impact Of Social Engineering</h2>
<br />
Social engineering through phishing is surprisingly easy to do and can have 
devastating consequences. Cybercriminals can gain access to emails and the 
personal identifiable information (PII) contained within them.Social engineering 
can also be used to influence people's opinions or to spread misinformation or 
malicious content. In short, the impact of social engineering on people and
organizations and the potential damage it can cause 
must be taken seriously.
<br />
<h2>Mitigations </h2>

- <b>Phising Campaigns</b> 
- <b>Train staff, friends, and family on security best practices </b>
- <b>Continually test the effectiveness of the training</b>
- <b>Technical measures such as installing firewalls and making regular system updates</b>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
