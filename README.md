# CSS設計 Sample

[demo site](http://css-architecture.yuta-k.net/)


## BEM + Sass( Mixin )

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
