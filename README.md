# vietnam-holidays

Vietnam holidays support for emacs. All information's based on wiki

# Installation

`git clone` then add following settings into your config file:

```lisp
(use-package vietnam-holidays
  :load-path "path-to-package"
  :config
  (progn
    (vietnam-holidays-setup)
  )
)
```