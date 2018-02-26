# Mini boilerplate 2018
This boilerplate is intended to be used in a "mobile-first" context, where the
mobile version is also shown to browsers that don't support CSS GRID and CSS VARIABLES.

The idea is to have a robust mobile version that can work everywhere, 
but nothing prevents you from enhancing it with modern features through @supports.

A predefined @supports query string is available in _variables.scss ($supports-string).
```css
@supports (#{$supports-string}) {
    display: grid;
}
```