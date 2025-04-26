# cs6262---project-1-introduction-to-penetration-testing-solved
**TO GET THIS SOLUTION VISIT:** [CS6262 – Project 1: Introduction to Penetration Testing Solved](https://www.ankitcodinghub.com/product/cs6262-project-1-introduction-to-penetration-testing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;105959&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6262 - Project 1: Introduction to Penetration Testing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
The goal of this project :

Penetration testing is an important part of ensuring the security of a system. This project provides an introduction to some of the common tools used in penetration testing, while also exploring common vulnerabilities (such as Shellshock and setUID bit exploits).

Environment Setup :

Files Provided Description

shellshock_server.ova The VM image (see setup Step 2).

assignment_questionnaire.txt Template for final submission.

This project requires the use of virtual box and multiple VMs.

Installing Virtual Box:

1. Install VirtualBox if it is not already installed. This project requires the latest version of VirtualBox 6.1.x. Using an earlier version of Virtual Box has been known to cause errors where the project VM freezes, so if you run into this, ensure you’re running on at least Virtual Box 6.1.0 or later.

2. Download the Oracle Virtual Box Extension Pack (available for download at the same location as

Virtual Box is).

3. Import the Extension Pack under File-&gt; Preferences-&gt; Extensions

4. In Virtual Box go to Tools -&gt; Preferences -&gt; Network.

5. Select the small plus sign in the upper right corner of the network preferences box to create a new NAT network. Select the NAT network and select the small gear below the add button to edit it. In the box that appears, change the name to something related to the project. Then save it, and close the preferences.

Installing the Kali Linux VM:

6. Visit https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download

7. Scroll down to “Kali Linux Virtual Box Images”, expand the tab, and select “Kali Linux VirtualBox

64-Bit”. You should be prompted to save the virtual machine, and then a download should begin.

8. Import the Kali Linux VM to Virtual Box. Once you’ve imported the VM, you’ll likely need to go into the VM Settings and increase the number of CPUs if possible, as well as the RAM. Also enable 3-d acceleration, and set the zoom level to 300 (it makes it easier to read).

9. Go to the new Kali VM’s settings. In the network tab change “Attached to:” from NAT to NAT Network in the Adapter 1 tab. The name of the network should autofill to your newly created network if you only have one, but if you have multiple NAT networks, you’ll need to select the correct one.

10. Repeat the process with the other VMs you want to communicate with the Kali VM.

11. Start the Kali VM. The default username/password is: kali/kali.

12. Ensure the guest additions are installed. If they’re not, go to devices-&gt;insert guest additions CD). Then follow the instructions in the popup window to install the guest additions..

13. In the top Virtual box menu bar of the Kali VM, go to Devices -&gt; Shared Folders -&gt; Shared Folders

Settings.

14. Click Machine Folders to ensure it’s highlighted. Click the small add folder icon on the right of the screen.

15. Select a path (in “Folder Path”) to a folder on your host machine that will act as the shared folder on the host. Give the folder a name, if it doesn’t autofill already. Check the “Auto-mount” box. Check the “Make Permanent” box. Click okay, and you should now see the folder under “Machine Folders”.

16. In a terminal on the Kali VM, run:

sudo usermod -a -G vboxsf $(whoami)

17. Now logout of the Kali VM and log back in (or just restart the Kali VM). The shared folder should be under: /media/sf_{shared folder name}

Vulnerable machine:

18. Download the project appliance via any of the following methods:

1. https://drive.google.com/file/d/1X7utm2Ygxpxy6gdCSKs9frA9fdsRHI4P/view?usp=sharing sha256sum: 699e5e1a02782df7c39c6638c8a520cf01ef146ab1653a0df2a422145f18201f

19. Import the downloaded OVA into VirtualBox (File -&gt; Import Appliance). Check the VM’s Network setting. Ensure Adapter 1 is set to NAT Network and the name of the NAT Network is the name you specified when creating the NAT Network in step 5.

20. Try to connect to the VM server from the Kali. Start the VM in VirtualBox (as no login is needed, you can use headless start, accessible by selecting the “Headless Start” option under the “Start” drop down menu in Virtualbox). Once you find the IP of the VM in Task 1 below, navigate to the following URL: http://&lt;IP address of the shellshock_server VM&gt;:&lt;http port found in part

