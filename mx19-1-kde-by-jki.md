---
# This page uses Hydejack's `about` layout, which shows the primary author's picture and about text at the top.
# You can change it to the regular `page` layout if you want.
layout: about

# The title of the page.
title: MX Linux 19.1 with KDE Plasma Desktop

date: "2020-03-14"

# Write a short (~150 characters) description of each blog post.
# This description is used to preview the page on search engines, social media, etc.
description: >
  ***`'Just-Kiss-It'`*** Presents **MX Linux 19.1**; sporting the **KDE Plasma 5.14.5 Desktop** experience! Just a Personal Respin, made with love for **MX Linux** & **KDE Plasma**.

# You can show the description on the page by deleting this line:
# hide_description: true

# TODO
image: /assets/img/blog/MX-19-1-KDE-by-JKI-icon.png
---

#### ***`'Just-Kiss-It'`***, and his sometimes obvious unprofessionalism, are in no way associated with the good folks over at [https://mxlinux.org](https://mxlinux.org). I'm just a guy who happens to enjoy running the KDE Plasma Desktop with MX Linux, has some experience doing so, both on Live USBs with Persistence enabled, and installed on various hardware (some of it quite ancient); and **I feel I have something worth offering to the community.** If anyone finds it useful, cool. I'm just a skinny poor old giraffe with bad manners, a penchant for free speech and a seeming inability to conform enough to develop social skills; who likes to tinker and play with Desktop Operating Systems. I'm not a developer, and I probably can't help you.

{% include green.html %} I've provided written documentation with the **`.ISO`** showing what I did, and there is more information at the **Download** Location:

## [https://sourceforge.net/projects/mx-19-1-kde-by-jki/](https://sourceforge.net/projects/mx-19-1-kde-by-jki/)

