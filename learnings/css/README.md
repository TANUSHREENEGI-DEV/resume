# 🌸 CSS Learnings – Day 4

## Introduction

Today I learned the basics of CSS (Cascading Style Sheets). HTML is used to create the structure of a webpage, while CSS is used to make it look attractive. CSS helps us add colors, fonts, spacing, borders, backgrounds, and proper layouts. Without CSS, webpages would only display plain HTML elements.

I also understood that HTML and CSS work together. HTML tells the browser what content to display, and CSS controls how that content looks on the screen.

---

# Understanding CSS Syntax

A CSS rule has three parts:

- **Selector** – chooses the HTML element.
- **Property** – defines what we want to change.
- **Value** – specifies the new style.

Example:

```css
h1{
    color: blue;
}
```

Here, `h1` is the selector, `color` is the property, and `blue` is the value.

---

# Ways to Add CSS

There are three ways to add CSS.

## 1. Inline CSS

Inline CSS is written inside an HTML tag using the `style` attribute.

```html
<h1 style="color: blue;">Welcome</h1>
```

It is useful for small changes but is not recommended because it mixes HTML and CSS.

---

## 2. Internal CSS

Internal CSS is written inside the `<style>` tag in the `<head>` section.

```html
<style>
h1{
    color: blue;
}
</style>
```

It is suitable for single-page websites but cannot be reused across multiple pages.

---

## 3. External CSS

External CSS is written in a separate `.css` file and linked using:

```html
<link rel="stylesheet" href="style.css">
```

This is the most commonly used method because it keeps the code clean and allows one CSS file to style multiple webpages.

---

# How Browsers Apply CSS

When a webpage loads, the browser first reads the HTML file and then applies the CSS styles. Linking the CSS file in the `<head>` section helps the webpage appear fully styled when it opens.

---

# CSS Selectors

Selectors tell CSS which elements should receive a style.

### Element Selector

Styles all elements of the same tag.

```css
h1{
    color:red;
}
```

### Class Selector

Starts with `.` and can be used on multiple elements.

```css
.card{
    background:white;
}
```

### ID Selector

Starts with `#` and is generally used for one unique element.

```css
#header{
    color:blue;
}
```

### Grouping Selector

Applies the same style to multiple elements.

```css
h1, h2, h3{
    color:red;
}
```

---

# Class vs ID

**Class**
- Starts with `.`
- Reusable
- Used for multiple elements

**ID**
- Starts with `#`
- Unique
- Used for one specific element

---

# CSS Box Model

Every HTML element is treated like a box with four parts:

- **Content** – the actual text or image.
- **Padding** – space inside the element.
- **Border** – surrounds the content and padding.
- **Margin** – space outside the element.

I also learned that **padding adds space inside the box**, while **margin adds space outside the box**.

---

# Browser DevTools

Using **Inspect** in the browser, I can:

- View HTML and CSS.
- Check applied styles.
- Edit CSS temporarily.
- Find mistakes easily.

This makes debugging much faster than guessing.

---

# File Paths

To connect an external CSS file, the file path must be correct.

If both files are in the same folder:

```html
<link rel="stylesheet" href="style.css">
```

The browser will load the CSS without any extra path.

---

# Practice Work

To apply these concepts, I completed the following tasks:

- Styled my Resume using External CSS.
- Created a Profile Card.
- Built a Navigation Bar.
- Designed different CSS Buttons.
- Organized my project into folders.
- Used Git commands to push everything to GitHub.
- Published my resume using GitHub Pages.

These practice projects helped me understand how CSS is used in real web development.

---

# CodePen Practice

🔗 https://codepen.io/editor/TANUSHREENEGI-DEV/pen/019f135a-ea09-7303-b153-c0d1190fc0cd# 🌸 CSS Learnings – Day 4

## Introduction

Today I learned the basics of CSS (Cascading Style Sheets). HTML is used to create the structure of a webpage, while CSS is used to make it look attractive. CSS helps us add colors, fonts, spacing, borders, backgrounds, and proper layouts. Without CSS, webpages would only display plain HTML elements.

I also understood that HTML and CSS work together. HTML tells the browser what content to display, and CSS controls how that content looks on the screen.

---

# Understanding CSS Syntax

A CSS rule has three parts:

- **Selector** – chooses the HTML element.
- **Property** – defines what we want to change.
- **Value** – specifies the new style.

Example:

```css
h1{
    color: blue;
}
```

Here, `h1` is the selector, `color` is the property, and `blue` is the value.

---

# Ways to Add CSS

There are three ways to add CSS.

## 1. Inline CSS

Inline CSS is written inside an HTML tag using the `style` attribute.

```html
<h1 style="color: blue;">Welcome</h1>
```

It is useful for small changes but is not recommended because it mixes HTML and CSS.

---

## 2. Internal CSS

Internal CSS is written inside the `<style>` tag in the `<head>` section.

```html
<style>
h1{
    color: blue;
}
</style>
```

It is suitable for single-page websites but cannot be reused across multiple pages.

---

## 3. External CSS

External CSS is written in a separate `.css` file and linked using:

```html
<link rel="stylesheet" href="style.css">
```

This is the most commonly used method because it keeps the code clean and allows one CSS file to style multiple webpages.

---

# How Browsers Apply CSS

When a webpage loads, the browser first reads the HTML file and then applies the CSS styles. Linking the CSS file in the `<head>` section helps the webpage appear fully styled when it opens.

---

# CSS Selectors

Selectors tell CSS which elements should receive a style.

### Element Selector

Styles all elements of the same tag.

```css
h1{
    color:red;
}
```

### Class Selector

Starts with `.` and can be used on multiple elements.

```css
.card{
    background:white;
}
```

### ID Selector

Starts with `#` and is generally used for one unique element.

```css
#header{
    color:blue;
}
```

### Grouping Selector

Applies the same style to multiple elements.

```css
h1, h2, h3{
    color:red;
}
```

---

# Class vs ID

**Class**
- Starts with `.`
- Reusable
- Used for multiple elements

**ID**
- Starts with `#`
- Unique
- Used for one specific element

---

# CSS Box Model

Every HTML element is treated like a box with four parts:

- **Content** – the actual text or image.
- **Padding** – space inside the element.
- **Border** – surrounds the content and padding.
- **Margin** – space outside the element.

I also learned that **padding adds space inside the box**, while **margin adds space outside the box**.

---

# Browser DevTools

Using **Inspect** in the browser, I can:

- View HTML and CSS.
- Check applied styles.
- Edit CSS temporarily.
- Find mistakes easily.

This makes debugging much faster than guessing.

---

# File Paths

To connect an external CSS file, the file path must be correct.

If both files are in the same folder:

```html
<link rel="stylesheet" href="style.css">
```

The browser will load the CSS without any extra path.

---

# Practice Work

To apply these concepts, I completed the following tasks:

- Styled my Resume using External CSS.
- Created a Profile Card.
- Built a Navigation Bar.
- Designed different CSS Buttons.
- Organized my project into folders.
- Used Git commands to push everything to GitHub.
- Published my resume using GitHub Pages.

These practice projects helped me understand how CSS is used in real web development.

---

# CodePen Practice

🔗 https://codepen.io/editor/TANUSHREENEGI-DEV/pen/019f135a-ea09-7303-b153-c0d1190fc0cd