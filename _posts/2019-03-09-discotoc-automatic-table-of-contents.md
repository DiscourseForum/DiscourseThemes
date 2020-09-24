---
title: DiscoTOC - automatic table of contents
author: Joe
homepage: https://github.com/discourse/DiscoTOC
download: https://github.com/discourse/DiscoTOC
demo: 
thumbnail: /images/111143/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/DiscoTOC/blob/master/LICENSE
category: Theme Components
meta_topic_id: 111143

---
This is a theme component that will allow you to generate an interactive table of contents for your topics with one click!

[Repository link](https://github.com/discourse/DiscoTOC)
`https://github.com/discourse/DiscoTOC`

Preview:
 https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966
(open it in a new tab)

<hr>

### Samples

Desktop 

![desktop: 690x431, 75%](/images/111143/pTLZB39C3uuHkzV64zefGWyLYHh.png) 

Mobile

![mobile: 242x500,75%](/images/111143/sxfPwdM7I3ngXMG2YMGm5O8IT42.png) 

### Features
*toc = table of contents*
- Automatically generates the entire toc via a button in the composer gear menu
- The toc will always be on the screen - scrolls with content like the topic progress widget
- As you scroll past sections in the topic, the active element in the table of contents will be set to active (blue highlight)
- adds id attributes to headings (you can link to a specific section from another topic / post)
- clicking on any link in the toc will instruct the browser to navigate to relevant section (smooth-scrolling) 
- adds a copy-able link next to each heading (if you want to link to it) 

- RTL support

- The colors are based on your current active color palette 

### How does it work? 

In a nutshell, it looks for headings in topics which are marked to have a toc (via the composer button) and if it turns out the current topic is marked, then it takes all the headings and puts them in the toc (nested in order of heading levels) - **this means that your markdown must be syntactically correct**. 

```
# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6
```

You're free to go back and fourth in heading levels, but the order must be correct

```
# heading 2 
## heading 3
## heading 3
### heading 4
## heading 3
# heading 2

etc...
```

In order for the links in the toc to work, headings must have id attributes. The component will check if the headings already have ids and if they do, then they are respected. This is handy if you ever manually created a toc. 

If the headings don't have ids, then it will generate an id for each heading based on its text (unwanted characters are stripped out)

once all of that is done, it will also add a link next to each button that links directly to that section:

![Untitled: 690x196, 75%](/images/111143/w6iMehZwACOFslmOnxVEpw3k9o9.png) 

### Settings

This theme only comes with one setting, the toc icon. (used to add the icon to the subset and I don't recommend changing it.

### Translations

The theme comes with three strings that you can translate or change. 

```
table_of_contents: "table of contents"
```

this used for the button that opens the toc on mobile

![mobile-button: 242x500](/images/111143/kT53ZAyEwBPSMCeQTJLgUxvMXDh.png) 

```
insert_table_of_contents: "Insert table of contents"
```

this is used as the text for the toc button in the composer gear menu

![composer-button: 690x407, 75%](/images/111143/zbNo93bKd3bncqB6HmRJMdq2YJo.png) 

```
topic_will_contain_a_table_of_contents: "This topic will contain a table of contents"
```

This is the text that shows up in the composer preview to indicate that the a toc will be generated for the topic 

![composer-prompt: 690x316](/images/111143/kkNQrtHRbfLh96i9LvdT0TNajog.png) 

### How do I create a toc? 

1. Write a topic with syntactically correct headings
2. Click the toc button in the gear menu (only shows up when creating a regular topic - replies and PMs are ignored
3. Profit.  

### What happens to the topic progress widget when a topic has a toc? 

As you can probably guess, there's no space to show both at the same time, so the way this component works is as follows

in a topic with a toc, the topic progress widget is hidden while the first post is on screen, and you see the toc instead.

Once you scroll past the first post, the toc will not scroll with you and the topic progress will be shown instead while you read any replies. 

So, first posts get the toc, and subsequent posts get the regular topic progress widget.

The happens on both desktop and mobile. 

### Are there any downsides to using this component? 

Nothing I am aware of, all the changes are done on the client-side. So you can easily remove the component and your posts would go back to the way they were before you installed it. 

### Limitations

This component assumes the standard topic layout. As such, it won't work with themes that modify that layout such as the Vincent theme. Support for popular themes that modify the layout will come at a later stage in the form of component settings.   

### How do I install this theme component?

Follow the [theme installation guide](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) and add the theme component to your active themes.

If you're new to Discourse themes, you can learn more about them [here.](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)

#### Credit

I started with Greg Franko's [tocify.js](http://gregfranko.com/jquery.tocify.js/) library. However, it looks like it's not been updated in a while, so this is essentially a hard-fork that removes a lot of unnecessary features, integrates and styles the rest for Discourse.

So, there are no external requests and the total size is ~ 4kb gzip.

Big thanks to @erlend_sh for lots of valuable feedback and to @david for his help with translations.


### TODO 
- live composer preview of toc content (might be too expensive)
- support for popular themes that alter topic layout
- clicking links next to headings will copy to clipboard automatically

This is a very early release, if you spot any problems or have ideas for improvement, please let me know.