---
title: Blog Post Styling
author: Taylor
homepage: https://github.com/tshenry/discourse-blog-post-styling
download: https://github.com/tshenry/discourse-blog-post-styling
demo: https://theme-creator.discourse.org/theme/tshenry/blog-post-styling
thumbnail: /images/110841/thumbnail.jpeg
license: MIT License
license_link: https://github.com/tshenry/discourse-blog-post-styling/blob/master/LICENSE
category: Theme Components
meta_topic_id: 110841

---
This theme component will allow you to designate a blog category and will alter the look and feel of all topics within that category to appear more like a traditional blog post. This is essentially a theme component adaptation of the https://meta.discourse.org/t/blog-post-plugin/34739.

Preview at https://theme-creator.discourse.org/theme/tshenry/blog-post-styling

![01%20AM: 494x500,100%](/images/110841/4Q6XCLltzpvpZQ5osW1iWShEKns.jpeg)

### Installation

[Repository Link ](https://github.com/tshenry/discourse-blog-post-styling)
`https://github.com/tshenry/discourse-blog-post-styling`

If you are unfamiliar with theme components and how to install them, check out the [theme installation guide ](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682). And if you’d like to learn more about Discourse themes, take a look at [this guide ](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966).


### Usage tips:
- The image code of your featured image **should be the first line of the post**. The component will "move" that image above the topic title to produce the effect shown in the above example image.
- You can use `<big></big>` tags around the first letter of a word to create an initial effect
- You may wish to enable the category setting `Navigate to first post after topics are read` to always highlight the blog post when first entering a topic.
- The main image is centered within the available space. You may need to edit your photo for it to display the way you'd like.
  [details="Additional details"]
  The height of the blog image container is  `440px`  and the width is 100% of the main container. The image is centered within the available space, so if your image has `500px` height, `30px` will be cropped from the top, and `30px` from the bottom. Horizontal cropping starts at `1100px` (the max-width of the main content on a Discourse site) and will increase as the window narrows. The ideal scenario is to use an image that either has a centralized subject, or one that has a generalized subject such as a pattern or a nature shot like the one I show in my example.
  [/details]

- You can apply the styling to multiple categories. This can be accomplished by comma separating the category slugs, making sure to omit any spaces before of after the commas. Sub-categories can be added by following these steps:
  1. Get the link to the subcategory and isolate the part after  `/c/`

     `https://meta.discourse.org/c/`**support/wordpress**

  2. Replace the  `/`  with a  `-`  so that you get  **support-wordpress**
  3. Add the result to the theme setting


- When you first create the blog post topic, you will need to refresh the page to see the main image appear above the content. This only happens right after it is posted and only for the author of the topic.

Suggestions on how the component can be improved are welcome. I can't promise I'll be able to add the feature, or make the change, but it will certainly be considered :)

**Current to-do/feature request list**

- Make sure the component plays nice with DiscoToC (especially with RTL)
- Allow tags to be used as a way to apply the styling to a post
- Allow videos to be used in addition to images


Special thanks to @Simon_Cossar and @awesomerobot for the heavy inspiration their prior work provided in creating this.