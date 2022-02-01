# CSS

## Basics

At the most basic level CSS divide to 3:

```CSS
Selector{
    property: value,
}
```

Types of selectors:

- Universal (\*) - select element of every type.
- Name of the element - select all elements with the same name.
- Class - select all the tags with this class

> Classes are added in the HTML:
> `<div class="red-color"></div>`

> **Note** - You can add multiple classes to the same element by separating
> them with a space between: `<div class="bg-blue font-red"></div>`

### Classes and ID's

Classes should be used only for styling.
Meanwhile, ID should be used more carefully as a way to say this is **THE ONLY**
tag that have them.

---

If there are more than one selector which have the same property:value then
we can omit them:

```CSS
.read,
.unread {
  color: white;
  background-color: black;
}
```

It is possible to chain selectors:

```CSS
.subsection.head{
    color:red;
}
```

When you chain a selector it selects an element that have both of the selectors.

## Properties

`color` - sets the text color
`background-color` - sets the background color > **Note**: you can use the following values: > `css > color: #1100ff; > color: rgb(100, 0, 127); > color: hsl(15, 82%, 56%); > color: rgba(15, 60, 32, 0.3); /*includes alpha value*/ >`
`font-family` - sets the font of the text

> It is possible to create fallbacks so if a font doesn't work in the browser then it can go to the next font.
>
> ```CSS
> font-family: "Times New Roman", sans-serif
> ```
>
> `font-size` - sets the size of the text
> `font-weight` - sets the boldness of text. Can be either a word or a number between 1-1000
> `text-align` - align text horizontally within the element.
> `height` - sets the height of the element. Prefer to use the word `auto`.
> `width` - sets the width of the element

## CSS Specification

1. Inline CSS
2. ID Selector
3. Class Selector (The one with the more classes is the choosen one)
4. Type selector
5. The last selector CSS that was written.

## Adding CSS to HTML

External CSS:

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
```

Internal CSS:

```html
<head>
  <style>
    div {
      color: white;
      background-color: black;
    }
  </style>
</head>
```

Inline CSS:

```html
<body>
  <div style="color: white; background-color: black;">...</div>
</body>
```

## CSS Chaining selectors

You can chain the classes or ID's:

```CSS
.first-class.chained-class{
    /*code goes here*/
}
```

Chaining the classes and id's means that the website will look if there is an element
which have all the classes and id - an **and** statement
