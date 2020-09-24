---
title: Big Header - Little Header
author: Taylor
homepage: https://github.com/tshenry/discourse-big-header-little-header
download: https://github.com/tshenry/discourse-big-header-little-header
demo: https://theme-creator.discourse.org/theme/tshenry/big-header-little-header
thumbnail: 
license: MIT License
license_link: https://github.com/tshenry/discourse-big-header-little-header/blob/master/LICENSE
category: Theme Components
meta_topic_id: 86811

---
This theme component will provide a stationary header with a large logo when scrolled at the top of the page. As you scroll down the page, the normal Discourse header bar will appear. This allows a large site logo to be cleanly displayed at the top of the page.

On mobile, the header bar will only display when the phone is in portrait orientation. Vertical space is usually fairly limited when you are in landscape orientation, so this will keep things open. To see the header again, you can either scroll to the top of the page or rotate the phone back to portrait orientation.

The best way to see what this theme component does is to try it out, which you can do by visiting:

https://theme-creator.discourse.org/theme/tshenry/big-header-little-header 

Here is my attempt at a small GIF of it in action (highly recommend clicking on the link above for a better illustration :slight_smile:) 

![demo: 640x299](/images/86811/zm7QkO83ZP6AqtAbkiiAzeriXkd.gif)

<h3>Settings:</h3>

There are currently three settings that should be pretty self-explanatory:

![21%20PM: 689x281](/images/86811/9ebOTqkpUz3WbJet6r7mahEE6wV.png)

<h3>Installation:</h3>

**IMPORTANT: You must be running [Discourse Version 2.0.0.beta4](https://meta.discourse.org/t/discourse-2-0-0-beta4-release-notes/82446) or later for this theme to work.**

Take a look at this topic for instructions on how to install the theme component:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682?source_topic_id=77929

**Import Link:**
>`https://github.com/tshenry/discourse-big-header-little-header.git`

<h3>About:</h3>

The [original proposal](https://meta.discourse.org/t/paid-big-120px-logo-to-small-40px-logo-smooth-transition/85429) for this came from @ryanerwin on the #marketplace. He asked that I generalize what I created for him and share it with the rest of the community. So this theme is very much inspired and brought to you by him :slightly_smiling_face: 


<h3>Notes:</h3>

Being that users love to customize their headers and the general area near the top of the page, there may need to be some additional adjustments made to handle conflicts with other customizations. I have tested this to work on a clean Discourse theme, but be prepared to tinker with it depending on how many other customizations you've done. It would be ideal to do as many of the modifications to this as a separate child theme component so that you do not lose track of your changes if/when the theme is updated.

<h3>Known issues:</h3>

Since this adds padding to the `div#main-outlet`, the topic timeline can be affected depending on how large your logo is. There are hard-coded ways to handle it, but that's not ideal. I will most likely make a post in #dev to outline all that I've tried and see if anyone has ideas on how to compensate for the extra padding.


<h3>Repo:</h3>

>[GitHub - tshenry/discourse-big-header-little-header](https://github.com/tshenry/discourse-big-header-little-header)

As always, please feel free to post if there are any questions, problems, or suggestions! My time is a little tight right now, but I will try address everything as quickly as possible :slight_smile: