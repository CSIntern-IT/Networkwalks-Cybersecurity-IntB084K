# Week 1 - Cybersecurity Lab Setup

**Networkwalks Cybersecurity Internship | Batch B083C**

## Introduction

For the first week of my cybersecurity internship, the main task was to set up a working lab environment using VirtualBox and Kali Linux.

The idea was to get everything installed and running properly so I could use it for the upcoming cybersecurity tasks. Since a lot of cybersecurity practical work involves using Linux and testing things in a separate environment, having a virtual machine makes things much easier without having to change anything on my main operating system.

This is basically a walkthrough of how I set everything up, the settings I used, and a few screenshots showing the process.

## My System

Before getting started, I checked my laptop's specifications just to make sure it could handle running a virtual machine alongside Windows.

Here are the details of the system I used:


<img width="1715" height="1191" alt="image" src="https://github.com/user-attachments/assets/53e6d10e-d775-4d8a-a533-fe66d18acc6e" />

## 1. Installing 7-Zip

I started off by installing 7-Zip, since the Kali Linux virtual machine file comes compressed and needs to be extracted before it can be used.

There wasn't really much to configure here. I just downloaded it, installed it, and used it later on when extracting the Kali files.

<img width="1462" height="872" alt="image" src="https://github.com/user-attachments/assets/705a1686-6d87-4006-9de1-6620ddd2906d" />


## 2. Installing VirtualBox

Next, I downloaded Oracle VirtualBox.

VirtualBox basically allows me to run another operating system inside my computer without needing to install it directly onto my main drive.

After the installation was finished, I opened VirtualBox to make sure everything was working before moving on to Kali Linux.

<img width="1972" height="1242" alt="image" src="https://github.com/user-attachments/assets/e124e483-aff8-4de1-ae57-b18bc6ec04cb" />
<img width="1920" height="1504" alt="image" src="https://github.com/user-attachments/assets/98b8045a-dfcc-4376-a255-60dbf1d33e88" />



## 3. Setting Up Kali Linux

After getting VirtualBox ready, I downloaded the Kali Linux virtual machine image.

I extracted the downloaded files using 7-Zip and added the Kali virtual machine to VirtualBox.

Once it showed up in VirtualBox, I went through the settings to check the RAM, CPU allocation, and other options.

I wanted to give Kali enough resources to run smoothly, but also leave enough for my main operating system to keep running normally.

Here are the settings I ended up using:

- **RAM:** **16354 MB**
- **Processors:** **32 CPUs**
- **Operating System:** Kali Linux
- **Network Adapter:** **Nat Network**

<img width="2880" height="1796" alt="image" src="https://github.com/user-attachments/assets/83ad60d0-ff93-401b-991a-500a28f7f234" />


## 4. Network Configuration

The next part was configuring the network settings for the virtual machine.

This was important because Kali needs network access for downloading updates, using certain tools, and completing networking-related lab tasks.

I opened the network settings in VirtualBox and configured the adapter according to the lab requirements.

After that, I checked that the settings had been saved properly.

<img width="1832" height="1168" alt="image" src="https://github.com/user-attachments/assets/7bd94ada-0d8a-44ea-ba89-4e04f49d6152" />


## 5. Running Kali Linux

Once everything was configured, I started the Kali Linux virtual machine.

I logged in and checked that the desktop loaded correctly. I also went through the basic settings and made sure the system was responding normally.

At this point, the main setup was pretty much done. I had Kali Linux running inside VirtualBox and could start using it for the lab activities.

<img width="1826" height="1170" alt="image" src="https://github.com/user-attachments/assets/16341fcb-41f8-405e-9074-6b58adf46eee" />

## 6. Problems Encountered & Troubleshooting
1. Network Option Missing in VirtualBox
One of the issues I encountered during the setup was that the Network option shown in the tutorial was not appearing in my VirtualBox Manager.

This meant I could not immediately follow the same network configuration steps shown in the guide.

I investigated the VirtualBox installation and configuration rather than assuming that the tutorial interface would be identical to my installation.

What I learned:

VirtualBox features and management options can depend on the installed version, installation state, and enabled components. When following a tutorial, the interface may not always match exactly, so checking the actual installation and configuration is important.

<img width="1936" height="1511" alt="image" src="https://github.com/user-attachments/assets/5fc8e8bb-8598-49a2-bf17-cc61bed66949" />

<img width="1024" height="813" alt="image" src="https://github.com/user-attachments/assets/6d3ccb91-aaba-4c0b-b8d7-78594d3896a8" />



## 7. Final Working Lab

After going through the installation and configuration process, I managed to get the Kali Linux virtual machine running on VirtualBox.

The main setup is now complete, with the required resources and network settings configured. I can use this environment for the upcoming cybersecurity practicals.

**Evidence:**

<img width="1830" height="1168" alt="image" src="https://github.com/user-attachments/assets/fe0676cb-c161-4fc4-80be-e719009b8111" />


## Screenshots / Evidence

I've added screenshots throughout the README showing the different stages of the setup, including the installations, VM configuration, network settings and the final working lab.

## What I Learned from Week 1 Project

This week's task gave me some hands-on experience with VirtualBox and setting up Kali Linux.

I got to understand a bit more about how virtual machines work, how to allocate hardware resources and how the network settings work inside VirtualBox.

I also learned that following a tutorial doesn't always mean everything will look exactly the same on your computer, so it's useful to check the settings yourself and figure things out when something doesn't work.

Overall, it was a good introduction to setting up the environment I'll be using throughout the internship.

## Security & Ethical Use

This lab is only meant for learning and practising cybersecurity in an authorized environment.

Any security testing will be carried out on systems that I own or have permission to test.

## Tools & Technologies

- Windows
- Oracle VirtualBox
- Kali Linux
- 7-Zip
- GitHub

## Project Information

**Program:** Networkwalks Cybersecurity Internship

**Batch:** B084K

**Week:** 1

**Project:** Cybersecurity Lab Environment Setup

**Author:** Prithvi Raghawa

## Disclaimer

This repository is just documentation of my Week 1 cybersecurity lab setup. The environment is intended for educational use and authorized security testing only.



