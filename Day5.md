## CSS Notes from Day 5

CSS stands for Cascading Style Sheets

It's a language for specifying how documents are presented to users.

### CSS Syntax
CSS is a rule based language - you define rules specifying groups of styles that should be applied to particular elements on your web page.

The rule opens with a selector. This selects the HTML element that we are going to style.

The language is broken down into modules. For instance background-color and border-color properties are defined in the Backgrounds and Borders module.

CSS is developed by a group within W3C called the CSS Working Group.

## Three ways to insert CSS

* External CSS
* Internal CSS
* Inline CSS

With an external style sheet, you can change the look of an entire website by changing just one file

An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the style element, inside the head section.

An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

### Cascading Order

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

### Reset CSS

The Goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on.

