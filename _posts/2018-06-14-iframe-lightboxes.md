---
title: Iframe Lightboxes
author: Joe
homepage: https://github.com/hnb-ku/discourse-iframe-lightboxes
download: https://github.com/hnb-ku/discourse-iframe-lightboxes
demo: 
thumbnail: /images/89853/thumbnail.jpg
license: GNU General Public License v2.0
license_link: https://github.com/hnb-ku/discourse-iframe-lightboxes/blob/master/LICENSE
category: Theme Components
meta_topic_id: 89853

---
This is a desktop-only theme component that adds the ability to open iframes in lighboxes

[Github repository link](https://github.com/hnb-ku/discourse-iframe-lightboxes) 

`https://github.com/hnb-ku/discourse-iframe-lightboxes`

<hr>

This component adds an "expand" button on top of iframes you enable it on:

![Capture2: 689x370](/images/89853/itwN4qCk2iwdQUzMpgPs8OiQHW3.jpg)

Clicking the button will open the iframe in fullscreen in a lightbox:

![Capture3: 690x416](/images/89853/nvPD3NZvGFoBuWymM4lALkPryj0.PNG)

Clicking either the dark area around the iframe or the *x* at the top right corner closes the lightbox. The same way it works for default image lightboxes.

<hr> 

**Settings** 

You target the iframes based on their origin domains in the component's settings:

![Capture4: 690x176](/images/89853/rJPYtBtoT21jwFmX7flXN8Hd1Hx.PNG)

:warning: Whatever domains you specify here also need to be whitelisted in the `allowed_iframes` setting to show up in posts in the first place. 

<hr>

**Usage examples:**

Here's a couple of examples besides the CodePen iframe above

Google forms iframe: 

![Capture5: 690x424](/images/89853/8IVl5NmaRomFD3YU6U8fWcfpMPZ.jpg)

Embedding the entire weather.gov website: 

![Capture: 690x379](/images/89853/skCZfulhoyTgW9aCpazHsBeWO9e.PNG)

<hr>

**How do I install this?** 

You install this component just like any other theme. Follow the instructions in the official guide:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

Once you're done, simply add the component to your current theme. Done!

<hr>

## Credit:

This component uses [Noël Bossart's](https://noelboss.com/) fantastic [Featherlight](https://noelboss.github.io/featherlight/) library (MIT license - 3kb gzip)