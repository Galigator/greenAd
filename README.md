# greenAd

# Here is a list of domaine/web-site that should be block to improve the web.
Install this list in your system (Windows/Linux/Mac ...) and you will get less AD, less spyware, less virus, less badware.


# Installation
The format of the file is ready to be add to your local 'hosts'.
All you need is to copy-paste the content of the file "hosts" at the end of your own 'hosts' file. Don't remove the old content, just add the new one.

Every major operating system has an 'hosts' file.

on windows 
c:\Windows\System32\drivers\etc\hosts

on Linux
/etc/hosts

In both cases you will need administrator permission.
You also need a text editor like "notepad++" to add the content into your 'hosts' file.


# How the blocking of spyware/badware work ? Why it work ?
The 'hosts' file tells your computer what is the IP address (a technical stuff) that match the human readable name from the address bar you can see in your browser (Edge/Firefox/Chrome ...). 
I browse the web as you do(but as an informatic-scientist), and when I saw bad things from a web site then I add the web site into my 'hosts' file.
The way I have add website in 'hosts' make your computer resolve the bad site as beeing your own computer; but your computer isn't a web server.
So nothing is done, the bad web site is just never call by your computer, and you stay protected.


# How can I still improve my protection/privacy/remove AD ?
When you saw a badware on a website, just append it to you 'hosts' file or open an 'issue' on this github project or send me a pull-request.
You can also install "Ghostery" or "ADBlock" plugins in your browser.
You can also install "Block site" plugins into your browser and configure it with the stopIP list file.
You can close tabs that you aren't using.
You can keep your computer up-to-date, as well as your browser.
You can install a web server(apache2/lighttpd) on your computer with a defaut rule that is to close popup open by script, and show a close button for 404 errors.

# How do you choose the web site you are blocking ?
When I am distrubed vy an AD/spyware/badware on internet, I just take a short pause and add it to my 'hosts' file.
I don't go everywhere, so there are many things that should be blocked but aren't.


# It is obvious for AD, but how do you know that something is a spyware/virus ?
I am developer so I watch network connections, and read things that look technical for you but that are obvious for me.
Here some of my criterons :
 - Bad grammar or obvious pishing.
 - Massive redirections from a know badware site.
 - Offuscated javascript that contain AD redirection.
 - Messages send to IP/domain that do not respond.
 - Uneccessary things done.
 
# I have use your list and now my internet doesn't work, this is your fault.
This software is provide as this.
Some site use bad-tricks to check that AD show correctly, and I cut every thing that looks like an AD.
I don't want to pay by watching AD; I don't want of thoses site, you are tell.