1&gt;/cgi-bin/shellshock.cgi

Then you should be able to see the content:

21. Notice that you don’t need the password to access the web content hosted on the VM server. Instead of using a real server, it’s safer to perform the attack on an emulated Apache HTTP Server VM. To be clear, you will not be logging into the shellshock VM during this project. Once you configure the shellshock VM (by following steps 17-20 above), you’ll be exploiting it externally, from the Kali VM, by exploiting the Shellshock vulnerability.

Project Tasks (100 points):

Task 1: Network Scanning – (20 points)

The first step in any penetration test is to gather information about the network and servers you’ll be exploiting. In this task, you will perform network scanning and answer a few questions based on your finding. On startup, the shellshock VM listens to several ports for incoming messages.

1. Find the IP address of the vulnerable VM on the NAT network.

2. Find the port number of http traffic to the Apache web server on the VM.

4. Establish connection with each of the open ports with service name “unknown” that you found in question 2. Once connection is established, the server receives a unique integer answer message. Hint: netcat can be used to listen to a particular port.

Task 2: Attack CGI Program– (20 points)

In this task, you will launch the Shellshock attack on a remote web server. Many web servers enable CGI, which is a standard method used to generate dynamic content on Web pages and Web applications. Many CGI programs are written using a shell script. Therefore, before a CGI program is executed, the shell program will be invoked first, and such an invocation can be triggered by a user from a remote computer. To access this CGI program from the Web, you need to first check the server VM is running. Then, you can either use a browser by typing the following URL:

http://&lt;IP address found in part 1&gt;:&lt;http port found in part 1&gt;/cgi-bin/shellshock.cgi

or use the following command line program curl to do the same thing:

$ curl http:// &lt;IP address found in part 1&gt;:&lt;http port found in part 1&gt;/cgi-bin/shellshock.cgi

For this task, your goal is to launch the attack through this URL, such that you can achieve something that you cannot do as a remote user. For example, you can execute some file on the server, or look up some file located on the server. When you successfully launch an attack, please execute the /bin/task2 program (which needs your GT username as the input) inside the VM. It will generate the submission hash for you.

For students that want to verify their work, here’s an example correct input/output for /bin/task2:

$ /bin/task2 g3

Here is your task2 hash: bed3f8d83f1b21fa8cc328b551069a0e59e62fc69b3ee6f68de766665f76beb7

Task 3: Reverse Shell with Metasploit – (20 points)

Now you’ve successfully launched the Shellshock attack, and you can execute commands on the server VM. However, during a penetration test, you likely won’t have time to craft a payload for every exploit you use. And, what if the server wasn’t in fact vulnerable to shellshock. How would you know if your exploit failed because it was wrong, or because there wasn’t a vulnerability?

That’s where Metasploit comes in. Metasploit is a standard in the penetration testing community. It allows pen testers to run precompiled exploits against a host, using predefined payloads. For this project, we’re going to use Metasploit to establish a reverse shell between your machine and the host machine.

Let’s first see how Metasploit works by using it to scan the open tcp ports of the shellshock_server VM. While this is a task better suited to tools like nmap (as seen in Task 1), it serves as a good demonstration of how to use a Metasploit module. If you’ve used Metasploit before, you can skip this introduction and go directly to the Task 3 assignments section at the end.

msfconsole

1. Begin by opening a new terminal on your Kali VM. In the new terminal type: . After a moment, the Metasploit Framework console (msfconsole) will load. For this project, the msfconsole is the main way of accessing Metasploit. While there are other tools and command prompts associated with Metasploit, the msfconsole is suitable for the entirety of this project.

2. For this example, we’re going to scan the ports of a host. You can use the results from task 1 to ensure Metasploit is behaving properly. In practice using a Metasploit module solely for the purpose of scanning ports on a host is a little overcomplicated, since nmap can do much more and takes less setup, but this does offer a good introduction to using a Metasploit module.

3. A Metasploit module is the base of any task performed in Metasploit. It roughly consists of Ruby code that is written to perform a certain task (like exploit a certain vulnerability, or scan a certain kind of system). There are multiple different varieties of modules, but for our purposes we’ll focus on three of them:

a. The Exploit modules: These are modules written to exploit a certain vulnerability.