[![Download mx-19-1-kde-by-jki](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/mx-19-1-kde-by-jki/files/latest/download)

![MX-19-1-KDE-by-JKI-icon.png](/assets/img/blog/MX-19-1-KDE-by-JKI-icon.png)

### I started a [thread on the **MX Linux Forum**](https://forum.mxlinux.org/viewtopic.php?f=127&t=56880&sid=14880020bfc46c7c078d73b538c24e21) about it, but don't want to fill up their Forum with questions about my Personal Respin.

I tried to lead any potential questioners to the NSFW site [8kun.top/freedomzine/](https://8kun.top/freedomzine/res/1418.html) for any discussion, because I have moderation powers there, and I have my machines set up so I don't see ads, so I sometimes forget that they advertise sex toys and other NSFW type stuff on there. But I did get a reminder!

![2020-03-18-truedat.png](https://i.imgur.com/ccqN0tP.png)

### I was just trying to keep the *riffraff* off the Forum!

Anyway, I didn't think about the fact that they might not want a link to a NSFW site on their forum, so I went in and edited that. But yeah, if you can handle possibly seeing a sex toy advertisement at the top or bottom of the page, [that thread on **>>>/freedomzine/**](https://8kun.top/freedomzine/res/1418.html) is a good place for questions and comments:

#### [https://8kun.top/freedomzine/res/1418.html](https://8kun.top/freedomzine/res/1418.html)

-----

#### Now, I'm just gonna repeat a little from my [README on Sourceforge](https://sourceforge.net/projects/mx-19-1-kde-by-jki/files/) here:

*(you can go [there](https://sourceforge.net/projects/mx-19-1-kde-by-jki/files/) to read the rest!)*

All I did was downloaded the **Feb 15, 2020 MX-19.1_x64 ISO**, updated, upgraded, installed the **KDE Plasma Desktop**, booted into that and carefully purged the XFCE cruft using `Aptitude` and `Synaptic`. Anyone could do it, but satisfactory results are difficult to achieve. I've had varying levels of success with marrying MX Linux & Plasma over several years, and this is the best Respin I've tried, and I have tried many.

I've used it live on a USB, installed it on several older machines & VirtualBox.

It runs great!

Recommending at least 4 GB RAM, 8GB is better. It IS KDE Plasma, after all!)
(Use 3D Acceleration & VMSVGA Settings in VirtualBox)

Yeah, it's a Personal Respin with Persistence.

### **Passwords:**

root: **URrootNAO**

demo: **URdemoNAO**

Remaster Your Own General Respin or I'll Post More `.ISO`s if there's a demand. I did make a General Respin also, and made snapshots of both at xz compression too, making them only a little over 2 GB, but my time is limited right now.

#### I also plan on making a short demonstration video about this Respin on my LBRY site real soon...  [https://lbry.tv/@Just-Kiss-It:2](https://lbry.tv/@Just-Kiss-It:2) so keep an eye out!

I hope some folks find this useful. You can all thank Adrian for starting me down this path several years ago.

Suffice it to say, **THIS RESPIN WORKS!**  (and yes, the `live-usb-maker` works fine too, that I mentioned I was worried about from the MX-18 days.) I have actually found nothing that doesn't work in this respin, and I have tested it extensively, and installed it on several machines; really old ones too.

-----

## WHAT I *DUN* SINCE!
#### 2020-03-29

I've had the chance to use this on a USB and install this on a couple machines just in the last couple weeks. Here are some of the things I did and my thoughts:

- **Upgrades...**
> There have been quite a few from MX in the last couple weeks, but no kernel upgrades or anything!

- **I installed this on an SSD -- SUPER FAST Install!**

    `sudo minstall` is your friend. Sorry I forgot to make a Desktop Install Icon!
> The **ntp server** was messed up, so it wouldn't immediately update. . I made the following command and fixed it:

    `sudo ntpdate -u us.pool.ntp.org`

 > but you can obviously use any ntp server you desire if you run into the same problem.

- **Ran a trim command for the `root` partition:**

    `sudo fstrim -v /`

    **and again for `/home`:**

    `sudo fstrim -v /home`

- **Checked for `noatime` in `fstab`.**
> Yup. The MX folks know what they're doing, and this distro supports **trim**. Just make sure your SSD does. It looks like it's set up to auto-trim once a week. If you want it set up for daily it's not too hard to figure out.

- **Turned on the WiFi --*FIRST REAL ISSUE!***
>The `kde-wallet` asked me for a password. I've never used it before, and have, in the past, just disabled the KDE Wallet subsystem in the KDE Wallet System Settings Module; but getting the Network Manager to auto-login without storing the Wi-Fi Password **unencrypted** for all users (which really isn't a preferred option) seemed more difficult than I had remembered. There are ways to fix this problem, if you run into it. I found some good info at [https://wiki.archlinux.org/index.php/KDE_Wallet](https://wiki.archlinux.org/index.php/KDE_Wallet); and I chose to deal with the *problem* by taking their advice, deleting the default wallet, creating a new blowfish one with no password (but set it to prompt me if any applications try to access it), and then it had no trouble ever-after auto-logging-in to the Wi-Fi Password I had entered.

- **Turned on the Conky and edited it.**

![2020-03-29/GREEN-St-Pat-Conky.png](https://i.imgur.com/wt7frk0.png)

- Installed a bunch of applications, like `MX Codecs`, `Krita`, `Inkscape`, `Kdenlive`, `Flameshot`, `Atom`, `Syncthing` and `Syncthing-GTK`, because that is how I do!


- Dolphin had a couple Folders on the left that were tied to the Username `'demo'`.
>Changed the name in the path and all was well.

- **Changed Download location to `Downloads` in both `Vivaldi` and `Firefox`.**

- **Changed `Spectacle` & `Flameshot` 'Save' locations to `/home/username/Pictures/Screenshots`.**

- **Changed `simple-screen-recorder` 'Save' location to `/home/username/Videos/simple-screen-recorder`**

- **Changed Mouse Acceleration from 2.0 to 3.0**
> On an old Dell Latitude E6400, the mousepad seemed slow to me, but differences of opinion have been expressed since!

{% include blue.html %} **Other than that, I can't think of much more pertinent information to relay here. Sorry I tend to blab off so much. Hope you were able to glean some useful information in amongst all my ramblings...**

#### *(More Detailed Notes at the [README](https://sourceforge.net/projects/mx-19-1-kde-by-jki/files/))*

## [https://sourceforge.net/projects/mx-19-1-kde-by-jki/](https://sourceforge.net/projects/mx-19-1-kde-by-jki/)

[![Download mx-19-1-kde-by-jki](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/mx-19-1-kde-by-jki/files/latest/download)

![MX-19-1-KDE-by-JKI-icon.png](/assets/img/blog/MX-19-1-KDE-by-JKI-icon.png)
