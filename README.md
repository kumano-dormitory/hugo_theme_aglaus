![screenshot](https://raw.githubusercontent.com/dim0627/hugo_theme_aglaus/master/images/screenshot.png)

# Features

* Google Analytics
* Disqus
* Share Buttons(fb, twitter, google+, pocket)
* Eye-catching Image
* MicroData
* Readable text(Customized Vertical Rhythm).

# Installation

Navigate to your Hugo site folder and run the following commands :

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/dim0627/hugo_theme_aglaus.git aglaus


# Configuration

**config.yaml**

``` toml
baseurl = "http://hugo.spf13.com/"
title = "Hugo Themes"
author = "Steve Francia"
copyright = "Copyright (c) 2008 - 2014, Steve Francia; all rights reserved."
canonifyurls = true
paginate = 3

[params]
  disqusShortname = "your disqus id." # optional
  toc = true # optional, When set to TRUE this parameter, table of contents appears in all articles.
```

**example post**

``` toml
+++
title = "Getting Started with Hugo"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2014-04-02"
categories = [
    "Development",
    "golang",
]

image = "image.jpg" # optional
toc = true # optional, When set to TRUE this parameter, table of contents appears in only this article.
+++

Contents here
```

# Contact us

Please mail to `dim0627@gmail.com` or SNS.

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

