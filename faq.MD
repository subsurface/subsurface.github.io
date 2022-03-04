---
layout: page
title: FAQ
lang: en
permalink: /faq/
ref: faq
---

<style>
p:not(.outside) {margin: 1em 0 1em 2.5rem!important; border-bottom: 1px solid rgba(0,0,0,0.25); padding-bottom: 1rem;}
p.noline,blockquote p {border-bottom: 0px!important; padding-bottom: 0px!important;}
</style>

<p class="outside">This page attempts to provide answers to some of the most common questions we keep receiving.</p>

# General

### Why Should I Use Subsurface?

Subsurface provides recreational scuba divers, tech divers, and diving professionals with an easy to use interface for planning and logging and organizing dives. Dives can be entered manually, via spreadsheets, directly from some other dive logging software, and most importantly from many dive computers. What if you change dive computers? This is no problem with Subsurface as it is not tied to a specific dive computer manufacturer. Tech divers will appreciate the dive planner which allows you to plan using VPM-B or Bühlmann ZH-L16. Testing bailout gases, comparing different gas mixes and gradient factors, and finally printing the plan is made easy. Subsurface is free and available on multiple platforms making it the perfect software for a wide range of scuba divers.

### What operating systems does Subsurface support?

Subsurface runs on Windows (32 and 64bit, Windows 10 and newer), MacOS (Intel, 10.13 and newer) and many flavors of Linux. Mobile versions of Subsurface are available for Android and iOS allow a portable platform for viewing your dive log and performing minor edits.

We provide Linux packages for Ubuntu, Linux Mint, Debian, openSUSE and Fedora. A Snap package and a generic AppImage is available for other distributions of Linux. Details on where to find Subsurface for your OS are on our [Downloads](https://subsurface-divelog.org/download/) page.

Subsurface-mobile is available on Google Play and the iTunes App Store.

### How much does Subsurface cost?

Subsurface is open source software. It's free to use (and no, we aren't looking for donations, either). It's written by a group of enthusiasts who do this in their spare time - including providing the Subsurface Cloud storage and all the other infrastructure. Please understand that this also means that they will respond to your requests when they have time, and they generally don't appreciate being treated like the support team of a commercial vendor. If you'd like a commercial dive log program, there are plenty others to choose from.

### Please add the following awesome feature

As mentioned in the previous question, Subsurface is written and maintained by volunteers. It also has several ten thousand users. The current feature set aims to find a reasonable balance between a user experience that is easy to understand, and addressing the most commonly requested features. New features often get rejected if none of the existing developers feel strongly that they would make a significant difference to the majority of our users.

### The gas consumption / SAC rate reported by Subsurface is wrong

Most likely you are expecting the gas consumption calculation to follow the naive idea gas laws. Unfortunately, real gases aren't ideal gases. And Subsurface [takes the compressibility of gases into account](https://thetheoreticaldiver.org/wordpress/index.php/2017/11/02/when-real-gas-corrections-matter/).

# OS support

## Windows

