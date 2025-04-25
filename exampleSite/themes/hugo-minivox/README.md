---
title: README
author: 'David R. Worman <david@worman.com>'
date: '2025-04-14T23:37:10.372925-05:00'
---

# README for HUGO-MINIVOX v0.1.0
                                                                                                          
**Minivox** is a Hugo theme that is intended to display information on screen without a bunch of fancy fluff getting in the way. Additional information [here](http://hugo-minivox.worman.com/about).

### Installation:

in your Hugo themes directory:
```
git clone https://github.com/drworman/hugo-minivox
```
If you plan on using a custom 404 page, then:
```
mv 404.html ../../layouts/
```
and configure your webserver to redirect 404 to: *`yoursite.com/404`*

### Configuration:

In addition to the baseline configuration for Hugo, your configuration file (hugo.yaml or hugo.toml) should contain:

### hugo.yaml
```
params:
  description: "website description"
  footer: "&copy; [your name](http://www.you.com) {Year}"
  author: "W. Shakespeare"
  authorEmail: "willyshakes@thebard.com"

```
or

### hugo.toml
```
[params]
description = "website description"
footer = "&copy; [your name](http://www.you.com) {Year}"
author = "W. Shakespeare"
authorEmail = "willyshakes@thebard.com"
```
#### *Note:* You can leave the *author* parameter as a blank value `""` if you do not want a default author to be set for every article. In this case you can specify the author parameter in the frontmatter of your markdown on a per post basis.

[![Screenshot](https://github.com/drworman/hugo-minivox/raw/master/images/screenshot.png)](http://hugo-minivox.worman.com)
