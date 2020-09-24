---
title: Sam's personal "minimal" topic list design
author: Sam Saffron
homepage: https://github.com/discourse/discourse-simple-theme
download: https://github.com/discourse/discourse-simple-theme
demo: https://theme-creator.discourse.org/theme/sam/simple
thumbnail: /images/23552/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-simple-theme/blob/master/LICENSE.txt
category: Themes
meta_topic_id: 23552

---

**Theme Location**: https://github.com/discourse/discourse-simple-theme

**Preview**: [https://theme-creator.discourse.org/theme/sam/simple](https://theme-creator.discourse.org/theme/sam/simple)


I have been thinking about this a lot, and decided to take a shot at a "minimal" front page customisation.

To select this theme head to your profile: https://meta.discourse.org/my/preferences and select the theme. (remember to click save)

<img src="//assets-meta-cdck-prod-meta.s3.dualstack.us-west-1.amazonaws.com/original/3X/d/f/dfd9212dba865fb66fc923bc9b14d7d4141c1961.png" width="690" height="414"> 


Here is a list of things I did

- Remove Views
- Remove Star 
- Get rid of avatar images use names instead
- De-emphasize categories
- Use more "traditional color" for topic link
- Use replies instead of posts

Some conclusions from my experiment:

- I think "Replies" is much more natural than column name than "Posts", technically its simply "Posts - 1", however its a far clearer concept to convey and it *correctly* calls attention to Topics with only 1 posts, cause 0 is a number that stands out.

- Long term I think we should offer a "less loud" category style, the current rainbow of colors puts categories in a far more important bucket than the content, categorization feels secondary to title to me. 

- I feel the sea of avatars is a bit loud, not recommending changing it right away but I think it does add a lot of busyness to our front page

- For me the more traditional topic title colors work better, I find they catch the eye and call attention to the title nicely 

- The simplified design is definitely a lot more "boring", but I find working through very long lists easier with it.

- I am really not sure about zebra striping anymore, I think its actually causing more harm than good, the subtle line works way better in my simplified design

- Star should go, its just adding noise for almost no gain

- I am not going to get into an "ago" argument again, but for the simplified design I would have preferred "1 hour ago" as opposed to "1h" the extra verbiage would have added clarity and there is room above the name. 

I don't think the "simple design" is **better** than our current design, I just think it is different, and perhaps more familiar to existing forum users. It packs less information. 

Interestingly the "simple design" does not work at all any wider than 850px or so, which calls out to a need for some sort of auxiliary column to complement it (with faq or shoutbox or ads or whatever). 

A very cool thing is that this is all achieved using the customize menu. 

### PRE-REQ

Select category style bullet in site settings.  

Theme lives at: https://github.com/discourse/discourse-simple-theme click "Import" on the theme screen to add it.


### Install guide

[How to install a theme or theme component](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682)