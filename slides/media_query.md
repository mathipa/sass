
## Media Queries

 <img src="https://raw.githubusercontent.com/mathipa/sass/master/img/grids.png" alt="grids.png">

```
  @media all and (min-width: 480px) and (max-width: 959px) {
    #content {
      @include zen-grid-item(6, 1);
    }
    .region-sidebar-first {
      @include zen-grid-item(1, 1);
    }
  }
  @media all and (min-width: 960px) {
    #content {
      @include zen-grid-item(3, 1);
    }
    .region-sidebar-first {
      @include zen-grid-item(1, 5);
    }
  }
```
