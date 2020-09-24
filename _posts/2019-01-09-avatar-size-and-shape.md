---
title: Avatar size and shape
author: Daniela
homepage: https://github.com/discourse/discourse-avatar-component
download: https://github.com/discourse/discourse-avatar-component
demo: 
thumbnail: /images/106124/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-avatar-component/blob/master/LICENSE
category: Theme Components
meta_topic_id: 106124

---
This is a theme component that will allow you to easily change size and shape of the avatars on your site. 

[Repository link](https://github.com/discourse/discourse-avatar-component):
`https://github.com/discourse/discourse-avatar-component`

![image: 547x500,70%](/images/106124/vcMc9ca9RM6ILkxPpmrjpM0wJdX.png) 

### Some details:

The description of the theme settings should be clear enough, but I add some details: 
- `latest avatar size`: change the avatars size on the `/latest` page, all the avatars will be visible up to the `medium` size. From `large` onwards, only the avatar of the last user who wrote on the topic will be displayed.
- `header avatar size`: it works well up to the 60px size. For avatars of larger size, the height of the header must be increased (`header height`) and consequently the margin-top that distances the header from the other elements of the page must also increase (`margin top`).
I chose not to change the position (in height) of the notification bubble (topics and PMs) so that they remain in line with the red bubble for flagged topics. These bubble will only move horizontally following the avatar size.

### How do I install this component?

You install this component just like any other theme. Follow the instructions in the official guide:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

Once you're done, simply add the component to your current theme.

--------

This theme component was written taking inspiration from the guides 
- https://meta.discourse.org/t/how-to-increase-avatars-size-on-posts-without-making-them-blurred/82214
- https://meta.discourse.org/t/how-to-increase-avatars-size-on-latest-without-making-them-blurred/89606
- https://meta.discourse.org/t/how-to-increase-header-avatar-size/46719

-------

### TODO
- I will probably have to create a particular theme setting for mobile
- The component has not been tested with unofficial plugins, almost certainly there will be fixes to do (of course PRs are always welcome)