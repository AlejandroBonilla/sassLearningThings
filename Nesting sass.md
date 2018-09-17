### Nesting sass

Sass allows nesting of CSS rules, which is a useful way of organizing a style sheet.

##### example normal css

```css
nav {
  background-color: red;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline-block;
}
```

##### But in sass we can do that

```sass
nav {
  background-color: red;

  ul {
    list-style: none;

    li {
      display: inline-block;
    }
  }
}
```

much more readeable !!!



