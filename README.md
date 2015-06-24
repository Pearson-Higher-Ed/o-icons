# o-icons [![Build Status](https://travis-ci.org/Pearson-Higher-Ed/o-icons.svg)](https://travis-ci.org/Pearson-Higher-Ed/o-icons)

## Quick start

```
<!-- Load web fonts with @font-face declarations  -->
<link rel="stylesheet" href="//build.origami.ft.com/bundles/css?modules=o-icons@^1" />

<!-- Use icons by selecting the appropriate class -->
<div>
  <i class="oc-icon-check"></i>
</div>

```

## Advanced usage

### Loading icon fonts

Turn off silent mode or use the `oIconsIncludeAll` mixin to include `@font-face` declarations and icon classes for all available icons:

```scss
// Turn off silent mode...
$o-icons-is-silent: false;
@import 'o-icons/main';

// ...or use the mixin
@include oIconsIncludeAll();
```

To include specific `@font-face` declarations, use the `oIconsInclude` mixin:

```scss
@include oIconsInclude(oc-icons);
```

## Browser support

Tested and working on:

|  Browser   | Versions                  |
|:----------:|:-------------------------:|
|   Chrome   |   36+                     |
|   Firefox  |   30+                     |
|   Safari   |   7+                      |
|   IE       |   9+                      |

## License

This software is published by Pearson Education under the [MIT license](LICENSE).
