---
layout: post
title: "`Just-Kiss-It`.github.io/`U_Will`"
date: "2020-01-09"
author: JKI
image: /assets/img/blog/2020-01-09/2020-01-09-183851.png
---

### *((('They')))* cannot stand in *your* way...
#### for **U** are the Master of The Temple.
##### [Just-Kiss-It.github.io/U_Will](https://just-kiss-it.github.io/u_will) seems like as good a place as *any* to start something, so here we go!
###### Description: "JKI giraffes around w/ `Jekyll`, `gh-pages`" and `HydeJack` Template"

### GIRAFFISMS :

> Hollywood Celebrities are using their public platforms like *'casting couches'* to conformity.

---

> ###### LIFE AFTER LIFE?
You gotta be a special kind of stupid to believe in that! It's right in the name! There ain't no life after life! It's the very opposite of living. So ya better learn how to live ***now!*** *(stop acting like you're already dead...)*

---

> Choosing a *'persona'*, a *'personality'*, an *'ego'* (especially an *'YUUUGE'* one!) as one's leader does not always go smoothly.
> ###### EGO...
> ***'This Is Why We Cannot Have Nice Things.'***

---

### Just Rid Yourself of `Google` **COMPLETELY** ***NOW!***
Here's kind of a chilling story... [
https://www.chicagotribune.com/news/criminal-justice/ct-jussie-smollett-special-prosecutor-investigation-20200108.html](https://www.chicagotribune.com/news/criminal-justice/ct-jussie-smollett-special-prosecutor-investigation-20200108-j3j3p2dypvf5vbbo5jpxrvcjsq-story.html)

All the more reason to get rid of `Google` completely!

Just because you're a lying, irresponsible, race-baiting xenophobe does not mean that ***all*** your data should be sifted through with a fine-tooth comb by people whose only real job is to determine how much of a liar you are in that **one** regard -- not **all** of them! *(and yes, you're a liar too.)* There is no end to the data the powers-that-be want to have access to -- ever more control of the populace...

-----

and if you thought there *was* such a thing as ***'REAL'***...

