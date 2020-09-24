---
title: Bundle ESM & CommonJS JavaScript into a Theme Component
author: Benjamin Lupton
homepage: https://github.com/bevry/extract-timestamp
download: https://github.com/bevry/extract-timestamp
demo: 
thumbnail: 
license: Other
license_link: https://github.com/bevry/duration-timestamp/blob/master/LICENSE.md
category: Theme Components
meta_topic_id: 147186

---
I recently published the theme component:

https://meta.discourse.org/t/youtube-timestamps-component/147091?u=balupton

Which does an ESM import of the npm package [extract-timestmap](https://github.com/bevry/extract-timestamp), which was scaffolded using [boundation](https://github.com/bevry/boundation) which generates a CommonJS edition for Node.js, and a ESM edition for browsers.

The theme component javascript `source/index.js` imports the dependency `extract-timestamp` like so:

https://github.com/bevry/discourse-component-youtubetimestamps/blob/34f5def462f44e35e7f3a7bb1dc9b95e800180db/source/index.js#L1-L5

Which uses this `build.bash` file to turn the `source/index.js` file that contains our theme component logic, into a `common/header.html` for discourse:

https://github.com/bevry/discourse-component-youtubetimestamps/blob/34f5def462f44e35e7f3a7bb1dc9b95e800180db/build.bash

Which is run by doing `bash ./build.bash` or if you are using a npm scripts workflow, via `npm run build` with:

https://github.com/bevry/discourse-component-youtubetimestamps/blob/34f5def462f44e35e7f3a7bb1dc9b95e800180db/package.json#L7

Which results in a `common/header.html` file that is packaged into a single file (bundling the imports from earlier):

https://github.com/bevry/discourse-component-youtubetimestamps/blob/34f5def462f44e35e7f3a7bb1dc9b95e800180db/common/header.html

This could be useful to others developing their own theme components.

I'll probably add first-class scaffolding support for discourse theme components to [boundation](https://github.com/bevry/boundation) at a later stage, to automate this guide.