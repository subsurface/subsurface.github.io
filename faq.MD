---
layout: page
title: FAQ
lang: en
permalink: /faq/
ref: faq
faq_general:
  - title: How much does Subsurface cost?
    content: Subsurface is open source software. It's free to use (and no, we aren't looking for donations, either). It's written by a group of enthusiasts who do this in their spare time - including providing the Subsurface Cloud storage and all the other infrastructure. Please understand that this also means that they will respond to your requests when they have time, and they generally don't appreciate being treated like the support team of a commercial vendor. If you'd like a commercial dive log program, there are plenty others to choose from.
  - title: Please add the following awesome feature
    content: As mentioned in the previous question, Subsurface is written and maintained by volunteers. It also has several ten thousand users. The current feature set aims to find a reasonable balance between a user experience that is easy to understand, and addressing the most commonly requested features. New features often get rejected if none of the existing developers feel strongly that they would make a significant difference to the majority of our users.
  - title: The gas consumption / SAC rate reported by Subsurface is wrong
    content: Most likely you are expecting the gas consumption calculation to follow the naive idea gas laws. Unfortunately, real gases aren't ideal gases. And Subsurface [takes the compressibility of gases into account](https://thetheoreticaldiver.org/wordpress/index.php/2017/11/02/when-real-gas-corrections-matter/).

faq_windows:
  - title: supported versions
    content: Subsurface runs on Windows 10 and 11. It should still run on Windows 8 (but then, why would you want to run that). Older versions aren't supported anymore. Please look at the Windows section below for OS specific questions.
  - title: where do I find the log files on Windows?
    content: The logs are in `C:\Users\Home\AppData\Roaming\Subsurface` in the two files `subsurface_out.log` and `subsurface_err.log`
  - title: which drivers do I need for my dive computer
    content: great question

faq_macos:
  - title: supported versions
    content: Subsurface runs on Intel Macs running macOS 10.13 and newer. Subsurface runs on M1 Macs in Rosettastone emulation mode. Please look at the macOS section below for OS specific questions.
  - title: can you make binaries available for older macOS versions?
    content: Apple stopped supporting macOS 10.14 and older. We still support 10.13 and 10.14 - adding even older versions creates a lot of work for the developers for an increasingly small audience
  - title: I can't download from my Bluetooth dive computer on macOS 12 / Monterey
    content: that is a known issue; we are working on a fix, but right now the only option is to download using a mobile device / Subsurface-mobile and sync your dive log using Subsurface Cloud.
  - title: is there a native version of Subsurface for the Apple M1 based Macs
    content: several of the key libraries that Subsurface is based on have only incomplete support for M1 based Macs. We are working on a limited M1 build, but for now you are better off running the Intel binaries.

faq_linux:
  - title: supported versions
    content: Subsurface can run on most Linux distributions. The developers actively maintain builds for current Fedora, openSUSE, and Ubuntu releases. There's also a Subsurface Snap and an AppImage. Generally try a distribution specific binary first. If that doesn't work, try the Snap or the AppImage. Please look at the Linux section below for more questions.
  - title: can you add binaries for my favorite Linux distribution?
    content: adding support for another Linux distribution is generally a lot of work and given the tiny user numbers not likely to happen. But please, talk to us if you think there is a distribution that we should add instead of the three that we currently support (Fedora, openSUSE, Ubuntu).
  - title: can I build my own binaries?
    content: yes, generally this is pretty easy (assuming you are somewhat familiar with C/C++ development under Linux). The `INSTALL` file in the source directory should get you started. Reach out to the developers if you need help beyond that (because likely that means we need to update the `INSTALL` file...)

faq_android:
  - title: what's the minimum Android version required
    content: currently the minimum is Android 5.0 (but many old Android versions have other issues running Subsurface-mobile, e.g. issues with the SSL certificates used on our servers).
  - title: which dive computers can I directly download from when using Subsurface-mobile on Android
    content: Bluetooth and BLE based dive computers as well USB serial dive computers should generally work (assuming they are supported by Subsurface at all, of course). What doesn't work are other USB devices (like USB HID (e.g., Suunto EON Steel family), USB storage (e.g., Uemis Zurich), MTP (e.g., Garmin)).

