+++
title = 'OverTheWire Bandit 0 Walkthrough'
date = 2024-05-14T21:02:52-05:00
draft = false
+++

# Introduction

If you have an interest in cybersecurity, you've probably heard of Capture the Flag.  Capture the Flag, or CTF for short, is a cybersecurity game played by those who want to improve their skills.  Participants are challenged to find a "flag" (usually a simple text string), which are hidden somewhere on the vulenerable server , via exploits.  [OverTheWire.org](https://overthewire.org/wargames/) is a website that hosts free challenges that teaches beginners the basics of CTF.  It is organized into different "war games", each with levels that increase in difficulty.  The recommended place to start is with their game called [Bandit](https://overthewire.org/wargames/bandit/), which is aimed at absolute beginners. I have been fascinated by CTF since learning about it in college, so I have decided to finally dive into Bandit.  The purpose of these write ups is to help me solidify my knowledge and understanding as I progress.

# Task
The goal of this level is for you to log into the game using SSH\
Server: bandit.labs.overthewire.org\
Port: 2220\
Username: bandit0\
Password: bandit0\

# Solution
To start Bandit, you need to login.  They want you to connect via SSH (Secure Shell Protocol), which is a way to remotely connect to another computer SSH is a UNIX program, so to use it on Windows you'll need to install an SSH client like Cygwin or Putty.  I will use WSL since SSH is preinstalled.  Logging in with SSH is as simple as\
`ssh <username>@<server> -p <port>`\
so in our case we can use\
`ssh bandit0@bandit.labs.overthewire.org -p 2220`\
enter the password and congratulations you have beat level 0!

You'll want to make sure you memorize this command because you'll be using it on every subsequent level to login.