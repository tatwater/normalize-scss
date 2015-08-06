# _normalize.scss v1

Normalize.scss is a Sass partial based on [Normalize.css](github.com/necolas/normalize.css), a customizable CSS file that makes browsers render all elements more consistently and in line with modern standards.

This Sass partial assumes the use of [Autoprefixer](github.com/postcss/autoprefixer) to handle browser prefixes.

## Usage

Simply include `_normalize.scss` early in your project's main Sass document, and you're good to go!

## Modifications

- All elements and pseudo-elements have been given `box-sizing: border-box`, a more natural box layout model
- All browser prefixes have been removed in favor of using Autoprefixer
