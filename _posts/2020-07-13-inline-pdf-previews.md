---
title: Inline pdf previews
author: Joe
homepage: https://github.com/discourse-com/discourse-pdf-previews
download: https://github.com/discourse-com/discourse-pdf-previews
demo: https://theme-creator.discourse.org/theme/Johani/pdf-previews
thumbnail: /images/157649/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-pdf-previews/blob/master/LICENSE
category: Theme Components
meta_topic_id: 157649

---
This is a desktop-only theme component that will allow you to create previews for pdf attachments.

[Repository link](https://github.com/discourse-com/discourse-pdf-previews)
`https://github.com/discourse-com/discourse-pdf-previews`

Preview:
[https://theme-creator.discourse.org/theme/Johani/pdf-previews](https://theme-creator.discourse.org/theme/Johani/pdf-previews)


#### Samples

before

![pdf-previews-before: 690x276, 75%](/images/157649/bkr8tcFJGzotRerRZY4xJVTkx3Z.png) 

after

![pdf-previews-after: 516x500](/images/157649/rcmciQemd54f1eKDM6G37PoT0iI.png) 


#### Notes

Like I mentioned above, this component will only work on desktop. There's very little benefit to showing the previews on mobile since everything will be so small and very hard to read.

This component uses the native browser implementation to render the pdfs, so the results will look different on different browsers. 

Also note that this respects the user's browser preferences for rendering pdfs inline. So, if the user does not want to allow pdfs to render inline, they will see something like this on Safari for example

![image: 690x471, 75%](/images/157649/icLzl1x8iNcXD35W0LfhifylET7.png) 

but that can be easily fixed if they trust your site.

Also, please note that pdf uploads are not allowed by default in Discourse. If you want to allow your users to upload pdf file, then you'll need add that extension to either the 

`authorized_extensions`

If you want all of your users to be able to upload pdfs, or

`authorized_extensions_for_staff`

if you want to limit that to staff members.

#### How do I use it?

1. install the component
2. allow pdf uploads
3. refresh the page
4. upload a pdf

That's it. The rest should work automatigcally.

#### How do I install this theme component?

Follow the [theme installation guide](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) and add the theme component to your active themes.

If you're new to Discourse themes, you can learn more about them [here.](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)