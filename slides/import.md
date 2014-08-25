
# @import

Sass also has the ability to import other Sass files, so lets say you wanted to import a file
(in the same as this sass file)

```
  @import "variables";
  @import "menus";
  @import "footer";

  body {
    font-size: $font;
    background-color: $my_background;
  }
```
