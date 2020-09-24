---
title: Tiles Image Gallery
author: Joe
homepage: https://github.com/hnb-ku/Discourse-Tiles-image-gallery
download: https://github.com/hnb-ku/Discourse-Tiles-image-gallery
demo: 
thumbnail: /images/81950/thumbnail.jpg
license: GNU General Public License v2.0
license_link: https://github.com/discourse/Discourse-Tiles-image-gallery/blob/master/LICENSE
category: Theme Components
meta_topic_id: 81950

---

#### Responsive Grid Galleries!
**10KB** (Gzip)
**3 http requests** on initial load 
<small>IE 11+  & modern browsers</small>

[Github repository link](https://github.com/hnb-ku/Discourse-Tiles-image-gallery)

`
 https://github.com/hnb-ku/Discourse-Tiles-image-gallery
`
<hr>


<div align="center">


![Capture: 457x500, 75%](/images/81950/6dOZGJ29JQ0zYifAkPkBVUQVVLG.jpg)![Capture2: 459x500, 75%](/images/81950/jCyP4e1Eth89S3bDzHzV13BaydQ.jpg)

<br>

![Capture3: 260x499, 75%](/images/81950/oZJJiJt0QhmgLdrmIYLhNH14huw.jpg)![Capture44: 250x500, 75%](/images/81950/xqj6otG8X4HdsAV8FMeec6m9yuO.jpg)![Capture4: 250x500,  75%](/images/81950/wlWc2Jbj85A51wa2thzoFz7qDj9.jpg)

</div>

<hr>

Built using [David Desandro](https://github.com/desandro)'s open source [Masonry](https://masonry.desandro.com/) and [ImagesLoaded](https://imagesloaded.desandro.com/) libraries - [MIT license](https://desandro.mit-license.org/)

_" ... released under the MIT license. Have at it."_



<hr>

#### How do I install this? 

You install this component just like any other theme. Follow the instructions in the official guide:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

Once you're done, simply add the component to your current theme. Done!

<hr>

#### How do I use this? 

This component adds a button to the composer. 

![Untitled: 690x278](/images/81950/zFAkV4td6ikkHpChhCEiEh2gDYm.png)

So all you have to do is:

1- Upload a bunch of images using the default Discourse upload button then highlight the code:

![Capture6: 497x500](/images/81950/bSW4e3xZSe9uVUu38Oyqi1QCh89.PNG)

2- Click the gallery button. 

You will get a **static preview** of the the selected images in the preview pane:

![Capture8: 690x417](/images/81950/zgEsKevjSPEM8OHzMGJfAlBr3hh.PNG)


Done! 

<hr>

#### Anything else I need to know? 

This component does not have any color / background styles in it. It will inherit the current theme's styles. 

Here's the theme component running on a different theme:

![Capture5: 525x500](/images/81950/nWHpTYKunV0ANuPoaeSWE1R1Xt5.jpg)

This theme component also **maintains the default Discourse lighbox behavior**, this means that clicking any of the images will open them in the **native lightbox viewer.**

![Capture9: 690x478](/images/81950/1u2hpYPZmq5anbhWquv66mqWYzQ.jpg)

#### Can I use both Slick and Tiles at the same time? 

You better believe it! :smile:

![Capture999: 411x500](/images/81950/n4oGM4yNCK86KcAC7IMdpqqWY5e.jpg)

This is possible by making both slick and tiles components of a theme.

Like this:

![Capture: 439x500](/images/81950/uDuhDUL8OaMbspNIiCBNthQj37W.PNG)

You can then make "my theme" in the example above the default theme or make it user-selectable and it would include both Slick and Tiles.

<hr>

A big thank you to everyone that helped along the way: :yum:

@Dax - Composer button
@cpradio - Button translations
@Mittineague - `ajaxComplete` handler
@Simon_Cossar - `api.onPageChange` handler
@vinothkannans - Topic page url regex
@sam - adding `data-theme-*` to whitelisted attributes

<hr>

Bug reports / Suggestions / PRs welcome. :wine_glass: