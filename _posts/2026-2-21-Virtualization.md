---
layout: test
title: Virtualization
---

Now I'm going to try to get Kali Linux running in a virtual machine.

I was going to use Proxmox, but I didn't have a USB handy. I have Windows 11 Pro, however, and Hyper-V comes with that already, so I might as well use that. There's a helpful guide for getting it running on the https://learn.microsoft.com/ website. I also downloaded the ISO for Kali Linux.

I got the virtual machine turned on, but I couldn't get it to boot with Linux. It seems I just had to go into settings and turn off "Secure Boot". But now I have another issue, I can't configure the network when I try to install the OS.

I'm going to try to adjust the settings. I'll change the Virtual Switch in the Network Adapter from "Not connected" to "Default Switch". And that seems to have done it! I'll just stick with the default and recommended settings for everything else.

And now it's working! Kali sure does have a lot of security tools. I think I'll be working with one of them for the next blog post.
