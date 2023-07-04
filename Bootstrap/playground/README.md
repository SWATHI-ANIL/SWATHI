# Basics
basic

## Bootstrap 5 changes

- dropped jQuery
- removed few components like jumbotron
- new utility classes
- Bootstrap icons

## Add dependencies

- css to head
- js min bundle to end of body

# [typography](https://getbootstrap.com/docs/5.3/content/typography/)

- h1...h6
  - tags
  - class
- display-1...display-6
- lead
- mark,s,u
- description list

# [Colors](https://getbootstrap.com/docs/5.3/customize/color/)

- [theme colors](https://getbootstrap.com/docs/5.3/customize/color/#theme-colors)
- [enable dark mode](https://getbootstrap.com/docs/5.3/customize/color-modes/#enable-dark-mode)
  - data-bs-theme="dark"
- text-\*
- bg-\*
- border-\*

# Layout

## [Breakpoints](https://getbootstrap.com/docs/5.3/layout/breakpoints/)

- mobile first
- 6 default breakpoints
- min-width

## [Containers](https://getbootstrap.com/docs/5.3/layout/containers/)

- .container -> set `max-width`
- .container-{breakpoint} -> width:100% till breakpoint
- .container -> fluid width:100% @ all breakpoints

## [Grid](https://getbootstrap.com/docs/5.3/layout/grid/)

- 12 column layout
- it should be inside a container
- if more than 12. wrap to next line
- show responsiveness
- show overflow
- alignment (add in row)
- gutter for padding b/w rows and cols

## [Columns](https://getbootstrap.com/docs/5.3/layout/columns/)

- alignment
  - justify-content
  - align-items
  - align-self
- order
  - higher order items are placed after lower ordered ones
- offset-\*
  - offset by \* column(s)

# [Components](https://getbootstrap.com/docs/5.3/customize/components/)

- base class modifier approach

  - .btn includes major styles
  - .btn-primary or .btn-success modifiers has the variant style
  - .btn-close

## [Button](https://getbootstrap.com/docs/5.3/components/buttons/)

- base class
- variants
  - primary, secondary, danger, success, link, dark
- types
  - close
- sizes
  - lg,md,sm
- disabled
- full block
- toggle (data-bs-toggle)

## [Nav](https://getbootstrap.com/docs/5.3/components/navbar/)

## [Tabs](https://getbootstrap.com/docs/5.3/components/navs-tabs/#tabs)

## [Accordion](https://getbootstrap.com/docs/5.3/components/accordion/)

## [List Group](https://getbootstrap.com/docs/5.3/components/list-group/)

## [Icons](https://icons.getbootstrap.com/)

## [Forms](https://getbootstrap.com/docs/5.3/forms/overview/)

## [Tooltips](https://getbootstrap.com/docs/5.3/components/tooltips/)

## [Modal](https://getbootstrap.com/docs/5.3/components/modal/)

## [Off-canvas](https://getbootstrap.com/docs/5.3/components/offcanvas/)
