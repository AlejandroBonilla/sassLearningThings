### if else in sass

> The @if directive in Sass is useful to test for a specific case - it works just like the if statement in JavaScript.
> 

simple example

```sass
@mixin make-bold($bool) {
  @if $bool == true {
    font-weight: bold;
  }
}
```

