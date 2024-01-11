# Starter Template Patterns

<!-- Please, do not remove these @TABLE EXAMPLES BEGIN and @TABLE EXAMPLES END comments or modify the table inside. This table is automatically generated from the data at _data/examples.json and _data/tags.json -->
<!-- @TABLE EXAMPLES BEGIN -->
| Folder                                                                                                         | Short description                          | Tags                                                                                                                                                                                                                                                                                   | Download .zip                                                                                                                      | Live Demo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [📁](https://github.com/WordPress/block-theme-examples/tree/master/twentytwentyfour-starter-template-patterns) | twentytwentyfour-starter-template-patterns | <small><code><a target="_blank" href="https://github.com/WordPress/block-theme-examples/wiki/Tags#block-theme">BLOCK THEME</a></code></small>, <small><code><a target="_blank" href="https://github.com/WordPress/block-theme-examples/wiki/Tags#curation">CURATION</a></code></small> | [📦](https://raw.githubusercontent.com/WordPress/block-theme-examples/master/_zips/twentytwentyfour-starter-template-patterns.zip) | [![](https://raw.githubusercontent.com/WordPress/block-theme-examples/master/_assets/icon-wp.svg)](https://playground.wordpress.net/#{%22$schema%22:%22https://playground.wordpress.net/blueprint-schema.json%22,%22landingPage%22:%22/wp-admin/themes.php%22,%22preferredVersions%22:{%22php%22:%228.0%22,%22wp%22:%22latest%22},%22steps%22:[{%22step%22:%22installTheme%22,%22themeZipFile%22:{%22resource%22:%22wordpress.org/themes%22,%22slug%22:%22twentytwentyfour%22}},{%22step%22:%22installTheme%22,%22themeZipFile%22:{%22resource%22:%22url%22,%22url%22:%22https://raw.githubusercontent.com/WordPress/block-theme-examples/master/_zips/twentytwentyfour-starter-template-patterns.zip%22},%22options%22:{%22activate%22:true}},{%22step%22:%22login%22,%22username%22:%22admin%22,%22password%22:%22password%22}]}) |
<!-- @TABLE EXAMPLES END -->

This is a child theme of the [Twenty Twenty-Four](https://wordpress.org/themes/twentytwentyfour/) theme, which is required for this example to work.

The goal of this child theme is to showcase an example of a block pattern that appears in a modal when a user adds a new template from the Site Editor. This template will only appear when create archive-type templates (e.g., archive, author, category, date, tag, and taxonomy). To read more about this feature, see the [Starter Template Pattern](https://developer.wordpress.org/block-editor/how-to-guides/curating-the-editor-experience/patterns/#prioritize-starter-patterns-for-template-creation) documentation in the Block Editor Handbook.

## Understanding the Example Code

This child theme adds a custom block pattern named `Archive Template`. The only file with code relevant to this example is:

- `patterns/template-archive.php`: Registers a custom pattern.