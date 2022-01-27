# HTML, CSS Notes

HTML, stands for Hyper Text Markup Language, which is used
to put headlines, paragraphs, tables.. on the page.

CSS, stands for Casscading Style Sheet, which is used to
set font, background color, etc.. on the page.

## HTML

### Tags

Tags will tell the browser where elements starts and end.
Tags example:
```html
<p>Some text between</p>
```

### HTML-Boilplate

`index.html` - should be the starting point of the project.
Web servers by default will look for this file when user load the page.

`<!DOCTYPE html>` - set the version of html to the latest version.

`<html>` - The root element of the webpage.

> **`lang` attribute** - specifies the language of the text content.


`<head>` - put important meta-information about the webpage.
**Shouldn't be used to display elements on the webpage.**

`<title>` - Includes in the `head` element. It sets the title of the webpage.

`<meta charset="utf-8">` - insures that the browser will display correctly
characters and icons.

`<body>` - Tag that will contain all the visual elements.

**Complete boilplate**
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>My First Webpage</title>
    <meta charset="UTF-8">
  </head>

  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```
