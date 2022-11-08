Search
======

A Plugin for moziloCMS 2.0

The Search Plugin inserts the configured HTML for the Search Form. This is useful, if the HTML Markup was changed due to styling reasons, which would be overwritten by an CMS Update.

## Installation
#### With moziloCMS installer
To add (or update) a plugin in moziloCMS, go to the backend tab *Plugins* and click the item *Manage Plugins*. Here you can choose the plugin archive file (note that it has to be a ZIP file with exactly the same name the plugin has) and click *Install*. Now the Search plugin is listed below and can be activated.

#### Manually
Installing a plugin manually requires FTP Access.
- Upload unpacked plugin folder into moziloCMS plugin directory: ```/<moziloroot>/plugins/```
- Set default permissions (chmod 777 for folders and 666 for files)
- Go to the backend tab *Plugins* and activate the now listed new Search plugin

## Syntax
```
{Search}
```
Inserts the Search HTML.

## License
This Plugin is distributed under *GNU General Public License, Version 3* (see LICENSE) or - at your choice - any further version.

## Documentation
A detailed documentation and demo can be found here:  
https://github.com/devmount-mozilo/Search/wiki/Dokumentation

---

This project is completely free to use. If you enjoy it and don't have the time to contribute, please consider [donating via Paypal](https://paypal.me/devmount) or [sponsoring me](https://github.com/sponsors/devmount) to support further support and development. :green_heart:
