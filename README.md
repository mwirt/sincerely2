# My Jekyll Boilerplate

A boilerplate with the setup I prefer when starting a new [Jekyll](https://jekyllrb.com/) site.

Includes jQuery 3.3.1, Bootstrap 4, Google webfont loader.

## Variables of Note

**share-image** is the location of an image that will be used when the url of the page is shared on facebook or twitter. Location is already set to img folder in assets, simply write the subpath from there. Example:

```
---
title: My Title
description: My Description
share-image: max-wirt.jpg
---
```

In _config.yml, there is a variable `theme-color`. Use this to set a color in your head metadata for favicons and theme.
