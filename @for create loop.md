#### @for create loop

> The @for directive adds styles in a loop, very similar to a for loop in JavaScript.
> 
> @for is used in two ways: "start through end" or "start to end". The main difference is that "start to end" excludes the end number, and "start through end" includes the end number.
> 

* exmple
```sass
@for $i from 1 through 12 {
  .col-#{$i} { width: 100%/12 * $i; }
}
```

that code will create the next code


```sass
.col-1 {
  width: 8.33333%;
}

.col-2 {
  width: 16.66667%;
}

...

.col-12 {
  width: 100%;
}
```````
[For example sass codecamp](:note:f243d191-4c08-4656-8d79-dc6dbd1ca819)
