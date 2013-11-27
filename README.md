K2 Redirector
=============
A simple Joomla plugin to perform a 301 redirect, en mass, of selected K2 views to the corresponding selected menu item. This plugin helps minimize exposure of unwanted automatically generated views, such as author pages,  with K2.

The non-SEF URLs for these views are:

- `index.php?option=com_k2&task=category` for the category view, Categories menu type
- `index.php?option=com_k2&task=user` for the user view, User page (blog) menu type
- `index.php?option=com_k2&task=tag` for the tag view, Tag menu type
- `index.php?option=com_k2&task=search` forthe search view, search results URLs in Advancded SEF Settings
- `index.php?option=com_k2&task=date` for the date view, date listings URLs in Advancded SEF Settings

Questions, problems, feature suggestions?
=============
Awesome! By all means, please create an [issue](https://github.com/betweenbrain/K2-Redirector/issues).

Status
====================
While the K2 Redirector plugin is being used in production, on a limited basis, it's status is still considered beta as backwards incompatible changes may take place.

Stable Master Branch Policy
====================
The master branch will, at all times, remain stable. Development for new features will occur in branches, and when ready, will be merged into the master branch.

In the event features have already been merged for the next release series, and an issue arises that warrants a fix on the current release series, the developer will create a branch based off the tag created from the previous release, make the necessary changes, package a new release, and tag the new release. If necessary, the commits made in the temporary branch will be merged into master.

Branch Schema
==============
The following branch schema will be followed:
* __master__: stable at all times, containing the latest tagged release for Joomla 3.x+.
* __develop__: the latest version in development for Joomla 3.x+. This is the branch to base all pull requests for Joomla 2.5+ on.
* __1.5-master__: stable at all times, containing the latest tagged release for Joomla 1.5.
* __1.5-develop__: the latest version in development for Joomla 1.5. This is the branch to base all pull requests for Joomla 1.5 on.


Contributing
====================
Your contributions are more than welcome! Please make all pull requests against the appropriate [develop](https://github.com/betweenbrain/K2-Redirector/tree/develop) branch for Joomla version 3.x+ and [1.5-develop](https://github.com/betweenbrain/K2-Redirector/tree/1.5-develop) for Joomla version 1.5.

