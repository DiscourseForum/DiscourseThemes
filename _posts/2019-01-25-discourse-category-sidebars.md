---
title: Discourse Category Sidebars
author: Kris
homepage: https://github.com/awesomerobot/discourse-category-sidebars
download: https://github.com/awesomerobot/discourse-category-sidebars
demo: https://theme-creator.discourse.org/theme/awesomerobot/discourse-category-sidebars
thumbnail: /images/107561/thumbnail.png
license: GNU General Public License v2.0
license_link: https://github.com/awesomerobot/discourse-category-sidebars/blob/master/LICENSE
category: Theme Components
meta_topic_id: 107561

---
This theme component takes a topic and applies it as a sidebar for a category's topic list. These sidebars are only visible when the browser is 767px or wider (most tablets and monitors). 

Want sidebars for tags? Check out [Discourse Tag Sidebars](https://meta.discourse.org/t/discourse-tag-sidebars/111114).

:eye: [Preview it on theme creator](https://theme-creator.discourse.org/theme/awesomerobot/discourse-category-sidebars )

![34%20PM: 690x423](/images/107561/Sicoc1Lk7eYzPbYd31gPk9oCFE.png) 

:hammer_and_wrench: [Github repo](https://github.com/awesomerobot/discourse-category-sidebars):  `https://github.com/awesomerobot/discourse-category-sidebars`

 :thinking: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


## What can I do with this theme component? 

* Choose a topic and display its content as a sidebar for a category. 

* Set a sidebar to be displayed on the /latest, /new, /unread, and /top pages by using `all` as the category name in your settings.

* Choose for the sidebars to appear on the left or the right of the topic list. 

* By default a category's sidebar will also display for all its subcategories unless a subcategory has its own sidebar defined (you can disable this by unchecking the `inherit parent sidebar` setting). 


## How do I configure it? 

Simply insert the category slug (from the category url, e.g. [example.com/c/](#)**staff**) and the id of the topic (e.g. [example.com/t/example-topic/](#)**57**)

![11%20PM: 690x125](/images/107561/zgogNJK74T0irhsWgzuQTHis6wP.png) 

I recommend creating sidebar topics in their respective categories, closing the topic so there are no replies, and unlisting it (so it doesn't appear in the topic list). 

Note that you can not use a topic in a private category as a sidebar in a public category (you can, but users without access to that private topic will just see a blank sidebar!). 

## Custom CSS 

Each category sidebar is wrapped with a class that contains the category slug, so for the staff category that would be `.category-sidebar-staff`. You can use these classes to style the individual sidebars. 

The body tag on pages with sidebars also has a class added so you can use `body.custom-sidebar` to apply styles on all pages that have a sidebar. 

---

:heart: Special thanks to @xrav3nz for laying the groundwork to make this component possible!