# iresults/styles-nav

Sass library with navigation mixins

## Installation

### composer

```json
{
    "require": {
        "iresults/styles-nav": "*"
    }
}
```

## Usage

### Examples

```scss
@use "iresults/styles-nav/scroll-hide" as scroll-hide;

header#page-header {
    @include scroll-hide.enable($hidden-top: 120px);
}
```
