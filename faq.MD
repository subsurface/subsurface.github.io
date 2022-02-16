---
layout: page
title: FAQ
lang: en
permalink: /faq/
ref: faq
---

<style>
p:not(.outside) {margin: 1em 0 1em 2.5rem!important; border-bottom: 1px solid rgba(0,0,0,0.25); padding-bottom: 1rem;}
</style>

<p class="outside">This page attempts to provide answers to some of the most common questions we keep receiving.</p>

# General

### How much does Subsurface cost?
Subsurface is open source software. It's free to use (and no, we aren't looking for donations, either). It's written by a group of enthusiasts who do this in their spare time - including providing the Subsurface Cloud storage and all the other infrastructure. Please understand that this also means that they will respond to your requests when they have time, and they generally don't appreciate being treated like the support team of a commercial vendor. If you'd like a commercial dive log program, there are plenty others to choose from.
### Please add the following awesome feature
As mentioned in the previous question, Subsurface is written and maintained by volunteers. It also has several ten thousand users. The current feature set aims to find a reasonable balance between a user experience that is easy to understand, and addressing the most commonly requested features. New features often get rejected if none of the existing developers feel strongly that they would make a significant difference to the majority of our users.
### The gas consumption / SAC rate reported by Subsurface is wrong
Most likely you are expecting the gas consumption calculation to follow the naive idea gas laws. Unfortunately, real gases aren't ideal gases. And Subsurface [takes the compressibility of gases into account](https://thetheoreticaldiver.org/wordpress/index.php/2017/11/02/when-real-gas-corrections-matter/).

# OS support

## Windows
### Supported versions
Subsurface runs on Windows 10 and 11. It should still run on Windows 8 (but then, why would you want to run that). Older versions aren't supported anymore. Please look at the Windows section below for OS specific questions.
### Where do I find the log files on Windows?
The logs are in `C:\Users\Home\AppData\Roaming\Subsurface` in the two files `subsurface_out.log` and `subsurface_err.log`
### Which drivers do I need for my dive computer
Great question - typically those are specific to the combination of dive computer and download cable that you use. And it's really hard to give universally correct answers.

## macOS
### Supported versions
Subsurface runs on Intel Macs running macOS 10.13 and newer. Subsurface runs on M1 Macs in Rosettastone emulation mode. Please look at the macOS section below for OS specific questions.
### Can you make binaries available for older macOS versions?
Apple stopped supporting macOS 10.14 and older. We still support 10.13 and 10.14 - adding even older versions creates a lot of work for the developers for an increasingly small audience
### I can't download from my Bluetooth dive computer on macOS 12 / Monterey
That is a known issue; we are working on a fix, but right now the only option is to download using a mobile device / Subsurface-mobile and sync your dive log using Subsurface Cloud.
### Is there a native version of Subsurface for the Apple M1 based Macs
Several of the key libraries that Subsurface is based on have only incomplete support for M1 based Macs. We are working on a limited M1 build, but for now you are better off running the Intel binaries.

## Linux
### Supported versions
Subsurface can run on most Linux distributions. The developers actively maintain builds for current Fedora, openSUSE, and Ubuntu releases. There's also a Subsurface Snap and an AppImage. Generally try a distribution specific binary first. If that doesn't work, try the Snap or the AppImage. Please look at the Linux section below for more questions.
### Can you add binaries for my favorite Linux distribution?
Adding support for another Linux distribution is generally a lot of work and given the tiny user numbers not likely to happen. But please, talk to us if you think there is a distribution that we should add instead of the three that we currently support (Fedora, openSUSE, Ubuntu).
### Can I build my own binaries?
Yes, generally this is pretty easy (assuming you are somewhat familiar with C/C++ development under Linux). The `INSTALL` file in the source directory should get you started. Reach out to the developers if you need help beyond that (because likely that means we need to update the `INSTALL` file...)

## Android
### What's the minimum Android version required
Currently the minimum is Android 5.0 (but many old Android versions have other issues running Subsurface-mobile, e.g. issues with the SSL certificates used on our servers).
### From which dive computers can Subsurface-mobile on Android directly download?
Bluetooth and BLE based dive computers as well USB serial dive computers should generally work (assuming they are supported by Subsurface at all, of course). What doesn't work are other USB devices (like USB HID (e.g., Suunto EON Steel family), USB storage (e.g., Uemis Zurich), MTP (e.g., Garmin)).

## iOS
### From which dive computers can Subsurface-mobile on iOS directly download?
Only Bluetooth and BLE based dive computers (that are already supported in Subsurface) work with iOS devices. No cable based downloads are possible.

# Issues with specific dive computers
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
