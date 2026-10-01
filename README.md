# hesperus-theme

An Emacs dark bluish theme inspired by the night sky.

## Screenshot

![hesperus-theme](https://i.imgur.com/sCelmVx.png)

## Installation

Not yet available on MELPA. Manual installation only.

### Manual

Clone the repository:

```
git clone https://github.com/hesperus-theme/emacs.git
```

Add the path to your Emacs config:

```elisp
(add-to-list 'custom-theme-load-path
             "/path/to/hesperus-theme/")
```

Then use `M-x customize-themes RET` to activate it, or simply load the theme inside your config, after the `custom-theme-load-path` declaration:

```elisp
(load-theme 'hesperus t)
```

## License

MIT. Check [the source code](./hesperus-theme.el).
