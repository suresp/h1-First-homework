# h1-First week homework
This was my first time taking the courses regarding the information security and most of the topics were new but during the first lecture and looking at the structure of upcoming weeks I could have the image that it will be interesting reading this course.
The first lecture was about learning the fundamentals, organizing and knowing the practise environments to be used in this course. The assignments involved in the first week were reading and summarizing the given topic, solving Over The Wire:Bandit, Install Debian, Install Webgoat target and solvetask on webgoat.

# a) Topic 
Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains, chapters Abstract, 3.2 Intrusion Kill Chain and 3.3 Courses of Action
# b) summary
Conventionally a kill chain known as systematic process to target and engage an adversary to create desired effects. Based on the same concept currently this paper presents a new kill chain model spefically for intrusions.With respect to computer network attack the different phases of kill chhain are as:

1.Reconnaissance: first step of penetration test. Main goal is to gather as much information as possible

2.Weaponization:Second step in cyber attack. main goal here is to build the tools required to attack the victim.

3.Delivery: It involves transmission of the weapon to the targeted environment.

4.Exploitation: Exploit takes advantage of target's vulnerabilities in software like installing malware

5.Installation: Installs the remote access on victim system

6.Command and Control(C2): "hands on thekeyboard" thus have access to target environment

7.Actions on objectives: Final step of data exfiltration.

courses of action matrix detect, deny, disrupt, degrade, deceive and destroy can be used to depict in different phases of cyber kill chain
Metrics of resiliency can be developed by measuring the performance and effectiveness of defensive actions against the intruders.

Karvinen 2020: Command Line Basics Revisited
Here i came to know the diffent command which is used in command line in Linux and BSD. Seemed bit similar to to commands in windows but will get them know better when i start using it more often.

# Over The Wire:Bandit the first levels(0-4)
![bandit game](https://user-images.githubusercontent.com/122970395/214176935-94fd6e87-0545-44d1-aca3-9fa4248cc9f2.png)

In this task it was asked to solve level 0-4 in Over The Wire Game:Bandit
It was performed using SSH connection to the host bandit.labs.overthewire.org, on port 2220. 
Here one level has to be completed in order to begin the next level.
Performing these levels i learned some commands like
ls used to list all files and directories within system
cat it lists, combine and writes file content to standard output.
if file name has spaces \ could be used in between words.

# Bullseye. Install Debian 11-Bullseye virtual machine in VirtualBox.
It was my first time installing OS in virtual box . I had some problems during the first installation but everything went well. I was struggling to work in the small window prompted during the installation. 

# WebGoat. Install WebGoat practice target.
Installing webgoat was performed according to the material provided and it required the registration.
 
 # Hacker warmup. Solve these tasks on WebGoa
 General: HTTP Basics
 
General: Developer tools
![webgoatfirst](https://user-images.githubusercontent.com/122970395/214187891-aab9fa2d-f54d-478b-a3df-92855b21df43.png)

   ![webgoat1](https://user-images.githubusercontent.com/122970395/214181422-1b591fba-8eee-4506-af14-fb971ff5a50d.png)
   
![webgoat2](https://user-images.githubusercontent.com/122970395/214181468-68f7c6db-5511-478c-9ae2-98d6456d712b.png)

It was difficult for me but looking at different resources i could find the magic number as first task. using developer tool was familiar to me as i had chance to learn during my previous javascript course.

# sources
https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf
https://terokarvinen.com/2020/command-line-basics-revisited/
https://overthewire.org/wargames/bandit/
https://terokarvinen.com/2021/install-debian-on-virtualbox/
https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/

