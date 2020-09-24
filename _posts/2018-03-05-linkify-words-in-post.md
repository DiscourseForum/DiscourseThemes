---
title: Linkify words in post
author: Sam Saffron
homepage: https://github.com/discourse/discourse-linkify-words
download: https://github.com/discourse/discourse-linkify-words
demo: 
thumbnail: /images/82193/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-linkify-words/blob/master/LICENSE
category: Theme Components
meta_topic_id: 82193

---
### Type

Theme component, this component can be included in your current theme. 

### Location

<https://github.com/discourse/discourse-linkify-words>

### How to Install

https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682

### What this does?

Allows you to automatically hyperlink certain words or patterns in your post with desired destination URL. 

### How to configure?

After importing the theme component, configure the theme settings with the format 

`WORD, https://destination.url.com`

or using regular expressions (in [JavaScript implementation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)) with the format

`/regex/, https://destination.url.com`

One item per line

![theme_settings: 690x161, 75%](/images/82193/zMAD7eNGXXTm4PDseTnlAtRI59H.png) 

### Using regular expressions
With regular expressions, you can match a certain pattern to a single URL. This is useful for synonyms or for words which can take different forms in the sentence etc.

However, you can also generate the URL automatically based on what was matched. For example, let's say you have a line of products, each with its own numeric id, and you want to autolink them to their own URLs. Using

`/product-([0-9]+)/, https://myshop.com/product/$1`

`product-42` will be autolinked to `https://myshop.com/product/42`
Notice the capturing parentheses in the regular expression and the `$1` in the URL which is substituted by the match inside the parenthesis. You can also capture multiple parts of the string and use `$2`, `$3` and so on.

Regular expressions are by default case sensitive (unlike WORD's which are case insensitive). However, you can change that by using a standard "i" modfier like this:

    /foo/i, https://example.com

In this case, FOO, Foo or foo will all be matched.

### Limitations

1. Replacement will only appear in the web UI and will not appear in emails.

2. Requires Discourse 2.0.0.beta3 +267 or later. 

### How this looks in action?

![image: 690x195](/images/82193/todQQGbJ6dc5J9ztEMOQUxQUsqs.png)

### Credits 

Big thanks to @Osama for building theme settings and  https://stackoverflow.com/questions/8949445/javascript-bookmarklet-to-replace-text-with-a-link for guiding on the implementation.