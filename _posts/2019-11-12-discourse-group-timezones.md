---
title: Discourse-group-timezones
author: Joffrey Jaffeux
homepage: https://github.com/discourse/discourse-group-timezones
download: https://github.com/discourse/discourse-group-timezones
demo: 
thumbnail: 
license: 
license_link: 
category: Theme Components
meta_topic_id: 133178

---
https://github.com/discourse/discourse-group-timezones

![22: 690x213, 75%](/images/133178/fTZsEEzmeATOTJJlbgVsxU3lyfh.png) 

The discourse-group-timezones theme component can help you display people of a group in a timezone ordered list. It will also show who is in holiday/week-end/out of working hours.

This is useful for people using Discourse with a remote and distributed team to work on projects.

### Installation

Follow the instructions at [Install a Theme component](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) using `https://github.com/discourse/discourse-group-timezones.git` as the repository URL.

:warning: This plugin relies on the `timezone` field of a User being set. This field is available at the moment only when using [discourse-calendar](https://github.com/discourse/discourse-calendar), so you need to have this plugin to use this component.

### Usage

```
[wrap=group-timezones group=project-x-team][/wrap]
```

* `group` is mandatory
* `size` is optional and accepts: `small`, `medium`, `large`, `auto`

### Component settings
 
* `working day start hour` let's you define when the working day usually starts
* `working day end hour` let's you define when the working day usually ends
* `close to working day hours extension` let's you define how many hours around start/end working hours are acceptable if urgent to get in contact with someone
* `working days` let's you define which days of the week are worked

----

Thanks to my fellow Discoursers who beta-tested it and provided great feedback/ideas.  

Hope you enjoy this component! :tada: