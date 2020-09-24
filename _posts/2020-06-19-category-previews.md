---
title: Category Previews
author: Taylor
homepage: https://github.com/tshenry/discourse-category-previews
download: https://github.com/tshenry/discourse-category-previews
demo: https://theme-creator.discourse.org/theme/tshenry/category-previews
thumbnail: /images/155296/thumbnail.png
license: MIT License
license_link: https://github.com/tshenry/discourse-category-previews/blob/master/LICENSE
category: Theme Components
meta_topic_id: 155296

---
This component will allow you to add "category previews" to your categories page so users are able to see that a category exists without having access to the actual category. The preview looks like a standard category, but can link to a specified page where a user can be educated on how to gain access.

I've included a simple example below, but there are many different ways this component can be configured. Please be sure to read all of the information included in the Theme Settings.

### Theme Creator Demo

<small>:warning: You will need to be logged into an account here on Meta for this to work </small>

1. Navigate to https://theme-creator.discourse.org and log-in using the button in the header if you are not already logged-in

2. Use the following link to activate the preview of this component: https://theme-creator.discourse.org/theme/tshenry/category-previews

3. Scroll down the category list until you find the "restricted category preview" category and attempt to enter it:

    ![image: 690x108, 75%](/images/155296/dVIKlYC4qO3fMKN31TIDm0GCvqY.png) 

4. You will be taken to a [published page](https://meta.discourse.org/t/page-publishing/151971) with instructions on how to proceed to access the category:

   ![Screen Shot 2020-06-18 at 5.33.58 PM: 690x298, 50%](/images/155296/zMm3Y5MSW99tdxK5aEVQ2tvXlHy.png) 


### Settings

I did my best to explain how this component works in the theme settings. The setup is not the most intuitive experience so feel free to ask questions and I will update the instructions to provide clarity.

![Screen Shot 2020-06-18 at 5.38.25 PM: 465x499](/images/155296/9oE7oEwcdXrnVYMHvhTXtodLNSy.png) 


### Additional Notes

I imagine there will be many different edge use-cases. I can't guarantee that I can make this component work with all of them, but feedback and suggestions are welcome :slight_smile:  Here are some things to keep in mind:

- Currently this will not work with the boxed categories styles. If there are enough requests, I can see about adding support
- There are `above-$CATEGORY` classes added to the previews that appear above a specific category. This can be used to add additional styling.
- This will not work with sub-categories displayed on the categories page
- Staff users and anonymous users will **always** see the category previews.
- Pay special attention to the **IMPORTANT** notes in the Theme Settings


### Installation

> :warning:  This requires core changes that were added in commit [ `a3e8124` ](https://github.com/discourse/discourse/commit/a3e812453ede5ad4a8ae00188c7aaf1fca4f77fc). Please make sure you have updated your site recently enough to have picked it up.

[Repository Link ](https://github.com/tshenry/discourse-category-previews)
`https://github.com/tshenry/discourse-category-previews`

If you are unfamiliar with theme components and how to install them, check out the [theme installation guide ](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682). And if you’d like to learn more about Discourse themes, take a look at [this guide ](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966).