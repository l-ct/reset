# CSS Reset

Written in [Stylus](http://stylus-lang.com/).

    $ npm i -g stylus
    $ stylus path/to/reset.styl path/to/css/dir

Use of `*` not great for performance. Uses `:focus {outline: 0;}` which is terrible for accesibility. Still, it's my baseline for projects.