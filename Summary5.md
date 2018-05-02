# Oops/Sl@ckers
## Week 16, iPXE Menu Update and **NetBoot.xyz** Integration.
### Pavel Danek

Hello to all of my Linux 2018 class!

This week's work was a little lighter for me, as I dedicated most of my time in the past two or so weeks to this.
I was asked to integrate Mr. Messerli's [NetBoot.xyz](https://github.com/antonym/netboot.xyz) work into our own menu.

That's how our updated [pboot.ipxe](Files/pboot.ipxe) came to be. I improved and extended the menu and handed my work over to Lucas. [Lucas's work](https://github.com/luschool/oopsslackersluschool) is extraordinary - check it out!
He's now going to attempt to integrate my work with his (which is work on TFTP server created on his Raspberri Pi, hosting the whole "Windows Deployment" of the first menu of the whole enterprise.

My first intention was to integrate the NetBoot.xyz menu seemlesly with mine. I would (almost) succeed, if it wasn't for the clever Messerli's signature and certificate checking throughout the code. You take a portion out and try to use it in yours and it won't work anymore.
My only chance would be to take the whole Messerli's script (which I understand now) and graft it onto mine, with the individual links preserved. I _just did not_ have enough time for that...

And so the final result before handing it over to Lucas is this:

After booting with iPXE, the first screen goes to the Windows/NetBoot Menu:
[Pic#1](Files/IMG_0001.JPG]

The next screen after choosing "Load NetBoot.xyz Menu":
[Pic#2](Files/IMG_0002.JPG]

The final screen, after loading NetBoot.xyz:
[Pic#3](Files/IMG_0003.JPG]

That's it for today!

"Thank you very much, thank you very much!"
---Elvis---
-Pavel.