b. The Auxiliary modules: These are modules written to perform some task related to exploiting a system (like scanning). Within the auxiliary modules there are many different kinds of modules. We’ll be using the “scanner” modules for this example.

c. Payloads: Calling these modules is a little misleading. They are the payloads (for example the shellcode) that are sent within the exploit.

The reason there are so many results is that “scanner” is a class of auxiliary modules (as seen by there being so many modules beginning with “auxiliary/scanner”). So searching for “scanner” (or “scan”) will give everything at all related to network or vulnerability scanning.

That seems a little better. Only 7 results. Since we’re scanning for open tcp ports, let’s use: “auxiliary/scanner/portscan/tcp”. In order to use a metasploit module, you should run the command: use module_name

You should now see “auxiliary(scanner/portscan/tcp)” after “msf5” indicating you are using the auxiliary(scanner/portscan/tcp) module.

6. Now that we’re using the correct module, we have to set the correct options. Try running the

While each of the options is marked as required, most of the pre-filled values work for our purposes. The only one we need to change is RHOSTS. RHOSTS should be the IP address of the host we want to scan. In this case, you should set it to the IP address of the shellshock_server VM, that you found in part 1. You can use the command: set rhosts IP_of_host. Now try running options again and ensure the RHOST option is set to the right IP address .

7. Now run run and you should see the same list of open ports that nmap showed. While “run” i s usually used to run auxiliary exploits, the command “check” and “exploit” are often used to check and run exploit modules.

Now you’ve seen an example of how to use Metasploit. You’ll follow a similar process when exploiting the shellshock vulnerability.

Task 3 Assignments:

1. Find an exploit module that exploits the shellshock vulnerability on an Apache web server. Once you’ve found the module, place the module name in assignment_questionnaire.txt.

2. Use show payloads to show the possible payloads for the module. Find a payload that spawns a reverse tcp shell. Place the full name of the payload in assignment_questionnaire.txt.

3. Run the exploit and spawn a reverse shell on the VM.

4. Run /bin/task3 in the resulting shell, then type cs6262 then your user ID. Report the hash value for your user ID in assignment_questionnaire.txt.

You’ll submit all of your answers for this section in assignment_questionnaire.txt. You should keep the reverse shell running after finishing Task 3, as you will need it in Task 4.

Task 4: Privilege Escalation – (20 points)

Your goal:

You aim to upgrade the privilege for your command shell by exploiting the setUID vulnerability. You will run in ask4 as the higher privileged user “shellshock_server”, not the default user “www-data”.

Background:

As a first step, type

whoami

in ask4 your_userI

Assignments: in your shell. You should see “www-data” which is your user ID. Now, run D. You would see a permission denied error. That is because in ask4 is

configured to allow only the “shellshock_server” user to run it. So, you need to find a way to run the task4 as the “shellshock_server” user. A feasible approach is to spawn a shell running as a “shellshock_server” user, and run the task4 through it.

You goal is to find a program which:

1. Hash a higher privilege than the default user.

2. Can spawn a shell.

What is the vulnerable program? What command do you use to search it? What command do you use to spawn a shell with the vulnerable program? And what is the hash value from in ask4 your_gtid (similar to /bin/task2)? Please leave your answers in assignment_questionnaire.txt.

Task 5: Password Cracking – (20 points)

To begin, start a Meterpreter shell (using a meterpreter shell payload) through the Metasploit shellshock module in Task 3. A Meterpreter shell is different from the reverse TCP shell in Task 3, as it allows you to run metasploit specific commands on the vulnerable machine (like download) . Navigate to

homeshellshock_serversecret_files. There are two encrypted .pyc files here. task51.zip is encrypted with zip, while task52.pyc.gpg is encrypted with gpg (a common file encryption tool in Linux). Download these two files (task51.zip and task52.pyc.gpg) to your Kali VM using the meterpreter.

We already know the developers of this web server aren’t very security savvy, since they let a shellshock vulnerability plus a setUID exploit give a high privilege shell on their machine. So, chances are they didn’t pick very secure passwords for these secret files. Your goal in this task is to crack the passwords of these two files using John the Ripper (a popular password cracker) and cewl (a password scraper).

