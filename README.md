# README

A Sass helper for use custom properties safely in production even for old browsers

### Description

- A `@mixin` is called from the CSS selector using a map. Each value within the mixin calls a `@function` searching for its corresponding value previously declared. The value is returned and applied to the CSS selector as a simple CSS property and also using the `var()` function

### Version

- 1.1.0

### Dependencies

- No dependencies

### How to implement

- Just include the `@mixin` and the `@function` in your Sass file
