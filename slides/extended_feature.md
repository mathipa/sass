
# @extend feature

Sass provides the @extend feature allowing you to extend a class from another one.

```
  .module-a {
    color: #ffffff;
    font-size: 12px;
  }
  .module-b {
     @extend .module-a;
  }

```
