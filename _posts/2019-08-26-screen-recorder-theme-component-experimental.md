---
title: Screen recorder theme component (experimental)
author: David Taylor
homepage: https://github.com/davidtaylorhq/discourse-media-recorder-theme
download: https://github.com/davidtaylorhq/discourse-media-recorder-theme
demo: https://theme-creator.discourse.org/theme/david/media-recorder
thumbnail: 
license: 
license_link: 
category: Theme Components
meta_topic_id: 126835

---
**Experimental** - not recommended for use on production sites (see below)

This theme component allows you to record your screen directly into the Discourse composer, using the [MediaRecorder API](https://developer.mozilla.org/en-US/docs/Web/API/MediaStream_Recording_API). 

[:link: Source](https://github.com/davidtaylorhq/discourse-media-recorder-theme)

[:paintbrush: Demo](https://theme-creator.discourse.org/theme/david/media-recorder)

To use, you need to add `webm` as a supported file format in your site settings.

Demonstration:

https://d11a6trkgmumsb.cloudfront.net/original/3X/3/3/339d1824ee7afeecfc33ce31f68eada697a10044.mp4 

Known issues:

- Recording videos is [only supported on Firefox and Chrome](https://caniuse.com/#feat=mediarecorder). (Safari coming in next version)

- Playing back the recorded videos (webm format) is not supported on mobile or desktop safari

- There is no file size indicator or limit, so if the video is too long it can cause an error when uploading

- There is no progress indicator when uploading

Hopefully browser support will eventually improve, so that this is usable. The same technique could be  adapted to record sound, or webcam video.