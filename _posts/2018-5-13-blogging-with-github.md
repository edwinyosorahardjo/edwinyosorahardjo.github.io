---
layout: post
title: Blogging with GitHub and Jekyll
categories: [Jekyll]
tags: [blogging, jekyll, github pages]
---

After googling around and reading some articles, finally, I made myself a blog with Github and Jekyll.

There are many ways to setup the blog with github, the easiest one for now by forking [Jekyll Now](https://github.com/barryclark/jekyll-now). By following the instructions, I got my blog up in minutes.

### Setting Up Jekyll Now
Here is what I done:
1. Fork [Jekyll Now](https://github.com/barryclark/jekyll-now)
2. Rename it to edwinyosorahardjo.github.io
3. Create robots.txt with no crawl so that I can play around without being crawled.
4. Change _config.yml
5. Change or Create blog post using a [markdown syntax](https://daringfireball.net/projects/markdown/) under _post directory.
   The blog post is using yyyy-mm-dd-filename.md file pattern

### Basic [markdown syntax](https://daringfireball.net/projects/markdown/) that I used
<pre>
    # H1
    ## H2
    ### H3
    --- hr
    _emphasized_
    __strong__
    1. ordered list
    - unordered list
    [text](link)
</pre>

### Setting up Jekyll (from scratch)
Forking Jekyll Now was pretty easy, so, I up for a harder challenge to setup [Jekyll](https://jekyllrb.com/) from scratch to see how it goes.
1. Install [Ruby Rail] (https://www.ruby-lang.org/en/downloads/) 
. run the quick-start instruction from [Jekyll](https://jekyllrb.com/) website
<pre>
    gem install bundler jekyll
 
    jekyll new my-awesome-site

    cd my-awesome-site

    bundle exec jekyll serve
</pre>

2. Now browse to http://localhost:4000

Having a look the configuration and the need of a lot of reading, I ended up customizing Jekyll Now configuration and see the built version on my local.

### Other tools that I install
1. [Git](https://git-scm.com/downloads)
2. [Tortoise Git](https://tortoisegit.org/)
3. [Notepad++](https://notepad-plus-plus.org)
4. [Visual Studio Code](https://code.visualstudio.com/download)