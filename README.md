# Skeleton.scss

Skeleton.scss is a modified, unofficial SASS port of the Skeleton CSS framework authored by Dave Gamache.


## Version

2.0.4


## Installation

To install Skeleton.scss via Bower:

```sh
$ bower install skeleton.scss
```


## Mixin(s?)

Currently, Skeleton.scss uses a single mixin for including targeted media queries inside of declaration blocks. More mixins may come later, though the point of this framework is to leverage SASS while keeping a minimal footprint that does not fundamentally alter the bare bones approach of the vanilla Skeleton framework.

### `respond-to($breakpoint)`
 The `respond-to` mixin takes a single argument, `$breakpoint`, which it uses as a key to query the `$breakpoints` map for a matching value. To tailor a specific ruleset, simply include the mixin with your desired breakpoint and responsive declarations.

    .container {
      ...
      @include respond-to('bp-extra-small') {
        width: $container-width-larger-than-bp-extra-small;
        padding: 0;
      }
    }


## Browser support

- Chrome latest
- Firefox latest
- Opera latest
- Safari latest
- IE latest

The above list is non-exhaustive. Skeleton works perfectly with almost all older versions of the browsers above, though IE certainly has large degradation prior to IE9.


## License

All parts of Skeleton are free to use and abuse under the [open-source MIT license](https://github.com/bradcliffe/skeleton.scss/blob/master/LICENSE.md).


## Colophon

Skeleton was built using [Sublime Text 3](http://www.sublimetext.com/3) and designed with [Sketch](http://bohemiancoding.com/sketch). The typeface [Raleway](http://www.google.com/fonts/specimen/Raleway) was created by [Matt McInerney](http://matt.cc/) and [Pablo Impallari](http://www.impallari.com/). Code highlighting by Google's [Prettify library](https://code.google.com/p/google-code-prettify/). Icons in the header of the documentation are all derivative work of icons from [The Noun Project](http://thenounproject.com). [Feather](http://thenounproject.com/term/feather/22073) by Zach VanDeHey, [Pen](http://thenounproject.com/term/pen/21163) (with cap) by Ed Harrison, [Pen](http://thenounproject.com/term/pen/32847) (with clicker) by Matthew Hall, and [Watch](http://thenounproject.com/term/watch/48015) by Julien Deveaux.


## Acknowledgement

Skeleton was created by [Dave Gamache](https://twitter.com/dhg) for a better web.
