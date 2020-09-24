---
title: Header submenus
author: Joe
homepage: https://github.com/discourse/discourse-header-submenus
download: https://github.com/discourse/discourse-header-submenus
demo: https://theme-creator.discourse.org/theme/Johani/header-submenus
thumbnail: /images/94584/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-header-submenus/blob/master/LICENSE
category: Theme Components
meta_topic_id: 94584

---
This is a theme component that will allow you to build a header menu - with submenus - using plain text!

[Repository link](https://github.com/discourse/discourse-header-submenus)
`https://github.com/discourse/discourse-header-submenus`

Preview:
[https://theme-creator.discourse.org/theme/Johani/header-submenus](https://theme-creator.discourse.org/theme/Johani/header-submenus)

<hr>

### Samples

Desktop

![1: 690x291, 80%](/images/94584/jdnkaNbCwPgz2YumeroeTl4aN7Q.png) 

![2: 690x294, 80%](/images/94584/iY1sWug2MUejDvzQYu8WHAct8uK.png) 

Mobile

![3: 246x500, 75%](/images/94584/m1WHIvykwgqZIZgEJqxG9eXp9Hn.png) 

### Settings

There are four groups of settings

1. **Menu items** 

    Enter the items you want to appear on the menu. One comma-delimited item per line in this order

    `Text, icon, title, view`

    Text:  what appears on the menu.
    Icon:  the icon displayed next to the item. If you do not want to use an icon, use `none`.
    Title:  the text that appears when the item is hovered.
    View:  Choose what devices the item appears on. 

    ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ `vdm` appears on both desktop and mobile 
    ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ `vdo` appears on desktops only, 
    ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ ‏‏‎ `vmo` appears on mobiles only. 

   Due to lack of space, it is not recommended to add more than 3-4 items on mobile.

2. **Submenu items**
 
   Enter a list of the submenu items you want to add to your menu. One comma-delimited item per line in this order

    `Parent, text, icon, URL, target, title`

    Parent:  the name of the parent menu item which this submenu item should show under. Use the `text` value from the list above.
    Text:  the text that shows for this submenu item.
    Icon:  the icon for this submenu item, use `none` if no icon is needed.
    URL:  the path this menu item links to. You can use relative paths as well.
    Target:  Choose whether this item will open in a new tab or in the same tab. Use `blank` to open the link in a new tab, or use `self` to open it in the same tab.
    Title:  the text that shows when the item is hovered.
    Dividers:  You can also add dividers between submenu items. To add a divider use `parent, divider`.

Here's a quick example to cover points 1 and 2 above:

Let's say I want to add a menu item called `Design` and add a few items to its submenu like so

![4: 276x329, 70%](/images/94584/23vkfStZCgnnB9ihByKXL18QK1f.png) 

I would first enter this as a `menu_item`

`Design, magic, Get inspired!, vdm`

And then enter these as `sub_menu` items

`Design, Galleries, th, #, blank, Cool galleries for you to look at.`
`Design, Design process, lightbulb-o, #, blank, Learn the basics.`
`Design, Blog design, columns, #, blank, What makes for a great blog?`
`Design, divider`
`Design, Freebies, gift, #, blank, Everyone likes freebies!`
`Design, Photoshop tutorials, book, #, blank, Photoshop for beginners.`
`Design, Design trends, bar-chart, #, blank, Stay on top of the current trends!`

That's it! 

The theme comes with a placeholder menu by default, so have a look at that and ask if you have questions. 

3. **Layout options.** 

   these are pretty self-explanatory 

   ![5: 690x215, 75%](/images/94584/efy7tyDd3n0cp9niT36YRzED9Ki.png)  

4. **Color options**
  
   These are empty by default, but if you add a color here, it will override the component's defaults which are based on the current color scheme. 

### How do I install this theme component?

Follow the [theme installation guide](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) and add the theme component to your active themes.

If you're new to Discourse themes, you can learn more about them [here.](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)