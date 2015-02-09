# CSS設計 Sample

Sass + Compass + SMACSS + BEM.


[demo site](http://css-architecture.yuta-k.net/)



## Categories

* Base
* Layout
* Module
* State
* Theme
* Tool
* Utility



## BEM + Sass ( Mixin )

```
//Element
@mixin e($name) {
  @at-root &__#{$name} {
    @content;
  }
}

//Modifier
@mixin m($name) {
  @at-root &--#{$name} {
    @content;
  }
}
```
