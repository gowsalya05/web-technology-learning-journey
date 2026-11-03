## Table of Contents

1. CSS Basics
2. Adding CSS to HTML
3. CSS Selectors
4. Combinator Selectors
5. Pseudo-Classes
6. Pseudo-Elements
7. Attribute Selectors
8. CSS Typography
9. Background Properties
10. Height and Width
11. Font Properties
12. CSS Box Model
13. Position Properties
14. Display Properties
15. Flexbox
16. CSS Grid
17. Transitions
18. 2D and 3D Transforms
19. Animations
20. Media Queries

---

## 1. CSS Basics

**CSS (Cascading Style Sheets)** is a style sheet language used to style and align HTML elements.

* CSS is used to control the appearance and layout of web pages.
* It is generally used with HTML to style web pages and user interfaces.
* CSS can change colors, fonts, spacing, borders, backgrounds, and layouts.
* CSS comments are written using `/* */`.

### CSS Syntax

```css
selector {
    property: value;
}
```

Example:

```css
p {
    color: red;
    font-size: 20px;
}
```

Here:

* `p` is the selector.
* `color` and `font-size` are properties.
* `red` and `20px` are values.

---

## 2. Adding CSS to HTML

There are three main ways to add CSS to an HTML document.

### 2.1 Inline CSS

Inline CSS uses the `style` attribute directly inside an HTML element.

```html
<p style="color: red;">Hello CSS</p>
```

### 2.2 Internal CSS

Internal CSS is written inside the `<style>` tag in the `<head>` section of the HTML document.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        p {
            color: blue;
        }
    </style>
</head>
<body>
    <p>Hello CSS</p>
</body>
</html>
```

### 2.3 External CSS

External CSS is written in a separate file with the `.css` extension.

HTML file:

```html
<link rel="stylesheet" href="style.css">
```

CSS file (`style.css`):

```css
p {
    color: green;
}
```

### @import Rule

The `@import` rule is used to import one CSS file into another CSS file.

```css
@import url("style.css");
```

---

## 3. CSS Selectors

CSS selectors are used to select HTML elements that we want to style.

### Types of CSS Selectors

1. Simple selectors
2. Combinator selectors
3. Attribute selectors
4. Pseudo-class selectors
5. Pseudo-element selectors

### 3.1 ID Selector (`#`)

The ID selector targets an element using its unique `id` attribute.

```html
<h1 id="heading">Welcome</h1>
```

```css
#heading {
    color: red;
}
```

### 3.2 Class Selector (`.`)

The class selector targets elements using their class name.

```html
<p class="para">Hello World</p>
```

```css
.para {
    color: blue;
}
```

Multiple elements can share the same class.

### 3.3 Universal Selector (`*`)

The universal selector selects all HTML elements.

```css
* {
    margin: 0;
    padding: 0;
}
```

### 3.4 Element Selector

The element selector targets HTML elements by their tag name.

```css
p {
    color: green;
}

h1 {
    font-size: 30px;
}
```

### 3.5 Grouping Selector (`,`)

The grouping selector applies the same styles to multiple selectors.

```css
h1, p, button {
    color: purple;
}
```

### Basic Selector Priority

When declarations conflict, specificity generally follows this order:

**ID selector > Class selector > Element selector**

The universal selector has very low specificity.

---

## 4. Combinator Selectors

Combinator selectors are used to select elements based on their relationship with other elements.

There are four main types:

1. Descendant selector
2. Child selector
3. Adjacent sibling selector
4. General sibling selector

### 4.1 Descendant Selector (Space)

Selects elements that are descendants of a specified element, at any nesting level.

```css
div p {
    color: red;
}
```

This selects all `<p>` elements inside a `<div>`, including nested descendants.

### 4.2 Child Selector (`>`)

Selects only the direct children of a specified element.

```css
div > p {
    color: blue;
}
```

This selects `<p>` elements that are direct children of `<div>`.

### 4.3 Adjacent Sibling Selector (`+`)

Selects the element that immediately follows another element and shares the same parent.

```css
h1 + p {
    color: green;
}
```

This selects the first `<p>` immediately following an `<h1>`.

### 4.4 General Sibling Selector (`~`)

Selects all matching siblings that follow the specified element and share the same parent.

