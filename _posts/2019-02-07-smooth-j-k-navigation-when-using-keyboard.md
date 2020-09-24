---
title: Smooth J/K navigation when using keyboard
author: Dan Ungureanu
homepage: https://github.com/discourse/discourse
download: https://github.com/discourse/discourse
demo: 
thumbnail: 
license: Other
license_link: https://github.com/discourse/discourse/blob/master/LICENSE.txt
category: Theme Components
meta_topic_id: 108634

---
> :warning: This theme component has been deprecated and reimplemented in core.

This theme component is on track to be implemented in core ([PR](https://github.com/discourse/discourse/pull/7084)).

https://github.com/udan11/discourse-jk-smooth-mooves

I amends the behaviour of <kbd>j</kbd><kbd>k</kbd> navigation within topics so the viewport scrolls as you hit the keys. 

It handles 3 cases:

1. Long posts will scroll to full view before going to next post
2. When you navigate between posts the window will scroll so you have context
3. It toggles to a fast navigation mode when long pressing a navigation key

This is installed on meta and can be used by selecting "Sam's Simple Theme"