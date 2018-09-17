### store data with Sass variables

One feature of Sass that's different than CSS is it uses variables. They are declared and set to store data, similar to JavaScript.

using variables 

```sass
$main-fonts: Arial, sans-serif;
$headings-color: green;

//To use variables:
h1 {
  font-family: $main-fonts;
  color: $headings-color;
}
```
##### example
* [Variables in sass example](:note:143ccc37-2e42-4cee-8c14-d501aeb88274)