```css
h1 ~ p {
    color: purple;
}
```

This selects all `<p>` siblings that appear after an `<h1>`.

---

## 5. Pseudo-Classes

A CSS pseudo-class is a keyword added to a selector to style an element in a particular state.

The symbol used for a pseudo-class is `:`.

### Syntax

```css
selector:pseudo-class {
    property: value;
}
```

### 5.1 Dynamic Pseudo-Classes

* `:link` — selects an unvisited link.
* `:visited` — selects a visited link.
* `:hover` — applies styles when the mouse pointer is over an element.
* `:active` — applies styles while an element is being activated.
* `:focus` — applies styles when an element receives focus.

Example:

```css
a:link {
    color: blue;
}

a:visited {
    color: purple;
}

a:hover {
    color: red;
}

a:active {
    color: green;
}

input:focus {
    background-color: lightyellow;
}
```

### 5.2 Structural Pseudo-Classes

* `:first-child` — selects an element that is the first child of its parent.
* `:last-child` — selects an element that is the last child of its parent.
* `:nth-child(n)` — selects an element based on its position among its siblings.

Example:

```css
li:first-child {
    color: red;
}

li:last-child {
    color: blue;
}

li:nth-child(2) {
    color: green;
}
```

To select even and odd children:

```css
li:nth-child(even) {
    background-color: lightgray;
}

li:nth-child(odd) {
    background-color: lightyellow;
}
```

You can also use formulas such as `2n` for even positions and `2n+1` for odd positions.

---

## 6. Pseudo-Elements

A CSS pseudo-element is used to style a specific part of an element.

The symbol used for a pseudo-element is `::`.

### Syntax

```css
selector::pseudo-element {
    property: value;
}
```

### Common Pseudo-Elements

* `::first-line` — styles the first line of text.
* `::first-letter` — styles the first letter of text.
* `::before` — inserts generated content before an element's content.
* `::after` — inserts generated content after an element's content.
* `::marker` — styles list-item markers.
* `::selection` — styles the portion of text selected by the user.

Example:

```css
p::first-letter {
    color: red;
    font-size: 30px;
}

p::first-line {
    font-weight: bold;
}

h1::before {
    content: "★ ";
}

h1::after {
    content: " ★";
}

li::marker {
    color: red;
}

::selection {
    background-color: yellow;
    color: black;
}
```

---

## 7. Attribute Selectors

Attribute selectors target HTML elements based on their attributes or attribute values.

### Select by Attribute Name

```css
input[type] {
    border: 1px solid blue;
}
```

This selects `<input>` elements that have a `type` attribute.

### Select by Attribute Name and Value

```css
input[type="text"] {
    background-color: lightyellow;
}
```

This selects `<input>` elements whose `type` attribute is `"text"`.

---

## 8. CSS Typography

CSS typography properties control the appearance and formatting of text.

### 8.1 Color

The `color` property sets the text color.

CSS supports color names, hexadecimal values, RGB values, and RGBA values.

```css
p {
    color: red;
}
```

Hexadecimal example:

```css
p {
    color: #ff0000;
}
```

RGB example:

```css
p {
    color: rgb(255, 0, 0);
}
```

In RGB:

* Red represents red intensity.
* Green represents green intensity.
* Blue represents blue intensity.
* Each component generally ranges from `0` to `255`.

Examples:

```css
color: rgb(255, 0, 0);     /* Red */
color: rgb(0, 0, 0);       /* Black */
color: rgb(255, 255, 255); /* White */
```

RGBA includes an alpha value that controls opacity.

```css
p {
    color: rgba(160, 200, 100, 0.4);
}
```

The alpha value ranges from `0` (fully transparent) to `1` (fully opaque).

### 8.2 Text Alignment

The `text-align` property controls horizontal text alignment.

Common values:

* `left`
* `right`
* `center`
* `justify`

```css
h1 {
    text-align: center;
}
```

### 8.3 Text Transform

The `text-transform` property controls letter capitalization.

```css
.upper {
    text-transform: uppercase;
}

.lower {
    text-transform: lowercase;
}

.capital {
    text-transform: capitalize;
}
```

### 8.4 Text Shadow

The `text-shadow` property adds a shadow to text.

