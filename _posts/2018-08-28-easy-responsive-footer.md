---
title: Easy responsive footer
author: Joe
homepage: https://github.com/discourse/Discourse-easy-footer
download: https://github.com/discourse/Discourse-easy-footer
demo: https://theme-creator.discourse.org/theme/Johani/easy-footer
thumbnail: /images/95818/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/Discourse-easy-footer/blob/master/LICENSE
category: Theme Components
meta_topic_id: 95818

---
This is a theme component that will allow you to build a fully-responsive footer using nothing but plain text.

[Repository link](https://github.com/discourse/Discourse-easy-footer)
`https://github.com/discourse/Discourse-easy-footer`

Preview:
[https://theme-creator.discourse.org/theme/Johani/easy-footer](https://theme-creator.discourse.org/theme/Johani/easy-footer)

<hr>

### Samples

Desktop

![1: 674x500, 75%](/images/95818/qsPQMvlmh3s72jxWlWDxXDnht6N.png) 

Mobile

![2: 246x500, 75%](/images/95818/vE28Bv5jzscGw2SFEnEdY0QckMD.png) 

### Settings

There are six settings in this component that will help configure it easily

**1. Heading**

   Text for the heading in the footer - you can use your site name for example - Max length 25 characters
    ![3: 690x185, 50%](/images/95818/p83nOCYSnRCl4Ij27NuPA5VvuBe.png) 

**2. Blurb** 

   a short blurb about your community - Max length 180 characters
  ![4: 690x180, 50%](/images/95818/vz1u9LJC99MTsw491aQbjevDEXt.png) 

**3. Link sections**

   Add link sections. The ideal number of sections is six. One item per line in this order: Text, title
    Text: what appears on in the footer
    Title: the text that appears when the item is hovered.
  ![5: 690x180, 50%](/images/95818/wtqQInrUiBwT3MxDgatwCamXunl.png) 

**4. Links**

Add links to link sections. One item per line in this order:
Parent, text, URL, target, title
It is a good idea to keep the number of links under each section similar
Parent:  the name of the parent section which this link shows under. Use the `text` value from the list above
Text:  the text that shows for this link
URL:  the path this item links to. You can use relative paths as well.
Target:  Choose whether this item will open in a new tab or in the same tab. Use blank to open the link in a new tab, or use self to open it in the same tab.
Title:  the text that shows when the link is hovered.

![6: 690x180, 50%](/images/95818/qs8Dl8LFzpKsTGe3V2w04zfr4Nj.png) 

**5. Small links**

You can add small links at the bottom of the footer like Terms of Service and Privacy. One item per line in this order:
Text, URL, target
Text:  The text that shows for the small link
URL: The path of the link
Target:  Use blank to open the link in a new tab and use self to open it in the same tab

![7: 690x184, 50%](/images/95818/4yXtLywgUtCTAtmOhIycmL3nBM9.png) 

**6. Social links**

Enter the social links you'd like to add to the footer in this format:
provider, title, URL, target
Provider:  is the name of the provider like Facebook or Twitter
Title:  The text that shows when the link is hovered
URL:  The path you'd like the link to have
Target:  Use blank to open the link in a new tab and use self to open it in the same tab

![8: 690x180, 50%](/images/95818/dexYBNmFJlN9qrbPSyuGk1bvr2C.png) 

### Notes

1. I left the placeholder items as defaults for the component so you can easily see what your settings should look like.

2. This component will use your theme's color scheme to generate the colors used for the elements in it. but all elements have unique classes added to them in case you want to override something.

3. Since this component uses theme settings, it means that I can update it in the future to either fix or improve it and the data you enter would not be lost :tada:

### How do I install this theme component?

Follow the [theme installation guide](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) and add the theme component to your active themes.

If you’re new to Discourse themes, you can learn more about them [here](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)