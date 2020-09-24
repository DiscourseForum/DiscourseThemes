---
title: Timeline mute button
author: Kris
homepage: https://github.com/awesomerobot/discourse-mute-button
download: https://github.com/awesomerobot/discourse-mute-button
demo: 
thumbnail: /images/127859/thumbnail.png
license: MIT License
license_link: https://github.com/awesomerobot/discourse-mute-button/blob/master/LICENSE
category: Theme Components
meta_topic_id: 127859

---
This is a simple theme component that adds an explicit mute toggle under the topic timeline. The button toggles between `mute` and `normal` tracking statuses. 

![29%20PM: 541x500,75%](/images/127859/pWwUJLEHq7ve1dVH1qA6IeutMt7.png) 

:octopus: [Github repo](https://github.com/awesomerobot/discourse-mute-button): `https://github.com/awesomerobot/discourse-mute-button`

:question:  https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


That's all it does!  If you don't care about the other tracking types you can hide that now-redundant button with some CSS



```css
.timeline-container 
.timeline-footer-controls 
button.dropdown-select-box-header {
    display: none;
}
```