Syntax:

```css
text-shadow: horizontal vertical blur color;
```

Examples:

```css
h1 {
    text-shadow: 2px 2px;
}

h2 {
    text-shadow: 2px 2px red;
}

h3 {
    text-shadow: 2px 2px 5px red;
}
```

### 8.5 Letter Spacing

The `letter-spacing` property sets the space between characters.

```css
p {
    letter-spacing: 2px;
}
```

### 8.6 Word Spacing

The `word-spacing` property sets the space between words.

```css
p {
    word-spacing: 5px;
}
```

### 8.7 Text Indentation

The `text-indent` property sets the indentation of the first line of text.

```css
p {
    text-indent: 30px;
}
```

### 8.8 Text Decoration

The `text-decoration` property adds decoration to text.

Common decoration lines:

* `underline`
* `overline`
* `line-through`
* `none`

```css
h1 {
    text-decoration-line: underline;
}
```

Other text-decoration properties:

```css
p {
    text-decoration-line: underline;
    text-decoration-color: red;
    text-decoration-style: dashed;
    text-decoration-thickness: 2px;
}
```

Common decoration styles include `solid`, `dashed`, `dotted`, `double`, and `wavy`.

The `text-decoration` shorthand can combine these values:

```css
p {
    text-decoration: underline red dashed 2px;
}
```

### 8.9 Line Height

The `line-height` property specifies the height of a line of text.

```css
p {
    line-height: 30px;
}
```

### 8.10 Box Shadow

The `box-shadow` property adds one or more shadows around an element's box.

Syntax:

```css
box-shadow: h-shadow v-shadow blur-radius spread-radius color;
```

Example:

```css
.box {
    box-shadow: 5px 5px 10px 2px gray;
}
```

The spread radius is optional, and the default shadow color is generally based on the element's `currentColor`.

---

## 9. Background Properties

CSS background properties control the background of an element.

### 9.1 Background Color

Sets the background color.

```css
body {
    background-color: lightblue;
}
```

### 9.2 Background Image

Sets an image as the background.

```css
body {
    background-image: url("image.jpg");
}
```

By default, background images repeat horizontally and vertically.

### 9.3 Background Repeat

Controls whether and how the background image repeats.

```css
body {
    background-repeat: no-repeat;
}
```

Common values:

* `repeat`
* `repeat-x`
* `repeat-y`
* `no-repeat`

### 9.4 Background Size

Controls the size of the background image.

```css
body {
    background-size: cover;
}
```

Another example:

```css
body {
    background-size: 100%;
}
```

### 9.5 Background Position

Controls the position of the background image.

```css
body {
    background-position: center;
}
```

Other common values include `top`, `bottom`, `left`, and `right`.

### 9.6 Background Attachment

Controls whether the background image scrolls with the page or stays fixed.

```css
body {
    background-attachment: fixed;
}
```

Common values:

* `scroll`
* `fixed`

### 9.7 Gradients

CSS gradients create smooth transitions between colors.

**Linear Gradient**

```css
.box {
    background: linear-gradient(to right, red, yellow);
}
```

**Radial Gradient**

```css
.box {
    background: radial-gradient(circle, red, yellow, green);
}
```

---

## 10. Height and Width

The `height` and `width` properties set the dimensions of an element.

```css
.box {
    width: 300px;
    height: 200px;
}
```

Common values include:

* `auto` — lets the browser calculate the value.
* Length values such as `px`.
* Percentage values such as `%`.
* `initial` — resets the property to its initial value.
* `inherit` — uses the parent's computed value.

### Minimum and Maximum Dimensions

* `min-width` — sets the minimum width.
* `max-width` — sets the maximum width.
* `min-height` — sets the minimum height.
* `max-height` — sets the maximum height.

Example:

```css
.container {
    width: 80%;
    max-width: 1000px;
    min-height: 200px;
}
```

---

## 11. Font Properties

CSS font properties control how text characters appear.

### 11.1 Font Size

The `font-size` property sets the size of the text.

```css
p {
    font-size: 20px;
}
```

Other possible values include `small`, `medium`, `large`, `smaller`, `larger`, and relative units such as `em` and `rem`.

### 11.2 Font Weight

