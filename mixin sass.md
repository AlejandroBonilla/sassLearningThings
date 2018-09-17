## mixin sass

In Sass, a mixin is a group of CSS declarations that can be reused throughout the style sheet.

how to declare mixin :

```sass
@mixin box-shadow($x, $y, $blur, $c){
  -webkit-box-shadow: $x, $y, $blur, $c;
  -moz-box-shadow: $x, $y, $blur, $c;
  -ms-box-shadow: $x, $y, $blur, $c;
  box-shadow: $x, $y, $blur, $c;
}
```
how to call mixin 

```sass
div {
  @include box-shadow(0px, 0px, 4px, #fff);
}
```````

[mixin sass example](:note:9e2e6242-799d-42d4-9620-00b839f0d1bd)