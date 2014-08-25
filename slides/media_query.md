
# Media Queries

Sass handles <u>media queries</u> in a better and more advanced ways than others.

```
  @media all and (min-width: 480px) and (max-width: 959px) {
      #content {
        width: 80%;
      }
      .region-sidebar-first {
        width: 25%;
      }
  }

  @media all and (min-width: 960px) {
    #content {
      width: 70%;
    }
    .region-sidebar-first {
      width: 30%;
    }
  }
```
