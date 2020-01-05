Fancy Research Links
====================

[![Latest Release](https://img.shields.io/github/release/JustCarmen/fancy_research_links.svg)][1]
[![webtrees major version](https://img.shields.io/badge/webtrees-v1.x-green)][2]

Fancy Research Links Module for webtrees. This is a webtrees 1 module. It cannot be used with webtrees 2.

Description
-----------
A sidebar module that provides quick links to popular research web sites, using the individuals name as the search reference. There is a base stylesheet added to the module which should work with any theme.

[Here][7] you can get a quick overview of the plugins (search links) available. The plugins are grouped by search area.

You can extend the list of possible research sites by making your own plugin. Look in the src/Plugin folder of the module for examples.

A quick guide to add your own plugin:

1. Take a copy of one of the existing files from the modules plugin folder and rename it. Note: not all plugin files are exactly the same. Some have more variables depending on the research site they are linking to.

2. In the new file, change the class to match the file name and change the name of the link to something suitable.

3. At the research site you are linking to, perform a simple name only search, and note the URL the search generates. Use this to change the output of the link in your new plugin file, in the 'createLink' section taking careful note where the variables need to be inserted.

4. If you made a plugin that could be interesting for other users you can do a pull request or send me a copy.

If you still have troubles creating your own link, you can open a new issue and do a request.

On the Fancy Research Links configuration page you can select the plugins you want to use in the sidebar.

Translations
------------
You can help to translate this module. Updates to translations should be made at [the translation server][3]. Changes made there will be pushed to this repository periodically and will be included in the next release of this module.

Installation & upgrading
------------------------
For more information about these subjects go to the [JustCarmen help pages][4].

Bugs and feature requests
-------------------------
If you experience any bugs or have a feature request for this module you can [create a new issue on GitHub][5] or [use the webtrees subforum 'customising'][6] to contact me.

 [1]: https://github.com/JustCarmen/fancy_research_links/releases/latest
 [2]: https://webtrees.github.io/download/
 [3]: https://poeditor.com/join/project/D0MZk3x9yi
 [4]: http://www.justcarmen.nl/help-category/modules-help
 [5]: https://github.com/JustCarmen/fancy_research_links/issues?state=open
 [6]: http://www.webtrees.net/index.php/en/forum/4-customising
 [7]: http://www.justcarmen.nl/fancy-research-links-link-list/
