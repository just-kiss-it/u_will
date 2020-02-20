---
layout: post
title: "*`'Firejail'`* Day..."
date: "2020-02-08"
author: "***`'Just-Kiss-It'`***"
image: https://i.imgur.com/w5rm4vC.png
---

### *`'Firejail'`* Day...

{% include red.html %} **73 Updates Today Too? Dayum!**

The kernel and headers reminded me to check how many I've got on my system and remove old kernels if necessary... Here's a relevant link... [https://www.tecmint.com/remove-old-kernel-in-debian-and-ubuntu/](https://www.tecmint.com/remove-old-kernel-in-debian-and-ubuntu/).

As for the suggestion of installing `'byobu'`... *Not* gonna happen... It seems far too *'Ubuntu'*-like for my taste!

Went into `'Synaptic'`. Saw I had some old cruft. Completely Removed `'gconf2'` and `'VirtualBox` 5.2'. *(I had forgotten to do that **way** back when!)*

Also decided to upgrade [`'YakYak'`](https://github.com/yakyak/yakyak) from version 1.5.3 to 1.5.4.

`'dpkg'` always makes for easy upgrades!

```
sudo dpkg -i yakyak-1.5.4-linux-amd64.deb
```

Speaking of `'dpkg'`... Here's a [`'dpkg'` Cheat Sheet](https://www.cyberciti.biz/howto/question/linux/dpkg-cheat-sheet.php)...

> {% include green.html %} **>inb4** "***He still uses Google 'Hangouts'!***"

Yeah, I *do* have some *'peeps'* who do, and I *do* find it convenient to use [**'YakYak'**](https://github.com/yakyak/yakyak) to interact with da *'ebil' Google 'Hangouts'* from Debian-based systems. Kind of like how I'm still hanging on to an old Gmail address I've been unable to fully extricate myself from yet; even though I have only interacted with it through [***'Thunderbird'***](https://www.thunderbird.net/en-US/) for many years. ***Time to Let It Go.***

- [x] {% include red.html %} Make getting rid of Google a priority.

### Well, ***updating*** *'YakYak'* didn't work! So, I purged it and reinstalled Version 1.5.3

Works again. Looked up ***'Issues'*** only to see that 4 days ago several others concurred that the latest [**'YakYak'**](https://github.com/yakyak/yakyak) does not work on Debian Buster. Probably wise to check the *'Issues'* before upgrading in the future

Decided to try to fix my **'AppImage'** problem, and **did** find out that it's *'Electron'* causing all this. Well, that and Debian and sandboxing... Anyway, some clues can be gleaned [Here:](https://github.com/laurent22/joplin/issues/2246) ...

![2020-02-08-180146.png](https://i.imgur.com/VbXyWbO.png)

[https://github.com/electron/electron/issues/17972](https://github.com/electron/electron/issues/17972)

[https://github.com/electron/electron/issues/16631#issuecomment-476082063](https://github.com/electron/electron/issues/16631#issuecomment-476082063)

### Probably time to just use [`'firejail'`](https://github.com/netblue30/firejail) to get around all these sandboxing issues...

[https://firejail.wordpress.com/download-2/](https://firejail.wordpress.com/download-2/)

[Firejail Demo](https://www.youtube.com/watch?v=J1ZsXrpAgBU).

But yeah, I'll probably get the `'firetools'` Qt GUI too... Plus `'firejail-profiles'`.

Nope! It wanted to install all kinds of crap with it! So, no...

But [https://www.wilderssecurity.com/threads/firejail-linux-sandbox.369309/page-25](https://www.wilderssecurity.com/threads/firejail-linux-sandbox.369309/page-25) has some clues too...

Grrr... Maybe I won't install `firejail` right now... It seems to come with more dependencies than it says it has... And I'm not really sure it's any better than when I read these threads a couple years ago...

[https://www.reddit.com/r/linux/comments/79mmzk/sandbox_your_applications_with_firejail/](https://www.reddit.com/r/linux/comments/79mmzk/sandbox_your_applications_with_firejail/)

[https://github.com/netblue30/firejail/issues/861](https://github.com/netblue30/firejail/issues/861)

[https://discourse.appimage.org/t/deeper-integration-with-firejail-for-sandboxing/88](https://discourse.appimage.org/t/deeper-integration-with-firejail-for-sandboxing/88)

wow...
[https://www.wilderssecurity.com/threads/firejail-linux-sandbox.369309/page-4](https://www.wilderssecurity.com/threads/firejail-linux-sandbox.369309/page-4)

DAYUM! I just wanna deal with *'sandboxing'* issues by going all `'Docker'` on  'em! [https://opensourceforu.com/2016/07/many-approaches-sandboxing-linux/](https://opensourceforu.com/2016/07/many-approaches-sandboxing-linux/)

![2020-02-08-220656.png](https://i.imgur.com/9rWa0ch.png)

![2020-02-08-221056.png](https://i.imgur.com/xxo9Gdp.png)

![2020-02-08-221303.png](https://i.imgur.com/92Ttsb3.png)

![2020-02-08-222401.png](https://i.imgur.com/gyZwblE.png)

[https://firejail.wordpress.com/documentation-2/firefox-guide/](https://firejail.wordpress.com/documentation-2/firefox-guide/)

#### [This link](https://ownyourbits.com/2017/10/29/sandbox-your-applications-with-firejail/) *really* puts the sandboxing issue succinctly; and is the one I started with a couple years ago...

[https://regginator729.wordpress.com/2017/12/22/firejail-sandbox-linux/](https://regginator729.wordpress.com/2017/12/22/firejail-sandbox-linux/)

### Jeezus! Why can't I just do:

```
HOME=/tmp/otherhome firefox
```
in order to have a sandboxed Home?

> ## {% include green.html %} LOL ! Watch ***`'Just-Kiss-It'`*** spin! Should we send him over the edge?

{% include spider.html %}

{% include giraffe.html %}

### [https://docs.docker.com/engine/security/security/](https://docs.docker.com/engine/security/security/)

### Maybe just build docker with seccomp and configure it via:  [https://docs.docker.com/engine/security/seccomp/](https://docs.docker.com/engine/security/seccomp/)?

In other words, with `'Docker'` I don't even need to install apps on my OS, so pretty much `'firejail'` is  a moot point, because I'd already be sandboxed...

![2020-02-10-125129.png](https://i.imgur.com/7ZLpbTj.png)

{% include red.html %} How about you ***Take a break...***

{% include green.html %} How about You *STOP JUDGING ME!*

{% include blue.html %} Well, it *is* a lot of *Links* that no one will ever click on!

{% include green.html %} You think *this* is bad? You should see my *'Notes'!*

#### Speakin' o' me *'Notes'!...*

### *'WebAssembly'* is like *'Docker'*!

[![2020-02-10-175546.png](https://i.imgur.com/mUijqkn.png)](https://www.youtube.com/watch?v=CMB6AlE1QuI)

##### [Rust, WebAssembly, and the future of Serverless by Steve Klabnik](https://www.youtube.com/watch?v=CMB6AlE1QuI)

> A lot of things have been said about WebAssembly inside of the browser; after all, that's why it was originally created. But a new case is emerging as well, and that's WebAssembly on the server. More specifically, we're seeing a rise of support for WebAssembly in serverless application platforms, combining two brand-new technologies together. We're also seeing a lot of growth of the Rust programming language, and its close alignment with WebAssembly. In this talk, Steve will talk about Rust, WebAssembly, serverless technologies, and how it all fits together.

**'Fastly'** and **'CloudFlare'** are competing with **'AWS'** using WebAssembly and Rust! And you ***know*** how I feel about *'Amazon'*!

### Break out of the 'sandbox' with **WASI** !

[![2020--02-08/2020-02-10-180815.png](https://i.imgur.com/vGGdx8h.png)](https://www.youtube.com/watch?v=fh9WXPu0hw8)

##### [Bringing WebAssembly outside the web with WASI by Lin Clark](https://www.youtube.com/watch?v=fh9WXPu0hw8)

> Earlier this year, we announced WASI, the WebAssembly system interface. With this system interface, WebAssembly can be used outside the browser in a portable and safe way.

> As Solomon Hykes, co-founder of Docker, said, "If WASM+WASI existed in 2008, we wouldn't have needed to create Docker. That's how important it is. Webassembly on the server is the future of computing."

> But WASI will be useful for so many other use cases, too. In this talk, we'll explain how WASI works and explore how different use cases can benefit from it.

### On [crates.io](https://crates.io) I checked out `pulldown-cmark`. It's a Markdown parser.

Yup. All over the map again... But...

#### If *you* think ***you*** are bored all to hell, ***just think how my girlfriend feels!***
Trust me when I tell you that merely playing her some good music will not be *near* enough to make up for all the time I'm spending on the computer! But we ***will*** listen to some good music! You're welcome to join us...

[![2020-02-10-190112.png](https://i.imgur.com/xlG3q7k.png)](https://www.youtube.com/watch?v=NWJ1thH_pUk)

---

[![2020-02-10-185343.png](https://i.imgur.com/r0KWMz8.png)](https://www.youtube.com/watch?v=-0SmXVrLlZ4)

---

[![2020-02-10-190714.png](https://i.imgur.com/rfjjI53.png)](https://www.youtube.com/watch?v=hb2VAxlwya4)

---

#### {% include green.html %} and *This* One Is *SO 'WORTH IT'!...*

[![2020-02-10/2020-02-10-181800.png](https://i.imgur.com/ZBdTqlm.png)](https://www.youtube.com/watch?v=6rBb_n6JJYY)
