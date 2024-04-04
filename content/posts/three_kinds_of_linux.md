---
title: "There are but three kinds of Linux."
date: 2023-09-02T12:01:00-05:00
draft: false
tags: {"Linux"}
---

*This article is meant to be a first guide to Linux, more specifically, answer the question of "which distro should I be using?", as well as explaining some of the impacts of that choice.*

So, you want to use Linux. This is what you need to get started.
The "Linux" part of Linux refers to the Linux Kernel — the part of the operating system that handles resource allocation, file system usage, hardware and software interaction, device drivers, and so much more. However, just the kernel is not enough for you to do everything you need to on your computer.
A Linux distribution is a nicely packaged operating system. It contains the Linux Kernel, but also a package management system (that lets you install and manage applications), and possibly some preinstalled apps that make your system usable. Each Linux distribution has its characteristic set of the aforementioned features.

As far as beginners are concerned, there are three kinds of Linux distributions to bother with for the desktop — Ubuntu derivatives, Fedora derivatives, and Arch derivatives.

### Ubuntu
Ubuntu, which is possibly the most famous Linux distro, is a derivative of the Debian Operating System. There are also lots of Ubuntu derivatives, which are Debian derivatives by proxy. Debian itself is not a great first desktop Linux distro, as it is updated far too infrequently and does not always have the latest features.

There are multiple versions of Ubuntu — It is updated every six months. However, one in every four releases (i.e. once every two years) is  Long-Term Support release (LTS). Ubuntu LTS is a good choice to start out with, as it has probably the most compatibility with software that wasn't initially written with Linux in mind. For example, the Steam Linux Game Client only "officially" supports the latest Ubuntu LTS release. This is not to say that Steam doesn't work on other distributions — it absolutely will on most, and there's probably someone who's already got it running. However, forum support is usually best with Ubuntu and you'll have to do less figuring out on your own.

Then there's the Ubuntu alternatives — Linux Mint, Zorin OS, Pop!\_OS, elementary OS, and so on. All of these are also great choices with their own spins on Ubuntu as a base. Mint's whole thing is being user friendly and easy to transition to from something like Windows. Zorin is also designed with newcomers in mind, and probably looks the best out of the box. Pop!\_OS touts great support and easy setup for gaming and parallel computing applications. elementary OS has simplicity and usability at the forefront.

Not all is sunshine and rainbows with Ubuntu, though. The developer of Ubuntu, Canonical Ltd., has made some controversial choices when it comes to things like the packaging format they use. They have been aggressively pushing the SNAP package management system, which is not entirely open-source and does not have the most valid reasons to exist in the first place. One of the biggest issues with the Linux community at large right now is fracturing of ideas and duplication of effort. If developers had come together and made fewer better polished ways to handle package management, for instance, then we wouldn't have little bugs and annoyances every so often. Canonical creating SNAPs and promoting them has not been conducive to the growth of the whole Linux ecosystem. Moreover, they do not support FLATPAK packages by default, which is largely agreed upon to be one of the best ways to package and use applications.

### Fedora
Fedora Linux is a Linux distribution made and managed by Red Hat, a software company that is known for Red Hat Enterprise Linux (RHEL), a very popular choice for enterprise Linux operations. Fedora strikes just the right balance between being stable and being on the cutting edge. It has the latest features that work seamlessly, and you don't need to give much more thought. Fedora just has simple numbered releases, 39 being the latest at the time of writing this article. Fedora does not have a very large derivative ecosystem, but that is because Fedora is just mostly compatible with almost everything and works great out of the box. If you are the kind of person who enjoys trying out the newest features but don't care to reinstall your system every few weeks, then Fedora is a great pick.

One of my little gripes with fedora is that the package manager, dnf, is not up to snuff. Sure, I like how it gives more information than apt out of the box, but its quite slow and annoying at times. However, there is a new version of dnf that is being worked on which will (hopefully) be a part of Fedora 40!

### Arch
Arch Linux by itself is not a good choice for beginners. Arch Linux comes with only the bare minimum, and does not even include a GUI if you don't install one yourself. However, there are some Arch derivatives that handle all that for you — some you should be looking at include Artix Linux, EndeavourOS, Garuda Linux, and Manjaro Linux.

If Arch comes with nothing but the bare minimum, why even bother with it, you might ask. There are some massive advantages to Arch and family — the Rolling Release philosophy, the Arch User Repository (AUR), and the Arch Wiki. All the applications and packages and the OS of Arch Linux itself is based on a rolling release philosophy. That is, new versions keep coming out as stable updates come out. For instance, if there was a change made to the Linux Kernel, it will probably hit Arch first. Fedora and Ubuntu will have these new versions integrated into the next release, which may be a few months to two years out. To go along with the rolling releases is the Arch User Repository (AUR). It is one of the largest collections of software and it oftentimes has some packages that are harder to find and work with on Ubuntu and Fedora. The Arch User Repository is exclusive to Arch and its derivatives.

If you're looking to tinker and learn more about how your operating system works and want to be on the bleeding edge of Linux, Arch is the choice for you. Do keep in mind that you are not stepping into the void when you make this choice. The Arch Wiki has information on nearly everything you need to know about your system. Its so good, I use it even when I'm on Ubuntu or Fedora sometimes.

### In Closing
There is a lot more to Linux than the distro you choose. If you feel like it, you could change windowing systems, init systems, desktop environments, file systems, and so much more. For a first foray into Linux, though, bother yourself with none of those. The choice comes out to Stable and Supported vs Leading edge vs Bleeding Edge. Do keep in mind that if you don't like something on Linux, no matter the distribution, you can most probably change it, and its most probably already been done before too. You really can't go wrong with any choice, so stop reading this article and get started already!