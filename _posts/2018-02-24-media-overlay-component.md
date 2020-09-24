---
title: Media Overlay component
author: David Taylor
homepage: https://github.com/davidtaylorhq/discourse-media-overlay-theme
download: https://github.com/davidtaylorhq/discourse-media-overlay-theme
demo: 
thumbnail: 
license: GNU General Public License v3.0
license_link: https://github.com/davidtaylorhq/discourse-media-overlay-theme/blob/master/LICENSE
category: Theme Components
meta_topic_id: 81418

---
Continuing from https://meta.discourse.org/t/media-overlay-plugin/60549...

# [Discourse Media Overlay Theme](https://github.com/davidtaylorhq/discourse-media-overlay-theme)

This theme component allows users to “pop out” media into a floating window while they browse the site. They can even navigate to a different topic and the media will continue working.

It works with any  `<iframe>`  or  `<video>`  (with some special treatment for lazyYT). It adds a button to every compatible thing, which then opens a little popup in the bottom right.

You can then “minimise” it, which keeps the audio going in the background, or completely close it.

![|320x255](https://d11a6trkgmumsb.cloudfront.net/original/3X/8/3/83b42b39445e04ed97987f87bb313fb5495507ac.gif)

At the moment the size of the video is decided by the original embed. I’d like to add a “resizing” feature, either a “click and drag”, or just simply 3 buttons “small”, “medium”, “large”.

Currently this obscures the composer… simple solution is to just close the popup if you want to write a post :wink:.

# Installation

The theme URL is 
```text
https://github.com/davidtaylorhq/discourse-media-overlay-theme
```

To install, follow these instructions:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682?source_topic_id=76662