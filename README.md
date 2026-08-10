# Syntaxwear Ecommerce Landing Page

## Overview

`ecommerce-syntaxwear` is a static ecommerce landing page built with semantic HTML and modular CSS. The site is designed for a shoe and sneaker brand and includes a fixed header, hero section, product categories, featured product grid, and footer.

## Features

- Responsive header with brand logo, main navigation, and secondary navigation links
- Full-width hero section with CTA buttons
- Category cards for sneaker styles
- Responsive featured products grid
- Footer with newsletter signup, social links, and navigation columns

## Project structure

```
index.html
README.md
assets/
  css/
    reset.css
    variables.css
    base.css
    layout.css
    components/
      header.css
      hero.css
      product-category.css
      product-grid.css
      footer.css
  images/
    banners/
    favicons/
    icons/
    logo/
    produtos/
```

## HTML

- `index.html` contains the full page structure
- Uses semantic elements such as `header`, `main`, `section`, `nav`, `footer`, `form`, and `ul`
- Includes a fixed navigation bar and a responsive mobile menu toggle

## CSS

### Global styles
- `reset.css` resets browser defaults using a modern reset approach
- `variables.css` defines theme colors and font settings
- `base.css` contains typography, buttons, and global layout rules
- `layout.css` is available for shared layout utilities (currently empty)

### Component styles
- `assets/css/components/header.css` styles the site header and navigation
- `assets/css/components/hero.css` styles the hero section background and content
- `assets/css/components/product-category.css` styles category cards and image backgrounds
- `assets/css/components/product-grid.css` styles the featured products grid
- `assets/css/components/footer.css` styles the footer layout, newsletter, links, and social icons

## Images

The site uses image assets from the following folders:

- `assets/images/banners/` — hero or banner assets
- `assets/images/favicons/` — site icons
- `assets/images/icons/` — UI icons for navigation and social links
- `assets/images/logo/` — brand logo files
- `assets/images/produtos/` — category and product imagery

## How to use

1. Open `index.html` in a browser.
2. Ensure the relative CSS and image paths are preserved when moving files.
3. Edit text, links, or images directly in `index.html` and the CSS files.

## Notes

- The site is static and requires no build tools.
- `layout.css` is currently empty and can be used for shared layout rules in the future.
- The navigation menu includes a mobile-friendly checkbox toggle controlled by `header.css`.


