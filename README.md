WBBAuthLogin
============

Warning
-------
This plugin has been forked from an IPB plugin with the same purpose. While documentation has been updated, the code is still being edited. Please do not install this thinking it's a WBB plugin - I will remove this warning when that is the case.

Description
-----------
WBBAuthLogin is a plugin for MediaWiki 1.27 and up which integrates MediaWiki with an [Woltlab Burning Board](https://www.woltlab.com/) forum's user database. By enabling the extension, it is possible to log into the MediaWiki installation using WBB user accounts. The extension creates local user accounts on MediaWiki, which are always authenticated though this extension.

As WBB usernames are not case sensitive, extension converts any username into a canonical form, to avoid duplicate local accounts being created for the same user.

Requirements
------------

* MediaWiki 1.27+
* Woltlab Burning Board 4.1.x
* MySQL database for WBB
* PHP 7.0+ (Untested for PHP 5.6 and older)
* MySQLi PHP extension

Documentation
-------------

~~Extensive documentation for the extension can be found on its [mediawiki.org page](https://www.mediawiki.org/wiki/Extension:IPBAuthLogin).~~

License
-------

This extension is licensed under the included GPLv3 license.

Contributing
------------

Contributions can be made to the plugin by submitting pull requests through its [GitHub repository](https://github.com/LuzFaltex/IPBLoginAuth/).

TODO
----

* The extension currently only supports IPB 3. Working through converting to WBB.
* Support for account recovery through MediaWiki.
* Possible support for account creation through MediaWiki.
