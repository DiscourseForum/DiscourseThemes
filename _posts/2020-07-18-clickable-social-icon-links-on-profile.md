---
title: Clickable Social Icon Links on Profile
author: juicecounty.prodigy
homepage: https://github.com/LeoMcA/namati-user-card-profile-theme
download: https://github.com/LeoMcA/namati-user-card-profile-theme
demo: 
thumbnail: /images/158136/thumbnail.jpeg
license: GNU General Public License v2.0
license_link: https://github.com/LeoMcA/namati-user-card-profile-theme/blob/master/LICENSE
category: Theme Components
meta_topic_id: 158136

---
A Theme Component that includes social icons as clickable within User Profile & User Cards if you are using the [User Cards Directory Theme Component](https://meta.discourse.org/t/user-card-directory/144479/29)

It's 99% copied from the discussion & code samples provided by @LeoMcA included in this conversation on [Meta](https://meta.discourse.org/t/link-custom-user-field-to-external-website/41218) and in [Namati User Card Profile Theme](https://github.com/LeoMcA/namati-user-card-profile-theme), but thought it would be helpful to dig it out from the thread and make it slightly more general.


[Repository Link](https://github.com/weallwegot/discourse-social-links-clickable)
`https://github.com/weallwegot/discourse-social-links-clickable`

## Sample

![Screen Shot 2020-07-18 at 11.57.12 AM: 690x174, 75%](/images/158136/shOfg0Jft7VVticID9PEfkJWMUG.jpeg) 


#### Notes

- Any users that don't include a value for an entry will not have the corresponding icon shown on their user card/profile
- Instagram & Twitter custom user fields only expect the user names (no "@" included), the name gets appended to the base URL
- I'd recommend making the Custom User Fields that will have icons *NOT* show on the User Card since it will then feel a bit redundant to have the text & the clickable icons. Just my opinion though, the theme does not automatically hide them.

#### Site Settings

Each custom field name entry should line up with what you call the customized user field in your discourse instance.
By default the theme-component will expect the names to be as shown below, but you can of course change them.
Strings are case-sensitive.
```
instagram_custom_field_name: 'Instagram'
twitter_custom_field_name: 'Twitter'
linkedin_custom_field_name: 'LinkedIn Profile'
```

Enjoy!