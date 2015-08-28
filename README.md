# less-color-helper
Simple LESS mixin for creating CSS color and background-color classes.

Usage:

    .color-helper(white, white);

    .color-helper(black, #000);

    @myColor: #123456;
    .color-helper(my-color, @myColor);

CSS Output:

    .white-color {
      color: #fff !important
    }

    .white-background {
      background-color: #fff !important
    }

    .black-color {
      color: #000 !important
    }

    .black-background {
      background-color: #000 !important
    }

    .my-color-color {
      color: #123456 !important
    }

    .my-color-background {
      background-color: #123456 !important
    }