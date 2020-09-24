---
title: Discourse Tag Banners
author: Kris
homepage: https://github.com/discourse/discourse-tag-banners
download: https://github.com/discourse/discourse-tag-banners
demo: https://theme-creator.discourse.org/theme/awesomerobot/tag-banners
thumbnail: /images/124240/thumbnail.png
license: GNU General Public License v2.0
license_link: https://github.com/discourse/discourse-tag-banners/blob/master/LICENSE
category: Theme Components
meta_topic_id: 124240

---
When visiting a tag-filtered topic list, this theme component displays the tag name in a banner at the top of the page... (similar to the https://meta.discourse.org/t/discourse-category-banners/86241 component.)

![35%20PM: 690x310](/images/124240/xIYDlOJH4IVtGPsmUfTRHu08Ovk.png) 

:telescope:  [Preview on theme creator]( https://theme-creator.discourse.org/theme/awesomerobot/tag-banners) 

:octopus: [Github repo](https://github.com/discourse/discourse-tag-banners.git): `https://github.com/discourse/discourse-tag-banners.git` 

:brain: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682

Unlike categories, tags don't get descriptions or custom colors so these banners don't have as many options as the category banner variety. 

But you can customize these banners with CSS. Each banner gets the tag name(s) appended as a class, for example:

``` 
.tag-banner-art {
  background: salmon;
  color: beige;
}
```

The banner also works with tag intersections (e.g., `community.example.com/tags/intersection/art/new-tag`)

![39%20PM: 690x263](/images/124240/gAy97RGtGKpVvTcX2BRQKNi9aXw.png) 

In this case you'd target `.tag-banner-art.tag-banner-new-tag` for CSS customization.

This theme component also comes with the setting to disable the banners for mobile (they're enabled by default)

![15%20PM: 690x123,75%](/images/124240/qC02FSkbDa3f3mdQllWvwRjrmxL.png)