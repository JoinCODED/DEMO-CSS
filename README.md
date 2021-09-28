# Demo CSS

## Main instructions

1. Inline styling -> You shouldn't do it
2. Stylehseet -> make a new .css file
3. link with style sheet using the auto complete `link:css` inside head

```html
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

## How css looks like

1. In css we can change the styles using selectors in this format

```
SELECTOR{
  PROPERTY: VALUE;
}
```

2. There are three types of selectors

   1. element selector -> specifies an HTML element `h1`, `div`

   ```css
   div {
     /*All divs are going to take this styling*/
     prop: value;
   }
   ```

   2. id selector -> specifies a single element attribute that uses `id`

   ```css
   #idName {
     prop: value;
   }
   ```

   3. Class selector -> 95% you should use classes

   ```css
   .className {
     prop: value;
   }
   ```

## Common properties

- [ ] `color`
- [ ] `background-color`
- [ ] `padding`
- [ ] `margin`
- [ ] `font`
- [ ] `font-size`
- [ ] `width`
- [ ] `height`
- [ ] `display`
- [ ] `position`

## Flex center

- Make sure the width and height are max

```css
.center {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100vw;
  height: 100vh;
}
```

## Positions common values

- when making position absolute, you move elements using `top, bottom, right, left, z-index`

```css
.abs {
  position: absolute;
  top: -10px;
  right: -10px;
  z-index: 5;
}
```

- The absolute is going to be asbolute position relatively to the closest container. To let the `.abs` class be relative to a container, put it inside a container, and make the container relative

```css
.container {
  position: relative;
}
```
