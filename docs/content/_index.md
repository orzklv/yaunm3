+++
+++

{% crt() %}
```
                          _.-------.._                    -,
                      .-"```"--..,,_/ /`-,               -,  \ 
                   .:"          /:/  /'\  \     ,_...,  `. |  |
                  /       ,----/:/  /`\ _\~`_-"`     _;
                 '      / /`"""'\ \ \.~`_-'      ,-"'/ 
                |      | |  0    | | .-'      ,/`  /
               |    ,..\ \     ,.-"`       ,/`    /
              ;    :    `/`""\`           ,/--==,/-----,
              |    `-...|        -.___-Z:_______J...---;
              :         `                           _-'
         _____L_ _ _______. .___________. ._____--"`
        |  ___| (_)_ __  _ __   ___ _ __  |__  /___ _ __ ___
        | |_  | | | '_ \| '_ \ / _ \ '__|   / // _ \ '__/ _ \
        |  _| | | | |_) | |_) |  __/ |     / /|  __/ | | (_) |
        |_|   |_|_| .__/| .__/ \___|_|    /____\___|_|  \___/
```
{% end %}

# Yaunm3: Flipper Zero

[Yaunm3](https://github.com/orzklv/yaunm3) is name of a Flipper Zero a journey written by [Orzklv](https://orzklv.uz) while exploring the world of Flipper Zero. It is a series of articles that will be published on a regular basis. The articles will cover the following topics:

- [Introduction to Flipper Zero](#) _(Coming Soon)_

## Attention

> <img src="https://github.com/orzklv/yaunm3/blob/master/.github/assets/animation.gif?raw=true" alt="Animation">
>
> <p align="center">If you run into issues while compiling & running, please consider leaving issues on this repository. Would be glad to work on them together.</p>

## Getting started

First, clone the repo anywhere in your computer:

```sh
git clone https://github.com/orzklv/yaunm3.git
```

If you want to patch firmware, check out `firmware` directory. It's highly recommended to read the ReadMe file to get to know how to compile and flash the firmware.

## Options

Duckquill offers some configuration options to make it fit you better; most options have pretty descriptive comments, so it should be easy to understand what they do.

### Custom stylesheets

You can add your own or override existing styles by creating custom stylesheet and adding it in the `config.toml`:

```toml
[extra]
stylesheets = [
  "YOUR_STYLE.css"
]
```

Additional stylesheets; expects it to be in the `static` directory. If you are using Sass it will be compiled there anyway.

If for some reason overridden class are not respected, try using `!important`. You can import styles from Duckquill using:

```scss
@use "../themes/duckquill/sass/NEEDED_FILE.scss";
```

### Primary color

Duckquill respects chosen primary color everywhere, simply change the primary color in `config.toml`:

```toml
[extra]
primary_color = "COLOR_CODE"
primary_color_alpha = "COLOR_CODE"
```

## Contribute

If you want to improve Yaunm3 in any way, feel free to open an issue, or better yet, a pull request! I appreciate every contribution!

## Credits

- [The Flipper Zero firmware source code](https://github.com/flipperdevices/flipperzero-firmware)
- [Zola](https://www.getzola.org) for being an amazing static site generator

## Thanks to ♥

- [Shakhzod Kudratov](https://shakhzod.me/) for purchasing this amazing tool.
- [Everyone](https://t.me/orzklvb) who supported me and said good stuff <3
