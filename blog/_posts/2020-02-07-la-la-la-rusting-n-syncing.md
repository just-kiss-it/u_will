---
layout: post
title: "La La La! Rusting and Syncing"
date: "2020-02-07"
author: "***`'Just-Kiss-It'`***"
image: https://i.imgur.com/BDxtL1B.jpg
---

### La La La! Rusting & Syncing

Wanna do some `Docker` shite, like **'pi-hole'** today; and I also wanna do [**'Syncthing'**](https://docs.syncthing.net/) and [**`'Broot'`**](https://dystroy.org/broot/).

The [**`'broot'` Github**](https://github.com/Canop/broot) has pertinent info also. ***Noyce*** *Directory Search* Tool! But from the [`'Broot'` Installation Page](https://dystroy.org/broot/documentation/installation/) I find out that I have to first install the ['Rust' Development Environment](https://www.rust-lang.org/tools/install), and [Getting Started With 'Rust'](https://www.rust-lang.org/learn/get-started) could end up being more than I need to look into right now! But, Oh Well! Here we go!

![2020-02-07-094411.png](https://i.imgur.com/74i4rrR.png)

![2020-02-07-101807.png](https://i.imgur.com/nI0cU6y.png)

![2020-02-07-102512.png](https://i.imgur.com/vuNrI7m.png)

So, I will be closing `bash`, maybe even jumping out of the Desktop for a minute, then jumping back in and running this command:

```
source $HOME/.cargo/env
```

unless maybe it automagically set up my paths variable!

Maybe I should find out first by  doing `rustc --version` first.

![2020-02-07-103655.png](https://i.imgur.com/FLYhRok.png)

![2020-02-07-100956.png](https://i.imgur.com/zAZ0dus.png)

### DAYUM!!!!

```
jki@jki-pc:~$ rustc --version
rustc 1.41.0 (5e1a79984 2020-01-27)
jki@jki-pc:~$ cargo install broot
    Updating crates.io index
  Downloaded broot v0.13.0
  Downloaded 1 crate (1.7 MB) in 2.88s
  Installing broot v0.13.0
  Downloaded log v0.4.8
  Downloaded open v1.3.3
  Downloaded toml v0.5.6
  Downloaded regex v1.3.4
  Downloaded chrono v0.4.10
  Downloaded clap v2.33.0
  Downloaded lazy_static v1.4.0
  Downloaded minimad v0.6.3
  Downloaded git2 v0.11.0
  Downloaded directories v2.0.2
  Downloaded simplelog v0.7.4
  Downloaded crossbeam v0.7.3
  Downloaded users v0.9.1
  Downloaded umask v0.1.8
  Downloaded crossterm v0.15.0
  Downloaded lazy-regex v0.1.2
  Downloaded glob v0.3.0
  Downloaded pathdiff v0.1.0
  Downloaded id-arena v2.2.1
  Downloaded termimad v0.8.12
  Downloaded custom_error v1.7.1
  Downloaded atty v0.2.14
  Downloaded crossbeam-epoch v0.8.0
  Downloaded crossbeam-utils v0.7.0
  Downloaded mio v0.6.21
  Downloaded unicode-width v0.1.7
  Downloaded num-traits v0.2.11
  Downloaded crossbeam-deque v0.7.2
  Downloaded crossbeam-channel v0.4.0
  Downloaded vec_map v0.8.1
  Downloaded textwrap v0.11.0
  Downloaded strsim v0.8.0
  Downloaded ansi_term v0.11.0
  Downloaded bitflags v1.2.1
  Downloaded libc v0.2.66
  Downloaded serde v1.0.104
  Downloaded aho-corasick v0.7.8
  Downloaded url v2.1.1
  Downloaded dirs-sys v0.3.4
  Downloaded term v0.6.1
  Downloaded parking_lot v0.10.0
  Downloaded signal-hook v0.1.13
  Downloaded thread_local v1.0.1
  Downloaded regex-syntax v0.6.14
  Downloaded memchr v2.3.0
  Downloaded crossbeam-queue v0.2.1
  Downloaded num-integer v0.1.42
  Downloaded cfg-if v0.1.10
  Downloaded time v0.1.42
  Downloaded libgit2-sys v0.10.0
  Downloaded matches v0.1.8
  Downloaded idna v0.2.0
  Downloaded percent-encoding v2.1.0
  Downloaded thiserror v1.0.10
  Downloaded parking_lot_core v0.7.0
  Downloaded dirs v2.0.2
  Downloaded lock_api v0.3.3
  Downloaded slab v0.4.2
  Downloaded net2 v0.2.33
  Downloaded scopeguard v1.0.0
  Downloaded autocfg v0.1.7
  Downloaded signal-hook-registry v1.2.0
  Downloaded iovec v0.1.4
  Downloaded memoffset v0.5.3
  Downloaded autocfg v1.0.0
  Downloaded smallvec v1.2.0
  Downloaded cc v1.0.50
  Downloaded unicode-normalization v0.1.12
  Downloaded thiserror-impl v1.0.10
  Downloaded libz-sys v1.0.25
  Downloaded unicode-bidi v0.3.4
  Downloaded pkg-config v0.3.17
  Downloaded rustc_version v0.2.3
  Downloaded arc-swap v0.4.4
  Downloaded jobserver v0.1.21
  Downloaded proc-macro2 v1.0.8
  Downloaded syn v1.0.14
  Downloaded quote v1.0.2
  Downloaded semver v0.9.0
  Downloaded unicode-xid v0.2.0
  Downloaded semver-parser v0.7.0
   Compiling libc v0.2.66
   Compiling cfg-if v0.1.10
   Compiling lazy_static v1.4.0
   Compiling autocfg v0.1.7
   Compiling semver-parser v0.7.0
   Compiling log v0.4.8
   Compiling smallvec v1.2.0
   Compiling autocfg v1.0.0
   Compiling bitflags v1.2.1
   Compiling scopeguard v1.0.0
   Compiling pkg-config v0.3.17
   Compiling proc-macro2 v1.0.8
   Compiling unicode-xid v0.2.0
   Compiling syn v1.0.14
   Compiling matches v0.1.8
   Compiling slab v0.4.2
   Compiling arc-swap v0.4.4
   Compiling unicode-width v0.1.7
   Compiling memchr v2.3.0
   Compiling serde v1.0.104
   Compiling ansi_term v0.11.0
   Compiling strsim v0.8.0
   Compiling vec_map v0.8.1
   Compiling percent-encoding v2.1.0
   Compiling regex-syntax v0.6.14
   Compiling glob v0.3.0
   Compiling open v1.3.3
   Compiling umask v0.1.8
   Compiling pathdiff v0.1.0
   Compiling custom_error v1.7.1
   Compiling id-arena v2.2.1
   Compiling minimad v0.6.3
   Compiling thread_local v1.0.1
   Compiling lazy-regex v0.1.2
   Compiling semver v0.9.0
   Compiling crossbeam-utils v0.7.0
   Compiling crossbeam-epoch v0.8.0
   Compiling unicode-normalization v0.1.12
   Compiling lock_api v0.3.3
   Compiling num-traits v0.2.11
   Compiling num-integer v0.1.42
   Compiling unicode-bidi v0.3.4
   Compiling textwrap v0.11.0
   Compiling rustc_version v0.2.3
   Compiling idna v0.2.0
   Compiling memoffset v0.5.3
   Compiling jobserver v0.1.21
   Compiling iovec v0.1.4
   Compiling dirs-sys v0.3.4
   Compiling net2 v0.2.33
   Compiling parking_lot_core v0.7.0
   Compiling signal-hook-registry v1.2.0
   Compiling atty v0.2.14
   Compiling time v0.1.42
   Compiling users v0.9.1
   Compiling quote v1.0.2
   Compiling url v2.1.1
   Compiling aho-corasick v0.7.8
   Compiling cc v1.0.50
   Compiling dirs v2.0.2
   Compiling directories v2.0.2
   Compiling mio v0.6.21
   Compiling parking_lot v0.10.0
   Compiling clap v2.33.0
   Compiling toml v0.5.6
   Compiling crossbeam-queue v0.2.1
   Compiling crossbeam-channel v0.4.0
   Compiling regex v1.3.4
   Compiling term v0.6.1
   Compiling signal-hook v0.1.13
   Compiling libz-sys v1.0.25
   Compiling libgit2-sys v0.10.0
   Compiling chrono v0.4.10
   Compiling broot v0.13.0
   Compiling thiserror-impl v1.0.10
   Compiling crossterm v0.15.0
   Compiling simplelog v0.7.4
   Compiling crossbeam-deque v0.7.2
   Compiling thiserror v1.0.10
   Compiling crossbeam v0.7.3
   Compiling termimad v0.8.12
   Compiling git2 v0.11.0
    Finished release [optimized] target(s) in 12m 58s
  Installing /home/jki/.cargo/bin/broot
   Installed package `broot v0.13.0` (executable `broot`)
jki@jki-pc:~$
```

![2020-02-07-110446.png](https://i.imgur.com/5crZtjk.png)

### but... *It WORKS!* and Well!

![2020-02-07-112421.png](https://i.imgur.com/3XC5Yxd.png)

![2020-02-07-114358.png](https://i.imgur.com/zpMzJOA.png)

As for ['Syncthing'](https://syncthing.net/), I'm ***DEFINITELY*** gonna find a use for ***that!*** I mean, it *has* uses...

![2020-02-07/2020-02-05-224700.png](https://i.imgur.com/Wuaf69t.png)

#### *(Did That.)* Now [*THIS:* https://docs.syncthing.net/intro/getting-started.html](https://docs.syncthing.net/intro/getting-started.html)...

![2020-02-07-204553.png](https://i.imgur.com/cBbtH8Y.png)

***I probably should have just used `Docker` to do the `'Syncthang'`!*** [https://github.com/djtm/syncthing-docker-scratch](https://github.com/djtm/syncthing-docker-scratch). Probably... [https://github.com/joeybaker/docker-syncthing](https://github.com/joeybaker/docker-syncthing).

But yeah, I now can keep my Markdown **Notes** and Photos organized and synced between all devices... ***FINALLY!*** It works damn well too. Better than **KDE Connect** ever ***dreamt*** of doing! *(btw, I use the [**'WriterPlus' App**](https://play.google.com/store/apps/details?id=co.easy4u.writer&hl=en_US)  for taking Markdown Notes on Android...)*

[![2020-02-10/WriterPlus-Icon.png](https://i.imgur.com/sqI9Kjn.png)](https://play.google.com/store/apps/details?id=co.easy4u.writer&hl=en_US)

-----

I also want to backup my `'dotfiles'` to a [`'git bare'`](https://www.saintsjd.com/2011/01/what-is-a-bare-git-repository/) private repository, backup my entire Home Directory, and spruce up my terminal a bit.

[https://stackoverflow.com/questions/7632454/how-do-you-use-git-bare-init-repository](https://stackoverflow.com/questions/7632454/how-do-you-use-git-bare-init-repository) is a nice link...

I also recall Derek, over at [Distro Tube](https://www.distrotube.com/) doing a video awhile back about managing *'dotfiles'* using a ``'git bare'`` repository that is worthy of review...

[![2020-02-10/2020-02-10-145711.png](https://i.imgur.com/35zy9dC.png)](https://www.youtube.com/watch?v=tBoLDpTWVOM)

[Git Bare Repository - A Better Way To Manage Dotfiles](https://www.youtube.com/watch?v=tBoLDpTWVOM) [16:55]


-----

I also wanted to make a short video today...

### *BUT...* My power went out for several hours, my daughter's last chicken was brutally murdered by a neighbor's dog, and many other responsibilities also cropped up.

Very few seem to be accepting personal responsibility for *anything* nowadays; and we all seem to be at each other's throats over *nothing* -- polarized with hatred, fear and blame. I don't think *anyone* is impressed.

### Time to grow up and take *your* turn to ***BE*** *'that-which-you-thought-you-were-not'*.

[![2020-02-10-183216.png](https://i.imgur.com/hUDf5rR.png)](https://www.youtube.com/watch?v=iDsCeIwfLtk)

##### [The Be Good Tanyas- For the Turnstiles](https://www.youtube.com/watch?v=iDsCeIwfLtk)

-----

Started looking into the [**Rust**](https://www.rust-lang.org/) programming language, and was checking out [`Cargo` **'Crates'**](https://crates.io/), and ran into ['Parity'](https://www.parity.io/) again. Been awhile, but I remember them. I'll be checking into ***that*** *'crate'* and learn a bit more about [***their*** technologies](https://www.parity.io/technologies/)... If you want a clue, it's about **Open-Source Software for Building the Decentralised Web**. *(and yes, the **'Ethereum'** blockchain figures prominently.)* I'm also interested in [**'Polkadot'**](https://polkadot.network/). More study must be done soon. As for the [**'Dot' Token**](https://polkadot.network/dot-token/)... hmmm...

#### Of course, I could always [launch my *own* blockchain](https://www.parity.io/substrate/)!

{% include green.html %} lol

{% include blue.html %} Pretty obvious you are moving deep into a *'research phase'...* I wouldn't be surprised if the next few blog entries exhibited *more 'neverending links'* than *ever* ***before!***

-----

### May wanna blast **'Tutanota'** today. Already prepared with screenshots of emails, etc...
> but no, I may either save that for later, or just *let it go.*

**Tutanota**'s very ***Logo*** is *emblematic* of, *'Took a turn for the worse and ended with a whimper...'*

![2020-02-07/2020-02-05_11-24-51.png](https://i.imgur.com/vZfYbVf.png)

-----

Did some editing of images and the last blogpost *(see  'Notes')*, but would ***REALLY*** like to  go to town on editing the old [https:/freedomzine.hashbase.io](https:/freedomzine.hashbase.io) site and the old [https://just-kiss-it.hashbase.io](https://just-kiss-it.hashbase.io) site. I also need to slip that [***'Killcen'*** Page](https://killcen.hashbase.io) in there somewhere, after sprucing things up a bit.

#### That would be me wrapping up the past...

Speaking of wrapping up the past...

### Got a bunch of Emails to write...

Not to mention...

### ['Articles'](/u_will/articles/)*!*
