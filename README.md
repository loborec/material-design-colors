# Material design colors

This is a color palette css file based on the material design colors. Each of these colors is defined as a color class for color and background-color properties.

Installation
---

You can install the library with composer or manually.

#### Composer

Step 1. Edit your `composer.json`:

```json
{
    "require": {
        "loborec/material-design-colors": "1.0.0"
    }
}
```

Step 2. Install it:

```bash
$ curl -sS https://getcomposer.org/installer | php
$ php composer.phar install
```

Step 3. Include in the webpage:

```html
<link rel="stylesheet" type="text/css" href="[url to material.min.css]" media="screen, print" />
```

#### Manually From Release

Step 1. [Download the latest release](https://github.com/loborec/material-design-colors/releases) and upload the css files to a folder on your server.

Step 2. Include in the webpage:

```html
<link rel="stylesheet" type="text/css" href="[url to material.min.css]" media="screen, print" />
```

#### Manually From Source

Step 1. [Download the source](https://github.com/loborec/material-design-colors/master.zip) and upload the css files to a folder on your server.

Step 2. Include in the webpage:

```html
<link rel="stylesheet" type="text/css" href="[url to material.min.css]" media="screen, print" />
```


Basic Use
---

```css
<div class='color-red-500 bg-pink-400'>Red text on pink background</div>
```