The `font-weight` property controls text thickness.

```css
p {
    font-weight: bold;
}
```

Common values:

* `normal`
* `bold`
* `bolder`
* `lighter`
* Numeric values such as `100` to `900`, depending on the font.

### 11.3 Font Style

The `font-style` property controls the style of text.

```css
p {
    font-style: italic;
}
```

Common values:

* `normal`
* `italic`
* `oblique`

### 11.4 Font Family

The `font-family` property specifies the font used for text.

```css
p {
    font-family: Arial, sans-serif;
}
```

---

## 12. CSS Box Model

The CSS box model describes how each HTML element occupies space on a webpage.

It consists of four main parts:

1. Content
2. Padding
3. Border
4. Margin

### Content

The content is the actual text, image, or other material inside the element.

### Padding

Padding is the space between the content and the border.

```css
.box {
    padding: 20px;
}
```

Padding properties:

* `padding-top`
* `padding-bottom`
* `padding-left`
* `padding-right`

### Border

The border surrounds the content and padding.

```css
.box {
    border: 2px solid red;
}
```

Border properties include:

* `border-width` — controls border thickness.
* `border-style` — controls the border style.
* `border-color` — controls border color.
* `border-radius` — rounds the corners.

Common border styles include `solid`, `dashed`, `dotted`, `double`, and `groove`.

Example:

```css
.box {
    border-width: 2px;
    border-style: solid;
    border-color: blue;
    border-radius: 10px;
}
```

### Margin

Margin is the space outside the border.

```css
.box {
    margin: 20px;
}
```

Margin properties:

* `margin-top`
* `margin-bottom`
* `margin-left`
* `margin-right`

### Complete Box Model Example

```css
.box {
    width: 200px;
    padding: 20px;
    border: 2px solid black;
    margin: 30px;
}
```

By default, the declared width applies to the content area. Padding and borders add to the total width.

The `box-sizing` property can change this behavior.

```css
* {
    box-sizing: border-box;
}
```

With `border-box`, the declared width and height include the content, padding, and border.

---

## 13. Position Properties

The CSS `position` property specifies how an element is positioned in a document.

Properties such as `top`, `right`, `bottom`, and `left` can be used to adjust positioned elements.

### 13.1 Static

`static` is the default position value. The element follows the normal document flow.

```css
.box {
    position: static;
}
```

### 13.2 Relative

`relative` positions an element relative to its normal position.

```css
.box {
    position: relative;
    top: 20px;
    left: 10px;
}
```

### 13.3 Absolute

`absolute` positions an element relative to its nearest positioned ancestor. If there is no such ancestor, it is positioned relative to the initial containing block.

```css
.parent {
    position: relative;
}

.child {
    position: absolute;
    top: 10px;
    right: 10px;
}
```

### 13.4 Fixed

`fixed` positions an element relative to the viewport. It generally stays in the same place when the page is scrolled.

```css
.box {
    position: fixed;
    top: 0;
    right: 0;
}
```

### 13.5 Sticky

`sticky` behaves like a relatively positioned element until a specified scroll threshold is reached. It then sticks within its scrolling container.

```css
header {
    position: sticky;
    top: 0;
}
```

---

## 14. Display Properties

The `display` property specifies how an element is displayed.

### 14.1 Block

A block-level element starts on a new line and generally takes up the available width.

Examples include `<div>` and `<p>`.

```css
.box {
    display: block;
}
```

### 14.2 Inline

An inline element does not start on a new line. The `width` and `height` properties generally do not affect its layout.

Example: `<span>`.

```css
span {
    display: inline;
}
```

### 14.3 Inline-Block

An inline-block element flows alongside other inline content while allowing width and height to be set.

```css
.box {
    display: inline-block;
    width: 150px;
    height: 100px;
}
```

### 14.4 Flex

Displays an element as a block-level flex container.

```css
.container {
    display: flex;
}
```

### 14.5 Grid

Displays an element as a block-level grid container.

```css
.container {
    display: grid;
}
```

---

## 15. Flexbox

Flexbox is a CSS layout model used to arrange items in a row or column.

To create a flex container:

```css
.container {
    display: flex;
}
```

### 15.1 Flex Direction

The `flex-direction` property sets the direction of flex items.

