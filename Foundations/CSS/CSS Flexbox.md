# CSS FlexBox layout

Flex container is created using: `display: flex`.

`flex : 1` - will affect the size of the flex element (how big it will be).
`flex` is a shortened property of:

- `flex-grow` - the element size
- `flex-shrink` - if the element will be smaller than all the flex items, they all will shrink to the same size
  - if you don't want an item to shrink then put: `flex-shrink: 0;`
- `flex-basis` - the base size of the element.
  - if set to `auto` it will look for a `width` property.

`flex-direction: column/row` - specify if we work on a col or a row
- cannot put `flex-basis: 0;`, must declare a size.

`justify-content` - align items across the x axes.
`align-items` - align items across the y axes.

`gap` - the same as adding margin just in between flex items.