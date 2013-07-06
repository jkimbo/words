---
title: Wintersmith
author: jkimbo
date: 2013-07-07
template: article.jade
---

Being a nerd I had better briefly go over the tech behind this new blog. As the
title suggests I am using a static site generator called
[wintersmith](http://wintersmith.io/) which is based
[node.js](http://nodejs.org/) and is written in
[coffeescript](http://jashkenas.github.io/coffee-script/). 

<span class="more"></span>

Since I am a big fan of JavaScript the fact it is written in node is appealing
and reason I chose it over other options such as [Jekyl](http://jekyllrb.com/).
I also chose a static site generator over a more traditional blog such as
Wordpress or Tumblr because I like the flexibility of it. I can change the look
and feel of a particular post to create amazing mini articles in the style of
[Trent Walton](http://trentwalton.com/). Well that is if I ever get that
creative. Also it allows me to write my posts in my favourite editor, vim, which
I love. 

To get started with wintersmith you will need node installed on your machine.
You can follow one of the easy install [methods](http://nodejs.org/download/) or
if you are on Linux, like I am, then download the source and compile. To install
wintersmith there are
[instructions](https://github.com/jnordberg/wintersmith#quick-start) on the
github page that are easy enough to follow. They will set you up with a simple
site that you can configure through the `config.json` file in the root
directory. It also provides you with some example posts that show what it can
do. Once you have got rid of them and added a couple of your own literary
masterpieces then run `wintersmith preview` to see them in the default theme
that I am currently running (this will hopefully change in the near future but
is good enough to start with). When you are happy with it all run `wintersmith
build` to output your static files to the `build/` directory which you can copy
to your server. 

This is only my second post using wintersmith but so far I am liking it. It also
looks like it is pretty extensible so I am looking forward to hacking it a bit
to get it to do some cool stuff for me. I also need to set up a more automated
way of uploading the build folder to my server. Probably using something like
[Grunt](http://gruntjs.com/) which I am currently in love with. Oh also the
whole blog code is available on [GitHub](https://github.com/jkimbo/words).
