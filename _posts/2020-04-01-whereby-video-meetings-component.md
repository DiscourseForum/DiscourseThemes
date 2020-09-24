---
title: Whereby video meetings component
author: Rafael dos Santos Silva
homepage: https://github.com/discourse/discourse-whereby
download: https://github.com/discourse/discourse-whereby
demo: 
thumbnail: /images/146482/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-whereby/blob/master/LICENSE
category: Theme Components
meta_topic_id: 146482

---


### What this does?

https://whereby.com/

This component allows embedding Whereby video conference calls into Discourse posts.

### Installation

For the component itself follow https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 with the repository at https://github.com/discourse/discourse-whereby.

On the Whereby side, **you need to [contact](https://whereby.com/information/product-api/) their team in order to be able to use the integration**. They need to register your Discourse domain on their system, so when you pass your `iframeSource` the Discourse domain comes in the `Content-Security-Policy: frame-ancestors` list. I'm not sure what Whereby tiers have this feature available, so please contact their team and let us know in the replies.


### Features

Whereby supports video calls directly from the browser on every modern browser, even the mobile ones, making it very appealing to Discourse users.

Configuration options: 

- admins can restrict the composer button only to staff
- adds a composer toolbar icon (can be limited to staff only in component's settings)
- displays a button with a configurable icon and label in posts 
- compatible with Whereby custom subdomains

Screenshots: 

![image: 608x500](/images/146482/1DUHmI6iAU484frnDO4GXMscDYA.png) 

![image: 584x500](/images/146482/akG3dj0Ai9HZt90HoWrCYu54S1D.jpeg) 

![image: 642x500](/images/146482/s21KiRBx75SYIwLN2WkGx1TUWqg.jpeg)

### Acknowledgements

This component is heavily based in the [Jitsi video conference component](https://meta.discourse.org/t/jitsi-video-conference-component/146046).

This component was only possible with the help from Caleb of the Whereby team.