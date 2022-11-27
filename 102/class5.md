# Design web pages with CSS
* What is CSS styles website (Cascading styles Sheets)
* user agent refers to the browser
* every browser has a default setting to make the website look stylish 
* Browser does not change but use a reset to update the browser and fix browsers inconsistencies
* CSS is a rule-based language
* The code needs to be turned on to be output to the screen
* you can use browser requirements to check compatibility and support for various browsers
- Selector is the way you can grab the HTML element you want to style
- property is the thing about the HTM element you want to change
- value is the property you want to change
- { <- curly brace
- ; after each style
* 3 ways of inserting style sheets
- When styling you can only have 1 id with a name
    - External CSS
    - Internal CSS
    - Inline CSS
## External CSS
- Change the look of the entire webpage
- HTML must include a reference to the style sheet.
- External styles are defined within the `<link>` element, inside the `<head>` of an HTML page.
- must be saved with `.css extension`
- example `body {`
   - `background-color: lightblue;`
  - `}`
## Internal CSS
- Internal style sheet may be used if one single HTML page has a unique style.
- It is defined inside `<style>` element, inside the `<head>` section of HTML
Example - `<style>`
-`body {`
- `background-color: linen;`
- `}`

- `h1 {`
- `color: maroon;`
-  `margin-left: 40px;`
- `}`
</style>`
## Inline CSS
- You can use the inline style for a single element
-example `<h1 style="color:blue;text-align:center;">This is a heading</h1>`

## Multiple Style Sheets
- if the same element is a different style sheet, the value of the last read style sheet is used

## Cascading order
- Style sheets have rules  where the number one has the highest priority
- Inline style
- External and internal style sheets
- Browser default

    - Inline style has the highest priority and will override external, internal styles, and browser defaults.

    - [Css-tricks](https://css-tricks.com/almanac/) is where you can find more tricks for CSS