[Exclusive: Samsung's NEON Revealed - Leaked Trailer Looks Perfectly Human!](https://www.youtube.com/watch?v=Q6f6EXX-79w) Wow.

-----

### Hilarious Links that are ***'WORTH IT'*** :


[Ricky Gervais' Monologue at the 2020 Golden Globes](https://www.youtube.com/watch?v=LCNdTLHZAeo); where Hollywood Gets Roasted!
> "*I Don't Care!*" Either, Ricky!

[Dave Chappelle's Acceptance Speech for the 2019 Mark Twain Prize](https://www.youtube.com/watch?v=FwyeYmXjD1A) was ***SO 'WORTH IT'!*** I love that man.

Jon Stewart does too... as this video... [Jon Stewart on Dave Chappelle re: 2019 Mark Twain Prize](https://www.youtube.com/watch?v=FAJG0bzvx-Q) demonstrates. Pretty darn funny.

-----

So, after taking care of some health concerns (and driving my girlfriend away by forcefully focusing on computer-crap), I forked the [`hydejack-starter-kit`](https://github.com/hydecorp/hydejack-starter-kit) and renamed it to **'U_Will'**. I then changed it over to the **`gh-pages` Branch**, deleted my **Master Branch**, then cloned the **`gh-pages` Branch** to my local machine, whereupon I did all my `jekyll`y magic on it *(see below)* so I could add, push and commit to Github from my local machine into the **`gh-pages` Branch**. Whew!

You too can clone whatever I do! I'm leaving it all open...

```
git clone https://github.com/just-kiss-it/u_will.git
```

After cloning locally, I took a break, got irritated with myself for not reaching a good enough stopping point, and irked with my girlfriend just for being a distraction, (as though that is not sometimes a *good* thing!); but then I got back to it...

Made this command in the directory I cloned into...

    bundle install

But oops...

![2020-01-09-175729.png](https://i.imgur.com/rPBuPBq.png)

So I did < `bundle update --bundler` >. Wew lad!

```
jki@jki-pc:~/Just-Kiss-It/u_will$ bundle update --bundler
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.                                                                                     
Fetching gem metadata from https://rubygems.org/.........
Fetching public_suffix 3.0.3
Installing public_suffix 3.0.3
Fetching addressable 2.5.2
Installing addressable 2.5.2
Using bundler 2.1.4
Using colorator 1.1.0
Fetching concurrent-ruby 1.1.4
Installing concurrent-ruby 1.1.4
Using eventmachine 1.2.7
Using http_parser.rb 0.6.0
Using em-websocket 0.5.1
Fetching multipart-post 2.0.0
Installing multipart-post 2.0.0
Fetching faraday 0.15.4
Installing faraday 0.15.4
Fetching ffi 1.10.0
Installing ffi 1.10.0 with native extensions
Using forwardable-extended 2.6.0
Fetching i18n 0.9.5
Installing i18n 0.9.5
Using rb-fsevent 0.10.3
Fetching rb-inotify 0.10.0
Installing rb-inotify 0.10.0
Fetching sass-listen 4.0.0
Installing sass-listen 4.0.0
Fetching sass 3.7.3
Installing sass 3.7.3
Fetching jekyll-sass-converter 1.5.2
Installing jekyll-sass-converter 1.5.2
Fetching ruby_dep 1.5.0
Installing ruby_dep 1.5.0
Fetching listen 3.1.5
Installing listen 3.1.5
Fetching jekyll-watch 2.1.2
Installing jekyll-watch 2.1.2
Fetching kramdown 1.17.0
Installing kramdown 1.17.0
Fetching liquid 4.0.2
Installing liquid 4.0.2
Using mercenary 0.3.6
Using pathutil 0.16.2
Fetching rouge 3.3.0
Installing rouge 3.3.0
Using safe_yaml 1.0.5
Fetching jekyll 3.8.5
Installing jekyll 3.8.5
Fetching jekyll-avatar 0.6.0
Installing jekyll-avatar 0.6.0
Fetching jekyll-default-layout 0.1.4
Installing jekyll-default-layout 0.1.4
Fetching jekyll-feed 0.11.0
Installing jekyll-feed 0.11.0
Fetching sawyer 0.8.1
Installing sawyer 0.8.1
Fetching octokit 4.13.0
Installing octokit 4.13.0
Fetching jekyll-gist 1.5.0
Installing jekyll-gist 1.5.0
Fetching jekyll-optional-front-matter 0.3.0
Installing jekyll-optional-front-matter 0.3.0
Fetching jekyll-paginate 1.1.0
Installing jekyll-paginate 1.1.0
Fetching jekyll-readme-index 0.2.0
Installing jekyll-readme-index 0.2.0
Fetching jekyll-redirect-from 0.14.0
Installing jekyll-redirect-from 0.14.0
Fetching jekyll-relative-links 0.6.0
Installing jekyll-relative-links 0.6.0
Fetching rubyzip 1.2.2
Installing rubyzip 1.2.2
Fetching jekyll-remote-theme 0.3.1
Installing jekyll-remote-theme 0.3.1
Fetching jekyll-seo-tag 2.5.0
Installing jekyll-seo-tag 2.5.0
Fetching jekyll-sitemap 1.2.0
Installing jekyll-sitemap 1.2.0
Fetching jekyll-titles-from-headings 0.5.1
Installing jekyll-titles-from-headings 0.5.1
Warning: the lockfile is being updated to Bundler 2, after which you will be unable to return to Bundler 1.
Bundle updated!
Post-install message from sass:

Ruby Sass is deprecated and will be unmaintained as of 26 March 2019.

* If you use Sass as a command-line tool, we recommend using Dart Sass, the new
  primary implementation: https://sass-lang.com/install

* If you use Sass as a plug-in for a Ruby web framework, we recommend using the
  sassc gem: https://github.com/sass/sassc-ruby#readme

* For more details, please refer to the Sass blog:
  http://sass.logdown.com/posts/7081811

jki@jki-pc:~/Just-Kiss-It/u_will$

```
Shite! Now what ?!!! I feel like I should have done `bundle exec jekyll serve` first. Grrr... Gonna try `bundle install` again... And voila!

```
Bundle complete! 15 Gemfile dependencies, 44 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
jki@jki-pc:~/Just-Kiss-It/u_will$
```

![2020-01-09-183851.png](https://i.imgur.com/lfG1NOV.png)

Now `bundle exec jekyll serve`...

Hmmm...

Well, that didn't work...

Guess I will run

< `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java` >

then...

`bundle update --bundler` again, I hope I'm doing this right?
> frickin' `ruby`... grrr...

No warnings, though, so... `bundle install` again...

Then `bundle exec jekyll serve`... but...

```
jki@jki-pc:~/Just-Kiss-It/u_will$ bundle exec jekyll serve
Configuration file: /home/jki/Just-Kiss-It/u_will/_config.yml
Invalid theme folder: _sass
      Remote Theme: Using theme qwtel/hydejack
            Source: /home/jki/Just-Kiss-It/u_will
       Destination: /home/jki/Just-Kiss-It/u_will/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
Invalid theme folder: _sass
      Remote Theme: Using theme qwtel/hydejack
       Jekyll Feed: Generating feed for posts
                    done in 3.636 seconds.
 Auto-regeneration: enabled for '/home/jki/Just-Kiss-It/u_will'
    Server address: http://127.0.0.1:4000/u_will/
  Server running... press ctrl-c to stop.
```
Guess I'll have to chase that '**_sass**' problem down. I think there were a couple websites mentioned above.

On the plus side though, I was able to get the website up and running on Port 4000! That means I am pretty much there.

Gonna do some changes locally this evening, do some add, commit, push action to Github, and I am ready to begin on this journey! *(whatever it is...)*

And what local changes did I make of import? Well, I edited the **Gemfile**...

*Commented* ***out*** the

    # gem "jekyll"

line; and *Commented* ***in*** the

    gem "github-pages", group: :jekyll_plugins

line...

Then did another `bundle exec jekyll serve --livereload`...

![2020-01-09-195827.png](https://i.imgur.com/wpTUBPM.png)

So, you can see how the `bundle install` command went for me.

But then, when I did `bundle update`? Grrr...

```
jki@jki-pc:~/Just-Kiss-It/u_will$ bundle update
Fetching gem metadata from https://rubygems.org/...........
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies.......................
Using concurrent-ruby 1.1.5 (was 1.1.4)
Using i18n 0.9.5
Fetching multi_json 1.14.1
Installing multi_json 1.14.1
Fetching activesupport 3.2.22.5
Installing activesupport 3.2.22.5
Fetching public_suffix 3.1.1 (was 3.0.3)
Installing public_suffix 3.1.1 (was 3.0.3)
Using addressable 2.7.0 (was 2.5.2)
Using bundler 2.1.4
Fetching coffee-script-source 1.11.1
Installing coffee-script-source 1.11.1
Fetching execjs 2.7.0
Installing execjs 2.7.0
Fetching coffee-script 2.4.1
Installing coffee-script 2.4.1
Using colorator 1.1.0
Fetching ruby-enum 0.7.2
Installing ruby-enum 0.7.2
Fetching commonmarker 0.17.13
Installing commonmarker 0.17.13 with native extensions
Fetching dnsruby 1.61.3
Installing dnsruby 1.61.3
Using eventmachine 1.2.7
Using http_parser.rb 0.6.0
Using em-websocket 0.5.1
Using ffi 1.11.3 (was 1.10.0)
Fetching ethon 0.12.0
Installing ethon 0.12.0
Fetching multipart-post 2.1.1 (was 2.0.0)
Installing multipart-post 2.1.1 (was 2.0.0)
Fetching faraday 1.0.0 (was 0.15.4)
Installing faraday 1.0.0 (was 0.15.4)
Using forwardable-extended 2.6.0
Fetching gemoji 3.0.1
Installing gemoji 3.0.1
Fetching sawyer 0.8.2 (was 0.8.1)
Installing sawyer 0.8.2 (was 0.8.1)
Fetching octokit 4.15.0 (was 4.13.0)
Installing octokit 4.15.0 (was 4.13.0)
Fetching typhoeus 1.3.1
Installing typhoeus 1.3.1
Fetching github-pages-health-check 1.16.1
Installing github-pages-health-check 1.16.1
Using rb-fsevent 0.10.3
Using rb-inotify 0.10.1 (was 0.10.0)
Using sass-listen 4.0.0
Fetching sass 3.7.4 (was 3.7.3)
Installing sass 3.7.4 (was 3.7.3)
Using jekyll-sass-converter 1.5.2
Using listen 3.2.1 (was 3.1.5)
Using jekyll-watch 2.2.1 (was 2.1.2)
Using kramdown 1.17.0
Using liquid 4.0.3 (was 4.0.2)
Using mercenary 0.3.6
Using pathutil 0.16.2
Fetching rouge 3.13.0 (was 3.3.0)
Installing rouge 3.13.0 (was 3.3.0)
Using safe_yaml 1.0.5
Using jekyll 3.8.5
Fetching jekyll-avatar 0.7.0 (was 0.6.0)
Installing jekyll-avatar 0.7.0 (was 0.6.0)
Fetching jekyll-coffeescript 1.1.1
Installing jekyll-coffeescript 1.1.1
Fetching jekyll-commonmark 1.3.1
Installing jekyll-commonmark 1.3.1
Fetching jekyll-commonmark-ghpages 0.1.6
Installing jekyll-commonmark-ghpages 0.1.6
Using jekyll-default-layout 0.1.4
Using jekyll-feed 0.13.0 (was 0.11.0)
Using jekyll-gist 1.5.0
Fetching jekyll-github-metadata 2.12.1
Installing jekyll-github-metadata 2.12.1
Fetching mini_portile2 2.4.0
Installing mini_portile2 2.4.0
Fetching nokogiri 1.10.7
Installing nokogiri 1.10.7 with native extensions
Fetching html-pipeline 2.12.3
Installing html-pipeline 2.12.3
Fetching jekyll-mentions 1.5.1
Installing jekyll-mentions 1.5.1
Fetching jekyll-optional-front-matter 0.3.2 (was 0.3.0)
Installing jekyll-optional-front-matter 0.3.2 (was 0.3.0)
Using jekyll-paginate 1.1.0
Fetching jekyll-readme-index 0.3.0 (was 0.2.0)
Installing jekyll-readme-index 0.3.0 (was 0.2.0)
Fetching jekyll-redirect-from 0.15.0 (was 0.14.0)
Installing jekyll-redirect-from 0.15.0 (was 0.14.0)
Fetching jekyll-relative-links 0.6.1 (was 0.6.0)
Installing jekyll-relative-links 0.6.1 (was 0.6.0)
Fetching rubyzip 2.0.0 (was 1.2.2)
Installing rubyzip 2.0.0 (was 1.2.2)
Fetching jekyll-remote-theme 0.4.1 (was 0.3.1)
Installing jekyll-remote-theme 0.4.1 (was 0.3.1)
Using jekyll-seo-tag 2.6.1 (was 2.5.0)
Fetching jekyll-sitemap 1.4.0 (was 1.2.0)
Installing jekyll-sitemap 1.4.0 (was 1.2.0)
Using jekyll-swiss 1.0.0
Fetching jekyll-theme-architect 0.1.1
Installing jekyll-theme-architect 0.1.1
Fetching jekyll-theme-cayman 0.1.1
Installing jekyll-theme-cayman 0.1.1
Fetching jekyll-theme-dinky 0.1.1
Installing jekyll-theme-dinky 0.1.1
Fetching jekyll-theme-hacker 0.1.1
Installing jekyll-theme-hacker 0.1.1
Fetching jekyll-theme-leap-day 0.1.1
Installing jekyll-theme-leap-day 0.1.1
Fetching jekyll-theme-merlot 0.1.1
Installing jekyll-theme-merlot 0.1.1
Fetching jekyll-theme-midnight 0.1.1
Installing jekyll-theme-midnight 0.1.1
Fetching jekyll-theme-minimal 0.1.1
Installing jekyll-theme-minimal 0.1.1
Fetching jekyll-theme-modernist 0.1.1
Installing jekyll-theme-modernist 0.1.1
Fetching jekyll-theme-primer 0.5.4
Installing jekyll-theme-primer 0.5.4
Fetching jekyll-theme-slate 0.1.1
Installing jekyll-theme-slate 0.1.1
Fetching jekyll-theme-tactile 0.1.1
Installing jekyll-theme-tactile 0.1.1
Fetching jekyll-theme-time-machine 0.1.1
Installing jekyll-theme-time-machine 0.1.1
Fetching jekyll-titles-from-headings 0.5.3 (was 0.5.1)
Installing jekyll-titles-from-headings 0.5.3 (was 0.5.1)
Fetching jemoji 0.11.1
Installing jemoji 0.11.1
Using minima 2.5.1
Using unicode-display_width 1.6.0
Using terminal-table 1.8.0
Fetching github-pages 203
Installing github-pages 203
Bundle updated!
Post-install message from dnsruby:
Installing dnsruby...
  For issues and source code: https://github.com/alexdalitz/dnsruby
  For general discussion (please tell us how you use dnsruby): https://groups.google.com/forum/#!forum/dnsruby
Post-install message from sass:

Ruby Sass has reached end-of-life and should no longer be used.

* If you use Sass as a command-line tool, we recommend using Dart Sass, the new
  primary implementation: https://sass-lang.com/install

* If you use Sass as a plug-in for a Ruby web framework, we recommend using the
  sassc gem: https://github.com/sass/sassc-ruby#readme

* For more details, please refer to the Sass blog:
  https://sass-lang.com/blog/posts/7828841

Post-install message from html-pipeline:
-------------------------------------------------
Thank you for installing html-pipeline!
You must bundle Filter gem dependencies.
See html-pipeline README.md for more details.
https://github.com/jch/html-pipeline#dependencies
-------------------------------------------------
jki@jki-pc:~/Just-Kiss-It/u_will$

```
#### ***WEW LAD !***

```
Bundle complete! 15 Gemfile dependencies, 82 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
jki@jki-pc:~/Just-Kiss-It/u_will$
```
Yeah, I ran the `bundle install` and `bundle update` commands one more time just to make sure it loved me *(with all <u>those</u> gems, it damn well better!)*, then another `bundle exec jekyll serve --livereload`...

![2020-01-09-203434.png](https://i.imgur.com/sv3Utc4.png)

then started looking for things in the theme to tweak...

![2020-01-09-210755.png](https://i.imgur.com/qCQYNxs.png)

Go through some of the documentation provided at [https://hydejack.com/docs/config/#github-pages](https://hydejack.com/docs/config/#github-pages) and start making this theme yours.
> assumes he will not eventually end up having to change it anyway! ***lol***

*(I won't be laughing then...)*

But I **am** gonna go figure out how to start making posts and post this, then push and commit to Github before going to bed...

Maybe I should sleep first and get a fresh start in the morning. It would be easy to make a mistake at this point; especially with all that **Ruby** *'bs'* that went down and the Gemfile changes that triggered all that. Who ***knows*** how it will react when I commit all that crap to **Github!**

#### Kinda wish I had first figured out [how to set up a `Docker` container to work with `Jekyll` and run my Github Pages site](https://www.youtube.com/watch?v=6UAf8b_2juk) before all this, *now!*

Getting started with [<u>`Docker`</u>](https://www.docker.com/) is essential at this point anyway. **Just Do It.**

Gotta stick those pictures up on ***Imgur*** in the morning too... *(Better have a better long-term plan than that!)*

Evidently cloud storage is cheap nowadays. **But you *know* how I like me 'dem images!**

-----

#### Useful Bash Commands:
(do I need to tell you not to use the **" < "** or the **" > "** symbols in these commands?)

< `git clone` >

< `git add .` >

< `git commit -m "message here"` >

< `git push` >

< `git log` >

< `git checkout` >

< `bundle exec jekyll serve --livereload` >

-----

Because I feel I have so much to do, I don't want to waste time sleeping. But rest is as important as activity, and colors said activity too! It is of vital importance, and should therefore, be placed rather high on the priority list. As the direct result of so much frenetic activity I have sometimes found myself driven to the point of exhaustion, where rest is no longer a choice -- but not so often now! I am older, and somewhat wiser. The trouble is, the older I get, the faster I reach the point of exhaustion, yet the more I feel I have to do! Why can I not lay down my labors with grace? **For *WHY* Do I Still Labor?**
