---
title: Kanban Board Theme Component
author: David Taylor
homepage: https://github.com/discourse/discourse-kanban-theme
download: https://github.com/discourse/discourse-kanban-theme
demo: https://theme-creator.discourse.org/theme/david/kanban
thumbnail: /images/118164/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-kanban-theme/blob/master/LICENCE.txt
category: Theme Components
meta_topic_id: 118164

---
This theme component allows you to display and organise topics using a kanban board interface. 

**[:link: Repository Link](https://github.com/discourse/discourse-kanban-theme)**

**[:link: Preview on Theme Creator](https://theme-creator.discourse.org/theme/david/kanban)**

![28: 690x451,100%](/images/118164/kVTXk4L7nyVmCkaBxiftem2SXaZ.png) 

So far, there are three modes. Categories, tags, and assignment. You can drag topics between lists to change the corresponding attributes:

https://d11a6trkgmumsb.cloudfront.net/original/3X/d/5/d520d87be01637757b6515a07b8b5d7e7456cc80.mp4 

Lists are 'lazy-loaded', so performance is reasonable, even for very large numbers of categories. You can enter fullscreen mode for even more space to organise your projects:

https://d11a6trkgmumsb.cloudfront.net/original/3X/d/f/df544b018996a41b9cbd3091f05256c1c68e9273.mp4 

The default board mode will be automatically determined using these criteria:
  - If this is the top level, use **categories** mode
  - If this is a category, and there are sub-categories, use **categories mode**
  - Otherwise, use **tags** mode. (Lists built from 'top tags' list)

You can change the board mode using the filter button on the left, and configuration changes will be reflected in the URL. Users can bookmark their favorite configuration in their browser. Administrators can customize the defaults per-category in the theme settings.

The most intuitive setup is "tags", where the tags displayed are in a [tag group with "only one tag from this group" enabled](https://meta.discourse.org/t/tags-category-restrictions-tag-groups-relationships/48260).

# #pr-welcome features:

- make the lists more configurable. e.g. allow administrators to define a combination of assignment, tags, and categories in one display

- Add support for dragging cards on mobile devices. Unfortunately they don't support [html drag and drop](https://www.w3schools.com/html/html5_draganddrop.asp)