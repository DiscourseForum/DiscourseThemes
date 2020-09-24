---
title: Topic Template Placeholder Text theme component
author: Rhidian Bramley
homepage: https://github.com/naidihr/discourse-topic-template-placeholders
download: https://github.com/naidihr/discourse-topic-template-placeholders
demo: 
thumbnail: /images/149053/thumbnail.png
license: MIT License
license_link: https://github.com/naidihr/discourse-topic-template-placeholders/blob/master/LICENSE
category: Theme Components
meta_topic_id: 149053

---
# Topic Template Placeholder Text theme component

This theme component enables you to display Topic Templates as placeholders (watermarks) instead of as editable template text.

This allows you to provide custom instructions as a placeholder for each topic.

For example:

This is the normal placeholder (watermark) text.

![image: 690x193](/images/149053/wntyCVdmTzzh6nzxelROg1PlJf0.png) 

NB You can already change this site-wide by changing the custom text 

> Go to Admin >> Customise >> Text
> 
> Then search for the text that you see there on the screen.
> A search for “BBCode” should get you what you want:
> 
> Then change the values for js.composer.reply_placeholder to the placeholder text you want to display

You can also set a Topic Template in each category

In the Edit Category dialog select Topic Templates. You can add a custom template for your category.

![image: 452x500](/images/149053/n9aDvdXKzTDFKFbITHZp5ONzHK3.png) 

This works well BUT the user has to delete the template text before they can start typing their post.

This theme component enables you to display the topic template text as a placeholder (watermark) text instead of the editable text. You simply click on the box and start typing.

It can be set to display all Topic Templates as placeholders, or you can do it on a case-by-case basis by adding a [placeholder] indicator to the Topic Template.

![image: 623x500](/images/149053/h6iER4oOurPMrcfqOTI5NUAkisF.png) 

### Install the theme component 

:hammer_and_wrench: Git repo: [https://github.com/naidihr/discourse-topic-template-placeholders](https://github.com/naidihr/discourse-topic-template-placeholders)

:thinking: [How do I install a Theme or Theme Component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)

### Credits
Thanks to @merefield for refactoring the JQuery element to use the Ember framework and Discourse core.

Please note the updated version is only tested to work on Discourse versions from 2.4.1 If you are on an earlier version of discourse, please try the original version which has been tested in version 2.3.10
Original version repo: [https://github.com/naidihr/discourse-topic-template-placeholders_original](https://github.com/naidihr/discourse-topic-template-placeholders_original)