Values:

* `row`
* `column`
* `row-reverse`
* `column-reverse`

```css
.container {
    display: flex;
    flex-direction: row;
}
```

### 15.2 Flex Wrap

The `flex-wrap` property controls whether items can move onto multiple lines.

Values:

* `nowrap`
* `wrap`
* `wrap-reverse`

```css
.container {
    display: flex;
    flex-wrap: wrap;
}
```

### 15.3 Justify Content

The `justify-content` property aligns items along the main axis.

Common values:

* `flex-start`
* `flex-end`
* `center`
* `space-between`
* `space-around`
* `space-evenly`

```css
.container {
    display: flex;
    justify-content: center;
}
```

### 15.4 Align Items

The `align-items` property aligns items along the cross axis.

Common values:

* `stretch`
* `flex-start`
* `flex-end`
* `center`
* `baseline`

```css
.container {
    display: flex;
    align-items: center;
}
```

### Complete Flexbox Example

```html
<div class="container">
    <div class="box">1</div>
    <div class="box">2</div>
    <div class="box">3</div>
</div>
```

```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
}

.box {
    width: 100px;
    height: 100px;
    background-color: lightblue;
}
```

---

## 16. CSS Grid

CSS Grid is a layout system used to arrange elements in rows and columns.

It helps create structured and complex web layouts.

### Grid Container

An element becomes a grid container when `display: grid` is applied.

```css
.container {
    display: grid;
}
```

### 16.1 Grid Template Columns

The `grid-template-columns` property defines the number of columns and their widths.

```css
.container {
    display: grid;
    grid-template-columns: 100px 200px 100px;
}
```

Using `auto`:

```css
.container {
    display: grid;
    grid-template-columns: auto auto auto;
}
```

Using `fr`:

```css
.container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
}
```

The `fr` unit represents a fraction of the available space.

Using `repeat()`:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

### 16.2 Grid Template Rows

The `grid-template-rows` property defines row sizes.

```css
.container {
    display: grid;
    grid-template-rows: 100px 200px;
}
```

### 16.3 Grid Column

The `grid-column` property specifies the columns an item occupies.

```css
.item {
    grid-column: 1 / 3;
}
```

This item starts at grid line 1 and ends at grid line 3.

### 16.4 Grid Row

The `grid-row` property specifies the rows an item occupies.

```css
.item {
    grid-row: 1 / 3;
}
```

### 16.5 Grid Area

The `grid-area` property can specify row and column start and end positions.

```css
.item {
    grid-area: 1 / 1 / 3 / 3;
}
```

The values represent:
`row-start / column-start / row-end / column-end`.

### Complete Grid Example

```html
<div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
</div>
```

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

.container div {
    background-color: lightblue;
    padding: 20px;
    text-align: center;
}
```

The `gap` property adds space between grid rows and columns.

---

## 17. Transitions

CSS transitions allow property values to change smoothly over a specified duration.

### Transition Properties

* `transition-property` — specifies which CSS property should transition.
* `transition-duration` — specifies how long the transition takes.
* `transition-timing-function` — controls the speed curve.
* `transition-delay` — specifies how long to wait before the transition starts.

### Timing Function Values

* `ease` — starts slowly, speeds up, then slows down.
* `linear` — maintains a constant speed.
* `ease-in` — starts slowly.
* `ease-out` — ends slowly.
* `ease-in-out` — starts and ends slowly.

### Example

```css
.box {
    width: 100px;
    height: 100px;
    background-color: red;
    transition: width 2s linear 1s;
}

