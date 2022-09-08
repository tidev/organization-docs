## Release process

Infos and checklists for SDK or CLI releases. Go through the list for each RC or GA release.

### General todos

* create new branch
* trigger changelog (automatic action/script?)
* clean up list: e.g. filter out "reverted" tickets
* create a post on titaniumsdk.com with the changelog:
 * version overview page (e.g. [11.x](https://github.com/tidev/titanium-docs/blob/main/docs/guide/Titanium_SDK/Titanium_SDK_Release_Notes/Titanium_SDK_Release_Notes_11.x/README.md))
   * add new detail page
 * detail page (e.g. [11.0.0.GA](https://github.com/tidev/titanium-docs/blob/main/docs/guide/Titanium_SDK/Titanium_SDK_Release_Notes/Titanium_SDK_Release_Notes_11.x/Titanium_SDK_11.0.0.GA_Release_Note.md))
   * copy the release notes
   * change the date/version
 * change [default readme](https://github.com/tidev/titanium-docs/blob/main/docs/guide/Titanium_SDK/Titanium_SDK_Release_Notes/README.md) and add latest GA infos
* blog post on tidev.io ([repo](https://github.com/tidev/tidev-www/tree/main/posts/2022))
* check [downloads.titaniumsdk](https://downloads.titaniumsdk.com/releases) for the correct version ([repo](https://github.com/tidev/downloads-www))
* test `ti sdk install latest` and `ti sdk install [version number]`
* tweet the blog post
* post it on slack in `#announcements`



## TODO

* add post templates with placeholders to quickly generate announcements
* extend the todos with SDK and CLI related actions
* add some fallbacks like: actions not triggered automatically -> do this by hand
