---
title: Codeblock Theme Picker
author: Joe
homepage: https://github.com/discourse/hljs-theme-picker
download: https://github.com/discourse/hljs-theme-picker
demo: https://theme-creator.discourse.org/theme/Johani/hljs-theme-picker
thumbnail: /images/146396/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/hljs-theme-picker/blob/master/LICENSE
category: Theme Components
meta_topic_id: 146396

---
This is a theme component that will allow you to easily change the theme used in code blocks

[Repository link](https://github.com/discourse/hljs-theme-picker)
`https://github.com/discourse/hljs-theme-picker`

Preview:
 https://theme-creator.discourse.org/theme/Johani/hljs-theme-picker

### Samples

![Some examples of the colors available: 690x294](/images/146396/8TSD5FL8D8sSQGC21kiqHYtiq5X.png) 

This is just a handful of the available options. This component includes [all 90 options](https://highlightjs.org/static/demo/) offered in the hljs repository. 

>  **Note:** while all the options are included in this component, it will only load the one you pick. So, there's no overhead.

### Version requirements

This component will only work on Discourse version `2.4.1` and higher. If your site is running an older version, it won't do anything. 

### How to use it
Due to the way this component is wired up, it will require a small change to one of your site settings. 

1. head to `your.site.com/admin/site_settings/`
2. search for `theme_authorized_extensions`
3. add `css` to that list.

Like so: 

![add css to theme authorized extensions: 690x121, 75%](/images/146396/nxwKrNv4bUwMrSzOMn9zRxwnwP4.png) 

:warning: You have to do this before you install the component, otherwise it won't work.

Once that's done, you can install the component just like any other component. 

Here's how you can do that.

 https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682

### settings

There's only one setting. It's a dropdown that contains a list of all the options. If you need to see what the options look like, have a look here https://highlightjs.org/static/demo/

Once you decide on a hljs theme to use, you can search the dropdown for the one you want and save the setting. You will need to refresh the page in order for everything to start working.

#### Credits

All of the hljs themes included in this component have copyright information in their respective files. The list of all of those authors (:heart:) is too big to add here, but you can see them [here](https://github.com/discourse/hljs-theme-picker/tree/master/assets).