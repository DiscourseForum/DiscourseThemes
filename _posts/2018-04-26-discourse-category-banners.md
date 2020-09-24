---
title: Discourse Category Banners
author: Kris
homepage: https://github.com/discourse/discourse-category-banners
download: https://github.com/discourse/discourse-category-banners
demo: https://theme-creator.discourse.org/theme/awesomerobot/discourse-category-banners
thumbnail: /images/86241/thumbnail.png
license: GNU General Public License v2.0
license_link: https://github.com/discourse/discourse-category-banners/blob/master/LICENSE
category: Theme Components
meta_topic_id: 86241

---
This theme component uses your existing category details to create banners for your category pages. 

[You can preview the theme on our theme preview site here](https://theme-creator.discourse.org/theme/awesomerobot/discourse-category-banners) (you'll have to navigate to a category page)

![54%20PM: 690x363](/images/86241/4cCuKxubnHSn1fc1p5BDUQPTU8R.png) 




<br/>

Github repo: https://github.com/discourse/discourse-category-banners

Not sure where to start? See: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

### What does this theme component do?

This theme component takes your existing category details, including name, description, and color and generates a banner at the top of the relevant category pages. 

This component looks for your category description, which is defined by the first paragraph in each category's "Category definition for ..." post. The banner background/text colors are defined by your category badge settings.

By default this will display on desktop and mobile across all Category and Subcategory pages, but will _not_ appear if you haven't given your category a description. 

### Theme component settings

This component comes with a few options to override the defaults. 

* **Show description**: disabling this will hide the description part of the banner. 
* **Show mobile**: disabling this will hide banners on mobile devices
* **Show subcategory**: disabling this will hide banners for subcategories 
* **Hide if no description**: disabling this will show banners even if a category description is not set
* **Exceptions**: if you don't want a category to have a banner, add its name here

### Additional CSS styling

If you want to customize these with some additional CSS you can target specific category headers by using this structure (example-category is your category name):

```
.category-title-header {
  &.category-banner-example-category {
        background: url(example.jpg);
  }
}
```

This component also adds the class `category-header` to the body tag as an additional CSS target.