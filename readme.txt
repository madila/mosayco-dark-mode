=== Dark Mode - Mosayco ===
Contributors:      Ruben Madila
Tags:              block
Tested up to:      6.6
Stable tag:        0.1.0
License:           GPL-2.0-or-later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

A way to integrate alternative colours for the dark mode version of you website, while adding a new block to toggle this behaviour or automatically use the user's device default.

== Description ==

This is the long description. No limit, and you can use Markdown (as well as in the following sections).

For backwards compatibility, if this section is missing, the full length of the short description will be used, and
Markdown parsed.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/mosayco-dark-mode` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Navigate to the Site Editor and add new Custom colours with the same colour slug and prefixed by  "dark-", e.g. "dark-accent-1".
4. Save the customisations.
5. Add the Dark mode block anywhere on your website, or let the plugin automatically toggle your website to the user's current theme.
6. Alternatively, use the theme.json custom "settings" > "custom" > "dark-mode" to add an array of colour alternatives, using the same naming conventions.


== Frequently Asked Questions ==

= Can I add dark mode gradients? =

Not at the moment, but I am working on an easy way to do it.

= Can I customise the Dark mode toggle button? =

I am in the process to declare the settings on the global scope so you can use the Global Styles to modify the block.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= 0.1.0 =
* Release

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above. This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation." Arbitrary sections will be shown below the built-in sections outlined above.
