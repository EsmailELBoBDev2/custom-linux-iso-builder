# WORKING...
<!--
# CUSTOM LINUX ISO BUILDER

## Backstory
A couple of days ago, a client on freelancer.com (*feel free to hire me btw:* ***https://www.freelancer.com/u/esmailelbobdev2***) asked me to create a bash script about "preseeding" Linux, and I was like what the heck is that and after looking into it, I liked the idea and started to learn more about it. 

***NOTE***: This bash script is different from the one I sent to my client. to avoid license conflict.

## Tested on
* Linux mint 21
* Zorin OS 16.1
* Debian 11
* Ubuntu 22.04.1

## SUPPORTED DISTROs
* Linux mint (*working on it*)
* Zorin OS (*working on it*)
* Debian (*working on it*)
* Ubuntu (*working on it*)
* More? Open reuqest and I will look into it.

## HOW TO USE & HOW IT WORKS
***->*** **How it works**:
* *Linux mint*: for linux mint, they already support preseeding and it's in their grub so the file get loaded, my script in linux mint's case is just appending your own custom preseed to linux mint preseed file.
* *Zorin os*: God, no. Zorin used to support preseeding the past, just like linux mint. but now it's not so my script first creates new folder called "preseed" then create new file called "preseed.seed" and appen your custom config into it and then adds the file to it's grub so it can be loaded in the livecd.
* *Debian & Ubuntu*: did not work on them yet as I'm fine tuning the script for now and I'm little busy.

***->*** **How to use it**:

Download the script alone or git clone the whole repo and then run the script and follow the questions to select which distro and it's verison. The distro will be downloaded to your `Downloads` folder (*will create one if it does not exist*) and unpack the ISO then edit needed files and repack the iso and will drop it again in your Downloads folder.

***NOTE***: Open the script and follow the comments to change the preseed config to make it fit your needs (*later will make whole different preseed file to make things clean*). This is a good place to start and learn more about the syntax: https://www.debian.org/releases/buster/example-preseed.txt

## FAQs
* Why "CUSTOM LINUX ISO BUILDER" name?

Because I do not know how to name things.
* What is "Preseed"

If you came to me a week ago and told me what is "preseed" I would be confused as you are. But preseed is more like auto-install script for debian-based distros (*unsure if it applies to other distros too, still learning*) and it's simply more like load the file in LiveCD than hit next and that loaded file or preseed will put your settings, so you simply hit next.

* Why this script?

Look, if you are going to ask questions like these, we better to break up.

* Can I submit PRs?

Sure! if you want a request and do not know how to code, open an issue or if you know how to code then open PR.

* How to say thanks?

Say "Thank you" out loud and I will hear it :smile:
-->
