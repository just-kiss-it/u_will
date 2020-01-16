---
layout: post
title: "Took It Easy Today"
date: "2020-01-15"
author: "***`'Just-Kiss-It'`***"
image: https://i.imgur.com/oOVRaDR.jpg
---

### Editing...

**My entire life needs a re-write!** Alas, re-writes suck. So does editing. Maybe I won't.

![2020-01-15-090300.png](https://i.imgur.com/Tj4KqOR.png)

But I *will* make some small changes in habit and form...

I'm changing a bunch of images and cleaning cruft...

![2020-01-15-171032.png](https://i.imgur.com/EpmXR0p.png)

### Seriously considering dropping my content into another theme.
`HydeJack` will not work for me long-term. Maybe for a 100 page blog, but it's slow and bloated, even though I forked the [`hydejack-starter-kit`](https://github.com/hydecorp/hydejack-starter-kit). *( is is smooth though!)* I really gotta give the guy, Florian, props though. I **do** like his theme. I'm just not skilled enough to fully understand it! Check out Florian's website: [https://qwtel.com/](https://qwtel.com/). You'll see that he has replaced image tags with custom elements and has some nice coded goodies on there that I want! Anyway, if I was just writing 100 articles or less this would be a perfect theme. But I'm looking for alternatives now, before I waste too much time customizing *this* one!

Speaking of customizing... Press this button:

[8kun.top/FreedomZine/](https://8kun.top/freedomzine/){: .btn} will take you to a comment board where you can make your own threads and comment to your heart's delight!

The code for the button is really sublime:

```
[8kun.top/FreedomZine/](https://8kun.top/freedomzine/){: .btn}
```
Hmmm... Lemme try *this* too...
```
{% include button.html url="https://8kun.top/freedomzine/" %}
```

Just press on the bar... {% include button.html url="https://8kun.top/freedomzine/" %}

And now this...
```
{% include button.html button_name="8kun" button_class="outline-primary" url="https://8kun.top/freedomzine/" %}
```

{% include button.html button_name="8kun" button_class="outline-primary" url="https://8kun.top/freedomzine/" %}

### I think the first way was the way to do it.

#### BTW, I added in a `'button.html'` file in `'_includes'` with the following info for those buttons...

```
<button type="button" onclick="window.location='{{include.url}}'" class="btn btn-{{include.button_class}} active">{{include.button_name}}</button>

```

Alright. Stop getting sidetracked! Nice little discussion though... [https://stackoverflow.com/questions/40688633/how-can-i-add-a-button-in-a-md-file-with-jekyll](https://stackoverflow.com/questions/40688633/how-can-i-add-a-button-in-a-md-file-with-jekyll)

-----

### The [`minimal-mistakes` theme](https://mmistakes.github.io/minimal-mistakes/) **is** pretty nice!

#### Here's the Quick-Start Guide: [https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

While researching the [`minimal-mistakes` theme](https://mmistakes.github.io/minimal-mistakes/) I ran across this [`minimal-mistakes` issue](https://github.com/mmistakes/minimal-mistakes/issues/2347) that kinda helps me understand the **`'_sass'`** problem I've been having -- as in, from what I can understand, nobody understands it! Many more knowledgeable minds than mine don't yet grok the issue; and really, other than throwing up errors, I haven't noticed any ill effects myself.

-----

![2020-01-16-065747.png](https://i.imgur.com/4m2gLx9.png)

-----

Good Stuff On This Whole Site: [https://kiazhi.github.io/blog/git/Working-on-Git-repository-branches](https://kiazhi.github.io/blog/git/Working-on-Git-repository-branches)

Here's all the `Jekyll` themes that work *out-of-the-box* with Github Pages: [https://jekyllthemes.io/github-pages-themes](https://jekyllthemes.io/github-pages-themes)

Is that another way of saying [Supported Themes](https://pages.github.com/themes/)???

Maybe Peruse ***THIS*** Site... [https://www.foxinfotech.in/2019/12/how-to-create-a-blog-using-github-pages-and-jekyll-with-a-few-clicks.html](https://www.foxinfotech.in/2019/12/how-to-create-a-blog-using-github-pages-and-jekyll-with-a-few-clicks.html)

If you're still deciding on which static site generator you should pick you will **definitely** want to check out ***this*** site: [https://www.staticgen.com/](https://www.staticgen.com/) (*or watch this video:* [Selecting the best static site generator for your blog](https://www.youtube.com/watch?v=EqdRW3I7CIc) by [Pluralsight.com Courses ~ static-site-generator-build-better-blog](https://www.pluralsight.com/courses/static-site-generator-build-better-blog)

-----

### As for some ***REALLY COOL VIDEOS :***

This [Insane Video Game Graphics From The Future!](https://www.youtube.com/watch?v=2ECocYt70Oc) Video is 10 min. of ***AMAZING WORK.***

I actually want to try  what is described in this video: [Why You Should Learn Natural Language Processing (NLP) with Hugging Face](https://www.youtube.com/watch?v=MMVCN2zMRzA) Maybe I'll use `HuggingFace` to write an article, just for fun! ***I'm sure that AI can't do any worse at writing than me!***

- [https://transformer.huggingface.co/](https://transformer.huggingface.co/)

And you ***KNOW*** I'm not gonna leave you without at least *one* good music link! Maybe I'll make a button for playing musical excerpts while you read these lengthy blog posts! *(yes, I'm still playing... See button above!)*

- [**Larkin Poe** ~ The Shadows Cover ("Apache")](https://www.youtube.com/watch?v=o7rDXhrlFAQ)

That gave me an idea, and now I need to find somewhere to host some music files for free that I can hotlink to. Hmmm... Probably get slammed for Copyright or something. *I don't understand all da rools & regs!* Aren't files like rabbits? [Steal This Film 1 & 2](https://www.youtube.com/watch?v=YJ2Fh3tAD-I) may change your mind about copyright laws. It changed mine many years ago.

But I just have something to say about **Larkin Poe**. Wow. I love their music and talent. I've got to link to my favorite song by [Larkin Poe - Mad As A Hatter](https://www.youtube.com/watch?v=dGEjbJkxFhs) for you. ***Just watch it and thank me later...***

And here's the music video for the song I'm thinking of putting on the button at the top of the page... [Fuck All The Perfect People - Chip Taylor & The New Ukrainians](https://www.youtube.com/watch?v=dt9GBafFzjE); but no, I'll find a more *'appropriate'* one for that -- but I still ***highly*** recommend you watch the video; and while you're at it, don't miss [F**k All The Perfect People Part II (The Last Video) - Chip Taylor](https://www.youtube.com/watch?v=0xK5YHU2-jY).

Kinda still need a place to host the files. This entire blog is still only 23 MB and I haven't even finished cleaning yet! I would like to keep it small -- so, *'hot-linking',* amirite?

The link [https://sndup.net/9rqw](https://sndup.net/9rqw) leads to an .mp3 file I uploaded to [sndup.net](https://sndup.net)... [Clap Your Hands](https://sndup.net/9rqw) by 'The Reverend Peyton's Big Damn Band'. I'll use it for the button, I guess.  You should really watch their video over at [https://www.youtube.com/watch?v=9Ra0DsbiNs0](https://www.youtube.com/watch?v=9Ra0DsbiNs0). I really don't think they would want anyone to waste their time asking for permission to help spread their music!

*(see how my `Notes` are bleeding into my `Blog` again? **watch that!**)*

But no, not going to make a button or have *'mood music'* or anything like that!

Just playing around today, obviously! Maybe I'll go do some cleanup and organization. I've done enough damage here...

### Do You Think I Posted Enough Links Today?
