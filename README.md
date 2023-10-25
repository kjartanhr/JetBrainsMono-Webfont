[![](https://data.jsdelivr.com/v1/package/gh/imeuropa/JetBrainsMono-Webfont/badge)](https://www.jsdelivr.com/package/gh/imeuropa/JetBrainsMono-Webfont)

> ⚠️ This project was created as a response to Google Font's lack of support for JetBrains Mono. Now that Google Fonts supports this specimen, it is recommended to [use it from there](https://fonts.google.com/specimen/JetBrains+Mono) instead.

# JetBrainsMono-Webfont
The JetBrainsMono font imported and ready to use in one CSS document using @font-face

## Import the font in your project

Simply download the repository as a .ZIP file and drop the `JetBrainsMono` folder into your fonts or css folder in your project. Then include the font by linking the CSS up with the HTML by using the `<link>` tag.

Alternatively you can load the CSS via the jsdelivr content delivery network by simply pasting this code snippet into the `<head>` section of your project:

`<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/kjartanhr/JetBrainsMono-Webfont@main/JetBrainsMono/JetBrainsMono.css">`

## Use the font properly

To use the JetBrainsMono font properly you should refrain from using the `font-weight` CSS rule and instead change the `font-family` rule to whichever of the following variations suits your use case:
* `JetBrainsMono-ExtraLight`
* `JetBrainsMono-ExtraLight-Italic`
* `JetBrainsMono-Light`
* `JetBrainsMono-Light-Italic`
* `JetBrainsMono-SemiLight`
* `JetBrainsMono-SemiLight-Italic`
* `JetBrainsMono-Regular`
* `JetBrainsMono-Italic`
* `JetBrainsMono-Medium`
* `JetBrainsMono-Medium-Italic`
* `JetBrainsMono-Bold`
* `JetBrainsMono-Bold-Italic`
* `JetBrainsMono-ExtraBold`
* `JetBrainsMono-ExtraBold-Italic`

To avoid compatability issues you should add a fallback to the default system monospace font in case the user's browser cannot load the font. This is done by adding a trailing comma to the name of the webfont followed by the word 'monospace'. An example of this would be `font-family: 'JetBrainsMono-Regular', monospace;`.

In the example above you can see that the webfont name is enclosed in single quotes, although not required, it is recommended to use these single quotes for fonts which are not by default enabled in CSS.

## License

As per the license of the JetBrainsMono font itself this project is licensed under the `Apache License 2.0` as an extension of the original project. 
