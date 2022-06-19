# Preparation for SheLeadsTech 25 June 2022 session

We will be using nmap for doing basic vulnerability assessments and penetration testing exercises. You should ideally bring a laptop with Windows 10 or Windows 11 installed. If you are bringing an office laptop, make sure you have administrative rights. If you are bringing your personal laptop, then you should have the administrative rights by default.

If you have a laptop running Kali Linux or macOS, the installation steps will be different from Windows and can be found below

## Prerequisites
1. Laptop with wifi, running either Windows 10 or Windows 11.
2. An account with administrative access to install NMAP.
3. Understand how to disable the Antivirus software on your laptop.

### What is NMAP?

[NMAP](https://nmap.org/) is a software tool commonly used to probe for open services or ports. It can either send IPv4 or IPv6 probes and is the mainstay software for most vulnerability assessments and penetration testing engagements. We will be using this tool for the session.


## Windows: Steps to install nmap on your laptop

1. Go to [NMAP](https://nmap.org/download#windows) and download the executable that says `nmap-7.92-setup.exe` using your favourite web browser



2. Upon downloading, install the application by double-clicking on it.
3. Verify it works by executing the application. To do so, click on the Start button (Lower left corner) and type `cmd`
4. Then `nmap` You should see lines scrolling down the terminal. Scrolling upwards you will see:
```
Nmap 7.92 ( https://nmap.org )
Usage: nmap [Scan Type(s)] [Options] {target specification}
TARGET SPECFIICATION:
  Can pass hostnames, IP addresses, networks, etc
  Ex: scanme.nnmap.org, microsoft.com/24, 192.168.0.1; 10.0.0-255.1-254
  ...
```
5. You're ready for the session


## macOS: Steps to install nmap on your laptop

By default, macOS does not come with either the Homebrew or the Macports package managers. You will need to install either one (definitely not both)

A. If you are using Homebrew
1. Run the Terminal application (Applications > Utilities > Terminal)

2. Now to update Homebrew
`sudo brew update`

3. Install nmap
`sudo brew install nmap`

B. If you are using Macports
1. Run the Terminal application (Applications > Utilities > Terminal)

2. Now to update Homebrew
`sudo port update`

3. Install nmap
`sudo port install nmap`


## Linux (Debian-based distributions): Steps to install nmap on your laptop

APT is the default package manager in Debian-based distributions, together with Kali Linux.

1. Update the apt repository
`sudo apt update`

2. Install nmap
`sudo apt install nmap`


## Linux (RHEL-based distributions): Steps to install nmap on your laptop

YUM is the default package manager in RHEL-based distributions; for example CENTOS, Red Hat Enterprise Linux.

1. Update the yum repository
`sudo yum update`

2. Install nmap
`sudo yum install nmap`

`
