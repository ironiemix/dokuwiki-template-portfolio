# Template for OpenSchulportfolio

This is the template for the OpenSchulPortfolio project. This is version 3 of the template. It's based on the default `dokuwiki` template and adds some modifications on top. It should be somewhat forward compatible with new DokuWiki releases.

## Configuration

* `closedwiki`: will remove all wiki functionality from the interface when a user is not logged in
* `topmenu_page`: the page to be included as top navigation
* `exportbox`: allows you to diable the export section in the sidebar
* `print_new_window`: open the print view in a new tab
* `toolbox`: allows you to diable the tools section in the sidebar

Please also see infos on [customization](https://www.dokuwiki.org/template:dokuwiki#customizing) for the `dokuwiki` template.

## Differences to v2

When you upgrade from an older version, you will notice that the configuration options have been greatly reduced. However most of the functionality is still there. Here is how the old config settings are correspondent to the new way of doing things.

* `sitetitle`: use DokuWiki's standard `title` setting
* `schoolname`: use DokuWiki's standard `tagline` setting
* `userpage`: use DokuWiki's `showuseras` setting and select "full name + user link"
* `userpage_ns`: configure the `user` interwiki link
* `infomail`: disable or uninstall the `infopage` plugin to disable this
* `discuss`: disable or uninstall the `talkpage` plugin to disable this
* `discuss_ns`: configure the `talkpage` plugin instead
* `topmenu`: just empty the `topmenu_page` configuration or delete the page
* `sidebar`: use DokuWiki's builtin sidebar support
* `sidebar_page`: use DokuWiki's standard `sidebar` setting
* `winML*`: The "Windows Musterlösung" single sign on mechanism is obsolete and no longer supported

 
## License

Copyright (C) Frank Schiebel <frank@linuxmuster.net>, 
              Andreas Gohr <dokuwiki@cosmocode.de>

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; version 2 of the License

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See the COPYING file in your DokuWiki folder for detail