The command line tools used in Task 5 are located in /usr/sbin on the Kali VM. In order to run them, you can either add /usr/sbin to the $PATH variable, or write /usr/sbin/ before each command.

You should use zip2john and gpg2john to extract the password hashes from the encrypted files. For task51.zip, try running John the Ripper incrementally. Report your John the Ripper command in assignment_questionnaire.txt (whether you also report your the zip2john and gpg2john commands is up to you, but they won’t be graded).

For task52.pyc.gpg, try running John the Ripper incrementally again. Hmm… it seems to run forever. That’s because John the Ripper is trying every possible combination of characters. If the password is too long (among other things), John the Ripper could run for years before it finds it.

But, just because the password is too long to be found incrementally, doesn’t mean it can’t be cracked.

Take a look at the shellshock.cgi page in the browser. It looks like it gives a link to a profile of the authors. If the authors aren’t great at picking secure passwords, maybe the password is something about them that we can guess from their profile page.

But, even if the password is on the profile page, it can still take a while to guess by hand. What if the password was kItt3n$ or deVEL0p3r. It would be hard to guess that, even if the word it was based on (like “kittens”, or “developer”) was on the profile page.

Once you find the passwords, report them in assignment_questionnaire.txt. Then decrypt the two files

(using zip for task51.zip and gpg for task52.pyc.gpg) and run python task51.pyc your_user_ID and python task52.pyc your_user_ID. Report the resulting hash values for your user ID in assignment_questionnaire.txt.

Deliverables:

Please use Gradescope to submit the assignment files. The link to Gradescope is found in Canvas under Courses tab -&gt; Gradescope. In Gradescope under active assignments click project 1 to upload your files. ● assignment_questionnaire.txt

● README.txt

Please note that there is a 5-point penalty for not following the format given in assignment_questionnaire.txt.

Reminders:

There is a 5-point penalty for not following the submission format shown.

Useful Links and References:

● Shellshock Vulnerability

◦ https://github.com/carter-yagemann/ShellShock

◦ https://en.wikipedia.org/wiki/Shellshock_(software_bug)

◦ http://seclists.org/oss-sec/2014/q3/650 ● curl

◦ https://curl.haxx.se/docs/manpage.html

◦ https://curl.haxx.se/download.html (curl.exe for Windows)

● netcat

◦ https://linux.die.net/man/1/nc

◦ https://eternallybored.org/misc/netcat/ (nc.exe for Windows)

● nmap

◦ https://nmap.org/book/man.html

● Metasploit

◦ https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/

● John the Ripper

◦ https://www.openwall.com/john/doc/ ● cewl

◦ https://tools.kali.org/password-attacks/cewl

Acknowledgment:

Documentation License, Version 1.2. The original document can be found at http://www.cis.syr.edu/~wedu/seed/

Checklist/Rubric:

Section Points ✓

1 Network Exploration 20

1.1 Correct first digits of the IP Address of the vulnerable VM. 5

1.2 Correct HTTP port. 5

1.3 Correct Port/Message Pairs (points divided evenly over all pairs) 10

2 Exploiting the System 20

2.2 Correct hash value from running /bin/task2. 20

3 Spawning a Shell with Metasploit 20

3.1 Correct exploit module 5

3.2 Correct payload module (there are multiple correct answers here) 5

3.3 Correct hash value from running /bin/task3. 10

4 Privilege Escalation 20

4.2 Correct vulnerable program name. 10

4.4 Correct hash value from running /bin/task4 10

5 Password Cracking 20

5.2 Correct password for task51.zip. 5

5.3 Correct hash value from running python task51.pyc. 5

5.6 Correct password for task52.pyc.gpg. 5

5.7 Correct hash value from running python task52.pyc. 5

– Possible Deductions

i. Incorrect assignment_questionnaire.txt format. -5

ii. Incorrect upload to Gradescope/Canvas. -5

2.1 No command given for exploiting the shellshock vulnerability. -5

4.1 No command given for finding the vulnerable program. -5

4.3 No command given for exploiting the setUID vulnerability. -5

5.1 No command given for cracking task51.zip. -5

5.4 No command given for scraping the shellshock server webpage. -5

5.5 No command given for cracking task52.pyc.gpg. -5

+ Your Submission Includes

Total: 100

assignment_questionnaire.txt – Answers to questions

README.txt
