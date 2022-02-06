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
