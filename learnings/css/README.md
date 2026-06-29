# CSS Learnings — Day 4

## What CSS does
HTML gives a webpage its structure — the headings, paragraphs, tables, forms, etc. CSS controls how that structure actually looks — colors, spacing, fonts, layout.

## Where CSS should go (the painter analogy)
We learned three ways to add CSS: inline (on the tag itself), internal (a `<style>` block in the HTML file), and external (a separate `.css` file linked via `<link>`).

External CSS is the one to actually use. The painter analogy explains why: if a painter colors a house *while* it's being built, you only ever see the finished house. But if the painter shows up *after* the house is built, you first see a plain grey house, then watch it get painted. CSS works the same way — if it's linked in the `<head>`, the browser loads the style before showing the page, so there's no flash of unstyled content. That's why the `<link>` tag goes in `<head>`, and why external CSS (kept separate from the HTML) is the standard, proper way to do it in real projects.

## Selectors
Selectors are how CSS finds which elements to style:
- **Element selectors** target every tag of that type, e.g. `h1 { }` styles all `<h1>` tags.
- **Class selectors** target specific elements you've tagged with a class, e.g. `.card { }` styles only elements with `class="card"`.
- **ID selectors** target one specific unique element, e.g. `#header { }`.

## Inspecting CSS with DevTools
Using Chrome DevTools (right-click → Inspect), I could open the **Elements** tab to see the actual HTML structure, and the **Styles** panel to see which CSS rules are applying to a selected element — and even edit them live in the browser to test changes before putting them in the real file.

## File paths
CSS files need the correct path to load properly — using `./` or just the filename (like `style.css`) when the CSS file sits in the same folder as the HTML file.

## CodePen Examples

- [CSS Selectors Demo](https://codepen.io/editor/TANUSHREENEGI-DEV/pen/019f135a-ea09-7303-b153-c0d1190fc0cd)