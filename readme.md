# Intro to CSS

## Contentπ£

- Box model
- CSS Layout
  - Float
  - Flexbox
- CSS Selector
- Understanding the cascade
## CSS Box Model β¬

- Every HTML element has a box around it π³
- π[jsfiddle - box model](https://jsfiddle.net/dtremblay/nmLzpeo7/125/)
- π[Interactive box-model demo](http://guyroutledge.github.io/box-model/)
- Box-sizing property

## Layout with Floatsπ

- Float is a CSS positioning property
- Initially used to wrap text around images
- Floats was being used for web layouts
- Element can be floated left or right
- Since the flow is changed, elements are not part of the normal flow
- The parent element contained floated elements can collapsed

- π[Floats - jsFiddle](https://jsfiddle.net/dtremblay/493tjkaz/412/)

## Flexbox π

- A better way to layout elements

> The Flexbox Layout (Flexible Box) provides a more efficient way to lay out, align and distribute **space** among **items** in a **container**, even when their size is unknown and/or dynamic.

- A flex container expands items to fill available free space or shrinks them to prevent overflow.

- When working with flexbox you need to think in terms of two axes β the **main axis** and the **cross axis**. The main axis is defined by the `flex-direction` property, and the cross axis runs perpendicular to it.

- π[Flexbox Layout Demo](https://jsfiddle.net/dtremblay/m70x3h6p/337/)
- π[Flexbox Breakout Exercise](https://gist.github.com/DominicTremblay/83357ef5d5d006a87a5774893bb9addd)
- π[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## CSS Selector

### Types of Selectors

- Basic Selector
- Class Selector
- ID Selector
- Attribute Selector
- Descendant Selector
- Sibling Selector

- π[Selectors](https://jsfiddle.net/dtremblay/e3v095ws/149/)

## Understanding The Cascasde π¦

When 2 or more conflicting style rules target the same element, the browser has to decide which CSS styles to apply, iow which style will win! π₯

### The Cascade (Simplified)

To determine the winning style, the browser will go through a cascade.

- 1οΈβ£ Selector Specificity - The more specific selector wins
- 2οΈβ£ Source Order - if the same specificity, the source order will matter

#### CSS Specificity

πSpecificity Rules

- The more specific selector gets applied
- A score is attributed to a selector

  - nb ids x 100 pts
  - nb classes x 10 pts
  - nb of elements x 1pt

* inline-style => 1000 pts

![specificity](./specificity1.png)

- π[Selectors Specifity](https://jsfiddle.net/dtremblay/xr94uLnb/127/)

#### Source Order π’

- The last style overwrites any preceding conflicting rule that has the same specificity.
- It also depends on how the style was added

3 ways to add styles

- 1οΈβ£Inline
- 2οΈβ£Internal
- 3οΈβ£External

## CSS Games

- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Flexbox Defense](http://www.flexboxdefense.com/)
- [Flexbox Zombies](https://geddski.teachable.com/p/flexbox-zombies)
- [CSS Diner](https://flukeout.github.io/)
- [Specifishity](https://specifishity.com/)