# README for HUGO-MINIVOX v0.1.1
                                                                                                          
**Minivox** is a Hugo theme that is intended to display information on screen without a bunch of fancy fluff getting in the way. Additional information [here](http://hugo-minivox.worman.com/about).

### Installation:

in your Hugo themes directory:
```
git clone https://github.com/drworman/hugo-minivox
```

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

[![Screenshot](https://github.com/drworman/hugo-minivox/raw/main/static/images/screenshot.png)](http://hugo-minivox.worman.com)
