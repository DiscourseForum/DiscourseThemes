---
title: Segment Tracking Theme Component
author: Simon Cossar
homepage: https://github.com/scossar/discourse-segment-theme-component
download: https://github.com/scossar/discourse-segment-theme-component
demo: 
thumbnail: /images/133335/thumbnail.png
license: MIT License
license_link: https://github.com/scossar/discourse-segment-theme-component/blob/master/LICENSE
category: Theme Components
meta_topic_id: 133335

---
This theme component allows you to send data about your site's usage to [Segment](https://segment.com/).

The component supports calling  `segment.identify`  when a user first logs on to the site. For site's using SSO, you can either send the user's Discourse ID, or their `external_id` to Segment. The component allow you to track views of the Discourse latest, categories, category, tag, and topic pages. It also allows you to track topic and post creation, likes, flags, and bookmarks.

### Installation

Follow the https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 guide to install the component. Use `https://github.com/scossar/discourse-segment-theme-component` to install it directly from its Git repository. You can also download it from [here](https://github.com/scossar/discourse-segment-theme-component).

### Configuration

Add your Segment Write Key to the `segment write key` setting. Then select which events you would like to track:

![image: 599x500](/images/133335/ahSM0TWYCpfE3wj75mVo29x1kXc.png) 

The component extends your site's content security policy to add `https://cdn.segment.com/analytics.js/`.

Let me know of any issues you run into with the component, or if there are ways that the data sent to Segment could be improved.