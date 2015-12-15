#Bear Included Themes

##Bear Skin _(bear_skin)_

Bear includes the [Bear Skin](https://www.drupal.org/project/bear_skin) base Drupal theme, which has some specific integrations with the bear installation profile. Bear Skin was originally built as a Zen sub-theme, but has since been updated to the point of Zen no longer being a dependency. Bear Skin 8 has never had a dependency of Zen.

##Bear Coat _(bear_coat)_

Bear Skin now includes Bear Coat as a sub-theme. Sub-themes allow styling and functionality to be inherited from a base theme, in this case Bear Skin. This allows theme developers to utilize Bear Skin's or Bear Coat's great features without having to redo any work. This also means that you can use the Bear Coat theme as your base theme to build your own custom theme inheriting it's core features.

To learn more about how to create a sub-theme of Bear Skin 8 or Bear Coat 8, please see the [Creating a Drupal 8 Sub-theme](https://www.drupal.org/node/2165673) Theming Guide on Drupal.org.

**Note:** It is NOT recommended to update Bear Skin, or any base theme for that matter, after creating your sub-theme unless there is a security update required. In the rare event that Bear Skin has a security update, you will want to do some additional tests to make sure there were not any changes made to the base theme that will affect your sub-theme.