# react-snippets-emacs
React/Redux/React-Native snippets with Typescript support for [Yasnippet](https://github.com/joaotavora/yasnippet)

## Installation

Just copy snippets folder to ```~/.config/emacs/snippets```


For expand a snippet without autocompletion add this option:
```
(use-package yasnippet
  ...
  :bind  ("M-j" . yas-expand) ;we are remember Emmet mode xD
  ...
)
```

For insert  ```import React from 'react'``` add to ```init.el```:
```
(setq react-import t)
```

For replace  React Fragments ```<></>``` to ```<div>``` add to ```init.el```:
```
(setq react-fragments-todiv t)
```

Enjoy ;)
