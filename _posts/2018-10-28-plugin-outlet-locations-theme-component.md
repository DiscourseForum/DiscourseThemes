---
title: Plugin outlet locations theme component
author: Richard - DiscourseHosting.com
homepage: https://github.com/discoursehosting/plugin-outlets-theme-component
download: https://github.com/discoursehosting/plugin-outlets-theme-component
demo: https://theme-creator.discourse.org/theme/RGJ/plugin-outlet-locations
thumbnail: /images/100673/thumbnail.png
license: 
license_link: 
category: Theme Components
meta_topic_id: 100673

---
Continuing the discussion from [Plugin Outlet Locations](https://meta.discourse.org/t/plugin-outlet-locations/29589):

I needed an updated version with all the plugin outlets that have been added recently and then I realised that it would be really easy to create a theme component for this, so there is no need to install a plugin any more.

https://github.com/discoursehosting/plugin-outlets-theme-component

The readme includes a script that will auto-generate the outlets based on the Discourse source code.

```
   #!/bin/bash
   grep -r plugin-outlet /var/www/discourse/app/|grep name|grep -o -e 'name=".*'|awk -F\" '{print $2}'|sort|uniq | while read p ; do
     echo "<script type=\"text/x-handlebars\" data-template-name=\"/connectors/$p/plugin-outlet-component\">"
     echo "<div class=\"outlet\">$p</div>"
     echo "</script>"
   done
```

![image: 690x272](/images/100673/evWVmujyWGsnqGN5v3GNOX980rx.png) 

![image: 449x500](/images/100673/bhRfHxoVLGxDoO3FzCkofYktBFy.png)

Theme preview: https://theme-creator.discourse.org/theme/RGJ/plugin-outlet-locations