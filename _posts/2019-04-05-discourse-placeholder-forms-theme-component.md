---
title: Discourse Placeholder Forms theme component
author: Joffrey Jaffeux
homepage: https://github.com/discourse/discourse-placeholder-theme-component
download: https://github.com/discourse/discourse-placeholder-theme-component
demo: 
thumbnail: /images/113533/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-placeholder-theme-component/blob/master/LICENSE
category: Theme Components
meta_topic_id: 113533

---
# discourse-placeholder

This theme component will let you build dynamic documentation, by creating a form that replaces any occurrence of a =PATTERN= in your post with the value from a text or selectable input field.

**[:link: Repository Link](https://github.com/discourse/discourse-placeholder-theme-component)**

**[:link: Preview on Theme Creator](https://theme-creator.discourse.org/t/discourse-placeholder-theme-component/1160)**

## Usage

```
[wrap=placeholder key=NAME description="Your name"][/wrap]
[wrap=placeholder key=COUNTRY default=US defaults=FR,DE,US,CN,AU,CA][/wrap]

Your email: =NAME=-=COUNTRY=@example.com
```

This will result in:

![14: 690x270](/images/113533/rl4HcPzgb3J06dRNE3g7mwfpdRy.png) 

[wrap=placeholder key=ZNAME description="Your name"]
This is used in mailing list
[/wrap]
[wrap=placeholder key=ZCOUNTRY default=US defaults=FR,DE,US,CN,AU,CA][/wrap]

Your email: =ZNAME=-=ZCOUNTRY=@example.com

As seen above, text inside the wrapper will be used as a long description.

```
[wrap=placeholder key=NAME description="Your name"]
This is used in mailing list
[/wrap]
```

## Available keys

- key: The key that should be replaced in your post
- default/defaults: default value(s)
- description: a placeholder text for the input


## Examples



[wrap=placeholder key=PLUGIN_NAME description="Name of your plugin"][/wrap]

```
# create a new plugin
rails g plugin =PLUGIN_NAME=
cd plugins/=PLUGIN_NAME=
```

https://meta.discourse.org/t/setting-up-file-and-image-uploads-to-s3/7229

---

We use it to create runbooks, howtos and reusable templates (it will work in code blocks). Please share your use cases!