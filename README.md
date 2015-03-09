# WordPress
Various WordPress tweaks and fixes in plugins

## Plugins

### [Duplicate Post](https://wordpress.org/plugins/duplicate-post/) by *lopo*

#### Clash with plugin
All-in-One Events Calendar

#### Issue
When you try to do "New Draft" and/or "Clone", you are redirected to a "WordPress Failure Notice" page at */wp-admin/admin.php?action=duplicate_post_save_as_new_post&post=ID* which says
> Are you sure you want to do this? Please try again.

The "Please try again." link loops back to */wp-admin/edit.php*

#### Solution
I posted solution to public forum thread ["Clone" and "New Post" not working](https://wordpress.org/support/topic/clone-and-new-post-not-working?#post-6518664) and *diff* file on [PasteBin](https://pastebin.com/RzxZv8E3).

Here you find patched plugin that works with AI1EC.