.box:hover {
    width: 200px;
}
```

In this example, the width changes smoothly when the mouse pointer moves over the box.

---

## 18. 2D and 3D Transforms

The CSS `transform` property changes the position, size, rotation, or shape of an element.

### 2D Transform Functions

Common 2D transform functions include:

* `translate()`
* `rotate()`
* `scale()`
* `scaleX()`
* `scaleY()`
* `skew()`
* `skewX()`
* `skewY()`
* `matrix()`

### 18.1 Translate

Moves an element from its current position.

```css
.box {
    transform: translate(50px, 20px);
}
```

### 18.2 Rotate

Rotates an element by a specified angle.

```css
.box {
    transform: rotate(45deg);
}
```

A negative angle rotates in the opposite direction.

### 18.3 Scale

Increases or decreases the size of an element.

```css
.box {
    transform: scale(1.5);
}
```

### 18.4 Scale X

Changes the width along the X-axis.

```css
.box {
    transform: scaleX(1.5);
}
```

### 18.5 Scale Y

Changes the height along the Y-axis.

```css
.box {
    transform: scaleY(1.5);
}
```

### 18.6 Skew

Skews an element along the X-axis and Y-axis.

```css
.box {
    transform: skew(20deg, 10deg);
}
```

### 18.7 Skew X

```css
.box {
    transform: skewX(20deg);
}
```

### 18.8 Skew Y

```css
.box {
    transform: skewY(20deg);
}
```

### 18.9 Matrix

The `matrix()` function combines 2D transformation values.

```css
.box {
    transform: matrix(1, -0.3, 0, 1, 0, 0);
}
```

It accepts six values representing scaling, skewing, and translation in a 2D transformation matrix.

### 3D Transform Functions

Common 3D transform functions include:

* `rotateX()`
* `rotateY()`
* `rotateZ()`

Examples:

```css
.box1 {
    transform: rotateX(45deg);
}

.box2 {
    transform: rotateY(45deg);
}

.box3 {
    transform: rotateZ(45deg);
}
```

* `rotateX()` rotates an element around the X-axis.
* `rotateY()` rotates an element around the Y-axis.
* `rotateZ()` rotates an element around the Z-axis.

---

## 19. Animations

CSS animations allow HTML elements to change from one style to another without requiring JavaScript.

Animations use `@keyframes` to define the styles at different points in an animation.

### Keyframes

```css
@keyframes example {
    from {
        background-color: red;
    }

    to {
        background-color: yellow;
    }
}
```

### Applying an Animation

```css
.box {
    width: 100px;
    height: 100px;
    background-color: red;
    animation-name: example;
    animation-duration: 4s;
}
```

### Animation Properties

#### 19.1 Animation Name

Specifies the name of the animation defined using `@keyframes`.

```css
animation-name: example;
```

#### 19.2 Animation Duration

Specifies how long one animation cycle takes.

```css
animation-duration: 4s;
```

If the duration is `0s`, no visible animation occurs.

#### 19.3 Animation Delay

Specifies the delay before the animation starts.

```css
animation-delay: 2s;
```

#### 19.4 Animation Iteration Count

Specifies how many times the animation runs.

```css
animation-iteration-count: 3;
```

To repeat continuously:

```css
animation-iteration-count: infinite;
```

#### 19.5 Animation Direction

Specifies the direction in which the animation plays.

Values:

* `normal` — plays forward.
* `reverse` — plays backward.
* `alternate` — alternates between forward and backward.
* `alternate-reverse` — starts backward and then alternates.

```css
animation-direction: alternate;
```

#### 19.6 Animation Timing Function

Controls the speed curve of the animation.

```css
animation-timing-function: ease-in-out;
```

### Complete Animation Example

```html
<div class="box"></div>
```

```css
@keyframes example {
    from {
        background-color: red;
    }

    to {
        background-color: yellow;
    }
}

.box {
    width: 100px;
    height: 100px;
    background-color: red;
    animation-name: example;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
}
```

---

## 20. Media Queries

Media queries are a CSS technique used to apply styles based on conditions such as viewport width.

They are useful for making web pages responsive across different screen sizes.

### Syntax

```css
@media media-type and (condition) {
    /* CSS rules */
}
```

### Example: Maximum Width

If the browser viewport is 600px or smaller, the background color becomes light blue.

```css
@media only screen and (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```

### Example: Responsive Layout

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

@media only screen and (max-width: 600px) {
    .container {
        grid-template-columns: 1fr;
    }
}
```

In this example:

* Larger screens display three columns.
* Screens with a viewport width of 600px or smaller display one column.

---

## Conclusion

CSS is used to style HTML elements and create web page layouts.

Important CSS topics include:

* CSS syntax and selectors
* Text and font properties
* Backgrounds and dimensions
* Box model
* Position and display
* Flexbox and Grid
* Transitions and transforms
* Animations
* Media queries for responsive design
