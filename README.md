# README for HUGO-MINIVOX v00.01.01
                                                                                                          
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

## Undocumented Feature

If you open statis/res/minivox.css in your favorite editor you will notice at the top this block of code:

```
@import url('/res/minivox-light.css');

/*
The filenames below refer to the base background color of each style.
Replace the @import line above with one of these to change the color scheme:

@import url('/res/minivox-dark.css');
@import url('/res/minivox-light.css');
@import url('/res/minivox-blue.css');
@import url('/res/minivox-green.css');
@import url('/res/minivox-purple.css');
@import url('/res/minivox-red.css');
@import url('/res/minivox-white.css');
*/
```

Hugo-Minivox ships with a number of color schemes ready to go for you, and if you view one of the schemes above you will see just how easy it is to develop and deploy your own custom colors with this theme as well.

[![Screenshot](https://github.com/drworman/hugo-minivox/raw/main/static/images/screenshot.png)](http://hugo-minivox.worman.com)
