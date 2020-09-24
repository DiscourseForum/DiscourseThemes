---
title: Versatile Banner
author: Taylor
homepage: https://github.com/tshenry/discourse-versatile-banner
download: https://github.com/tshenry/discourse-versatile-banner
demo: https://theme-creator.discourse.org/theme/tshenry/versatile-banner
thumbnail: /images/109133/thumbnail.jpeg
license: MIT License
license_link: https://github.com/tshenry/discourse-versatile-banner/blob/master/LICENSE
category: Theme Components
meta_topic_id: 109133

---
This theme component is an evolution of the very popular https://meta.discourse.org/t/banner-themes-and-instructions-for-customizing-them/82368.  The goal is to provide more ease and flexibility through the use of theme settings.


Preview at https://theme-creator.discourse.org/theme/tshenry/versatile-banner

![Banner_Theme: 690x319,70%](/images/109133/gTBUt3C7UuesIXDfe5pmk4JxGJK.jpeg) ![mobile_demo: 256x500, 60%](/images/109133/omf9O0E0IRaTDJ5VnguDVDBLiJp.gif) 


Below is a highlight of the features:

- Limit display to logged-in users or anonymous users
- Limit display to be exclusively mobile or desktop
- Limit display to specific pages
- Dismissible, expandable, and always visible options
- Full browser width option
- Color management
- Heading and column customization using HTML (see below for more)
- Persistent state option (see below for more)




#### Customizing your banner's content
Banner content is broken up into the main heading and columns. You can have up to 4 columns on your banner, however, the recommended number is 3 or fewer due to width limitations. HTML templates are provided and can be customized to meet your individual needs. You can also control each column's width and add whatever image or font awesome icon you want to the top of each column.

#### Using the persistent state option
The persistent state option will rely on up to two cookies. These cookies will contain a name for the banner and a true/false value that relates to the banner's state. If you have any concerns with using cookies on your site, it's best to avoid using this setting. Choosing a relative time option for the `cookie_lifespan` setting will make sure the banner remains closed/expanded/collapsed for that amount of time after the user presses the appropriate button. Without this setting, the banner resets with every full page load. If you make a change to the banner and want to ensure that all users see those changes, even those that had previously closed the banner, be sure to change the "cookie name." It will essentially reset any persistent state, then allow user to close the banner once more.

### Installation

[Repository Link ](https://github.com/tshenry/discourse-versatile-banner)
`https://github.com/tshenry/discourse-versatile-banner`

If you are unfamiliar with theme components and how to install them, check out the [theme installation guide ](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682). And if you’d like to learn more about Discourse themes, take a look at [this guide ](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966).

If you have any ideas for improvement, or issues to report please don't hesitate to share.