### How do I install Subsurface on Windows?
[Download the installer](https://subsurface-divelog.org/download/) and double-click on it. You will get a warning that the installer is from an unknown publisher (but should identify that publisher as Dirk Hohndel). Please click Yes to allow installation. Next you are presented with the license for Subsurface, after that you can choose where you would like to install Subsurface (the default should be reasonable in most cases) and the Start Menu Folder where a shortcut to call Subsurface and an entry to uninstall Subsurface will be installed.

### Supported versions

Subsurface runs on Windows 10 and newer. It should still run on Windows 8 (but then, why would you want to run that). Older versions aren't supported anymore.

### Where do I find the log files on Windows?

The logs are in `C:\Users\Home\AppData\Roaming\Subsurface` in the two files `subsurface_out.log` and `subsurface_err.log`

### Which drivers do I need for my dive computer

Great question - typically those are specific to the combination of dive computer and download cable that you use. And it's really hard to give universally correct answers.

### Is there a virus in the Subsurface installer?

If you get a warning message or if Subsurface is blocked by your anti virus (AV) software, that is almost certainly a false positive. Subsurface is not built on a Windows machine, it is cross built from source on Linux on a well maintained and clean server.
<br /> <!-- adding an empty line in the .MD file creates a new paragraph which in turn creates a separator line when rendered -->
Most/all Windows Anti-Virus software packages support an “add exception” feature, which skips an executable from being scanned. Try adding Subsurface to the list of non-harmful software. If the Subsurface installer download is detected as malware, please temporary disable your AV software until Subsurface is installed
<br />
In either case, please inform your AV software vendor of a “false positive” as we assure your that Subsurface is not malware.

### Subsurface suddenly stops accessing the cloud

This can have many reasons, but a really odd one we have found is that some anti-malware products on Windows seemingly randomly decide that the traffic between Subsurface and the cloud server is an indication of malware activity and interrupt the transmissions. This can lead to cloud storage corruption and prevents things from working. You may have to add an exception for Subsurface to your hyper-aggressive anti-malware tool.

## macOS

### How do I install Subsurface on MacOS?

[Download the installer](https://subsurface-divelog.org/download/) DMG and open it. Drag the Subsurface icon on to the Applications icon.

### Supported versions

Subsurface runs on Intel Macs running macOS 10.13 and newer. Subsurface runs on M1 Macs in Rosettastone emulation mode.

### Can you make binaries available for older macOS versions?

Apple stopped supporting macOS 10.14 and older. We still support 10.13 and 10.14 - adding even older versions creates a lot of work for the developers for an increasingly small audience.

### I can't download from my Bluetooth dive computer on macOS 12 / Monterey

That is a known issue; we are working on a fix, but right now the only option is to download using a mobile device / Subsurface-mobile and sync your dive log using Subsurface Cloud.

### Is there a native version of Subsurface for the Apple M1 based Macs

Several of the key libraries that Subsurface is based on have only incomplete support for M1 based Macs. We are working on a limited M1 build, but for now you are better off running the Intel binaries.

### Why is my IRDA (infrared) based dive computer not working on a Mac?

Subsurface on the Mac does not currently support IRDA based dive computers. This is an issue of missing support libraries for us to use -- other dive log software may have implemented their own IRDA stack on the Mac, we have not. Subsurface on Windows and Linux does support IRDA based dive computers just fine.

## Linux

### Supported versions

Subsurface can run on most Linux distributions. The developers actively maintain builds for current Ubuntu, Linux Mint, Debian, openSUSE and Fedora releases. There's also a Subsurface Snap and an AppImage for other distributions. Generally try a distribution specific binary first. If that doesn't work, try the Snap or the AppImage.

### Can you add binaries for my favorite Linux distribution?

Adding support for another Linux distribution is generally a lot of work and given the tiny user numbers not likely to happen. But please, talk to us if you think there is a distribution that we should add instead of the ones that we currently support.

### Can I build my own binaries?

Yes, generally this is pretty easy (assuming you are somewhat familiar with C/C++ development under Linux). The `INSTALL` file in the source directory should get you started. Reach out to the developers if you need help beyond that (because likely that means we need to update the `INSTALL` file...).

# Mobile support

### How do I install Subsurface-mobile on my phone / tablet?
For Android and iOS you can simply install the Subsurface-mobile apps that are available in the respective app stores. Enable cloud storage in Subsurface from your PC and store your dive information in the Subsurface cloud. The dives will now be available on your mobile device as well. Subsurface-mobile does not support all the features of the desktop version Subsurface. For example dive planning is not available in Subsurface-mobile. Dives cannot be downloaded directly from dive computers into Subsurface-mobile, however dives can be manually added to your dive log.

From all other devices (including tablets and phones with OSs that we don’t support with Subsurface-mobile), you can open our [cloud website](https://cloud.subsurface-divelog.org/) and log in with the same email address / password. This allows you to access your dive data from any device with a web browser.

## Android

### What's the minimum Android version required

Currently the minimum is Android 5.0 (but many old Android versions have other issues running Subsurface-mobile, e.g. issues with the SSL certificates used on our servers).

### From which dive computers can Subsurface-mobile on Android directly download?

Bluetooth and BLE based dive computers as well USB serial dive computers should generally work (assuming they are supported by Subsurface at all, of course). What doesn't work are other USB devices (like USB HID (e.g., Suunto EON Steel family), USB storage (e.g., Uemis Zurich), MTP (e.g., Garmin)).


## iOS

### From which dive computers can Subsurface-mobile on iOS directly download?
Only Bluetooth and BLE based dive computers (that are already supported in Subsurface) work with iOS devices. No cable based downloads are possible.

# Usage

### How do I know I have the latest version of Subsurface?

From the Help menu, select “Check for updates”.
Also refer to the [News](https://subsurface-divelog.org/category/news/) section on the Subsurface website for announcements about new releases.

### How can I import my dives into Subsurface?
<p class="noline">There are multiple ways to import into Subsurface. From the User Manual,</p>
<p class="noline">For manually logged dives:</p>
> To add a dive to a dive log, select Log → Add Dive from the Main Menu. The program then shows three panels on which to enter information for a dive: two tabs in the Info panel (Notes and Equipment), as well as the Dive Profile panel that displays a graphical profile of each dive.

<p class="noline">To import from a dive computer:</p>
> A dive computer can be hooked up to the user’s PC using these steps:
> - The interface cable should be connected to a free USB port (or the Infra-red or Bluetooth connection set up as described later in this manual).
> </br>
> - The dive computer should be placed into PC Communication mode. (Refer to the manual of the specific dive computer).
> </br>
> - In Subsurface, from the Main Menu, select Import → Import From Dive Computer.

Then, follow the prompts to select your particular dive computer. More detailed information can be found in the User Manual.
<br />
There is also the possiblity of adding dives from other software or websites. See the User Manual for the most up to date information on this – it can be found in Section 5.3.

### How can I use more than one tank with the same gas?

This is a typical question for side mount divers or some tec divers. Subsurface supports having more than one tank with the same gas, even if some dive computers don’t. Simply add a gas change to your second tank of the same gas as both tanks will be included in the gas use calculations. In order to add gas changes simply right-click on the profile at the appropriate spot and you will be offered to add such an event.

### Why is Subsurface not able to download my dives from my dive computer?

Clean the contacts. Clean the contacts again. Make sure the connector is firmly connected. Wiggle it. Seriously. Make sure the dive computer is in transfer mode (this isn’t necessary for all dive computers but for many common ones). Check with other software that the download works in general. Try another cable. See our user manual for pairing with BT (BlueTooth) and the general use case.

### Why is the CSV import failing?

The CSV import has a couple of caveats. You should avoid some special characters like ampersand (&), less than (<), greater than (>) and double quotes (“), the latter if quoting text cells. The file should use UTF-8 character set, if having non-ASCII characters. Also the size of the CSV file might cause problems. Importing 100 dives at a time (without dive profile) has worked previously, but larger files might exceed limits of the parser used. When having problems with CSV imports, try first with a smaller sample to make sure everything works.

### How can I use Subsurface for multiple users?

Potentially the best way to acheive this is to use multiple user accounts on the computer, all operating systems have built-in support for multiple users. This was the Subsurface configuration for each user is truely separated.
<br />
Potentially the easiest way to acheive this is to store logs of different users to separate log files. From Subsurface, you can open individual files for different divers and multiple users are supported quite well, the downside of this approach is that it's incompatible with Subsurface cloud storage.
<br />
A blend of these approaches where you want multi-user Subsurface support within a single computer user account then Subsurface has the ability to do this too, simply launch Subsurface with the *--user* flag e.g. *subsurface --user=joebloggs*. From this user-specific workspace you can then open either locally stored or cloud hosted dive logs.

### How can I load pictures and associate them with my dive?

Select the dives you want to load and associate the pictures with. Then right click on one of the selected dives and select “Load images” from the popup menu. This will bring in a file selection dialog where you can select one or multiple pictures. When the selection is done and you hit Open, you get a new dialog where you can shift the times of the images. This is described in more detail in our user manual.
<br />
If you are having trouble with loading the images, check that you have at least one of the following tags in the Exif headers DateTimeOriginal or DateTime. We take the time from these fields to detect if the image was shot during the dive or not. If the picture is edited, you should store the original Exif information on the new/edited image for it to be loaded properly.

### Can I import my dives from my old log software?

Many common programs are already supported and we are always happy to try to add new ones. If your old log software supports exporting the log book, we might well be able to import that (for example via CSV files or UDDF). However, usually support for importing the native format will help you to get more complete information into Subsurface. To implement support for the log format, we will need a sample log file. It would be great to have also a screenshot from the original log software or description of the dive that is shown on the sample log. Preferably we would like to have a reasonably simple dive to get basic support and another dive that has as many features enabled as possible (e.g. gas changes during the dive). Please post this information to the user forum or send it to the developer mailing list subsurface@subsurface-divelog.org. Unfortunately some of the log formats we have not been able to decipher (as some vendors have decided to encrypt their log files to increase the degree of lock-in of their customers), so there are no guarantees that this will bring support for your old log software, but it is worth a try.

### How do I download dives from my Bluetooth dive computer (e.g., Shearwater, OSTC)?

Downloading dives over Bluetooth on all platforms is done using the “Choose Bluetooth download mode” option when downloading dives, and pairing with the detected dive computer. This is further explained in the [Subsurface User Manual](https://subsurface-divelog.org/documentation/subsurface-4-user-manual/).
<br />
Previous versions of Subsurface required setting up an RFCOMM connection from the command line before downloading dives from a Bluetooth enabled dive computer. This is no longer the case.

### How do I download dives from my Bluetooth LowEnergy, BLE, Bluetooth Smart dive computer (e.g., Shearwater Perdix AI, Shearwater Perdix (latest models), Suunto EON Steel)?

At this point (February 2022, Subsurface 5.0.6 / Subsurface-mobile 3.4.1) the current release versions of Subsurface and Subsurface-mobile support connecting to dive computers over BLE on all supported platforms with the exception of macOS 12. We have seen reports where AppImages on Linux fail to connect to local BT/BLE devices, but native packages on Linux work.

### I cannot download all my dives, only the most recent ones even though my dive computer's manual states that it records history of e.g. 999 dives.

Dive history is different than the dive profiles on the log. The history only keeps track of the total number of dives and total amount of time spent below surface. The logs, on the other hand, store the dive profile, but they have limited amount of memory to do so. The exact amount of dive profiles that can be stored on the device depend on sample interval and duration of the dives. Once the memory is full the oldest dives get overwritten with new dives. Thus we are only able to download the last 13, 30 or 199 dives.
<br />
If you have downloaded your dives to different dive logging software before they were overwritten, there is a high chance that Subsurface can import these. However, if the logs are only on your dive computer, they cannot be salvaged after being over written by new dives.

### What to do when authentication to cloud storage fails?

If you have configured your correct user credentials to Subsurface and cloud authentication still fails, try to change the password on Subsurface preferences. There has been a change in the cloud service that can cause an error on sync, but password change with correct credentials fixes the issue.
<br />
If your credentials are still not working or there is something else wrong, contact Dirk to sort it out.

### Can Subsurface store my files on a different cloud server?

Subsurface can store your dive log securely on the Cloud, backing up your data, allowing you to view your dive logs on a desktop, Android and iOS apps. There is only one cloud server available (https://cloud.subsurface-divelog.org) allowing the developers the ability to enhance Subsurface, fix issues, and support users (with your permission) if something goes wrong with the CloudServer. This becomes unmanageable if multiple cloud servers are supported.
<br />
If you wish to backup your log on a remote storage server, the documention describes how to store your data on DropBox or other similar services such as TeamDrive, MiniBox,etc.

### How can I clear my settings

Sometimes your settings may end up being messed up or corrupted. That should be quite rare, but when it happens there are two approaches to fixing the problem.
<br />
One, if you can still run Subsurface, open the preferences, pick 'Reset' at the very bottom of the left pane and click that button.
<br />
If that doesn't work it gets more complicated and things become OS dependent.
<br />
On Windows you need to delete the Subsurface Registry keys.
<br />
On macOS you need to delete `~/Library/Preferences/org.hohndel.subsurface.Subsurface.plist`  (the fact that this includes the name `hohndel` is the result of an unforunate early decision made ages ago that is rather hard to undo without breaking stuff).
<br />
On Linux it depends on a number of factors where the settings are, but usually it's `~/.config/Subsurface/Subsurface.conf`
<br />
Oh, and all of these names changes if you are using the `--user=...` feature to have different settings for different users.

# Issues with specific dive computers

### Can you add support for dive computer X?

We support a large number of dive computers already and are always happy to add support for more. Please contact us via the user forums so we can try to help. Some vendors have actively helped us in our work and adding support for new models from those vendors is usually easy. Other vendors are more neutral, some are actively hostile. Without help from the vendor it can be rather challenging to reverse engineer the transfer protocol and the dive encoding, but with sufficient help from you it is often possible to do so.
<br />
A good starting point is often to send us a libdivecomputer log and dump (you can pick those in the dive computer download dialog) when connecting to the dive computer using a similar existing model (if possible).

### Old style Suunto dive computers

Most of the download cables are FTDI based and need the appropriate drivers installed. Some other third party cables need different drivers. Without those drivers, the dive computer device won't show up. Once you can see the device (`COMn` or `/dev/tty...`), if you get timeouts or data errors, see the <a href="#i-get-timeouts-or-data-error-when-downloading">data error question</a>.

### I get timeouts or data error when downloading

Astoundingly commonly the reason are wet or dirty contacts or a low battery. It doesn't matter if the dive computer turns on. Download mode often requires much higher stable voltage to work. And sadly we even have seen situations where the vendor dive log will work (because it can do a much better job at 'error correction'), but Subsurface won't download until you have a fresh battery and really clean and really dry contacts.

### BLE (Bluetooth Low Energy) downloads are incredibly slow

Yes, yes they are. Since Subsurface supports BLE download from many different dive computers from many different vendors, the code is often not as well tuned for a specific dive computer as the vendor app can be. So unfortunately these downloads are painfully slow. Usually downloading a few dives a day is tedious, but not horrible. But especially a first download with a hundred or more dives can take an hour and longer - and sometimes it is hard to complete the download without running into errors that lead the download to abort. It really pays off to download early and often. And if the dive computer offers a way to download with a USB cable (in addition to BLE, like for example the Suunto EON Steel family), that is definitely preferable especially for that first download.

## Garmin Descent

### Does Subsurface-mobile support the Garmin Descent?

The Descent dive computers are only supported on Windows, macOS, and Linux, and only for cable based download. There are no plans to support BLE downloads on any platform.

### Can I import '.FIT' files directly?

If for some reason you cannot get regular input to work, but have access to the `.FIT` files, you can still use Subsurface to import (or better, download) those. Simply create a folder `...somepath.../Garmin/Activity` and copy the `.FIT` files into that folder. Now start a Subsurface download and enter `...somepath...` (without the `Garmin/Actity` part) in the Connection field and press Download.

### Garmin Descent Mk2/Mk2i doesn't want to connect

The Descent Mk2/Mk2i is an MTP device which causes occasional problems when trying to download from it using Subsurface. MTP supports only a single connection, so other MTP apps may prevent Subsurface from talking to your dive computer. Exit apps like the Android File Transfer.

### Garmin Descent Mk2/Mk2i on Windows

You need the correct USB driver in order to talk to the Descent Mk2/Mk2i:<br>- download [Zadig 2.6](https://zadig.akeo.ie/) and run it<br>- plug in the Descent and select MTP<br>- wait for Zadig to offer the Descent as an option (this may require an unplug / replug cycle)<br>- select the Descent and tell Zadig to install `libusb-win32` (wait for this to finish which takes a while)<br>- unplug the Descent and plug it back in, again selecting MTP<br>- now Subsurface is able to download from it (don't enter anything in the connection field

# Other questions

If your question wasn't answered here, please check the [User Forum](https://subsurface-divelog.org/user-forum/) (try the search function) and if you don't find an answer there, create a new topic and ask for help.

<p class="outside"> This FAQ is maintained on [GitHub](https://github.com/subsurface/subsurface.github.io) -- pull requests welcome.  <p>

***
