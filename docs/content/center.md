---
title: Center
category: Layout
source: https://github.com/kevtiq/bace-css/blob/main/src/layout/_center.scss
---

The `.center` class allows you to center elements on the screen. It is responsive by nature, as it allows you to set a max-width and side-paddings through utilities. It sets itself apart by allowing specific elements to break from the set max-width and (for instance) take the entire width of the page (e.g. hero images).

![](/img/center.png)

## Utility classes

The available utility classes to alter the settings for `.center` are listed below.

- `.center-w-<name>`: set the max-width of the layout, including any potential side-padding. Based on `$bace-breakpoints`.
- `.center-g-<name>`: set the padding on each of the sides. The padding is applied to all direct children of the parent. Based on `$bace-sizes`.
- `.center-exception`: allows children to flow outside the max-width set in the parent.
- `.center-stretch`: class that makes all the children 100% width as well.
- `.center-inside`: class to center childeren.

> If the utility classes are not flexible enough and you want to adjust the way the layout pattern behaves, adjust the `--center-gutter`, and/or `--center-width` custom properties on the element you are applying this pattern to.
