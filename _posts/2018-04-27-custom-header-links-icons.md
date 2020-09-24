---
title: Custom header links (icons)
author: Joe
homepage: https://github.com/discourse-com/discourse-icon-header-links
download: https://github.com/discourse-com/discourse-icon-header-links
demo: https://theme-creator.discourse.org/theme/Johani/header-links
thumbnail: /images/86307/thumbnail.PNG
license: GNU General Public License v2.0
license_link: https://github.com/discourse/discourse-icon-header-links/blob/master/LICENSE
category: Theme Components
meta_topic_id: 86307

---
This is a theme component that will allow you to add linked icons to the Discourse header easily.  

<hr>

[Github repository link](https://github.com/discourse-com/discourse-icon-header-links)

`
https://github.com/discourse-com/discourse-icon-header-links
`

Demo:

https://theme-creator.discourse.org/theme/Johani/header-links 

<hr>

### Samples


**Desktop**

![Capture3: 640x500, 75%](/images/86307/kJlmzT2ud3mCJHkJFEQmKQWltrj.PNG)

**Mobile**

![Capture: 265x500, 75%](/images/86307/y535IH0ImOb6nd7twn5v9WnYPQ7.PNG)

<hr>

This component includes a theme setting that allows you to add as many links as you want, determine their icons, and decide which devices they show up on! 

![Capture4: 690x208](/images/86307/eOA92Duj1YklzkOo39iCVs4a9io.PNG)

<hr>

The pattern for links is as follows:

`
Title,Icon,URL,View,Target
`

Title is.. well..the title you want the link to have.

URL is where you want the user to go when they click. Include protocol like `https://`
Alternatively, as @dnsmichi pointed out, you can also use relative links like `/c/staff` 

Icon can be any [FontAwesome 5 (free) icon](https://fontawesome.com/icons) name without the `fa-` 'fab-' 'fas-' or 'far-' parts

If the icon you want to use does not show up, then add it to the `svg_icons` setting in the component. if you add new icons, they need to be prefixed with FontAwesome 5 prefixes like fab, far and fas.

View can have one of three values:

**vdo:**  
Desktop only

**vdm:** 
Mobile and desktop

**vmo:** 
Mobile only

<hr>

Target can be:

**self**
Opens link in the same tab

**blank**
Open link in a new tab

<hr>

#### How do I install this?

follow the official theme installation guide here:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682

Then add the component to your theme as a theme component and you're all set! 

<hr>


### Credits 

This is based on @techAPJ's awesome tutorial here: https://meta.discourse.org/t/add-new-link-on-header-beside-search-icon/48621

and on @vinothkannans's Brand header theme which was a great reference for the structure of this component.