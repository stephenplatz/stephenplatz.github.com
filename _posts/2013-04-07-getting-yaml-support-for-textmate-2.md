---
layout: post
title: "Getting YAML support for TextMate 2"
description: ""
category: Jekyll 
tags: [YAML, SL, TextMate]
---
{% include JB/setup %}

I still use OS X 10.6 (when I use a Mac at all!), and since I've been using TextMate 2 as my editor, I need to use an [unofficial build](https://github.com/nanoant/textmate/downloads). Most of the time so far TM works fine and I'm happy using it. Recently I've been experimenting with Jekyll for this blog, so I thought it may be nice to have some YAML support for it, but I found that sometimes enabling bundles [causes TextMate to hang](https://github.com/textmate/textmate/issues/85). The solution is pretty simple, in my case I just cloned [the yaml.tmbundle repository](https://github.com/textmate/yaml.tmbundle) into `~/Library/Application\ Support/TextMate/Managed/Bundles/` with git and _voila_ all my `.yml` files are now parsed correctly in the editor. 
