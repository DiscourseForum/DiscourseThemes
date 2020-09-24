---
title: Custom source code formatting component
author: Daniela
homepage: https://github.com/discourse/discourse-custom-code
download: https://github.com/discourse/discourse-custom-code
demo: 
thumbnail: /images/108059/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-custom-code/blob/master/LICENSE
category: Theme Components
meta_topic_id: 108059

---
A theme component that allows you to customize the font and colors for source source shared on the site.

[Repository link](https://github.com/discourse/discourse-custom-code)
`https://github.com/discourse/discourse-custom-code`

![image: 479x500](/images/108059/hpzYx7etX1V0lRGo9pPYANd70Be.png)  

### Some details

Generally, the fonts used to write code are part of the [`monospace` family](https://fonts.google.com/?category=Monospace). The most known fonts are:

- [Inconsolata](https://fonts.google.com/specimen/Inconsolata) 
- [Fira Mono](https://fonts.google.com/specimen/Fira+Mono)
- [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro)
- [Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)
- [Ubuntu Mono](https://fonts.google.com/specimen/Ubuntu+Mono)

_(That said, this does not prevent anyone from experimenting with the most disparate fonts!)_

To change font go to https://fonts.google.com
- choose the font you want to use
![image: 690x249,50%](/images/108059/nMujytDvZYVGkApj6IRSfeLmDTb.png)    

- and customize it
![image: 242x500,50%](/images/108059/lWTcCd7IITr4VYBek4um1YUjCKw.png) 

- Select <kbd>EMBED</kbd> and copy the string relative to the family font (1) inside the theme setting `Font`
![image: 539x500,50%](/images/108059/ned7eeDeHJLkeh5HGENI2pj3iol.png) 

- Copy and paste the string relative to CSS (2) inside the theme setting `font-family` (do not add the character `;` at the end of the string).

All the other settings should be clear enough.

The settings of this component are divided between **light** and **dark** theme. If you use both, remember to add the component to both themes.

-----------------------


![image: 690x232,70%](/images/108059/lWxvqytdDePVe6VpXdAhgYPTWl5.png)  

![image: 663x500,70%](/images/108059/lJBv1G9csaaLpKS0bbasYLUUMLP.png)  

------------------

### How do I install this component?

You install this component just like any other theme. Follow the instructions in the official guide:

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

Once you're done, simply add the component to your current theme.