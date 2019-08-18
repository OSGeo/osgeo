# OSGeo web fonts

The OSGeo web font allows to use the [OSGeo fonts](https://github.com/OSGeo/osgeo/tree/master/marketing/branding/fonts) in any html document, with a cross-browser approach. Released under an [OFL 1.1]( https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL) license, it gathers the following fonts: 

* [Sintony](https://github.com/etunni/sintony) - created by Eduardo Rodriguez Tunni.
* [Miriam Libre](https://github.com/MichalSahar/Miriam-Libre) - created by Michal Sahar.

Please refer to the [OSGeo style guide](https://github.com/OSGeo/osgeo/blob/master/marketing/branding/styleguide-osgeo.pdf) for more detailed instructions on their use. 

# How to use

Download and extract **OSGeo-webfont.zip**. Copy the `/fonts` and `/css` folders to your working directory. The `/fonts` folder must contain all the `.svg`, `.ttf`, `.eot`, `.woff` and `.woff2` downloaded files. The `/css` folder must contain the `OSGeo-webfont.css` file.

Include the following link tag in the `head` section of your HTML document:

```http
<link rel="stylesheet" href="path/to/css/OSGeo-webfont.css" type="text/css">
```

Use the font names in your CSS, for example:

```css
h1, h2, h3 {
font-family: miriamlibrebold;
}
```
```css
h4, h5, h6 {
font-family: miriamlibreregular;
}
```
```css
.text-default {
font-family: sintonyregular;
}
```
```css
.text-bold {
font-family: sintonybold;
}
```

# Available font-families

| Font-family           | Font              | Font-weight  |
| ---------------|:----------:|:----------:|
| sintonyregular       | Sintony         | Regular          |
| sintonybold           | Sintony         | Bold               |
| miriamlibreregular | Miriam Libre | Regular          |
| miriamlibrebold     | Miriam Libre | Bold               |
