---
layout: post
title: "The Nose KNOWS!"
date: "2020-01-12"
author: "***`'Just-Kiss-It'`***"
image: https://i.imgur.com/znAyJG1.jpg
---

Woke wonderfully with lounge-cat, Eeyore....

I fully recommend letting it *all* out like my girl, Kate did in her YouTube presentation this morning... [Rocksmith - Iron Maiden - The Trooper - アイアンメイデン bass](https://youtube.com/watch?v=pO79G9iYlAA) Just watch this from 3:33 and thank me later. Letting it all out is important! I may do a short clip of just that portion and upload it to [My Bitchute Channel](https://www.bitchute.com/channel/just-kiss-it/) later today.

And, as a follow-up to the video I posted on the 9th regarding Samsung NEON's leaked info... [Samsung's NEON is Officially Confirmed - Trailer Analysis](https://www.youtube.com/watch?v=wgxXjlutKao). I still have nothing to say about that but **WOW.**

-----

I still need to organize my thoughts regarding the **Categories**. I really want no more than 7 main categories. I'd like to maybe make some navigation buttons too and maybe a site-map. It would be best to get some ideas from others who have done this before. I may find good guides on [Chris Titus Tech](https://www.christitus.com/) and [Distro Tube](https://distrotube.com/) (he's all still *'lorem ipsum dolor'*!) about Hugo, but I'll be doing a lot of floundering because I am in a Template that is over my head with all the **_sass** and blah blah blah... Maybe I'll do some fun stuff like make some clickable icons on the front page for [My Bitchute Channel](https://www.bitchute.com/channel/just-kiss-it/) and [8kun.top](https://8kun.top/freedomzine/) too, because I plan on having it as a place for people to be able to freely comment outside the [Disqus](https://disqus.com/) system. Since I am my only reader right now, I have no reason to create space to comment on my own shite! It's bad enough I'm taking the time to say it to begin with! ***EVERYONE***'s got somethin' to say, nowadays; but ***NOBODY*** is listening! *(which reminds me, I've got that article,* [***'Can U Here Mi NAO?'***](404.md) *to finish up!)* ...

Establishing a productive workflow may be as difficult as it is important. I was looking through the old HydeJack commits and learned a few things; but, like always, I found myself getting sidetracked again (just like I did on `HUGO` this morning!)

> What Now?

#### [Setting up GPG with Github](https://help.github.com/en/github/authenticating-to-github/managing-commit-signature-verification)

```
gpg --list-secret-keys --keyid-format LONG
```

Yeah, I don't really wanna use any of my own keys, and I don't have one for the email I associated with Github, and I don't want to expose ***that*** either, and I think I'll just make another key to associate with my Verified Github Email Address...

Here's a couple links... [Setting your commit email address](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address)...

and another doozy... [Blocking command line pushes that expose your personal email address](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/blocking-command-line-pushes-that-expose-your-personal-email-address)...

#### This link... [Authenticating to Github](https://help.github.com/en/github/authenticating-to-github) also looks exciting.

It is. Pretty much the definitive guide I would say!

As does this... [Caching your GitHub password in Git](https://help.github.com/en/github/using-git/caching-your-github-password-in-git)...

My girlfriend is reading over my shoulder and about ready to ***kill*** me if I do not go for a walk with her ***NAO!*** This is not the kind of *`git`* **she** wants me doin' right now!

Alright. I'll tackle this link [https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address) upon my return...

Alright, here goes...

```
jki@jki-pc:~$ gpg --full-generate-key
gpg (GnuPG) 2.2.12; Copyright (C) 2018 Free Software Foundation, Inc.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Please select what kind of key you want:
   (1) RSA and RSA (default)
   (2) DSA and Elgamal
   (3) DSA (sign only)
   (4) RSA (sign only)
Your selection? 1
RSA keys may be between 1024 and 4096 bits long.
What keysize do you want? (3072) 4096
Requested keysize is 4096 bits
Please specify how long the key should be valid.

I think that's enough for y'all...

```

OK. Yay. One knows nothing still...

```
jki@jki-pc:~$ gpg --list-secret-keys --keyid-format LONG

You won't be needing the outcome of that command. I have it in my Notes.

jki@jki-pc:~$ gpg --armor --export nopenotgonnaleavethat
-----BEGIN PGP PUBLIC KEY BLOCK-----

Yeah, that's not Blog-worthy for y'all either!

-----END PGP PUBLIC KEY BLOCK-----
jki@jki-pc:~$
jki@jki-pc:~$ git config --global user.signingkey justkissitifyouthinkthisnumbershouldbeexposed
jki@jki-pc:~$ test -r ~/.bash_profile && echo 'export GPG_TTY=$(tty)' >> ~/.bash_profile
jki@jki-pc:~$ echo 'export GPG_TTY=$(tty)' >> ~/.profile
jki@jki-pc:~$
```

![2020-01-12-145653.png](https://i.imgur.com/mbCIJUU.png)

#### Remember this command:

```
git config commit.gpgsign true
```

from any local repository! (not gonna do the global command:

```
git config --global commit.gpgsign true
```
though...) Read here: [https://help.github.com/en/github/authenticating-to-github/signing-commits](https://help.github.com/en/github/authenticating-to-github/signing-commits) for more...

#### Further Study?

##### [`gpg-agent`](https://linux.die.net/man/1/gpg-agent)

![2020-01-12-151625.png](https://i.imgur.com/gZIHYy7.png)

-----

OK. Helped daughter get set up with [KeepassXC](https://keepassxc.org/), [ProtonMail](https://protonmail.com/) and [ProtonVPN](https://protonvpn.com/) finally. Hope she actually really ***uses*** the tools. It just takes practice, but it's a lifetime good habit, and I have found Keepass to be **indispensable** for *years!*

-----

Now back to something more fun!

#### Browsing 4chan in terminal style with [`chancli`](https://github.com/Gimu/chancli) !!!

**No h8.** I still occasionally lurk /g/, and this looks like fun to play with. I'm actually thinking of forking it and making it work with [https://8kun.top/freedomzine/]([https://8kun.top/freedomzine/) as my first Python Project, and having other [[https://8kun.top](https://8kun.top) Board Owners offer me SusuCoin or other cryptos to list their worthless obscure boards in my CLI! Far more likely, however, that I'll just leave 8kun to the Q-tards and forever-virgins...

![2020-01-12-171558.png](https://i.imgur.com/e8JhBRU.png)

That is probably better to play with in a VM anyway. `urwid` has like 14 dependencies of it's own, and you're probably missing a few... I know I was! Python anyway. Here I go again! Seems like it was only a few years ago I got on *that* kick!

-----

Spent quality time with family this evening.

#### Things to do before bed:

- Kate Belching Video (downloaded and will edit tmrw...)
- Giraffe Logo (a quick attempt below)
- LBRY -- Check it out... (still doing that...)
- Slap my Notes in `Jekyll` and edit.
- add, commit & push to Github...

![JKI-logo-2.png](https://i.imgur.com/zRVtGAm.png)

Good luck seein' **that** in dark mode!

That was my first attempt at using Inkscape that I started the other day and finished tonight, btw...
