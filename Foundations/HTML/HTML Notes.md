# HTML, CSS Notes

HTML, stands for Hyper Text Markup Language, which is used
to put headlines, paragraphs, tables.. on the page.

CSS, stands for Casscading Style Sheet, which is used to
set font, background color, etc.. on the page.

## HTML

---

### Comments

Comments aren't read by the browser, they are there to help the developers
to communicate and explain the code better.

`<!-- Text between -->` - This is how you create a comment.


### Tags - explained

Tags will tell the browser where elements starts and end.
Tags example:
```html
<p>Some text between</p>
```

---

## HTML-Boilplate

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

---

## HTML Tags

`<p>` - Used to create paragraphs

`<h1>-<h6>` - Headers to the page.
> **Note** - `h1` should always use for the heading overall page.

`<strong>` - will bold the text in between the tags. It is important for
screen readers because it will change the voice of the reader.

`<em>` - puts italic font and emphasis the element for screen readers.

`<ul>` - A bullet list. Used when you don't care about the order of the list
you just want everything to be on a list.

`<ol>` - A list with numbers, usually use to rate something or keep an order.

`<li>` - A list item
> **Note** - this tag is used in both `<ol>` and `<ul>`

`<a>` - tag to link to relative and absolute files.
- Absolute - link to webpages on the internet.
  > For example: link to google main site: `<a href="www.google.com">Hello world</a>`
- Relative - link to webpages in your website.
  > For example: link to the about page of the website: `<a href="about.html> About </a>`

`<div>` - An empty tag, usually best for styling with CSS
`<span>` - same as div but it on the text level and not on a block level
