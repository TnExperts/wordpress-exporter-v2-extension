# WordPress Exporter Redux Extension
Plugin that demonstrates the hooks in [WordPress Exporter Redux][] that allow
plugins to extend an export.

## Description

For this plugin to do anything at all, you will need to install/activate [WordPress Exporter Redux][].

This plugin doesn't actually do anything useful.  It merely demonstrates how a plugin
can take advantage of the hooks provided in [WordPress Exporter Redux][] that are not in
the standard exporter.

[WordPress Importer]: https://wordpress.org/plugins/wordpress-importer/
[WordPress Importer Redux]: https://github.com/pbiron/wordpress-importer-v2
[WordPress Exporter Redux]: https://github.com/pbiron/wordpress-exporter-v2
[WordPress Exporter Redux: Issues]: https://github.com/pbiron/wordpress-exporter-v2/issues
[WXR 1.3-proposed]: https://github.com/pbiron/wxr/1.3-proposed

## How do I use it?

1. Install and activate the [WordPress Exporter Redux][] plugin.
2. Install this plugin directly from GitHub. ([Download as a ZIP](archive/master.zip))
3. Activate this plugin
4. Head to Tools
5. Select "Export (v2)"
6. Follow the on-screen instructions.

## Change Log

### 0.2

* Now uses WP_XMLWriter
* Rewrote as a class (instead of using anonymous funcs)

### 0.1

* Init commit

## How can I help?

Have a comment/suggestion about the hooks in [WordPress Exporter Redux][] that this plugin demonstrations?
Head on over to [WordPress Exporter Redux: Issues][] and open an issue.

Have a comment about this plugin, per se?  I probably won't respond (after all, this is only a "demo")...but
if it is something really serious, then go ahead and open an issue here.