faq_ios:
  - title: which dive computers can I directly download from when using Subsurface-mobile on iOS
    content: only Bluetooth and BLE based dive computers (that are already supported in Subsurface) work with iOS devices. No cable based downloads are possible.

faq_dc:
  - title: I get timeouts or data error when downloading
    content: astoundingly commonly the reason are wet or dirty contacts or a low battery. It doesn't matter if the dive computer turns on. Download mode often requires much higher stable voltage to work. And sadly we even have seen situations where the vendor dive log will work (because it can do a much better job at 'error correction'), but Subsurface won't download until you have a fresh battery and really clean and really dry contacts.
  - title: BLE (Bluetooth Low Energy) downloads are incredibly slow
    content: yes, yes they are. Since Subsurface supports BLE download from many different dive computers from many different vendors, the code is often not as well tuned for a specific dive computer as the vendor app can be. So unfortunately these downloads are painfully slow. Usually downloading a few dives a day is tedious, but not horrible. But especially a first download with a hundred or more dives can take an hour and longer - and sometimes it is hard to complete the download without running into errors that lead the download to abort. It really pays off to download early and often. And if the dive computer offers a way to download with a USB cable (in addition to BLE, like for example the Suunto EON Steel family), that is definitely preferable especially for that first download.
  - title: Garmin Descent
    content: The Descent dive computers are only supported on Windows, macOS, and Linux, and only for cable based download. There are no plans to support BLE downloads on any platform.
  - title: Garmin Descent - directly importing '.FIT' files
    content: If for some reason you cannot get regular input to work, but have access to the `.FIT` files, you can still use Subsurface to import (or better, download) those. Simply create a folder `...somepath.../Garmin/Activity` and copy the `.FIT` files into that folder. Now start a Subsurface download and enter `...somepath...` (without the `Garmin/Actity` part) in the Connection field and press Download.
  - title: Garmin Descent Mk2/Mk2i doesn't want to connect
    content: The Descent Mk2/Mk2i is an MTP device which causes occasional problems when trying to download from it using Subsurface. MTP supports only a single connection, so other MTP apps may prevent Subsurface from talking to your dive computer. Exit apps like the Android File Transfer.
  - title: Garmin Descent Mk2/Mk2i on Windows
    content: You need the correct USB driver in order to talk to the Descent Mk2/Mk2i:<br>- download [Zadig 2.6](https://zadig.akeo.ie/) and run it<br>- plug in the Descent and select MTP<br>- wait for Zadig to offer the Descent as an option (this may require an unplug / replug cycle)<br>- select the Descent and tell Zadig to install `libusb-win32` (wait for this to finish which takes a while)<br>- unplug the Descent and plug it back in, again selecting MTP<br>- now Subsurface is able to download from it (don't enter anything in the connection field
---


{% include accordion.html %}

Some of the most common questions we keep responding to.

<h2>General</h2>

{% include faq_item.html items=page.faq_general faq_section="general" %}

<h2>OS support</h2>

Subsurface runs on Windows, macOS, Linux, Android, and iOS.

<h3>Windows</h3>

{% include faq_item.html items=page.faq_windows faq_section="windows" %}

<h3>macOS</h3>

{% include faq_item.html items=page.faq_macos faq_section="macos" %}

<h3>Linux</h3>

{% include faq_item.html items=page.faq_linux faq_section="linux" %}

<h3>Android</h3>

{% include faq_item.html items=page.faq_android faq_section="android" %}

<h3>iOS</h3>

{% include faq_item.html items=page.faq_ios faq_section="ios" %}

<h2>Issues with downloads from dive computers</h2>

{% include faq_item.html items=page.faq_dc faq_section="dc" %}

<h2>Other questions</h2>

If your question wasn't answered here, please check the [User Forum](https://subsurface-divelog.org/user-forum/) (try the search function) and if you don't find an answer there, create a new topic and ask for help.

This FAQ is maintained on [GitHub](https://github.com/subsurface/subsurface.github.io) -- pull requests welcome.
