---
layout: post
title: "Getting YAML support for TextMate 2"
description: ""
category: Jekyll 
tags: [YAML, SL, TextMate]
---
{% include JB/setup %}

I still use OS X 10.6 (when I use a Mac at all!), and since I've been using TextMate 2 as my editor, I need to use the [unnofficial build](https://github.com/nanoant/textmate/downloads) for my platform. Most of the time TM works fine and I'm happy using it. Recently I've been experimenting with Jekyll, so I thought it may be nice to have some YAML support for it, but I found that enabling bundles was a problem, see [this issue](https://github.com/textmate/textmate/issues/85). The solution here was pretty simple, in my case I just cloned [the yaml.tmbundle repository](https://github.com/textmate/yaml.tmbundle) into `~/Library/Application\ Support/TextMate/Managed/Bundles/` with git and _voila_ all my `.yml` files look much better. Since the issue on GitHub seems to effect earlier builds, I assume that this is not a platform specific issue, but one that has been corrected in later builds. 
