Nmap Portable

This is a 100% portable (though maybe not 100% functional) "boxed" version of Nmap.  This executable will run *without* external dependencies on Windows 10.

Why?

Portable applicaitons are useful in all sorts of enviornments.  I have a tendency to use applications that do not modify the registry, or leave a large footprint on a device.

Have you ever been trying to solve a problem online and come across an old thread with the "answer," only for the link not to work or someone saying "figured it out on my own, nevermind!?"  Well... I was reading a thread from 2008 discussing this topic (https://portableapps.com/node/15594) and realized that very few have taken time to do this... So here we are.

How did this happen?

Npcap is a resource that nmap needs to function on Windows, so portability has always been a challange.  

I have taken Nmap 7.92 [2021-08-08], and Npcap (log files included) so you can see how the build occured.

Why should I trust you?

You shouldn't [trust anyone]!  Good for you!  Please do your own research before running binaries off the internet.

How can I contribute?

I am open to any contributiors.  Submit a PR or message me on Twitter! :)

#TODO

Testing on Windows XP, 7, 8, 10, 11 for compatability.

How do I scan?

Open PowerShell or CMD
Navigate to the directory of the binary (nmap-portable.exe)
./nmap-portable.exe nmap -h

There are some really great documents regarding Nmap.

Check out:
https://hackertarget.com/nmap-cheatsheet-a-quick-reference-guide/
https://nmap.org/book/port-scanning-tutorial.html

How do I build this myself?

Coming soon.