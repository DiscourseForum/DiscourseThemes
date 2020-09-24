---
title: Topic list sidebar navigation
author: Kris
homepage: https://github.com/awesomerobot/discourse-sidebar-nav
download: https://github.com/awesomerobot/discourse-sidebar-nav
demo: https://theme-creator.discourse.org/theme/awesomerobot/sidebar-nav
thumbnail: /images/94056/thumbnail.png
license: GNU General Public License v2.0
license_link: https://github.com/awesomerobot/discourse-sidebar-nav/blob/master/LICENSE
category: Theme Components
meta_topic_id: 94056

---
![45%20PM: 690x263](/images/94056/tpAW6cIS7rTunqs4xnPxmPUylb2.png) 

:warning: _Because it uses modern CSS features, this component will not work in Internet Explorer (at all) or versions of Edge, Firefox, Safari, or Chrome that were released before May 2017 ([version details here](https://caniuse.com/#feat=css-grid))._

:microscope:  [Preview it on the theme creator](https://theme-creator.discourse.org/theme/awesomerobot/sidebar-nav)

:link:  [Github repo](https://github.com/awesomerobot/discourse-sidebar-nav): ` https://github.com/awesomerobot/discourse-sidebar-nav.git`

:man_shrugging: [How do I install a theme component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)


----
# What does this theme component do?

**The short version:** This takes our standard topic list navigation and puts it into a sticky sidebar (as long as your browser is wider than 768px). You also have the option in the settings to show the sidebar on the right.

**The long version:** We've talked about this layout a little bit on Meta previously (https://meta.discourse.org/t/proposing-a-left-aligned-slide-out-hamburger-menu/30287), and I was curious to see what it would be like to simply move our existing navigation to a sidebar. 

To build this I used a combination of grid, flexbox, and a value for `position` called `sticky`. Sticky is _very_ new to browsers ([version support](https://caniuse.com/#feat=css-sticky)), and as you'd guess, it makes an element sticky on scroll... the nice thing about it is that unlike `position: fixed`, it doesn't take your element out of its existing position in the layout. If your browser doesn't support sticky, the sidebar simply doesn't stick.

Keep in mind that since this is a drastic layout change, this component may not be immediately compatible with other themes.