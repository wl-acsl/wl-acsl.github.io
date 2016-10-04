---
layout: post
title:  "Some info stuff!"
date:   2016-10-03 16:29:45 -0400
categories: update
---

We're cool. We have a Jekyll blog now. NBD.

## SSH into our DigitalOcean Server!

For reference, our server runs Ubuntu 14.04 LTS Server edition.

If you've filled out the form from Sam, you should have an account on our fancy new Linux server over at NYC.

### Windows
From y'all's own Microsoft computey tooteys, you can use [MobaXTerm](http://mobaxterm.mobatek.net/download-home-edition.html) or [Putty](https://the.earth.li/~sgtatham/putty/latest/x86/putty.exe) to SSH (remote desktop) into our servers, where we can do cool stuff on Linux. For instructions, look at the section below...

### macOS / Linux
Open __Terminal__ and type in:

    ssh yourusername@ssh.wlcat.tech

    # if the above doesn't work, try:
    ssh yourusername@104.131.118.86

    # for troubleshooting, if you know what to do:
    telnet 104.131.118.86 22

and hit ENTER. If it asks you to verify an RSA fingerprint, do it, then type in your password, and you're in!

For the basic of using a command-line shell, [here's a good LifeHacker primer](http://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything). Also, you can ask me (Linus, who's writing this) or Sam or Cory.

## From school computers / Windows computers
  
1. Open `mobaXterm` from `Student Commons\Thompson\ACSL\` folder or whereever else you downloaded it into
2. `cortex` into the hostname, then your __school username__ for the username
3. Once you're in with your __school password__, type in the command above in the _macOS / Linux_ section, and you're in!

For editing text files, I'd recommend `nano` as a nice beginner editor. Then upgrade to `vim` or `emacs`. Both are nice options, and between the exec board members we use all three. Both Vim and Emacs can be crazy powerful, and they're simple enough to start out with. 

### Final Tip
If you have any command that you don't recall exactly how to use, do `man command-name` and it'll tell you exactly how to use that command in a nice little thingy.`

