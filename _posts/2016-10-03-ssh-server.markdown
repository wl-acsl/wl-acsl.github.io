---
layout: post
title:  "SSH Server"
date:   2016-10-03 16:29:45 -0400
categories: update
---

Welcome to the first post of the all new CAT Club information blog!

## SSH into our DigitalOcean Server!

For reference, our server runs Ubuntu 16.04.1 LTS Server edition.

If you've filled out the server account request form from Sam, you should have an account on our fancy new Linux server in NYC.

### Windows

From your Microsoft computers, you can use [MobaXTerm](http://mobaxterm.mobatek.net/download-home-edition.html) or [Putty](https://the.earth.li/~sgtatham/putty/latest/x86/putty.exe) to SSH (remote desktop) into our servers, where we can do cool stuff on Linux. For instructions, look at the section below...

### macOS / Linux
Open __Terminal__ (or equivalent) and type in:

    ssh yourusername@ssh.wlcat.tech

    # if the above doesn't work, try:
    ssh yourusername@104.131.118.86

    # for troubleshooting, if you know what to do:
    telnet 104.131.118.86 22

and hit ENTER. If it asks you to verify an RSA fingerprint, do it, then type in your password, and you're in!

For the basic of using a command-line shell, [here's a good LifeHacker primer](http://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything). Also, you can ask me (Linus, who's writing this), Sam, Cory, or any other member of the exec board.

## From school computers
  
1. Open `mobaXterm` from `Student Commons\Thompson\ACSL\` folder or whereever else you downloaded it into
2. `cortex` into the hostname, then your __school username__ for the username
3. Once you're in with your __school password__, type in the command above in the _macOS / Linux_ section, and you're in!

We have to do this weird extra process because the school network blocks direct SSH connections.
It is frustrating, yes, but at least we can still access our server from inside the school.

For editing text files, I'd recommend `nano` as a nice beginner editor. Then upgrade to `vim` or `emacs`. Both are nice options, and between the exec board members we use all three. Both Vim and Emacs can be crazy powerful, and they're simple enough to start out with. 

### Final Tip
If you have any command that you don't recall exactly how to use, do `man command-name` and it'll tell you exactly how to use that command.
If more concerns arise, the executive board and the internet is available at your fingertips to help solve the problem.

