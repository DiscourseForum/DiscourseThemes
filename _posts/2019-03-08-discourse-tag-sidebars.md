---
title: Discourse Tag Sidebars
author: Kris
homepage: https://github.com/awesomerobot/discourse-tag-sidebars
download: https://github.com/awesomerobot/discourse-tag-sidebars
demo: https://theme-creator.discourse.org/theme/awesomerobot/discourse-tag-sidebars
thumbnail: /images/111114/thumbnail.jpeg
license: GNU General Public License v2.0
license_link: https://github.com/awesomerobot/discourse-tag-sidebars/blob/master/LICENSE
category: Theme Components
meta_topic_id: 111114

---
This theme component takes a topic and applies it as a sidebar for a tag's topic list. These sidebars are only visible when the browser is 767px or wider (most tablets and monitors). 

Want sidebars for categories? Check out [Discourse Category Sidebars](https://meta.discourse.org/t/discourse-category-sidebars/107561).

:eye: [Preview it on theme creator](https://theme-creator.discourse.org/theme/awesomerobot/discourse-tag-sidebars) - (navigate to the `art` tag)

![01%20PM: 690x250](/images/111114/lLedo1tkXnfk325vz30Zy1HSP7F.jpeg) 

:hammer_and_wrench: [Github repo](https://github.com/awesomerobot/discourse-tag-sidebars):  `https://github.com/awesomerobot/discourse-tag-sidebars`

 :thinking: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


## What can I do with this theme component? 

* Choose a topic and display its content as a sidebar for a tag. 

* Choose for the sidebars to appear on the left or the right of the topic list. 

## How do I configure it? 

Simply insert the tag name and the id of the topic (e.g. [example.com/t/example-topic/](#)**57**)

![15%20PM: 690x142](/images/111114/h3QE4j94a6m6Iqrcq0AACp0Px0T.png) 

I recommend creating sidebar topics in their respective tags, closing the topic so there are no replies, and unlisting it (so it doesn't appear in the topic list). 

Note that you can not use a topic in a private category as a sidebar in a public area. 

## Custom CSS 

Each tag sidebar is wrapped with a class that contains the tag name, so for the `test` tag that would be `.tag-sidebar-test`. You can use these classes to style the individual sidebars. 

The body tag on pages with sidebars also has a class added so you can use `body.custom-sidebar` to apply styles on all pages that have a sidebar.