# CSS Parent and Child Boxes

## Description

This project demonstrates how to create and style **parent and child boxes using HTML and CSS**.

It covers the **CSS box model, margins, borders, colors, multiple classes, and CSS positioning**.

## Concepts Used

### 1. Universal Selector

The universal selector `*` selects all HTML elements.

```css
* {
    box-sizing: border-box;
}
```

`box-sizing: border-box` makes the specified `width` and `height` include the **content, padding, and border**.

---

### 2. Parent Box

The `.parentbox` class creates the parent container.

```css
.parentbox {
    border: 4px solid black;
    width: 400px;
    height: 500px;
    margin: 220px;
}
```

It demonstrates:

* Border
* Width
* Height
* Margin

---

### 3. Child Boxes

The `.childbox` class provides common styling for the child elements.

```css
.childbox {
    border: 4px solid black;
    width: 70px;
    height: 40px;
    margin: 20px;
}
```

Each child box can also have another class for its individual styling.

---

### 4. Multiple Classes

An HTML element can have multiple classes separated by a space.

```html
<div class="childbox colr1">childbox1</div>
<div class="childbox colr2">childbox2</div>
<div class="childbox colr3">childbox3</div>
```

Here:

* `childbox` → provides the common box styling.
* `colr1`, `colr2`, `colr3` → provide individual styles.
* `childbox1`, `childbox2`, `childbox3` → are the text inside the elements.

---

### 5. Background Colors

This project uses three different CSS color formats.

#### Named Color

```css
.colr1 {
    background-color: blanchedalmond;
}
```

#### RGB Color

```css
.colr2 {
    background-color: rgb(67, 140, 101);
}
```

#### Hexadecimal Color

```css
.colr3 {
    background-color: #e48d09;
}
```

---

### 6. CSS Positioning

This project also demonstrates CSS positioning using:

```css
position: fixed;
```

#### Fixed Position

`position: fixed` removes the element from the normal document flow and positions it relative to the **viewport**.

```css
.colr3 {
    position: fixed;
    top: 190px;
}
```

The `top: 190px` places the element **190px from the top of the viewport**.

The element stays fixed in that position even when the page is scrolled.

---

### 7. Margin

Margin creates space **outside the border** of an element.

For example:

```css
margin: 20px;
```

This applies `20px` of margin to all four sides.

The parent box uses:

```css
margin: 220px;
```

which applies `220px` of margin to all four sides.

---

### 8. Border

The `border` property adds a border around an element.

```css
border: 4px solid black;
```

This means:

* `4px` → border width
* `solid` → border style
* `black` → border color

---

### 9. Box-sizing

The default `box-sizing` value is `content-box`.

This project uses:

```css
* {
    box-sizing: border-box;
}
```

With `border-box`, the specified `width` and `height` include the **content, padding, and border**.

Margin is not included.

---

## Learning Objective

The purpose of this project is to understand how **parent and child elements** are created and styled using CSS.

It also provides practice with:

* CSS box model
* Width and height
* Margin
* Border
* Background colors
* Multiple classes
* Universal selector
* `box-sizing`
* Fixed positioning

## Technologies Used

* HTML
* CSS

## Key Takeaways

Through this project, I learned how to:

* Create parent and child boxes.
* Use CSS classes.
* Apply multiple classes to one element.
* Use borders, width, height, and margins.
* Apply different color formats.
* Use the universal selector.
* Use `box-sizing: border-box`.
* Use `position: fixed`.
* Position an element using `top`.
* Understand the basic CSS box model.
