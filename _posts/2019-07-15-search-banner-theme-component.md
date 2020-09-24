---
title: Search banner theme component
author: Kris
homepage: https://github.com/awesomerobot/discourse-search-banner
download: https://github.com/awesomerobot/discourse-search-banner
demo: https://theme-creator.discourse.org/theme/awesomerobot/discourse-search-banner
thumbnail: /images/122939/thumbnail.png
license: GNU General Public License v3.0
license_link: https://github.com/awesomerobot/discourse-search-banner/blob/master/LICENSE
category: Theme Components
meta_topic_id: 122939

---
This is a component that puts a search bar along with optional headline and subhead text in a banner above the main topic list navigation. 

By default this banner appears on all top-level topic pages (latest/new/unread/top/categories... anything in the `top menu` site setting) but it can also be set to only display on a community's homepage.

![17%20PM: 690x326](/images/122939/2Z6exUfF0VM7H6RD3mwDirDWI4r.png) 


:building_construction: [Github repo](https://github.com/awesomerobot/discourse-search-banner): `https://github.com/awesomerobot/discourse-search-banner.git`

:telescope: [Preview it on theme creator](https://theme-creator.discourse.org/theme/awesomerobot/discourse-search-banner )

:question:  [How do I install a theme component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)


:sparkling_heart: This very heavily borrows from @angus' https://meta.discourse.org/t/header-search-theme/67959 


### Available settings

* Set the headline and subhead text
* Show the banner on all top-level topic pages (default), just the homepage, or all pages
* Show the banner for everyone, logged in, or logged out users 
* Set a background image

### Custom styling

The HTML element gets a class named `.display-search-banner` wherever this banner appears, and the banner itself is wrapped with the `.custom-search-banner` class, so with some CSS you should be able to customize the appearance of this banner however you see fit.


### Future enhancements 

* Add an option to enable the banner in specific categories