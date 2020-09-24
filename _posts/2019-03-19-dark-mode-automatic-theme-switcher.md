---
title: Dark Mode Automatic Theme Switcher
author: Penar Musaraj
homepage: https://github.com/pmusaraj/discourse-dark-mode
download: https://github.com/pmusaraj/discourse-dark-mode
demo: 
thumbnail: 
license: MIT License
license_link: https://github.com/pmusaraj/discourse-dark-mode/blob/master/LICENSE
category: Theme Components
meta_topic_id: 112071

---
> :warning: Discourse now supports https://meta.discourse.org/t/automatic-dark-mode-color-scheme-switching/161593 in core, this component is now deprecated and should no longer be used. 

[Repository](https://github.com/pmusaraj/discourse-dark-mode):

```text
https://github.com/pmusaraj/discourse-dark-mode
```

Installation instructions: https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682 

### What this does?

This component allows automatic switching to a dark theme when the browser is set to dark mode. This works **for logged-in users** only on all browsers that support the [prefers-color-scheme](https://caniuse.com/#feat=prefers-color-scheme) media query. 

By default, this component is enabled and individual users can turn it off in their Preferences > Interface screen. Admins can also set the component to be default off, in which case users will see a button to enable automatic switching in their interface preferences 

https://d11a6trkgmumsb.cloudfront.net/original/3X/0/4/043dcb92eed5f4a179d050826cb1e009d16761f5.mp4 

### How it works? 

If the browser is in dark mode, this component will reload Discourse with the dark theme enabled. If the browser returns to light mode, this component will reload with the default enabled theme. 

It will also reload if dark mode is toggled while user is on the site (as shown in video above). 

(If you have more than two themes enabled, and the user has selected a theme other than default or dark, this component will do nothing, i.e. it will respect the user's choice.)

### Configuration

* Make sure you have a dark theme installed, and that it is selectable by users 
* Add this component to both the default theme and the dark theme (very important, if you don't add it to both themes, users won't be able to switch back to the default theme)
* In the component settings, enter the id of your dark theme in `dark theme id`