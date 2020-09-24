---
title: Discourse-icon component
author: Joffrey Jaffeux
homepage: https://github.com/discourse/discourse-icon
download: https://github.com/discourse/discourse-icon
demo: 
thumbnail: 
license: 
license_link: 
category: Theme Components
meta_topic_id: 143374

---
discourse-icon is a new theme component which allows you to use icons from your SVG icon subset in a post.

Usage:
```
[wrap=icon id=square][/wrap]
```

Example:
This is the [wrap=icon id=far-square][/wrap] icon and the [wrap=icon id=pencil-alt][/wrap] icon.

```
This is the [wrap=icon id=far-square][/wrap] icon and the [wrap=icon id=pencil-alt][/wrap] icon.
```

Code:
https://github.com/discourse/discourse-icon

Note: if the icon doesn't show it's because it's not in your subset. If you are admin you can add it in your site settings: `svg icon subset`.