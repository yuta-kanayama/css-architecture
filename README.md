# CSS設計2015のサンプルファイル


## BEM + Sass( Mixin )

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

