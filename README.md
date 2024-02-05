# react-snippets-emacs
React/Redux/React-Native snippets with Typescript support 

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

For remove  ```import React from 'react'``` add to ```init.el```:
```
(setq react-import t)
```

For replace ```<div>``` to React Fragments ```<></>``` add to ```init.el```:
```
(setq react-fragment t)
```

Enjoy ;)
