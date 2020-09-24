---
title: Quick Quote Theme Component
author: Robert
homepage: https://github.com/merefield/discourse-quick-quote
download: https://github.com/merefield/discourse-quick-quote
demo: 
thumbnail: 
license: GNU General Public License v2.0
license_link: https://github.com/merefield/discourse-quick-quote/blob/master/LICENSE
category: Theme Components
meta_topic_id: 143621

---

Repo:  https://github.com/merefield/discourse-quick-quote

### What it does

Simply: it changes the behaviour of the Post Reply buttons (not Topic reply) to quote a Post automatically  in a single click.

There are several settings to refine what is quoted and when.  You can even specify nesting of quotes for that 'old skool' feel.

Because the automated quote is delivered to the Composer, you can refine it manually from there if you so wish (but that kind of defeats the 'quick' part :snail:). 

It doesn't change the behaviour of the bottom Topic Reply button, nor the Quoting tool.

### Why

* Some have felt the act of quoting takes too many clicks in the base install.  This is more of an issue on touch devices.

* "Auto-quoting" is particularly useful when the reply is to a post quite a way back.  This plugin counts how far back the referenced post was and will automatically enter a quote if far enough back.  This helps people understand context a bit quicker.

* It brings back 'Nested Quotes'!  (default OFF) The Component may be particularly attractive to those who are used to some of the 'old skool' forum platforms :space_invader:  and is a matter of taste - if you like to see nested quotes you now can, but be aware of the consequences to space!

### You don't need it if

You are 100% happy with out-of-the-box Topic Post Reply behaviour.  I am, but it's great to have options, right?

### Settings

`quick_quote_post_location_threshold:` "Number of posts back before quick quote enabled."

Control how far back a post needs to be before the auto-quoting is actioned.  Avoids unnecessary quotation of recent posts.

`quick_quote_remove_links:` "Remove all links (inc. pictures) from quotes"

Cleans things up and improves use of space

`quick_quote_remove_prior_quotes:` "Remove all prior (nested) quotes"

Enabled by default.  Clear this setting for the ultimate nested old-skool experience. (Sorry Jeff! ;) )

`quick_quote_remove_contiguous_new_lines:` "Remove unnecessary new lines"

New lines are over-rated.

`quick_quote_character_limit:` "Quote character limit (uses last x chars if total length is greater)"

Excerpts are pretty basic :slight_smile: Revert to Quote tool if you need a more targeted quote (which is not overridden by the plugin)

### Known Limitations

The Theme Component is fairly simple in the way it handles the preparation of a quote.  Some settings work better together than others and it's up to the admin to determine what works for them.  Some complexity is avoided, e.g. there is an excerpt character limit which can break words in half.  Formatting is simplified as tags are removed to avoid the risk of truncating a tag and causing corruption - again this is to achieve simplicity.  Quote processing relies heavily on regular expressions, not all of which are completely foolproof, but work 'well enough'.  These may be refined over the life of the Theme Component.

This was recently ported over from my identical Plugin, but may have picked up bugs in that process.   Let me know if you come across any.

### My sponsor and the inspiration for this Component

Please thank @Merlls_Rizzini for sponsoring this work. The functionality is a brain dump from both of us and is partially inspired [by this post](https://meta.discourse.org/t/unfortunately-i-had-to-pull-the-plug/117508?u=merefield) by @eesty.

NB This was based on my Fast Quote Plugin, but moved to a Theme Component format to give more site managers access if they are hosted by a third party.  @sam suggested this was converted to a Theme Component as there was no back-end component and @sully gave me the final push to move this over having created his very own Theme version.

All feedback welcome.