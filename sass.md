# SaSS

## Variables

### Global variables

Format `${property}-{variant}`.

```scss
$color-white: #ffffff;
$font-family-sans: Lato, sans-serif;
$border-width-thin: 1px;

$space-s: 5px;
$space-m: 10px;
$space-l: 20px;
$space-xl: 35px;
$space-xxl: 50px;
```

### Component variables

Format `${component}-{variant?}-{state?}-{property}`. Sizes and colors must fall into a global variable.

```scss
$button-border-width: $border-thin;
$button-small-padding: $space-s;
$button-primary-background: $color-gray-20;
$button-primary-hover-background: $color-gray-10;
```
