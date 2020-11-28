# vi • son/rouge
### Stylesheet library for [vi • son/mixing senses](https://mixing-senses.art) related projects

Typically use this as a submodule and import needed `*.sass` files into your root stylesheet or into your components.

#### Base style + ITCSS structure
Define a `$font-root` variable that points to the root fonts directory.

```sass
$font-root: "../../assets/fonts"

/* 1. Settings - variables, config-switches
@import ./rouge/1-settings/_colors.sass
@import ./rouge/1-settings/_fonts.sass
@import ./rouge/1-settings/_variables.sass
@import ./rouge/1-settings/_breakpoints.sass
@import ./rouge/1-settings/_typograhpy.sass

/*** 2. Tools - mixins and functions
@import ./rouge/2-tools/_responsive-font-size.sass
@import ./rouge/2-tools/_media-queries.sass

/* 3. Generic - ground-zero styling (normalize, reset)
@import ./rouge/3-generic/_reset.sass

/* 4. Base - unclassed HTML element styles
@import ./rouge/4-base/_button.sass
@import ./rouge/4-base/_document.sass
@import ./rouge/4-base/_headings.sass
@import ./rouge/4-base/_images.sass
@import ./rouge/4-base/_input.range.sass
@import ./rouge/4-base/_input.text.sass
@import ./rouge/4-base/_input.text.sass
@import ./rouge/4-base/_links.sass
@import ./rouge/4-base/_text.sass

/* 5. Objects - cosmetic-free design patterns
@import ./rouge/5-objects/_button.send.sass
@import ./rouge/5-objects/_btn.sass
@import ./rouge/5-objects/_emoji.sass
```
