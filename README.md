# Practicing Linux Commands
In this repo I will show how I practice basic Linux commands with basic checkpoints
## verify apt is installed
- running <code>apt</code>

<img src="https://i.imgur.com/PMeGNuB.png">

Since I am practicing in Ubuntu which is Devian based, APT is already installed by default.
## Installing Suricata
Suricata is an open-source Intrusion Detection System (IDS) and Intrusion Prevention System (IPS) developed by Open Information Security Foundation.
- Install Suricata
To install and remove software on Linux you need elevated permissions, there is a command that gives you such permissions whithout the risk of logging into the root user and potentially cause serious harm to your system. the command is called <code>Sudo</code>, it could make more sense if you see it as "SUper DO".

<code>sudo apt install suricata</code>

<img src="https://i.imgur.com/jT0tDUa.png">

- Verify Suricata is installed

To verify suricata is installed, run <code>suricata</code>

<img src="https://i.imgur.com/DYAWDog.png">

## Removing Suricata
Again, to install and remove software in linux, you need <code>sudo</code> command.

<code>sudo apt remove suricata</code>

<img src="https://i.imgur.com/ey9vI0A.png">

## Install tcpdump
Tcpdump is a command-line tool that can be used to capture network traffic, it allows you to analyze TCP/IP and other packets being transmitted in the network.

run <code>sudo apt install tcpdump</code>
<img src="https://i.imgur.com/JYc4eV9.png">

## List the installed applications 
To list the installed applications run <code>apt list --installed</code>

<img src="https://i.imgur.com/Aggqqix.png">

## Reinstall suricata and list the installed applications
Reinstall suricata and verify that both tcpdump and suricata are installed

run <code>apt list --installed</code>

<img src="https://i.imgur.com/xkW7OQc.png">
<img src="https://i.imgur.com/nSrlraK.png">
