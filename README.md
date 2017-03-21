# Custom Open Graph URLs WordPress plugin

Define custom OG URLs for each one of your posts. If you don't add a custom OG URL, the default one (post permalink) will be used.

## There are a few required conditions for this to work

- Jetpack must be active on your site.
- Jetpack's Sharing module or Jetpack's Publicize module have to be active.
- No other Open Graph plugin must be installed on your site.

## How to use the plugin

The plugin won't add any new input field or interface on your site. Once it's active, you can specify a custom Opeg Graph URL for each post by going to Posts > All Posts in your dashboard, clicking on the post you want to edit, and using the Custom Fields input field to add a new custom field with the name `custom_og_url` and the value you need, like so:

![Custom Fields' interface](https://cloud.githubusercontent.com/assets/426388/24169580/62189994-0e7e-11e7-9c9e-68548cf25444.png)

If you do not see a Custom Fields interface in your post editor, make sure it is enabled in your Screen Options at the top of the screen:

![Screen Options](https://cloud.githubusercontent.com/assets/426388/24169702/c07b4ab8-0e7e-11e7-9138-bc365ece7832.png)

## More info.

Find out more about this plugin here:
- [Original request](https://wordpress.org/support/topic/sharing-social-share-counts-are-gone/#post-8941087)
- [Filter used in the plugin](https://developer.jetpack.com/hooks/jetpack_open_graph_tags/)
