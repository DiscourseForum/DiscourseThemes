---
title: FlexFooter component
author: Joe
homepage: https://github.com/hnb-ku/discourse-FlexFooter-theme-component
download: https://github.com/hnb-ku/discourse-FlexFooter-theme-component
demo: 
thumbnail: /images/77929/thumbnail.PNG
license: GNU General Public License v2.0
license_link: https://github.com/hnb-ku/discourse-FlexFooter-theme-component/blob/master/LICENSE
category: Theme Components
meta_topic_id: 77929

---


[Repository link](https://github.com/hnb-ku/discourse-FlexFooter-theme-component)
`https://github.com/hnb-ku/discourse-FlexFooter-theme-component`


### Screenshots

Desktop:

![Desktop screenshot: 673x500, 75%](/images/77929/xNYy9DI51BYR46ygUjNvVC6AH9c.PNG)


![Desktop screenshot zoom: 690x264, 73%](/images/77929/s4sSWu4BrcYGSuWY5IUavgjx09K.PNG)

Mobile:

click for full size

![Mobile Screenshot: 185x500, 45%](/images/77929/yTKDDVrgyWtiw3dCe7jzmoKruI1.PNG)


<hr>

### Installation

:warning: This theme component requires you to actually look at the code and change it to your preferences. 

This is a skeleton. You still need to add content / links.

<hr> 

To install this theme, follow the theme installation instructions:

[https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)

<hr>

Once the theme from the repository is installed, follow these steps: 

1- Create a separate theme component and name it (example: **FlexFooter Child**)
2- Go to [the samples folder](https://github.com/hnb-ku/discourse-FlexFooter-theme-component/tree/master/samples) 
3- Pick a template (there's only one for now)
4- Copy the code from the template and add it to your newly created **FlexFooter Child** 
**in the common > Footer section**. 
5- Copy the following variables and add them to the common CSS section in **FlexFooter Child** you can edit them as needed to change colors.
```
$df-top-footer-background: rgb(40, 40, 40);
$df-bottom-footer-background: rgb(17, 17, 17);
$df-top-link-color: inherit;
$df-bottom-link-color: rgb(185, 185, 185);
$df-shared-text-color: rgb(175, 175, 175);
$df-shared-heading-color: rgb(255, 255, 255);
$df-base-font-size: 1em;
```
5- Now add **FlexFooter Theme Component** and **FlexFooter Child** as a components under your new theme.

<hr>

You should then be able to modify the html of the footer and the color variables in your newly created **FlexFooter Child**

You can pretty much add anything inside the cards, from mailing list signup forms,  images, text, links, ads, or iframes 

You only need to look for the portion between 

`<!-- start card content -->` 
and 
`<!-- end card content -->` 

remove the placeholders, and add your content. and you're good to go.