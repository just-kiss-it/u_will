---
layout: post
title: "Not Happy with `LBRY`"
date: "2020-01-14"
author: "***`'Just-Kiss-It'`***"
image: https://i.imgur.com/MCe6Tkc.png
---

### This day started with me writing, and it will probably end with me writing.
I really want to get the website better organized today, but thoughts are flowing, and I must write while I'm in the mood.

[`Atom`](https://atom.io) just updated, which reminded me that I need to learn how to properly use [`Atom`](https://atom.io) with [Github](https://github.com)... and adding that sentence to my **Notes** reminded me that I need to organize my **Notes** better -- which leads me to the organization of this blog... How exactly do I want to structure it? Now would be a good time to figure that out. One thing I want to keep in mind is how to structure things in such a way as to make it somewhat easy to just drop my content into another theme if I want to (which is probable, if I can't fix the **"_sass"** problem...)

-----

I would really like to see an organized structure for the blog develop immediately; so here is my...
### <u>Tentative Idea re: Blog Page Structure:</u>

- **Preface** (may get written at end of each day tho!)
- **Giraffisms**
- The **Rousing** Convocation
- **Tech**
- **Musings**
- **Links**

I can intersperse cool quotes and pics throughout!

I kinda like the workflow of not pushing to Github until morning, because my thoughts are clearer in the morning after doing some writing.

-----

### I also need structure for the Pages:

- Blog
- Articles
- Links to Videos

-----

### Bitchings and Moanings:

![2020-01-14-085448.png](https://i.imgur.com/MCe6Tkc.png)


In my opinion, [**`LBRY`**](https://lbry.tv/@Just-Kiss-It)  is **not** ready for the primetime, and will **never** go anywhere. Sorry, [Distro Tube](https://www.distrotube.com/videos/is-lbry-a-viable-alternative-to-youtube/), I love you man, but **you are wrong,** Derek. I know. I've actually *used* ***all*** the platforms you talked about (and more), and I can assure you that even [Bitchute](https://www.bitchute.com/channel/just-kiss-it/) has a better chance of *'making it'*  than [**`LBRY`**](https://lbry.tv/@Just-Kiss-It); and here is why:

- It's a Peer-to-Peer Application (that doesn't even work! at least not for me, and if I can't get it to work on my machine after trying for a whole day, I can guarantee you that 99.9% of people will not waste their time at all.) I'm about done. It's supposed to be easy to set up on Debian. It isn't. Dunno about Windoze, but I know it doesn't run on Arch-based systems either, and I heard there were problems getting it to work on Ubuntu too. This is **exactly** the point they were at when I checked them out over a year ago. **Unusable.**

- It is **not** intuitive, the User Interface is terrible, (although it has improved over the last year).

- There is far too much focus on cryptocurrencies. Sorry. I know! I like 'em, and so do many others, but the average person does not care; nor do they understand, or want to be made to feel like they have to understand in order to use the site.

- There's too much porn for the site to **ever** go mainstream in its current form. Not saying porn is not mainstream; it is -- but being constantly assaulted with porn even when your settings supposedly block that is annoying to me, and an absolute deal-breaker for many.

- imho, the only people who use LBRY are the kind of people who, like me, get *'memed'* into things. What do I mean? Well, I've actually installed Arch several times. I've used numerous tiling windows managers, text-based browsers, even tried [`surf`](https://surf.suckless.org/) from [**Suckless**](https://suckless.org/) just a couple days ago -- the only thing I ***haven't*** been *memed* into was **installing Gentoo!** Now I feel *memed* into `LBRY`. It'll probably grow on me... ~~like a cancer (like `vim`!)~~

On that note, guess I'll go try to fix the `LBRY` app by opening some ports or something...

![2020-01-14-121011.png](https://i.imgur.com/nYfCfrn.png)

> and yes, I checked my router. UPnP is turned on and the log reflects that's not the problem, so messing with Port 3333 or 4444 seems uneccessary. Wanna see the log?
```
2020-01-14 14:52:39,282 INFO     lbry.extras.daemon.Components:378: found upnp gateway: Yeah, it found my router, but NUNYA.
2020-01-14 14:52:39,293 INFO     lbry.extras.daemon.Components:391: got external ip from UPnP: 11.69.777.420
2020-01-14 14:52:39,294 INFO     lbry.extras.daemon.Components:404: add UPnP port mappings
2020-01-14 14:52:39,346 INFO     lbry.extras.daemon.Components:421: set up redirects: {'TCP': 3333, 'UDP': 4444}
2020-01-14 14:52:39,530 INFO     lbry.extras.daemon.Components:226: start the dht
2020-01-14 14:52:39,535 INFO     lbry.extras.daemon.Components:250: Started the dht
2020-01-14 14:52:39,537 INFO     lbry.extras.daemon.Components:148: Starting torba wallet
2020-01-14 14:52:40,839 INFO     torba.client.basedatabase:237: connecting to database: /home/jki/.local/share/lbry/lbryum/lbc_mainnet/blockchain.db
2020-01-14 14:52:40,846 INFO     lbry.dht.node:124: DHT node listening on UDP 0.0.0.0:4444
2020-01-14 14:52:42,318 WARNING  torba.client.basenetwork:75: Wallet server (spv1.lbry.com:50001) returned an error. Code: 1 Message: unsupported protocol version: 2.0
2020-01-14 14:52:42,319 WARNING  torba.client.basenetwork:102: Server error, ignoring for 1h: spv1.lbry.com:50001 -- unsupported protocol version: 2.0
```

### **'unsupported protocol version 2.0'** ?

![2020-01-14-122625.png](https://i.imgur.com/1XKod2V.png)

Well, opening Port 50001 did something, but it said it had an error at first, and it still would not let me sign in once it finally started. No Dizzying Geometrical Pattern this time though...

![2020-01-14-141416.png](https://i.imgur.com/bfglDZv.png)


![2020-01-14-133751.png](https://i.imgur.com/drOGzgp.png)

Gonna try restarting again and see what happens!

But no change, other than I get the dizzying geometrical pattern again; but **I still Can't Sign In.** It just wastes my RAM and processor, while probably mining LBC for others, and hosting their porn on my computer. Yay. Do you see why I don't think this `LBRY` thing is going to ***ever*** take off? (I wrote an article on this more than a year ago.)

Yes, I'll try the Authentication Issue next, since that's the only possible issue I haven't addressed yet. Why, oh why are you forcing me to install `gnome-keyring` though! I don't wanna! This had better not mess up my own keyring!

### So, as a reminder to myself regarding the LBRY files...

![2020-01-14-134515.png](https://i.imgur.com/9ewJItJ.png)

Have I said ***this*** yet? **LBRY** is ***NOT 'WORTH IT'.***
> and yes, I know that one does not have to use the app, and you can just use it on the web at [https://lbry.tv](https://lbry.tv), but grrr... I want the Desktop App.

The way `LBRY` is set up I just want to get on there, collect my rewards, then go somewhere else. Sorry if you don't like my opinion, but the platform itself sucks. Also, if you think it doesn't push porn when your settings ask it not to, you aren't on the same [https://lbry.tv](https://lbry.tv) website that I am. I may have mentioned that before, but you know what? I'm mentioning it again! Just like the porn that is jammed into my eyeballs again and again every time I watch any video on that website. Seriously? They can't even code the NSFW shite to not show up in the suggested video list when one's settings say lay off the porn? Why not?

Also, my computer has slowed down significantly since installing this worthless, unusable app that I cannot sign in to.

### I ABSOLUTELY DO NOT RECOMMEND `'LBRY'` FOR ***ANYBODY*** AT THIS TIME.
> Tell us what you ***REALLY*** think, ***`'Just-Kiss-It'`!!!***

-----

The following is just some rambling advice for anyone thinking they might like to have a website for themselves... It will probably grow and turn into an article, as my ramblings often do...

### So You Say You Want a Website?
> #### Trust Me, You Don't.

But let's say you *thought* you did...

Just how much time and effort would you want to put in? I mean, *really?* What is your goal? What are you trying to achieve? *What* do you want to say, and *how* do you want to say it? Which is more important to you -- content or design -- and just how much of one do you need to sacrifice for the other? Do you, like me, have some very specific ideas, and some more general ideas -- but you find that those ideas do not mesh well into one cohesive subject-matter that makes sense? ***Maybe you need more than one website!***

Alright, alright, let's not get out in front of ourselves here! Just because ***`'Just-Kiss-It'`*** thinks ***he*** may need more than one website, does not mean ***you*** do! So how would one go about finding the answers to all these questions -- and how would one even commence such an undertaking, especially if one knows absolutely *nothing* about building or maintaining a website? Daunting, to say the least! **But it doesn't have to stop you from accomplishing your goals.** Do you think you are too old, too young or too dumb to learn new skills? We all feel that way when facing unfamiliar ventures, yet there can be a certain level of excitement also. Let's try to keep this excitement level going now, shall we? I mean, ***nobody*** is interested in the *'same old same old'*, and neither are you! That is why it is *always* recommended to take it easy and learn a little at a time, rather than overwhelm yourself with everything at once.

> But taking recommendations has never been my forte. I like to learn everything at once!

Maybe you should take a look at that. No judgment. But getting overwhelmed, frustrated and angry never helped anyone; and it ***will*** color your creations; more than you know. So try to take it easy on yourself. You don't want your frustrations to end up repelling anyone who comes into contact with your creations now, do you? So, start with the idea that you want to take it easy, and learn these new skills over a period of time; then you will not get impatient when obstacles come up -- because, like anything *else* that is *'WORTH IT'*, **difficulties *will* come up.**

### Don't get out ahead of yourself!

If you are just starting with an idea, but have no idea how to go about presenting your idea to the world via a website, you should probably find out if you really want a website at all! What are you trying to do? Maybe showcase art or photos? That would be a different kind of website than, say, a blog.

### What kind of content will I have?
That should be your first question.

### How do I want to manage said content?
That should be your second question.

As to the first question: Let's say you want to just start off with a simple blog that you can build out later into something else (when you figure out what you want to do when you grow up!) I'm going to recommend you play around a bit with [Beaker Browser](https://beakerbrowser.com/). I'll be making a video on that as soon as I get a working microphone. It's easy as pie, and you could have a working website for free (fully anonymous too, I might add!), in 5 minutes with zero know-how, and you won't have to give any personal information out to anyone either. It's a good place to start, and it will give you an idea if you are even interested in creating a website. [Hashbase](https://hashbase.io/) will even host your site (up to 100 MB) for free, so there's really no excuse not to get your feet wet. You can see a couple of my older attempts at [https://freedomzine.hashbase.io](https://freedomzine.hashbase.io) and [https://just-kiss-it.hashbase.io](https://just-kiss-it.hashbase.io). I used a Template on the ***'FreedomZine'*** website, and I just went all [Markdown]() crazy, building the [Just-Kiss-It.hashbase.io](https://just-kiss-it.hashbase.io) website on the fly, last month while blogging about it. I made a video too, but no sound! Microphone went out. I'll revisit the video soon though, and link to it here... Anyway, what I'm trying to get across is that **it's simple!** If I can do it, anybody can do it. You don't want to learn `HTML` or `CSS`? You don't have to! A smattering of the basics would not hurt in the long run, but ***take it easy!*** As for `PHP` or `SQL`... Trust me, **If you do not have a *really* good reason to drag around a huge database, and work with an insecure *Content Management System* like [Wordpress](https://wordpress.com/) or [Wix](https://www.wix.com/) -- DON'T**. Thank me later. Most normal people with normal needs do not need to go to all that work. Also, why have a Dynamic Website, when you can go Static? I did. Static websites are blazingly fast and easy to manage. The workflow is nice, and you can spend your time focused on creating content, rather than spending all your time trying to make things look right on the page on everyone's devices, etc... As far as static site generators go, after using several, I'm sticking with `Jekyll`. `HUGO` is alright, but less intuitive, imho; and I'll admit the **Google** connection may be affecting my attitude. Anything they touch I tend to eventually shy away from.

Anyway, I'll have a lot more to say about this later, but I just wanted to get out some thoughts on the matter in preparation for the video I'm making for my Aunt and Mom about how to easily create a website for free.

-----

Speaking of getting some thoughts out...

I've got a few things to say about:

- Protest Distros, and **being *against* things** in general, rather than being ***for*** anything.
- **Rebellion** in general, and why fighting authority is a losing battle. Much better to ***be*** the authority.
- **Our Relationships with Authority** in general, and how they color ***everything*** we do, on an individual and society-wide level.
- **Judgment**, and how it affects ***EVERYTHING.***
- **Anger** (mine ususally stems from judgment, real or perceived, negative or positive, it makes no difference -- **your judgment just plain pisses me off!**)
- **Resentment** (because, in my mind I often feel judged, and I'm already angry about that, so I begin to resent the very presence of others.)
- **Religion** (Oh yeah! ***DEFINITELY*** gonna go *there!* You think I won't? It has orchestrated the realities of so many individuals throughout time that I would be remiss not to pound on it as relentlessly as it has pounded on all of humankind, and me personally. More on that later...)
- **Conformity** versus **Authenticity**. (This will be a common theme. I talk about it a lot.)

-----

### So, I want to Create Some Content!

I want to write and get my thoughts out. Kind of driven to do so anyway. Writers just do that -- they write. So I want to have a place for that. I want to create space for sharing my thoughts, plans, projects and creations. I'll be making more videos soon too (hopefully you can't find all the older ones!) As for who I am in real life? I'm a lot more like a giraffe than you might think. I don't make any money, and I don't attempt to. That would be harlotry. And yes, working for fiat debt-based currency is **literal prostitution.** You trade your valuable time and energy for scraps of paper or digits on a screen. I don't. I'm just an old used up whore, who worked hard physical labor jobs for decades, and ended up ~~*'disabled'*~~ enabled to do nothing else but use my mind and inner ingenuity to write voluminous tomes and impossibly huge sentences, casting aspersions on all who would deign to play the game *'the way it is supposed to be played'*, *'the way everybody else does'*, etc... not because I think I'm *better* than anyone else, but because I have a stubborn form of integrity (probably related to my hatred of authority), and ***I Refuse to Sacrifice My AUTHENTICITY for ANYTHING.*** I absolutely hate the **FAKENESS** so prevalent in society today.

### I reject your *Contrived Reality* and substitute my own!

### Just so I make this more than clear, I consider **Google**, **Fakebook** and **Twatter** to be a huge part of the *'fakeness'* problem, so you will not find me supporting those platforms.

I'm not against making an honest living. We all have to do what we can to support ourselves and our families. But I will personally forego all advertising, unless it is something I really believe in; and even then, I would ***NEVER*** allow an advertiser to have a say in what kinds of content I choose to create. But they ***do*** sorta have a say ***anyway!*** If one is attached to that ad revenue stream they may mince their words, or curb their authenticity in favor of retaining that income, even if that possible income loss is only a thought in their mind, **ad revenue always colors content.**

That reminds me of something George Orwell said:
> "All the papers that matter live off their advertisements, and the advertisers exercise an indirect censorship over news."  ~ George Orwell

Of course, he also said...
> "News is something somebody doesn't want printed; all else is advertising."  ~ George Orwell

### So, what am ***I*** advertising?
### FREEDOM.
### Honesty, Integrity & Authenticity.

### So, I guess I'll have to rely on donations then!
Grrr... Why do I feel like a panhandler all of a sudden?

I am interested in a lot of things, like security, privacy, freedom of speech, anonymity... you know, all those things that get one called a *'rayciss ebil nahtzee!'* nowadays; so yeah, I won't be putting out more than a *'giraffic persona'* to the world any time soon. But what you should be asking yourself is,

### "Do *I* reflect more than a mere *'persona'* to the universe?"
If not, why not?

I do tend to watch some videos on YouTube on occasion. In fact, you may often find me recommending *you* watch some! (I listed some below!) I do **not** support Google in any other way, and if I can find the videos elsewhere I'll watch them there. Yes, I hate Google that much. I'll be writing an article and making a video on how to easily unGoogle very soon, so keep an eye out! So that would be **NO.** I do **not** have a YouTube Channel. I don't monetarily support anybody but my family because I have no money, but I **do** approve of some of the content I see being created there, and I *definitely* spread links to the good stuff around to the people I know. I'll be posting a list of recommended channels soon here too...

As for now, I'll just mention that I *do* watch [***'Distro Tube'***](https://www.youtube.com/channel/UCVls1GmFKf6WlTraIb_IaJg/featured) and [***'Chris Titus Tech.***](https://www.youtube.com/user/homergfunk) I'm a lot like them, (minus the shaved head, or normie Windoze IT experience.) I *used to* watch [***'Switched to Linux'***](https://www.youtube.com/channel/UCoryWpk4QVYKFCJul9KBdyw) just for fun sometimes, but he's not been fun at all as of late. (I blame religion, but he's mostly just been too whiny lately -- kinda reminds me too much of myself at times! And don't get ***me*** started on ***my*** ISP! Alright, maybe it's a phase (I go through them all the time), but...

**I always want to remember to have fun and to be fun!**

I've had different experiences and take a different approach, but that's also why my viewpoint is valuable too. I'm no competition, because I'm not making any money -- so how could I be threatening anyone else's income stream?

### I'm irreverent, non-professional, awkward, and long-tongued, but fun.

Why do I suddenly feel like I'm filling in an online-dating form?

### How do I differ from *'other*' content creators?
- I don't *think* like a normal *'content creator'*; as in, I do not think that I ***'own'*** my own engenderings.

- I do not own the *viewpoint* of others -- *when, where* or *how* they experience my creativity.

- My main focus and goal is not to make money, or even support myself or my family. It never has been.
> Yet I've managed to raise two children completely on my own, home school almost all the way through, and took my kids around the world on an income that is one-third of the poverty level!

> inb4 illegal activities. Nope! Focus on what is important. Have kids? Spend time with 'em.

- Focusing on self-expression to the exclusion of all else has allowed ***`'Just-Kiss-It'`*** to get caught up in *different* illusions than some *'other'* viewpoints have -- and, **ain't that always the way of *'Self'*?!**

- I am not caught up in, nor do I support the advertising model the way it is on the internet today.
> Nobody likes ads, but content creators are as much to blame as anyone for becoming attached to revenue streams where such blatant lack of integrity is involved.

- I don't want to get caught up in creating or guarding revenue streams.

- I don't want to whine or blame others; but I **do** want to point out pernicious behavior when I recognize it; even in myself.

- I don't want to talk about things I barely have any experience with, nor do I want to talk about what everyone else is talking about. I want to talk about what matters.
> ##### Well, to me, anyway!

And just what is that? Let's find out together now, shall we?

-----

Another day gone and I still did not get the LBRY app going on my computer.

Still chasing down info on the `_sass` deprecation...

[`Jekyll` Website re: `_sass`](https://jekyllrb.com/docs/assets/)

I enjoyed a few laughs reading this guy's **README**... [https://github.com/rawfunkmaharishi/rawfunkmaharishi.github.io](https://github.com/rawfunkmaharishi/rawfunkmaharishi.github.io) and he did have some decent info in there about Github Pages **years** ago.

Huh? [Parse CSS and add vendor prefixes to rules by Can I Use](https://github.com/postcss/autoprefixer)

Gleaning clues... [https://github.com/mmistakes/minimal-mistakes/issues/1114](https://github.com/mmistakes/minimal-mistakes/issues/1114)

As far as on HydeJack's site... nothing about that.

But there is some interesting stuff in here:

[https://hydejack.com/docs/advanced/#adding-a-custom-social-media-icon](https://hydejack.com/docs/advanced/#adding-a-custom-social-media-icon)

![2020-01-14-163005.png](https://i.imgur.com/W5y6Qoj.png)

I did not know about [IcoMoon](https://icomoon.io/).

Of course, there's an [APP](https://icomoon.io/app/) for that.

and these docs... [https://icomoon.io/#docs](https://icomoon.io/#docs) may come in handy...

-----

#### RECOMMENDED VIDEOS:

- [Seattle Sucks Part 1: The Fall of Antifa ~ Slightly Offens*ve](https://www.youtube.com/watch?v=ebL6uyNX1ss)

- [Seattle Sucks Part 2: Antifa Strikes Back ~ Slightly Offens*ve](https://www.youtube.com/watch?v=hY5UXHkGk6g)

- [VORTEX MATH NIKOLA TESLA 3 6 9 THE KEY TO UNIVERSE Part 1 and 2](https://www.youtube.com/watch?v=OXbVZc10lnk)

- [Choose Your Sacrifice - Jordan Peterson's Best Advice to Young Adults](https://www.youtube.com/watch?v=ZjI7vqizTRc)

- [Something Encodes Our Genetics Besides DNA](https://www.youtube.com/watch?v=6Ygl18fsChU)
