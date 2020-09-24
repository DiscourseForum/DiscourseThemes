---
title: Alternative Voting Category Style
author: Taylor
homepage: https://github.com/tshenry/discourse-alternative-voting-category-style
download: https://github.com/tshenry/discourse-alternative-voting-category-style
demo: 
thumbnail: /images/101532/thumbnail.png
license: MIT License
license_link: https://github.com/tshenry/discourse-alternative-voting-category-style/blob/master/LICENSE
category: Theme Components
meta_topic_id: 101532

---
This theme component offers alternative styling for any specified categories that make use of the Discourse Voting plugin.

https://meta.discourse.org/t/discourse-voting/40121


### Installation

[Repository Link](https://github.com/tshenry/discourse-alternative-voting-category-style)
`https://github.com/tshenry/discourse-alternative-voting-category-style`


If you are unfamiliar with theme components and how to install them, check out the [theme installation guide](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682). And if you'd like to learn more about Discourse themes, take a look at [this guide](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966).


### Preview

![voting-preview: 689x346](/images/101532/uzLAkWsoRg70tarRf2CCpKVtvj9.png) 



The overall idea is based off of [this mockup](https://meta.discourse.org/t/unique-index-style-for-voting/59499/6?u=tshenry) created by @erlend_sh.


### Notable Features

- Compact view
- More prominent vote count
- Colored icon to indicate that you voted on the topic


### Settings

There is currently one setting use to specify which categories to apply the style:

![voting-settings: 690x159](/images/101532/v4BKhYAWmKRSh7Pe1pq4GE8Bkqr.png)

### Extra Customizations

If you want to customize the look of specific tags within your voting topic (see the "IN PROGRESS" tag in the preview image above), you can create an additional component and modify the following CSS to fit your needs


``` scss
.voting-category.list-container {
    .topic-list-item:not(.about-topic) {
        // Common styling for all listed tags
        [data-tag-name="in-progress"],
        [data-tag-name="my-tag-one"],
        [data-tag-name="my-tag-two"] {
            font-weight: bold;
            text-transform: uppercase;
            font-family: Trebuchet MS;
        }
        // Specific styling for individual tags
        [data-tag-name="in-progress"] {
            color: #9e63d0;
        }
        [data-tag-name="my-tag-one"] {
            color: #5bd04a;
        }
        [data-tag-name="my-tag-two"] {
            color: #5f5dd0;
        }
    }
}
```

### Future

The one thing that you may notice missing from the original mockup is an excerpt of the topic under the topic title. This feature would require changes to core or the voting plugin that will need to wait for now.

As always, please let me know if you experience any issues.

Big thanks @Simon_Cossar and @erlend_sh for working with me on this :heart_eyes: