# Trojan Horse Attacks

If you were referred here, you may have been "hacked" by a Trojan horse
attack. It's crucial that you read this page and fix yourself immediately.
Failure to do so could result in being disconnected from the IRC network,
letting strangers access your private files, or worst yet, allowing your
computer to be hijacked and used in criminal attacks on others.

by [Joseph Lo](http://bishop.mc.duke.edu/%7Ejyl) aka Jolo, with much help from
countless others

This page is part of IRChelp.org's security section at [http://www.irchelp.org
/irchelp/security/](http://www.irchelp.org/irchelp/security/)

updated Feb 5, 2006

**Contents:**

  * I. What is a Trojan horse?
  * II. How did I get infected?
  * III. How do I avoid getting infected in the future?
  * IV. How do I get rid of trojans?!?
  * Appendices

* * *

## I. What is a Trojan horse?

Trojan horse attacks pose one of the most serious threats to computer
security. If you were referred here, you may have not only been attacked but
may also be attacking others unknowingly. This page will teach you how to
avoid falling prey to them, and how to repair the damage if you already did.
According to [legend](http://www.royalty.nu/legends/Troy.html), the Greeks won
the Trojan war by hiding in a huge, hollow wooden horse to sneak into the
fortified city of Troy. In today's computer world, a Trojan horse is
[defined](http://foldoc.doc.ic.ac.uk/foldoc/contents/security.html) as a
"malicious, security-breaking program that is disguised as something benign".
For example, you download what appears to be a movie or music file, but when
you click on it, you unleash a dangerous program that erases your disk, sends
your credit card numbers and passwords to a stranger, or lets that stranger
hijack your computer to commit illegal [denial of service](/irchelp/nuke/)
attacks like those that have virtually crippled the DALnet IRC network for
months on end.

The following general information applies to all operating systems, but by far
most of the damage is done to/with Windows users due to its vast popularity
and many weaknesses.

(Note: Many people use terms like Trojan horse, virus, worm, hacking and
cracking all interchangeably, but they really don't mean the same thing. If
you're curious, here's a quick [primer](trojanterms.html) defining and
distinguishing them. Let's just say that once you are "infected", trojans are
just as dangerous as viruses and can spread to hurt others just as easily!)

## II. How did I get infected?

Trojans are executable programs, which means that when you open the file, it
will perform some action(s). In Windows, executable programs have file
extensions like "exe", "vbs", "com", "bat", etc. Some actual trojan filenames
include: "dmsetup.exe" and "LOVE-LETTER-FOR-YOU.TXT.vbs" (when there are
multiple extensions, only the last one counts, be sure to [unhide your
extensions](trojanext.html) so that you see it). More information on risky
file extensions may be found at this [Microsoft
document](http://support.microsoft.com/support/kb/articles/q262/6/31.asp?LN
=EN-US&SD=gn&FR=0).

Trojans can be spread in the guise of literally ANYTHING people find
desirable, such as a free game, movie, song, etc. Victims typically downloaded
the trojan from a WWW or FTP archive, got it via [peer-to-peer file
exchange](warez.html) using IRC/instant messaging/Kazaa etc., or just
carelessly opened some email attachment. Trojans usually do their damage
silently. The first sign of trouble is often when others tell you that you are
attacking them or trying to infect them!

## III. How do I avoid getting infected in the future?

**You must be certain of BOTH the source AND content of each file you download!** In other words, you need to be sure that you trust not only the person or file server that gave you the file, but also the contents of the file itself. 

Here are some practical tips to avoid getting infected (again). For more
general security information, please see our main [security help
page](index.html).

  1. **NEVER download blindly from people or sites which you aren't 100% sure about.** In other words, as the old saying goes, don't accept candy from strangers. If you do a lot of [file downloading](warez.html), it's often just a matter of time before you fall victim to a trojan. 
  2. **Even if the file comes from a friend, you still must be sure what the file is before opening it**, because many trojans will automatically try to spread themselves to friends in an email address book or on an IRC channel. There is seldom reason for a friend to send you a file that you didn't ask for. When in doubt, ask them first, and scan the attachment with a fully updated anti-virus program. 
  3. **Beware of hidden file extensions!** Windows by default hides the last extension of a file, so that innocuous-looking "susie.jpg" might really be "susie.jpg.exe" - an executable trojan! To reduce the chances of being tricked, [unhide those pesky extensions](trojanext.html). 
  4. **NEVER use features in your programs that automatically get or preview files.** Those features may seem convenient, but they let anybody send you anything which is extremely reckless. For example, never turn on "auto DCC get" in mIRC, instead ALWAYS screen every single file you get manually. Likewise, disable the preview mode in Outlook and other email programs. 
  5. **Never blindly type commands that others tell you to type, or go to web addresses mentioned by strangers, or run pre-fabricated programs or scripts** (not even popular ones). If you do so, you are potentially trusting a stranger with control over your computer, which can lead to trojan infection or other serious harm. 
  6. **Don't be lulled into a false sense of security just because you run anti-virus programs**. Those do **not** protect perfectly against many viruses and trojans, even when fully up to date. Anti-virus programs should not be your front line of security, but instead they serve as a backup in case something sneaks onto your computer. 
  7. Finally, don't download an executable program just to "check it out" - if it's a trojan, the first time you run it, you're already infected! 

## IV. How do I get rid of trojans?!?

Here are your many options, none of them are perfect. I strongly suggest you
read through all of them before rushing out and trying to run some program
blindly. Remember - that's how you got in this trouble in the first place.
Good luck!

  1. **Clean Re-installation**: Although arduous, this will always be the only sure way to eradicate a trojan or virus. Back up your entire hard disk, reformat the disk, re-install the operating system and all your applications from original CDs, and finally, if you're certain they are not infected, restore your user files from the backup. If you are not up to the task, you can pay for a professional repair service to do it. 
  2. **Anti-Virus Software**: _Some_ of these can handle _most_ of the well known trojans, but _none_ are perfect, no matter what their advertising claims. You absolutely MUST make sure you have the very latest update files for your programs, or else they will miss the latest trojans. Compared to traditional viruses, today's trojans evolve much quicker and come in many seemingly innocuous forms, so anti-virus software is always going to be playing catch up. Also, if they fail to find every trojan, anti-virus software can give you a false sense of security, such that you go about your business not realizing that you are still dangerously compromised. There are many products to choose from, but the following are generally effective: [AVP](http://www.kaspersky.com/products.html), [PC-cillin](http://www.antivirus.com/pc-cillin/), and [McAfee VirusScan](http://www.mcafee.com/). All are available for immediate downloading typically with a 30 day free trial. For a more complete review of all major anti-virus programs, including specific configuration suggestions for each, see the HackFix Project's [anti-virus software page](http://www.hackfix.org/software/antivirus.html) [all are ext. links]. When you are done, make sure you've updated Windows with all [security patches](http://windowsupdate.microsoft.com) [ext. link]. 
  3. **Anti-Trojan Programs**: These programs are the most effective against trojan horse attacks, because they specialize in trojans instead of general viruses. A popular choice is [The Cleaner](http://www.moosoft.com/products/cleaner/download/), $30 commercial software with a 30 day free trial. To use it effectively, you **must** follow hackfix.org's [configuration suggestions](http://www.hackfix.org/software/configure/cleaner.html) [ext. link]. When you are done, make sure you've updated Windows with all [security patches](http://windowsupdate.microsoft.com) [ext. link], then change all your passwords because they may have been seen by every "hacker" in the world. 
  4. **IRC Help Channels**: If you're the type that needs some hand-holding, you can find trojan/virus removal help on IRC itself, such as EFnet #dmsetup or DALnet #NoHack. These experts will try to figure out which trojan(s) you have and offer you advice on how to fix it. The previous directions were in fact adapted from advice given by EFnet #dmsetup. (See our [networks page](/irchelp/networks) if you need help connecting to those networks.) 

## Appendices:

These files were referred to in the text above, and provide additional
information.

  * [IRChelp.org Security Page](index.html)
  * [Hacker / Cracker / Trojan / Virus? - A Primer on Terminology](trojanterms.html)
  * [How to unhide Windows file extensions](trojanext.html)

* * *

![-navigational bar-](/irchelp/Pix/ihnavbar.gif)

[ [go back](/irchelp/) | [search](/irchelp/search_engine.cgi) |
[help](/irchelp/help.html) | [send email](/irchelp/mail.cgi) ]

[all pages (C) IRCHELP.ORG or original authors](/irchelp/credit.html)
