+++
title = "Hello World"
date = "2023-10-27T19:56:42+02:00"
author = "Marcel Müller"
authorTwitter = "" #do not include @
cover = ""
tags = ["static-site-generator", "cloudflare"]
keywords = ["", ""]
description = "Just a first try"
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

# Welcome
This are my first steps playing with [Hugo](http://gohugo.io).

The terminal theme should offer simple ways to include picture...
{{< image src="/img/atari520st.jpg" alt="My first friend" position="center" style="border-radius: 8px;" >}}

... and code:
{{< code language="css" title="Really cool snippet" id="1" expand="Show" collapse="Hide" isCollapsed="true" >}}
pre {
background: #1a1a1d;
padding: 20px;
border-radius: 8px;
font-size: 1rem;
overflow: auto;

@media (--phone) {
white-space: pre-wrap;
word-wrap: break-word;
}

code {
background: none !important;
color: #ccc;
padding: 0;
font-size: inherit;
}
}
{{< /code >}}
