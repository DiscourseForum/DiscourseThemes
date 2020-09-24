---
title: Discourse Gifs component
author: Rafael dos Santos Silva
homepage: https://github.com/discourse/discourse-gifs
download: https://github.com/discourse/discourse-gifs
demo: 
thumbnail: /images/158738/thumbnail.png
license: 
license_link: 
category: Theme Components
meta_topic_id: 158738

---


Repository at https://github.com/discourse/discourse-gifs.git

```text
https://github.com/discourse/discourse-gifs.git
```

Installation instructions: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682.

After installing you need to [change a site setting](https://meta.discourse.org/t/discourse-gifs-component/158738/17?u=falco). This is mandatory.

# Discourse Gifs

This theme component add a button to the composer that allows you to search for gifs and easily add the best one to your post.

![image: 690x195](/images/158738/fvh4R0wvkG3iRX9ipYs2Ke6OhRD.png) 


![image: 690x407](/images/158738/AoyyjBE3CIKDqWLluY2H3dbgMV2.jpeg) 


Clicking one one inserts it on your current composer, which looks like:

<div data-theme-discourse-gifs="container"><video muted loop autoplay playsinline disableRemotePlayback disablePictureInPicture width="500" height="280" poster="https://media.tenor.com/images/a5ca165d8a8ae869bce94a1857c4b003/raw"  alt="want" title="want"><source src="https://media.tenor.com/videos/16da6ce085d1c9a559622d38f3898c1b/mp4"></video><img src="https://media.tenor.com/videos/16da6ce085d1c9a559622d38f3898c1b/mp4" width="500" height="280"></div>


### Details

This is heavily based on a old fork of [ReplyGif: Adding reaction GIF easily](https://meta.discourse.org/t/replygif-adding-reaction-gif-easily/33195), so thanks to @cpradio. The big differences are:

- It uses videos instead of gifs, so it's a lot more efficient for bandwidth.

- It is a theme-component, so it is way easier to install and update.

- It uses the Tenor API

- No need to fiddle with nginx to setup a proxy for HTTPS


### To Do

- Infinite Scrolling for results