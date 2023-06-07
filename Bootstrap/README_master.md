- what is Bootstrap
  - CSS, HTML and JS
- how to add

# [Colors](https://getbootstrap.com/docs/5.3/customize/color/)

- [theme colors](https://getbootstrap.com/docs/5.3/customize/color/#theme-colors)
- [enable dark mode](https://getbootstrap.com/docs/5.3/customize/color-modes/#enable-dark-mode)
  - data-bs-theme="dark"
- bg-\*
- text-\*
- text-bg-\*
- border-\*

# [typography](https://getbootstrap.com/docs/5.3/content/typography/)

- h1...h6
  - tags
  - class
- text-body-\*
- display-1...display-6
- lead
- inline
  - mark,s,u
  - .mark, .small, .text-decoration-\*
- alignment
  - text-center, text-left,..
  - text-{breakpoint}-\*
- list
  - unstyled
  - inline
- wrapping
  - text-wrap
  - text-nowrap
  - word-break
- transform
  - capitalize
  - uppercase
  - lowercase
- font-size
- font-style
- font-weight
- line-height
- font-monospace

# [Sizing](https://getbootstrap.com/docs/5.3/utilities/sizing/)

- relative to parent
  - 25%, 50%, 75%, 100%, auto
  - h-\*
  - w-\*
  - mw-\* (max-width)
  - mh-\* (max-height)
- relative to view port
  - min-vw-100
  - min-vh-100
  - vw-100
  - vh-100

# [Spacing](https://getbootstrap.com/docs/5.3/utilities/spacing/)

- {property}-{sides}-{breakpoint}-{size}
- property
  - m: margin
  - p:padding
- sides
  - t: top
  - b: bottom
  - s: start/right
  - e: end/left
  - x: inline
  - y: block
- breakpoint
  - sm...xxl
- size
  - 0: none
  - 1...5
  - auto :set margin to `auto`

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

## [Breakpoints](https://getbootstrap.com/docs/5.3/layout/breakpoints/)

- mobile first
- 6 default breakpoints
- min-width

## [Containers](https://getbootstrap.com/docs/5.3/layout/containers/)

- .container -> set `max-width`
- .container-{breakpoint} -> width:100% till breakpoint
- .container-fluid -> fluid width:100% @ all breakpoints, no jump

# [Grid](https://getbootstrap.com/docs/5.3/layout/grid/)

- 12 template columns
- col "equal width"
- col-{breakpoint}-{span}
- row-cols-\*
- gutters
  - g-\*
  - gy-\*
  - gx-\*
  - g-0

## Components

### [Accordion](https://getbootstrap.com/docs/5.3/components/accordion/)

- control's `.collapse`
- for border-less add `.accordion-flush`
- always open omit `.data-bs-parent` on each `.accordion-collapse`
- set `aria-expanded`
- if controls a single item add `aria-controls` and it will provide navigation shortcuts

### [Cards](https://getbootstrap.com/docs/5.3/components/card/)

- card
- card-body
  - card-title
  - card-subtitle
  - card-text
  - card-link
- card-footer
- card-img-top/bottom
- use sizing utility

### [Carousel](https://getbootstrap.com/docs/5.3/components/carousel/)

[example](https://codepen.io/ShihabSuS/pen/abRXdBz)

- basic
  - first item to have `.active`
- indicators
- captions
- cross-fade `.carousel-fade`
- auto-play `data-bs-ride="carousel"`
