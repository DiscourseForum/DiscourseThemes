---
title: Topic footer buttons theme components
author: Joffrey Jaffeux
homepage: https://github.com/discourse/discourse-custom-topic-button-component
download: https://github.com/discourse/discourse-custom-topic-button-component
demo: 
thumbnail: 
license: MIT License
license_link: https://github.com/discourse/discourse-custom-topic-button-component/blob/master/LICENSE
category: Theme Components
meta_topic_id: 116968

---
Hi, let me introduce you two new simple theme components which have essentially the same goal but slightly different:

https://github.com/discourse/discourse-custom-topic-button-component

This component will let you define a button visible at the bottom of your topic to open a URL of your choice.

You can customise label/title/icon/link. Links accept multiple placeholders:

```
<TOPIC_ID>
<USER_ID>
<USERNAME>
<TOPIC_TITLE>
<TOPIC_SLUG>
```

which will be replaced accordingly.

https://github.com/discourse/discourse-topic-group-button-component

Has the same behaviour, except you can define a group to limit the visibility of this button.

---

These components are very simple right now, we could improve them in the future if we see real usage of it and issues.