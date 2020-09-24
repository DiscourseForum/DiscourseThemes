---
title: Discourse Popular Tag Sidebar
author: Kris
homepage: https://github.com/awesomerobot/discourse-popular-tag-sidebar
download: https://github.com/awesomerobot/discourse-popular-tag-sidebar
demo: 
thumbnail: /images/107853/thumbnail.png
license: GNU General Public License v2.0
license_link: https://github.com/awesomerobot/discourse-popular-tag-sidebar/blob/master/LICENSE
category: Theme Components
meta_topic_id: 107853

---
This theme component displays a category's most popular tags in a sticky sidebar on screens wider than 767px (most tablets and desktop devices). 

:warning: You must enable the `show filter by tag` setting on your site for this theme component to work.

![59%20PM: 690x302](/images/107853/yhCeYkwetjDPQYHVrgblo9fIOZd.png) 



:hammer_and_wrench: [Github repo](https://github.com/awesomerobot/discourse-popular-tag-sidebar):  `https://github.com/awesomerobot/discourse-popular-tag-sidebar`

 :thinking: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


## What can I do with this theme component? 

* Display 3-30 Popular tags in a sidebar for each category

* Set the sidebar side to left or right

* Prevent the sidebar from appearing in certain categories

* Change the "Popular tags" header text

![55%20PM: 690x381, 75%](/images/107853/fyExwJaDaalY1o5wi7jNJCXQNFS.png) 


## Custom CSS 

Each sidebar is wrapped with a class that contains the category name, so for the UX category that would be `.ux-sidebar`. You can use these classes to style individual sidebars. 

The html tag on pages with sidebars also has a class added so you can use `html.custom-sidebar` to apply styles on all pages that have a sidebar.