---
title: Discourse Category Headers theme component
author: Rhidian Bramley
homepage: https://github.com/naidihr/discourse-category-headers
download: https://github.com/naidihr/discourse-category-headers
demo: 
thumbnail: /images/148682/thumbnail.png
license: MIT License
license_link: https://github.com/naidihr/discourse-category-headers/blob/master/LICENSE
category: Theme Components
meta_topic_id: 148682

---

This theme component provides a number of enhancements for the Discourse category header.

The 'standard' Discourse category header is displayed at the top of each category page, above the navigation links and list of topics. It is normally only visible if a category logo image has been uploaded in the category settings. The header displays the logo and a short description of the category, taken from the first paragraph of the ‘About the.. category’ topic. 

### This theme component provides the following enhancements

The category header is now shown by default for all categories. It now includes the name of the category in addition to the logo (if set)  and the category description. It can also now include a logo background image and can be styled to show as either a 'box' or a 'banner', using the category color settings . There are a wide range of configurable options in the theme settings. 

### Theme settings

* <b>show category name:</b> Show the category name in the header
* <b>show category description:</b> Show the category description text (the first paragraph of the "About this category" topic)
* <b>description text size:</b> Size of text within the category description
* <b>text align: </b>Alignment of the text within the category header
* <b>show subcategory header:</b> Show header for subcategories
* <b>show parent category name:</b> Prefix the parent category name on the subcategory headers (this acts as a breadcrumb link to the parent category page)
* <b>show lock icon:</b> Show the lock icon on categories protected by permissions
* <b>show category logo:</b> Show the category logo image within the header
* <b>show parent category logo:</b> Show the parent category logo when a subcategory logo is not set
* <b>show site logo:</b> Show the small site logo if a category logo is not set
* <b>position logo:</b> Position of the logo within  the box
-- 'left' and 'right' display the logo inline with the text. 
-- 'top' displays the logo above aligned with the text
* <b>size logo:</b> Position of the logo within the header. 
-- Small is 50px high similar to a subcategory box logo. 
-- Standard is 150px high. 
-- Original is the size of the image uploaded
* <b>header style:</b> Set the header style to either: 
-- Box: the category header is displayed in the same style as the standard Discourse boxes
-- Banner: set the header background to the category background color and text to the foreground color 
-- None: no border or background styling
* <b>header background image:</b> Applies if you have uploaded a category background image 
-- 'contain', 'cover' and 'resize' display the background within the header. 
-- 'outside' is the Discourse default displaying it outside the header, over the whole page.
* <b>show mobile: </b>Show category header on mobile devices
* <b>force mobile alignment:</b> Force mobile alignment of logo-text to the top-centre of the header
* <b>hide if no category description:</b> Hide header if category description is not set
* <b>hide category exceptions:</b> Headers will not show for these categories

### Install the theme component 

:hammer_and_wrench: Git repo: [https://github.com/naidihr/discourse-category-headers](https://github.com/naidihr/discourse-category-headers)

:thinking: [How do I install a Theme or Theme Component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)

### Credits
Thanks to @Johani for his excellent [Developer’s guide to Discourse Themes](https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648)
This theme component was inspired by other themes notably the [Discourse Category Banners](https://meta.discourse.org/t/discourse-category-banners/86241) theme by @awesomerobot 

## Examples

Box style: The category header is displayed in the same style as the subcategory boxes

![image: 690x307](/images/148682/qdDI3CnhysCTJqbkXc7E7x3J86u.png) 

Subcategory, note the subcategory doesn't have a logo but is set to inherit the parent category logo. The parent category name is also set to show as a breadcrumb link.

![image: 690x150](/images/148682/17eO7iplUsYobNlKgo3KKPy6TgH.png) 

If the subcategory has it's own logo it will display it instead.

![image: 690x158](/images/148682/e0Xb4pt2dtvj23IDNjMjyX6Wpcz.png) 

Mobile view showing a different text and icon alignment.

![image: 193x250](/images/148682/ogwFqbjRW6GPvMngjPWtWkspxr3.png)

Text size settings.

![image: 690x119](/images/148682/t2GHqdpxaHwdx5lMWQdJLsWHY5G.png) 
![image: 690x121](/images/148682/f5FViLOydNBGwhEFibVrc2Fe2yV.png) 
![image: 690x123](/images/148682/s3HspeA6G8ALK8DTbxmI1zw7vQ5.png) 

Alignment options example center text, logo right.

![image: 690x119](/images/148682/29cbMIzZdjsgUFL5CdpowKAbRxx.png) 

Banner style: Uses the category background and foreground colors

![image: 690x152](/images/148682/lAejDn69EPalVbLeQYw6KeZUfyU.png) 

Background image: Uses the category background image

![image: 690x157](/images/148682/kVivOQ3UwFFelRyfnvCrbrSGjkj.jpeg)