---
title: Category icons component
author: Penar Musaraj
homepage: https://github.com/discourse/discourse-category-icons
download: https://github.com/discourse/discourse-category-icons
demo: 
thumbnail: /images/104683/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-category-icons/blob/master/LICENSE
category: Theme Components
meta_topic_id: 104683

---
[Repository](https://github.com/discourse/discourse-category-icons):

```text
https://github.com/discourse/discourse-category-icons
```

Installation instructions: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

### What this does?

This component allows category badge links to have icons next to the category name. Here is an example of how this would look, with category style set to `none`: 

![image: 690x269](/images/104683/jKjEX9qOJlSBungXbRN6KRTQLt4.png)  

Here is how  this would look with category style set to `box`: 

![image: 690x264](/images/104683/1fQXvQpm9dHBhhpx4CZkCWj9M0P.png) 

Configuration is pretty straightforward: 

![image: 690x406, 75%](/images/104683/A7GFPsrTdXnHoZjOsy5MBe6SjRX.png)    

Note that this component also lets you override the `category lock icon` used to denote private categories. 

*January 2020 update*: thanks to @rogerco, you can now use the "partial" keyword to partially match category slugs (i.e. entering "book,icon,red,partial" would match all category slugs containing "book").

### Issues

* Does not correctly respect the icon color when using with the `bullet` category style. In general, though, this shouldn't be used with the bullet or bar category styles, the UI would be unnecessarily busy.

See also the [Tag Icons](https://meta.discourse.org/t/tag-icons-component/109757) component, which does the same thing for tags.