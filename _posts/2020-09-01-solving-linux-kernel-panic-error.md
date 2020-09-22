---
title: "Solving Linux Kernel Panic Error in Ubuntu 20.X"
categories:
  - Blog
tags:
  - tech, troubleshooting
---

Amid the ongoing Covid pandemic, most of the time is spent now-a-days in from of machines, working in my current day's job to create clinical platform product helping top pharma companies develop vaccine, to fight coronavirus. It's during the some rare weekend that, I get time, to spend on my pet projects and hobbies.

On my dual boot, Dell XPS 17, i have recently created a dual boot Windows 10 and Ubuntu 20.04. Current focus has been on music production using LMMS.

Thus, it was a surprise and unfortunate, that I came across a 'Kernel Panic' error at boot time. The laptop won't boot into linux at all.

I verified the Windows partition boot, and found it to be working fine, thus HDD seemed to be ok.
A quick Disk SMART test, was successful as well.

After looking around for some answers in ubuntu forums, came across a simple solution.

1. On the GRUB screen, go to Advanced options for Ubuntu.
2. Select a most recent - 1 kernel.
3. Continue to boot.
4. Most likely your issue would have resolved, and you will land in gnome desktop
5. Run system updates to stabalize the system, and let it complete fully.
6. Reboot, and verify that latest kernel is now being used.

This is it, a simple set of steps to fix this issue.
Winding back in time, I recollected, in the event just prior to the issue, I had a screen freeze and hard shutdown, during the updates. this probably messed up the kernel image, leading to the issue.

Happy Ubuntu Fan.
