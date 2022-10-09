<div align="center">
  <h1>Emacs Hurl</h1>

Emacs major mode for Hurl.

</div>

---

## Features

- Keyword highlight

## Installation

### Doom Emacs

in `packages.el`

``` lisp
(package! hurl-mode :recipe (:host github :repo "azzamsa/emacs-hurl"))
```

### straight.el

``` lisp
(straight-use-package
 '(hurl-mode :type git :host github :repo "azzamsa/hurl-mode"))
```

## Credits

- [Tony Wang's Emacs Fish Mode](https://github.com/wwwjfy/emacs-fish)
