---
title: Custom Header Links
author: Joe
homepage: https://github.com/discourse/discourse-custom-header-links
download: https://github.com/discourse/discourse-custom-header-links
demo: https://theme-creator.discourse.org/theme/Johani/custom-header-links
thumbnail: /images/90588/thumbnail.PNG
license: GNU General Public License v2.0
license_link: https://github.com/discourse/discourse-custom-header-links/blob/master/LICENSE
category: Theme Components
meta_topic_id: 90588

---
This is a theme component that will allow you to add custom text-based links to the header easily.

[Github repository link:](https://github.com/discourse/discourse-custom-header-links)
`https://github.com/discourse/discourse-custom-header-links` 

Demo:
[https://theme-creator.discourse.org/theme/Johani/custom-header-links](https://theme-creator.discourse.org/theme/Johani/custom-header-links)

<hr>

**Samples:**

Desktop

![Capture: 690x361](/images/90588/hNmYrn6Wji3WuLxEyBwnDWosMeK.PNG)


Mobile
![Capture: 251x499, 75%](/images/90588/sgzozZ88GP69ai9NYQRrMaXTLJB.PNG)

(due to very limited space I don't recommend adding more than one link on mobiles)

<hr>

**Settings:**

Adding links is straightforward. Every link needs 6 items. You enter comma delimited values in this order:

`link text, link title, URL, view, target, hide on scroll`


**Link text:** the text for the link.
**Link title:** the text that shows when the link is hovered.
**URL:** The path for the link (can be relative).
**View:** vdm = desktop and mobile, vdo = desktop only, vmo = mobile only.
**Target:** blank = opens in a new tab, self = opens in the same tab.
**Hide on scroll:** remove = hides the link when the title is expanded on topic pages keep = keeps the link visible even when the title is visible on topic pages.

If you're not sure what `hide on scroll` does, here's an example: 

![headerLinks: 690x388](/images/90588/upAYsc6lqpsp6akDH2bh7Lovjcg.gif)

**Most Liked** and **Privacy** are set to `keep` and so they remain visible. The other links are set to `remove`, and so are hidden when the title expands in the header.  This only affects topic pages.

**Links position**: This setting allows you to change the default layout so links will appear on the left near the logo instead of on the right. Note that when positioned to the left, links will automatically be hidden when scrolling within topics to make room for the topic title. 

<hr> 

#### How do I install this component?

Follow the [theme installation guide ](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) and add the theme component to your active themes.

If you’re new to Discourse themes, you can learn more about them [here. ](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)