---
title: Trust-Level Avatar Flair
author: Taylor
homepage: https://github.com/tshenry/discourse-trust-level-avatar-flair
download: https://github.com/tshenry/discourse-trust-level-avatar-flair
demo: 
thumbnail: /images/82656/thumbnail.png
license: MIT License
license_link: https://github.com/tshenry/discourse-trust-level-avatar-flair/blob/master/LICENSE
category: Theme Components
meta_topic_id: 82656

---
This theme component allows an admin to add flair to user avatars based on the user's trust level. Trust level flair displays anywhere on the site that you would normally see group flair. There are a few theme settings to adjust the position of the flair in relation to the avatar.

<h4>Basic Examples (with group flair in place)</h4>

![examples: 690x175](/images/82656/9JGwdugRr17Iq1Uy7rMPYFDoXz7.png)

There is also a bottom-right position that will either replace group flair or be replaced by group flair depending on how you set the **"group flair always on top"** setting.

<h2>Installation</h2>

See https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682?source_topic_id=77929 And if you are brand new to themes, I highly reccomend checking out the https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966.

**Import Links:**
>`https://github.com/tshenry/discourse-trust-level-avatar-flair`


## Main setup


**Using images as flair**

You will need to add your own flair images to the theme component. A good size is around 100×100px. The one I used in the example above is 88×88px. There is a transparent template image included that can be used as a starting point.

The easiest way to add an image is to select the <kbd>+ Add</kbd> button under the **Uploads** section of the theme component and choose your flair image file. Repeat this for each flair image you want to include. Once you have the images uploaded, right click on the blue link and copy the url of the image. Finally, paste the url into the trust level field of your choice.

![39%20AM: 550x499, 60%](/images/82656/hf7JlPKLXtwDjvtLScDeMQFu4sJ.png) 

![30%20AM: 690x120, 75%](/images/82656/iGsN0ZyByUXK30HjVcvl2hwwueG.png)
<br>

**Using Font Awesome for your flair**

You can use Font Awesome icons instead of using uploaded images. A full list of available icons can be found [here](https://fontawesome.com/v4.7.0/icons/). All you need to do is **check the setting to use Font Awesome** then add the name of the icon to the appropriate flair image field:

![16%20AM: 690x164, 75%](/images/82656/gKhC4YoSUfahoF8qHHHLx2mbkkE.png) 

![24%20AM: 690x118, 75%](/images/82656/c1EnL8zBay0y1GS5Rl9WOSBJws3.png)

_IMPORTANT NOTE: Currently you cannot mix Font Awesome and images, if there is a strong interest in doing so, I can look into it further._


**Settings**

You will find that there are several settings available within this theme component. They have descriptions explaining what they do and how to use them, but if anyone has an suggestions on how to improve them to make things more clear, please let me know!

Hovering over the trust-level avatar flair will display the name of the trust level. If you wish to change the name of the trust level, you can go to **Admin > Customize > Text Content** and search for the following to change the names:

- `trust_levels.newuser.title`
- `trust_levels.basic.title`
- `trust_levels.member.title`
- `trust_levels.regular.title`
- `trust_levels.leader.title`

<h2>About</h2>

This was inspired by the discussion started here:

https://meta.discourse.org/t/proposal-flair-on-avatar-for-trust-level/81250

**Repo:** 
>[GitHub - tshenry/discourse-trust-level-avatar-flair](https://github.com/tshenry/discourse-trust-level-avatar-flair)

<br>
Please feel free to post if there are any questions, problems, or suggestions!