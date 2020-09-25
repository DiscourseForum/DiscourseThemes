# Discourse Themes & Theme Components
A directory of the best-looking themes and theme components for Discourse forum software.


## Notice of Non-Affiliation and Disclaimer
We are not affiliated, associated, authorized, endorsed by, or in any way officially connected with the Discourse.org, and Civilized Discourse Construction Kit, Inc or any of its subsidiaries or its affiliates.

The names Discourse, Discourse.org, Discourse logo as well as related names, marks, emblems and images are registered trademarks of their respective owners.


## Submitting a Theme
Have a theme or theme component you want to share?

### Simple & easy steps to submit
* Fork [DiscourseThemes.dev on GitHub](https://github.com/DiscourseForum/DiscourseThemes)
* [Optional] Make a `350x300` thumbnail and drop it in the `images/[meta_topic_id]` directory. Then, list its filename in the post's markdown file. This step is optinal.
* Create a new post in the `_posts` directory and fill out the relevant YAML fields. See `/_drafts/1970-01-01-post-sample.md` for an example. Authors usually post a topic on https://meta.discourse.org then copy & paste their markdown here.
* Push your changes up and open a pull request.


### Example

An example of Front Matter

```yaml
---
title: My amazing Discourse theme
author: My name
homepage: https://github.com/myrepo/owesome-addon
download: https://github.com/myrepo/owesome-addon
demo: https://theme-creator.discourse.org/theme/MyName/owesome-addon
meta_topic_id: 99157649
category: Themes
thumbnail: /images/99157649/thumbnail.png
license: MIT License
license_link: https://github.com/myrepo/owesome-addon/blob/master/LICENSE
---

Your markdown content goes here. Authors usually post a topic on https://meta.discourse.org then copy & paste their markdown here.

```

Note that
* `title`, `author`, `download`, `meta_topic_id`, `category` are required.
* `category` must be `Themes`, `Theme Components`, or `Color Palettes`. This field ONLY accepts a single category.
* Other fields are recommended.



## TODO
- [ ] Author avatar using https://github.com/benbalter/jekyll-avatar


## License
License: MIT
