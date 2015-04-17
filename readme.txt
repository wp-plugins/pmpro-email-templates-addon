=== PMPro Email Templates ===

Contributors: strangerstudios, messica
Tags: pmpro, email, templates, customize, member, membership, subscription, addon
Requires at least: 3.5
Tested up to: 4.0
Stable tag: .5.3

== Description ==
Customize PMPro email templates right from the WordPress dashboard!
Simply select an email template from the dropdown list, edit, and save!

== Features ==
* Edit email templates directly from the WordPress dashboard!
* Imports existing email templates from paid-memberships-pro/email/ directory
* Ability to disable header, footer, and even entire emails.
* Filter to handle all $data variables
* Variable reference on Email Templates page

== Installation ==
1. Upload the `pmpro-email-templates` directory to the `/wp-content/plugins/` directory of your site.
2. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==
* I found a bug in the plugin.
  * Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/strangerstudios/pmpro-email-templates/issues

== Changelog ==
= .5.3 =
* BUG: Fixed bug where the wp_login_url() was not being set properly and throwing a warning that could break checkout.

= .5.2 =
* Added ability to disable header, footer, or even entire emails.

= .5.1.4 =
* Fixed magic quotes bug when saving template data.

= .5.1.3 =
* Fixed issue with database table name

= .5.1.2 =
* Hotfix: WordPress repo trunk was missing files

= .5.1.1 =
* Fixed various bugs with building the email body

= .5 =
* Fixed Subject bug
* Submit button is now disabled instead of hidden when saving templates - it just looked weird.

= .4 =
* Fixed warnings when setting up $data array.
* Fixed issue where emails were getting double content.

= .3 =
* Added reset button
* Added AJAX saving.
* Bug/style fixes

= .2 =
* Removed wp editor.
* Fixed some warnings.

= .1 =
* This is the initial version of the plugin.

