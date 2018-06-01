# My Jekyll Boilerplate

A boilerplate with the setup I prefer when starting a new [Jekyll](https://jekyllrb.com/) site.

Includes jQuery 3.3.1, Bootstrap 4, Google/Typekit webfont loader, Font Awesome 5 svg/js.

## Site variables of note
**In _config.yml**

`theme-color: ` Use this to set a color in your head metadata for favicons and theme.

`ga-id: ` Place your Google analytics ID here.


## Page variables of note

`share-image: ` is the location of an image that will be used when the url of the page is shared on Facebook or Twitter. Location is already set to img folder in assets, simply write the subpath from there. Example:

```
---
title: My Title
description: My Description
share-image: max-wirt.jpg
---
```

## Includes of note


#### video.html

Use `{% include video.html ratio="16by9" url="https://www.youtube.com/embed/Sjx9oSJDAVQ" %}` for responsive video embeds.

Works for YouTube and Vimeo videos. `ratio` is the aspect ratio of your video. Can be "1by1", "4by3", "16by9", or "21by9". `url` is the url in the embed code for the video.sincerely productions n' new website
