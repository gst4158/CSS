# SCSS Dynamic Font Families

Uses a SCSS array to create a list of global class names and a dynamic mixin.

The mixin takes a string and checks if it is in font-family array. If it finds the value, then pull the CSS attributes associated with that family. If it does not find it; then just use whatever the user has input.

For the default class names the font-list array list looped through and creates a style for each item.
